# Copilot Instructions

## Start every task with repository context
- 🧠 Read `/memory-bank/memory-bank-instructions.md` first.
- 🗂 Load all `/memory-bank/*.md` files before each task.
- 📂 Also load files from the active feature folder (e.g. `/memory-bank/authentication/`).
- 🚦 Follow the Kiro-Lite workflow: PRD → Design → Tasks → Code.
- 🔒 Follow rules in `copilot-rules.md`.
- 📝 On "/update memory bank", refresh activeContext.md & progress.md.

Before substantial work, read `.github/instructions/memory-bank.instructions.md`
and then review the active files under `memory-bank/` (`projectbrief.md`,
`productContext.md`, `activeContext.md`, `systemPatterns.md`, `techContext.md`,
`progress.md`, and `memory-bank/tasks/_index.md`). The MemoryBank is this
repository's persistent project context, so use it to recover architecture
history, active work, and task-level decisions across sessions.

Use `AGENTS.md` as the canonical reference for contributor-facing assets,
LangChain/LangGraph resources, skill mirrors, and runtime-agent workflow.
