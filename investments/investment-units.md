---
schema: foundry-doc-v1
title: "Investment units"
slug: investment-units
aliases:
  - topic-investment-units
category: investments
type: topic
content_type: topic
status: active
quality: complete
language_protocol: PROSE-TOPIC
short_description: "The equity units issued by each direct-hold vehicle in MCorp's Direct-Hold framework."
paired_with: investment-units.es.md
audience: public
bcsc_class: public-disclosure-safe
language: en
last_edited: 2026-07-30
see_also:
  - topic-perpetual-equity-model
  - topic-direct-hold-framework
  - topic-property-ledger-technology
---

Investment units are the equity units issued by each direct-hold vehicle within MCorp's [[topic-direct-hold-framework|Direct-Hold]] framework. Each investment unit represents a proportional interest in the specific direct-hold vehicle — not a share in a pooled fund or a proportional claim on a portfolio of properties.

**Correction (2026-08-02, verified against [[corporate-glossary]]):** the
Direct-Hold framework belongs to Woodfine Capital Projects Inc. (WCP) as promoter,
not MCorp — MCorp is "not the general partner, administrator, or governing body of
any Direct-Hold vehicle." **Flagged, not resolved.**

Units are registered through the partnership's book-entry system and are transferable to willing counterparties subject to the restrictions set out in the applicable partnership agreement. The [[topic-perpetual-equity-model|Perpetual Equity Model]] governs the holding horizon for these units.

## Overview

Investment units are asset-specific instruments. A unit issued in one named property carries no claim on, and confers no exposure to, any other property in the MCorp holding structure. This isolation is structural: it derives from the Direct-Hold framework rather than from contractual representation. An investor holding units in three separate assets holds three separate positions with three separate ledgers, three separate operating statements, and three separate distribution entitlements.

## Denomination and Issuance

The unit count for a named asset is established at the time of onboarding and recorded as the fixed supply in the property ledger. Denomination is expressed as a fractional percentage: one unit in a 10,000-unit register represents 0.01 percent of the economic interest in that asset.

The issuing entity does not create additional units without a formally documented corporate resolution. Dilution is therefore not an inherent feature of the instrument; any decision to increase unit supply is a material corporate decision subject to full disclosure to existing unit holders before it takes effect.

## Rights

Each investment unit in a named asset carries three categories of rights.

**Economic rights.** Unit holders receive a proportional share of distributions declared for the relevant asset. Distributions, when declared, are paid in proportion to outstanding unit counts; no unit within the same asset carries a preferential distribution right over another.

**Transfer rights.** Units are freely transferable to any eligible counterparty. Transfers are recorded in the property ledger in the sequence received by the vehicle's governing body, which is contractually obligated to admit an eligible transferee — declining only on a short, enumerated list of grounds — rather than exercising open-ended approval discretion; other unit holders have no approval role. The transferee acquires the full economic and information rights of the transferor upon ledger settlement.

**Information rights.** Unit holders in a named asset receive periodic operating statements for that asset, including revenue, operating expenses, and the current interest coverage ratio. Information is asset-specific and does not extend to other properties in the corporate holding structure.

## Interest Coverage Ratio

Each direct-hold structure maintains an interest coverage ratio (ICR) floor of 1.2× — net operating income to interest obligations (excluding principal repayment) — as a covenant established in the applicable limited partnership agreement governing borrowing capacity. The ICR is calculated per asset; there is no cross-subsidy between properties. An asset operating between 1.2× and 1.4× ICR is within the range typical of commercial real-estate lending covenants. An asset below 1.2× enters a preservation protocol in which distributions are suspended until the ratio is restored.

The ICR floor is a direct protection for unit holders: it prevents distributions from being drawn from a property whose operating income is insufficient to sustain them. No distribution is declared from an asset whose ICR falls below 1.2×.

## Relationship to the Perpetual Equity Model

Investment units are the instrument through which the [[topic-perpetual-equity-model|Perpetual Equity Model]] is expressed. The perpetual holding horizon — no mandatory exit, no fixed fund cycle — means unit holders do not face a compulsory redemption event. Liquidity is available over-the-counter by identifying an eligible counterparty; the corporate entity does not participate in the exit.

## The bottom line

Investment units are asset-specific, fixed-supply instruments with no cross-exposure between properties in the corporate structure. The 1.2× ICR floor suspends distributions before they outpace operating income. Ordinary transfers require no discretionary approval decision — the vehicle's governing body is contractually obligated to admit an eligible transferee, declining only on a short, enumerated list of grounds. For a regulated buyer, the combination of ledger-recorded ownership, structural asset isolation, and an ICR-linked distribution gate provides a predictable framework for permanent equity allocation to named real property.

## See also

- [[topic-perpetual-equity-model|Perpetual Equity Model]]
- [[topic-direct-hold-framework|Direct-Hold Framework]]
- [[topic-property-ledger-technology|Property Ledger Technology]]
