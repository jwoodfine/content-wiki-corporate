---
schema: foundry-doc-v1
title: "Technology services agreement"
slug: technology-services
aliases:
  - topic-technology-services
short_description: "Structure of the services agreement under which PointSav Digital Systems provides platform infrastructure to each Direct-Hold vehicle's governing body as a contracted technology vendor."
category: company
index_group: technology-and-investor-services
type: reference
content_type: topic
quality: complete
status: archived
archived: 2026-08-24
archived_reason: "Retracted — the specific service-agreement mechanics (data destruction obligations, exclusions list, service scope) do not trace to any of the ~32 real ingest source files. Consolidated into vendor-customer-model.md, which states only the confirmed fact that PointSav is a separate technology subsidiary. Track-B integrity review, 2026-08-24."
superseded_by: vendor-customer-model
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-08-24
editor: pointsav-engineering
paired_with: technology-services.es.md
cites: []
---

PointSav Digital Systems provides technology services to each Direct-Hold vehicle under a contractual services agreement implementing the [[topic-vendor-customer-model|vendor-customer model]]. The agreement defines the scope of PointSav's engagement, the data obligations PointSav holds toward each vehicle's governing body — in Canada, the General Partner, Woodfine Professional Centres Inc. — and the boundaries that prevent the technology services relationship from crossing into investment management or fiduciary advisory functions. PointSav's obligations operate alongside the [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]] under which the governing body retains custody of all ledger data.

## Key takeaways

- PointSav is a contracted technology vendor, not a partner, co-manager, or advisor; it does not hold equity in any managed properties or receive a share of investment returns.
- Each vehicle's governing body retains legal custody of all ledger data; PointSav is contractually obligated to deliver a complete data export on request and to destroy data on the governing body's instruction at agreement termination.
- Investment advice, regulatory compliance advice, and all fiduciary functions are explicitly outside PointSav's engagement scope and belong solely to each vehicle's governing body; MCorp handles day-to-day investor onboarding and communications as a task delegated to it by the governing body.

## Agreement structure

The services agreement establishes PointSav as a contracted technology vendor — not a partner, not a co-manager, and not an advisor on investment or fiduciary matters. PointSav delivers defined services; each vehicle's governing body directs those services and retains all [[topic-data-governance|data custody]], investment decision authority, and ultimate investor relationship responsibility.

PointSav does not hold equity in any managed property under the agreement. PointSav does not receive a share of investment returns. Compensation is structured as a technology services fee, not as a carried interest or performance allocation.

## Service scope

The agreement covers:

- Platform development and software maintenance for the property ledger infrastructure and investor portal
- Server infrastructure and private key management for ledger operations
- Data export and portability services on the governing body's request
- Security monitoring and system integrity functions
- Operational system support and incident response

Services outside this scope — investment advice, regulatory compliance advice, and fiduciary representation — are explicitly excluded from PointSav's engagement.

## Data obligations

The agreement requires PointSav to maintain ledger data in formats accessible to the governing body, to deliver a complete data export on request, and to destroy data pursuant to the governing body's instructions at agreement termination. These obligations ensure that the governing body's data custody rights are not dependent on the continuation of any specific technology services relationship.

PointSav does not transfer, sell, or independently use custodied data. All data processed under the agreement remains under the governing body's legal custody.

## Exclusions

PointSav does not provide:

- Investment advice or recommendations on asset acquisition, disposition, or financing
- Investor suitability determinations
- Regulatory compliance advice or fiduciary services
- Representation of any vehicle to the OSC or any other regulatory body
- Investor communications or reporting to security holders

These functions belong to each vehicle's governing body, which may delegate day-to-day investor onboarding and communications to MCorp. Inquiries from investors about the platform or the ledger infrastructure are referred to the governing body as the responsible fiduciary.

## Separation of failure modes

The services agreement is structured so that an operational disruption at PointSav does not affect a governing body's legal title to assets, and a financial event elsewhere in the group does not terminate PointSav's obligations to maintain data integrity and platform availability. Neither party's operational difficulties automatically impair the other's core function. This separation is the practical expression of the vendor-customer model at the contractual level.

## The bottom line

The technology services agreement keeps PointSav's role strictly operational and technical, with no discretion over data, no investor-facing functions, and no participation in investment returns. Each vehicle's governing body directs the platform and retains portable custody of all data, so its operational control over the ledger is not contingent on any specific technology relationship. The agreement is structured so that an operational disruption at either party does not automatically impair the other's core function.

## See also

- [[topic-vendor-customer-model|Vendor-Customer Model]] — the structural separation between PointSav and each vehicle's governing body that the services agreement reflects
- [[topic-data-governance|Data Governance]] — each governing body's data custody framework that governs PointSav's obligations under the agreement
- Property Ledger Technology — the technical infrastructure PointSav maintains under the agreement
