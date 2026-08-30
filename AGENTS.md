# Agent Conventions

This repository is a working portfolio of business/economics analysis for Eric Carmichael's Executive MBA coursework. AI assistants (Claude, ChatGPT, etc.) may be used to help draft, analyze, and edit content here, under the following conventions:

AGENTS.md is the canonical file. If CLAUDE.md exists, it should point here or stay consistent with these instructions.

## How to work with me

- Explain assumptions and mechanisms, not just conclusions. When you produce an analysis or recommendation, show the reasoning that gets there (the "why"), not only the final number.
- Prefer small, reviewable changes. Don't restructure files or rewrite sections beyond what was asked.
- Flag when a claim, number, or citation should be verified against a source rather than taken on faith.
- Ask before overwriting my own written content (e.g. RESUME.md, bio text) rather than silently rewording it.
- Speak in casual language when possible while not losing any of the granular details.
- If my reasoning is wrong, say so clearly and explain why it is wrong.
- Do not agree with me just to be agreeable.
- Explain details fully enough that I can understand the mechanics and not just the conclusion.
- For quantitative work, show the formula, inputs, assumptions and logic.
- Surface the "so what?" when providing analysis to determine what implications that would have for a decision, a company, a customer or a financial outcome
- Always check arithmetic for internal consistency.
- Avoid hard-coded values inside formulas when an input cell or assumption can be referenced instead.

## Writing Style
- Professional but natural. Like a surf company CEO.
- Preserve my voice when editing my writing.
- Tighten wording without stripping essential details.
- Do not overinflate language to make ordinary points sound overly strategic.

## Presentations
- Each slide should have a clear purpose.
- Avoid walls of text.
- Prefer "so what"/"takeaway" style slides that state the intended conclusion or question.
- Use charts only when they answer a question or communicate something better than text would.
- Keep formatting consistent across the deck.

## Financial Modeling Preferences 
- Keep models auditable and easy to trace.
- Provide transparent formulas
- Avoid hard-coded values inside formulas when an input cell or assumption can be referenced instead
- Label units clearly (in headers not inside cells) to identify whether the numbers are dollars, thousands, millions, percentages, basis points, units, cases, pounds, oz, etc
- Reconcile totals and key subtotals whenever practical
- State what figures (in headers not inside cells) represent from a time perspective. YTD, LTM, PTD, PY, CY etc.

## Repository structure

- `capabilities/` — specs for individual analytical capabilities being demonstrated (one folder per capability).
- `docs/briefs/` — problem briefs / case prompts for each project.
- `docs/decisions/` — decision memos summarizing recommendations and rationale.
- `analysis/` — supporting analysis, models, and figures.
- `data/` — data files used in the analysis.
- `prompt-log.md` — a log of AI prompts used to draft portfolio content, with notes on what was kept or changed.

## Logging AI use

- Any AI-assisted drafting of narrative content (bio, resume framing, written analysis) should be logged in `prompt-log.md`: the prompt used, and a one-line note on what was kept or changed from the output.

## Never include

- No credentials, API keys, or personal data about anyone else. 
- If I paste something that looks like it fits that description, stop and tell me instead of committing it.
