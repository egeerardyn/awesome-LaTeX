# AGENTS.md

## Project context

This repository (`egeerardyn/awesome-LaTeX`) is an **awesome list**: a curated collection of LaTeX-related resources.
The primary content is in `README.md`, where entries are listed as links plus short descriptions.

Key expectations from existing contribution guidance:
- Keep changes curated and high-signal (quality over quantity).
- Keep formatting consistent with existing list style.
- Preserve structure and ordering conventions unless a change explicitly targets structure.

## Agent guardrails for edits

When editing this repository, agents are allowed to:
- Add, remove, or refine entries when the change improves curation quality.
- Fix typos, grammar, and formatting issues.
- Repair broken links **to the same underlying resource**.

When handling links, agents must follow these strict rules:
1. **Do not change a link to a different resource/project/entity.**
   - Example of forbidden behavior: replacing a project link with a competitor or unrelated page.
2. **Allowed:** update a URL when the resource has moved, as long as it is clearly the same resource.
   - Acceptable evidence includes:
     - HTTP redirect behavior (e.g., 301/308) to the new canonical URL.
     - The original website explicitly states it has moved and points to the new location.
     - Repository/project maintainers provide an official migration notice.
3. If move evidence is unclear, keep the existing link and do not guess.
4. Prefer canonical, stable URLs (official project/docs/repo pages) over temporary or tracking links.

## Adding entries and opening pull requests

[CONTRIBUTING.md](CONTRIBUTING.md) is the source of truth for what may be added; follow its inclusion criteria. In short:
- Fill in the [pull request template](.github/pull_request_template.md) completely and truthfully. That includes disclosing **AI use** (you are an AI agent, so say so, plus how a human was involved) and any **affiliation** with the tool.
- One item per pull request. Do not touch unrelated lines, reorder existing entries or reflow the file.
- Entry format: `- [Name](link) - Description.`, one line, capitalised, ending with a period, at the bottom of the most relevant section.
- Badges: `![foss]` only for open-source software (check for a LICENSE file). Platform badges `![mac]`, `![linux]`, `![windows]` only when the tool is *not* cross-platform (see the Legend in README.md).
- Mark paid or freemium tools in the description.
- Projects should have about 3 months of public history. If yours does not, argue for the exception in the pull request instead of omitting the fact.
- Do not submit tools you have not verified exist and work as described; never invent features, prices or URLs.

## Checks before opening a pull request

CI runs these on every pull request; run them locally first:
- `npx --yes awesome-lint@latest` must pass.
- New links must pass the link checker. Locally: `lychee --config lychee.toml README.md` (or the `lycheeverse/lychee` Docker image).

The default branch is `master`.

## Scope and safety

- Make minimal, focused changes tied to the requested task.
- Do not introduce unrelated refactors or bulk churn.
- Do not add promotional or low-quality entries.
- Preserve existing license and attribution information.
