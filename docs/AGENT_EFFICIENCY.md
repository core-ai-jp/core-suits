# Agent efficiency guide

Supplemental to `AGENTS.md` and `CLAUDE.md`. Existing security, organization isolation, validation and product contracts always take priority.

- Scope each task to the smallest relevant paths; inspect filenames, diffs and targeted ranges before loading large files.
- Read only the relevant private `core-knowledge` index and decision records when needed; record the exact source revision. Never publish private records.
- Reuse verified context from the current task; avoid repeated reads of unchanged files.
- Make minimal patches; avoid unrelated refactors, formatting, dependency changes and generated artifacts.
- For code changes, preserve required `npm run check` and `npm run build` checks and any relevant negative tests. Cost savings never justify skipping required validation.
- Avoid parallel agents unless there are genuinely independent subtasks. After a failed tool call, diagnose before retrying; stop on persistent permissions or integration failures.
- Require explicit approval for production changes, secrets, access controls, destructive actions, external communication and paid services.
- Handoff concisely: changed paths, validation, source revision, blockers and next step.
- Token or credit savings must be measured rather than estimated as facts.
