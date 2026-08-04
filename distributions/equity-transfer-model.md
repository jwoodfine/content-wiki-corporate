---
schema: foundry-doc-v1
title: "Equity transfer model"
slug: equity-transfer-model
aliases:
  - topic-equity-transfer-model
short_description: "Over-the-counter transfer mechanism that allows investors to exit their position directly to eligible counterparties, without requiring a liquidity pool or corporate buyback."
category: distributions
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-07-30
editor: pointsav-engineering
paired_with: equity-transfer-model.es.md
cites: []
---

Each Direct-Hold vehicle's Investment Units transfer over-the-counter between private parties; the vehicle's own governing body records the completed transfer. Two structural principles govern the model: freely transferable equity within a short, enumerated set of conditions, and peer-to-peer execution — no formal secondary market, no market maker, no corporate buyback facility. The model relies on the [[topic-fiduciary-data-mandate|fiduciary data mandate]] for ledger integrity and operates alongside the [[topic-interest-coverage-ratio|interest coverage ratio]] discipline applied at the asset level.

**Correction (2026-08-04):** this article describes the Direct-Hold Solutions'
structural design as a class. Only the Canada vehicle (Woodfine Professional Centres
Limited Partnership) is currently established; it is currently subject to an active
BCSC cease-trade order, under which units are not currently freely transferable. The
United States, Spain, and Mexico vehicles are planned, not yet established. **Flagged,
not silently rewritten.**

## Key takeaways

- Direct-Hold equity is freely transferable to any eligible counterparty without a general partner approval decision in the ordinary case — distinguishing the model from restricted-equity structures where the issuer holds a right of first refusal or exercises open-ended transfer-approval discretion. In Canada, the General Partner is contractually obligated to admit an eligible transferee, declining only on a short, enumerated list of grounds.
- No Direct-Hold vehicle maintains a formal secondary market, matched-order book, or buyback facility; liquidity is determined by the market of willing, eligible buyers, not by corporate policy.
- Each transfer is recorded on the asset ledger with a full chain of title, so ownership of a fractional interest is always evidenced by a ledger entry rather than a paper certificate.

## Freely transferable equity

Each Direct-Hold vehicle issues Investment Units in its own isolated [[topic-property-ledger-technology|property ledger]]. "Freely transferable" means a holder may offer their interest to any eligible counterparty; the vehicle's governing body does not exercise business judgment over who may acquire it. In Canada, the General Partner is contractually obligated to admit any transferee — subject only to two narrow, enumerated grounds: (a) counsel's opinion that the transfer would violate securities or other law, or (b) the General Partner's belief that the transferee's required eligibility representations are untrue. Each unit of equity issued constitutes an [[topic-investment-units|investment unit]] in the named asset.

This distinguishes the model from restricted-equity structures — common in private real estate vehicles — where the issuer retains an open-ended right of first refusal or exercises discretionary transfer-approval power. A transferee does make the same eligibility representations (residency, investor-status, and similar) on each transfer — this is not a business-judgment re-approval, but it is a real, recurring step, not the absence of one.

## Over-the-counter execution

Transfer execution is between private parties. No Direct-Hold vehicle maintains a formal secondary market, a matched-order book, or a buyback facility. In Canada, the General Partner records the transfer once the required documentation is delivered — a ministerial recording step, not a discretionary approval, though a narrow, enumerated set of transfers can be declined (see above) or, after the fact, reversed: a holder who causes the partnership adverse tax consequences by becoming a non-resident can be required to divest, at independent-appraiser fair value. An investor seeking liquidity locates an eligible counterparty through their own commercial relationships or through broker-dealer channels that operate independently of the corporate entity.

## No subjective liquidity requirements

Traditional fund structures impose redemption gates, liquidity reserves, and lock-up periods subject to fund manager discretion. The Equity Transfer Model contains none of these mechanisms — see [[topic-redemption-elimination|Redemption Elimination]] for the structural rationale. Liquidity terms are determined by the market of willing buyers, not by corporate entity policy. The [[topic-perpetual-equity-model|perpetual equity model]] applies the same logic over an indefinite holding horizon.

## Ledger integrity

The asset ledger records each transfer with a full chain of title. Ownership of a fractional interest is a ledger entry, not a paper certificate. The mathematical integrity of the ledger is maintained by the corporate entity's fiduciary data systems — described further in [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]].

## The bottom line

The Equity Transfer Model removes the corporate entity from the liquidity equation without removing it from the record-keeping obligation. Investors can transfer their position to an eligible counterparty at any time; the vehicle's governing body's role is to record that transfer accurately — declining only on the narrow, enumerated grounds described above — not to exercise open-ended approval discretion or to provide a market for it. The absence of redemption gates and liquidity windows is a design feature, not a limitation: it eliminates the structural tension between asset liquidity and investor liquidity that characterizes pooled fund structures. The ledger — maintained under the fiduciary data mandate — provides the authoritative record of every transfer in the chain of title.

## See also

- [[topic-direct-hold-framework|Direct-Hold Framework]] — the ownership structure that makes equity freely transferable
- [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]] — data governance requirements that underpin ledger integrity
- [[topic-redemption-elimination|Redemption Elimination]] — why no corporate buyback facility exists

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
