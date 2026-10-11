# Repository instructions

Before relying on company-wide context, read the private `gauchecellist1201-png/core-knowledge` repository in this order: `AI_CONTEXT.md`, relevant records in `09_DECISIONS/`, `50_記憶/索引.md`, `AI-COMPANY/AI_DEVELOPMENT_OS/AI_DEVELOPMENT_OS.md`, and `PROVIDER_NEUTRAL_RULES.md`. Record the exact knowledge commit read. Never copy private knowledge, customer data, or local machine details into this public repository.

Read and preserve `CLAUDE.md` as the detailed project contract, then inspect `README.md`, package and lock files, task-relevant source, and CI. The provider-neutral role assignment supersedes historical provider-specific implementer/reviewer labels. Respect the existing architecture and report UNKNOWN facts instead of guessing.

Never output or commit secrets. Follow the current owner approval boundary in private `core-knowledge`: requested in-scope work proceeds through verification; confirm immediately before money-related execution and production changes to user-visible appearance. Preserve this repository’s technical security, authorization, and data-integrity safeguards, and keep sensitive, destructive, or external actions within the explicit task and runtime permissions. Preserve user changes. For code changes run `npm run check` and `npm run build`; keep new permanent checks wired into `check`, and prove new guards with a safe negative test.

Keep organization isolation, private customer media, AI cost recording, real-data precedence, and honest product claims intact as required by `CLAUDE.md`. Return durable decisions and important migration changes to `core-knowledge` with sources and status.

## Efficient execution

For task scoping, targeted reads, retry limits, and concise handoffs, follow [`docs/AGENT_EFFICIENCY.md`](docs/AGENT_EFFICIENCY.md). This supplements rather than overrides the security, knowledge provenance, and validation rules above.

## Efficient AI-assisted development

For the shared workflow, see the private `core-ai-jp/core-knowledge` guide `AI-COMPANY/AI_DEVELOPMENT_OS/WORKFLOWS/TOKEN_EFFICIENT_DEVELOPMENT.md` when available. Keep these repository instructions and all local security, data, and validation contracts in force.

- Scope the task first. Search paths and diffs, then read only the source, tests, and decisions needed to establish the relevant facts. Reuse verified context and avoid rereading unchanged material; do not omit required company decisions or security context.
- Keep changes narrow. Use compact JSON only when handing work to another agent, with relevant fields such as `repo`, `task`, `state`, `decisions`, `files`, `checks`, and `blockers`. JSON does not itself reduce tokens; omit irrelevant history.
- Do not repeat identical failed calls. Diagnose the result first; at most one materially changed retry for a safe, read-only operation. Before retrying a write, check whether it already succeeded.
- Run this repository's required checks and the checks that cover changed behavior. For documentation-only edits, verify the diff, links, and privacy. Do not run production probes just to validate documentation.
- Jev is optional for batched, low-risk classification or routing only when already available and authenticated, and only when its total call cost is expected to be lower than the work it saves. Use one batch; review low-confidence or consequential items. Do not use it for writing, summaries, extraction, complex reasoning, or calculations. Do not install it, configure credentials, or invoke a paid API automatically.
- Follow the current owner approval boundary in `core-knowledge`: confirm immediately before money-related execution and before a production change to user-visible appearance. Keep other actions within the explicit task and runtime permissions; preserve technical security safeguards and do not send external messages, expose secrets, or overwrite others' work without authorization.
- Report changes, checks, and unresolved items briefly. Token or credit savings remain unmeasured until usage is compared.
