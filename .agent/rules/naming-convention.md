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
