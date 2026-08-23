---
schema: foundry-doc-v1
title: "Fiduciary data mandate"
slug: fiduciary-data-mandate
aliases:
  - topic-fiduciary-data-mandate
short_description: "Custody and sovereignty requirement that the corporate entity holds physical control of the ledger hardware and cryptographic keys, not a third-party custodian."
category: governance
index_group: data-custody
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-07-30
editor: pointsav-engineering
paired_with: fiduciary-data-mandate.es.md
cites: []
---

The Fiduciary Data Mandate is the operating requirement that each Direct-Hold vehicle's governing body — in Canada, the General Partner, Woodfine Professional Centres Inc. — holds direct physical and cryptographic control of all records defining investor equity positions, asset valuations, and chain of title. The mandate treats reliance on third-party cloud infrastructure for investor ledger data as a fiduciary failure, not a vendor relationship: a governing body that cannot access its own ledger records without a third party's cooperation cannot independently discharge its obligations to investors. The mandate underpins the [[topic-direct-hold-framework|Direct-Hold framework]], enables the [[topic-equity-transfer-model|Equity Transfer Model]], and is applied alongside the Interest Coverage Ratio discipline at the asset level.

## Key takeaways

- The mandate requires each vehicle's governing body to hold direct physical and cryptographic control of all investor ledger records — reliance on third-party cloud infrastructure for these records is classified as a fiduciary failure, not a vendor relationship.
- The PointSav platform implements the mandate by providing self-hosted ledger infrastructure where the governing body holds the private keys and physical hardware; no third party can access ledger data without the governing body's cryptographic consent.
- The mandate's scope is limited to investor ledger data and chain-of-title records — marketing, tenant management, and communications infrastructure may use hosted services. MCorp may operate the investor-facing portal onto that ledger as a delegated task, but does not hold the underlying custodial keys.

## What the mandate covers

The mandate applies to all data that records investor equity positions, asset valuations, transaction history, and chain of title. These records constitute the legal foundation of the investor relationship. A vehicle's governing body cannot be the beneficial holder of assets if it does not control the data that defines those assets.

## Third-party cloud dependency as fiduciary risk

Traditional property investment vehicles rely on third-party software platforms, hosted databases, and cloud-native accounting systems. These create a structural vulnerability: the legal record of investor ownership is maintained by entities whose interests may diverge from the investor's. A cloud provider's service disruption, acquisition, or policy change can interrupt access to records the governing body does not physically control.

The Fiduciary Data Mandate closes this vulnerability by treating digital sovereignty as equivalent to physical asset ownership. A governing body that owns a building but cannot access the ledger proving it owns the building is functionally dispossessed.

## PointSav platform

Each vehicle's governing body's compliance with the mandate is supported by the PointSav platform under the [[topic-technology-services|technology services agreement]]. PointSav provides the operating infrastructure for investor ledger management: a self-hosted system where the governing body holds the private keys, the physical hardware, and operational control of the software stack. No third-party intermediary has access to ledger data without the governing body's cryptographic consent. The arrangement is governed by the [[topic-vendor-customer-model|vendor-customer model]] that separates platform operation from fiduciary responsibility.

## Scope and limits

The mandate applies to investor ledger data and chain-of-title records. It does not extend to marketing materials, tenant management systems, or communications infrastructure — those may use hosted services. The distinction: whatever would need to be produced in a legal dispute about investor ownership is within scope.

An investor cannot exercise governance rights over an asset whose legal ledger they cannot access. The mandate closes this structural gap: a governing body that controls its own ledger infrastructure can always produce the authoritative record, regardless of third-party service availability. The discipline complements broader [[topic-data-governance|data governance]] obligations and the [[about-continuous-disclosure|continuous-disclosure regime]] applicable to the issuer.

## The bottom line

The Fiduciary Data Mandate is a sovereignty principle applied to digital records. A governing body that owns a building but cannot access the ledger proving it owns the building is functionally dispossessed — the mandate closes that gap by requiring physical and cryptographic control to remain with the vehicle's own governing body at all times. The PointSav platform implements this requirement operationally; the corporate structure separates platform operation from fiduciary responsibility. The result is that the governing body — in Canada, Woodfine Professional Centres Inc. — can always produce the authoritative record of investor equity positions and chain of title, independent of any third-party service's availability or continued cooperation.

## See also

- [[topic-direct-hold-framework]] — the ownership structure that the fiduciary mandate protects
- [[topic-equity-transfer-model]] — how ledger integrity supports free equity transfer
- Interest Coverage Ratio — the financial discipline applied alongside the data mandate

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
