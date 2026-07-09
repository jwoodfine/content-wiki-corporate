# Cleanup Log — content-wiki-corporate

Living record of in-flight cleanup work, open questions, and decisions.
Read at session start. Update when meaningful cleanup occurs.

Last updated: 2026-07-09.

---

## Active issues

### ⚠ Cluster-clone / canonical convention divergence (Master must resolve)

The canonical at `/srv/foundry/customer/content-wiki-corporate/` uses bare filenames
(`direct-hold-framework.md`). The cluster-clone uses `topic-*` prefix filenames
(`topic-direct-hold-framework.md`). These are incompatible — a plain git push from
the cluster-clone would conflict.

Canonical also lacks: `leapfrog-facts.yaml`, `about.md`, `contact.md`,
`disclaimers.md`, `index.es.md`, `short_description` fields, and all
C8–C10 content.

Resolution: Master Session must rebase or merge to reconcile the convention, then promote via Stage 6.
Until resolved: do NOT run `promote.sh` for this repo.

### BCSC language review (recommended before public milestone)

The five original financial topic pairs (direct-hold-framework, equity-transfer-model,
fiduciary-data-mandate, interest-coverage-ratio, redemption-elimination) were authored
prior to the formal BCSC posture codification. A systematic pass to verify forward-looking
language discipline is recommended before any public-facing disclosure review milestone.
No known violations — this is a precautionary verification.

---

## Recently closed

### 2026-07-09 — CC BY-ND 4.0 content-licence policy note added (important-information.md + disclaimers.md, EN/ES)

`381e341` (Jennifer, 2026-07-09). Closes item 3 of operator decision message
`command-20260706-decisions-journal-important-information-6of7`: "Content licence: CC
BY-ND 4.0, no derivatives... record this as a footer/policy note on the 3 wikis." Added
a **Content licence.** / **Licencia de contenido.** paragraph to `important-information.md`
+ `.es.md` (site-wide band, shown on every page) and a matching `## Licence` / `## Licencia`
section to `disclaimers.md` + `.es.md` (long-form article), placed after the existing
Jurisdiction section in each. This repo already carried 26 (of 28) per-article
`CC BY-ND 4.0` copyright footers as an established convention (per the 2026-05-25
"Institution quality pass" entry above, which corrected a `by/4.0` → `by-nd/4.0` defect) —
the new site-wide note formalizes and matches that existing per-article practice; no
conflict found. Verified via `important-information.md`/`disclaimers.md` read-first pass
before editing, plus a repo-wide grep for prior "CC BY"/"licencia" mentions.

**Flagged, not fixed here — cross-repo note:** `media-knowledge-projects` had only 4 of
~183 articles carrying the `by-nd` footer, with 34 carrying a plain `by/4.0` (no-ND)
footer — a pre-existing per-article inconsistency in that sibling repo, unrelated to this
session's site-wide note. Left untouched (out of this session's scope — a 34-file mass
edit is a separate, larger correctness call); see the parallel entry logged in
`media-knowledge-projects` if that file exists, or the mailbox message to Command
(`re: CC BY-ND 4.0 content-licence footer — live on 3 wikis`, 2026-07-09) for the full
finding. `media-knowledge-documentation` (PointSav engineering wiki, distinct product)
was deliberately **not** given a CC BY-ND note — it already declares plain CC BY 4.0
(full derivatives permitted) in `about.md`, `contribute.md`, `disclaimers.md` §Licence,
and `pointsav-media-kit.md`, consistent with its open-source posture; the operator's
CC BY-ND rationale ("Woodfine's actual disclosed position") is specific to the two
Woodfine disclosure wikis. Flagged to Command rather than silently overwritten or
silently skipped.

### 2026-05-20 — C8–C10: 10 new topics + ES bilingual pairs

`cb53200` (Peter, 2026-05-20): 4 company-identity topics + 6 operational topics + 10 ES
bilingual pairs. Closes the article-backlog open item from NEXT.md §Article backlog.

### 2026-05-20 — YAML expansion + about.md scope update

featured-topic.yaml rotation pool expanded to 15 topics. leapfrog-facts.yaml expanded to
9 facts. about.md content scope updated to reflect the 15-article corpus.

### 2026-05-20 — .agent/rules/ bootstrap

repo-layout.md and cleanup-log.md (this file) created. Closes the bootstrap pending item
from NEXT.md.

---

## Open questions

None currently — surface here when editorial decisions are deferred.
