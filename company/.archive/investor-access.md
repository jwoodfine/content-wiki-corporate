---
schema: foundry-doc-v1
title: "Investor access"
slug: investor-access
aliases:
  - topic-investor-access
short_description: "How investors in Direct-Hold assets access position data, financial reports, and ledger records through the MCorp-operated investor portal."
category: company
index_group: technology-and-investor-services
type: reference
content_type: topic
quality: complete
status: archived
archived: 2026-08-24
archived_reason: "Retracted — the 'MCorp-operated investor portal' concept does not trace to any of the ~32 real ingest source files. Every 'portal' reference found in the real source material describes a government regulatory filing portal (SEDAR+, CNMV, CNBV STIV-2), the opposite concept. Track-B integrity review, 2026-08-24."
superseded_by: none
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-08-24
editor: pointsav-engineering
paired_with: investor-access.es.md
cites: []
---

An investor in a [[direct-hold-framework|Direct-Hold]] asset holds a position in a specific named property. Access to position data, financial reports, and transaction records is provided through the investor portal operated by MCorp. The portal reflects the investor's ledger position — equity percentage, financial event history, and transfer records — for each asset in which they hold a position, with the ledger itself maintained under the authority of the vehicle's own governing body (in Canada, the General Partner, Woodfine Professional Centres Inc.). The position is structured as [[investment-units|investment units]] in the named asset.

## Key takeaways

- Position data, financial reports, and transfer records are presented per asset — the portal does not aggregate across multiple Direct-Hold positions, because each asset is its own distinct financial and legal unit.
- Financial disclosures triggering material change reporting under NI 51-102 are filed on SEDAR+ as well as through the investor portal, satisfying continuous-disclosure obligations.
- MCorp operates the investor portal and controls access provisioning and revocation as a delegated task; PointSav maintains the portal infrastructure — the division of responsibility matches the broader vendor-customer model. Ledger custody and transfer recording sit with the vehicle's own governing body, not MCorp.

## Position data

Position data represents the investor's current fractional equity in the named asset: the percentage held, the date of acquisition, the acquisition cost recorded on the ledger, and the cumulative financial event history since acquisition. Position data is specific to the asset — it does not aggregate across multiple Direct-Hold positions. Each asset is its own financial and legal unit.

## Financial reports

MCorp provides investors with periodic financial reports for each asset in which they hold a position, as a task delegated to it by the vehicle's governing body. Reports cover asset-level performance: occupancy rate, rental income, debt service, distributions, and net operating income. Reports do not aggregate across assets; each report corresponds to a single asset and a single investor's position in that asset.

The frequency and format of financial reports is governed by MCorp's investor communications standards, consistent with the [[about-continuous-disclosure|disclosure obligations]] applicable under NI 51-102. Where financial events trigger material change reporting, that disclosure occurs through SEDAR+ as well as through the portal.

## Transfer records

When an investor transfers equity to an eligible counterparty under the [[equity-transfer-model|Equity Transfer Model]], the ledger records the transaction: timestamp, transferring party identity, acquiring party identity, and the percentage transferred. The transferring investor receives confirmation of the completed transaction. The acquiring investor receives an updated position statement reflecting the new equity percentage.

The vehicle's governing body — in Canada, the General Partner — records the transfer and is contractually obligated to admit an eligible transferee, declining only on a short, enumerated list of grounds (a securities-law opinion, or false eligibility representations); it does not otherwise exercise approval discretion or broker transfers between private parties. MCorp has no role in this step.

## Over-the-counter transfer

No Direct-Hold vehicle operates a formal secondary market, a matched-order book, or a buyback facility — see [[redemption-elimination|Redemption Elimination]] for the structural rationale. Investors seeking liquidity identify an eligible counterparty independently. The corporate entity does not intermediate this process and makes no representation about the availability or pricing of private liquidity for any specific asset.

Broker-dealer channels that operate independently of the corporate entity may be engaged by investors to arrange transfers; neither MCorp nor the vehicle's governing body makes any representation about the suitability, availability, or cost of such channels.

## Portal access

Portal access is credential-based. MCorp is responsible for investor authentication and for provisioning and revoking portal access, as a task delegated to it by the vehicle's governing body. PointSav maintains the portal infrastructure; MCorp controls who is provisioned access and under what conditions. Credentials are issued at the time an investor completes the onboarding process for a specific asset.

## The bottom line

The investor portal provides a ledger-accurate view of each investor's position in each named asset — not a summary portfolio view. Reports, transfer confirmations, and position statements are all asset-specific, reflecting the Direct-Hold structure in which each property is a discrete legal and financial unit. MCorp does not broker liquidity or operate a secondary market; its portal role is to provide accurate, timely access to the records that define the investor's position. Ledger updates and transfer admission decisions sit with the vehicle's own governing body, which records transfers when they occur, declining only on the narrow grounds described above. The portal is a read-and-record interface, not a trading venue.

## See also

- [[equity-transfer-model|Equity Transfer Model]] — the mechanics of peer-to-peer equity transfers in Direct-Hold assets
- [[about-continuous-disclosure|Continuous Disclosure Obligations]] — the OSC reporting requirements that govern financial disclosures made through the portal
- Property Ledger Technology — the technical infrastructure that maintains position data and financial event history
