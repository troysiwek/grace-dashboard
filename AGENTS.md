# Rose - Local Instructions

> Canonical file: `AGENTS.md`. If `CLAUDE.md` exists beside it, it should be a symlink to this file. Edit `AGENTS.md`, not the symlink.

Rose is the local workspace for Troy's newsletter and brand system. It is rooted at `Troy-Active/Rose/` and serves two active tracks:

- High Beam - BrightSol-Enterprise newsletter and supporting research
- AI Wake Up Call - BrightSol-ai newsletter and supporting research

## Read first

When working anywhere under Rose, read the most specific instruction files in this order:

1. Root `AGENTS.md` in `My Drive`
2. This file
3. The relevant track file:
   - `High-Beam-Principles.md` for High Beam
   - `AI-Wake-Up-Call-Principles.md` for AI Wake Up Call
4. `environment.md` for config and platform pointers
5. `Newsletter-Architecture-PROJECT-LOG.md` for the architecture history and open decisions
6. `Shared/Research-Harness/` for source pull, fact-check, counter-agent, and NotebookLM prompts
7. `voice-instructions.md` before writing anything in Troy's voice

## Folder rules

- Treat `Troy-Active/Rose/` as the canonical Rose root, not a subfolder of Career-Brand.
- Use the track folders for active work:
  - `High-Beam/` for enterprise newsletter work
  - `AI-Wake-Up-Call/` for SMB newsletter work
- Keep working notes in Markdown.
- Use `.docx` only when the deliverable needs Word-native editing or comments.
- Never write secret values into Drive files.
- Keep the project log append-only. If the session changes the Rose architecture, log it in `Newsletter-Architecture-PROJECT-LOG.md`.

## Rose setup sanity check

- `setup_rose.sh` is a bootstrap helper and must stay aligned with the actual Rose root.
- If the script and the folder structure disagree, the folder structure wins.
- If you add a subfolder-specific `AGENTS.md`, read it before editing anything there.
