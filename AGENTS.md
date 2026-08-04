# AGENTS.md

## Project context

This repository (`egeerardyn/awesome-LaTeX`) is an **awesome list**: a curated collection of LaTeX-related resources.
The primary content is in `/home/runner/work/awesome-LaTeX/awesome-LaTeX/README.md`, where entries are listed as links plus short descriptions.

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

## Scope and safety

- Make minimal, focused changes tied to the requested task.
- Do not introduce unrelated refactors or bulk churn.
- Do not add promotional or low-quality entries.
- Preserve existing license and attribution information.
