# Agent Conventions

This repository is a working portfolio of business/economics analysis for Eric Carmichael's Executive MBA coursework. AI assistants (Claude, ChatGPT, etc.) may be used to help draft, analyze, and edit content here, under the following conventions:

## How to work with me

- Explain assumptions and mechanisms, not just conclusions. When you produce an analysis or recommendation, show the reasoning that gets there (the "why"), not only the final number.
- Prefer small, reviewable changes. Don't restructure files or rewrite sections beyond what was asked.
- Flag when a claim, number, or citation should be verified against a source rather than taken on faith.
- Ask before overwriting my own written content (e.g. RESUME.md, bio text) rather than silently rewording it.

## Repository structure

- `capabilities/` — specs for individual analytical capabilities being demonstrated (one folder per capability).
- `docs/briefs/` — problem briefs / case prompts for each project.
- `docs/decisions/` — decision memos summarizing recommendations and rationale.
- `analysis/` — supporting analysis, models, and figures.
- `data/` — data files used in the analysis.
- `prompt-log.md` — a log of AI prompts used to draft portfolio content, with notes on what was kept or changed.

## Logging AI use

Any AI-assisted drafting of narrative content (bio, resume framing, written analysis) should be logged in `prompt-log.md`: the prompt used, and a one-line note on what was kept or changed from the output.
