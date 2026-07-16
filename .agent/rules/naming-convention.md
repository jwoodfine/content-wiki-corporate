# Naming convention — media-knowledge-corporate

## Canonical category taxonomy

The canonical category taxonomy is `categories.yaml` at the repo root. It is
the **single source of truth** for category ids, display names, scope lines,
audience, and display order. The wiki engine consumes it for the category
nav. Do not encode a competing category list anywhere else (CLAUDE.md,
article frontmatter, or ad-hoc docs); reference `categories.yaml` instead.

## Decision log

**2026-07-02 — Category set ratified.** The plain-language,
BCSC-conservative category set — 8 themes / 13 directories (six story
categories, five per-entity `reports*` shelves, plus shared `research` and
`reference`) — was ratified this session and written to `categories.yaml`.
Category names are neutral, factual descriptions of the company; no name or
scope line invites investment or implies a return. This supersedes the
informal 6-category layout described in the archive CLAUDE.md.

Rationale, the old → new rename table, the migration map, and the full BCSC
disclosure posture are in
`.agent/audit/2026-07-02-category-redesign/proposal-corporate.md`.

**2026-07-15 — `research` category retired.** Ratified by Command via mailbox
reply (operator-confirmed before execution) as a reversal of both the
2026-07-02 decision above and `BRIEF-category-redesign-phase-c.md`'s locked
decision, both cited explicitly per Command's own instruction. JOURNAL papers
were never actually seeded into this shelf and never will be — the sovereign-
per-surface JOURNAL model (`BRIEF-journal-research-programme.md`, project-editorial)
routes all JOURNAL content to each product site's own `/research` page instead of
the three media-knowledge wikis. The `research/_index.md`(+`.es.md`) empty shell
is removed; `categories.yaml` drops the `research` entry (12 categories remain).
No articles existed in this category — zero content lost, zero redirects needed.
