---
schema: foundry-doc-v1
title: "How sensitivity and stress-test analysis works for Direct-Hold Solutions"
slug: sensitivity-and-stress-test-methodology
aliases: []
short_description: "How Direct-Hold Solutions model interest-rate, occupancy, and development-yield stress against the 1.20x interest-coverage covenant."
category: financial-model
index_group: valuation-and-forecasting-methodology
type: topic
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-08-03
editor: pointsav-engineering
paired_with: sensitivity-and-stress-test-methodology.es.md
cites: []
---

Every Direct-Hold Solution is modeled against a $100.00 capital-preservation reference unit and a 1.20x minimum interest-coverage covenant set in its debenture financing terms. This article walks through the sensitivity and stress-test methodology applied to that model: how a single coverage driver — interest rate, occupancy, or development yield — is flexed in isolation to observe its effect on coverage and build-out; how the issuer's adaptive build-out lever is designed to hold the covenant rather than breach it; how a maximal combined shock, sized to severe historical downturns, is absorbed through a corrective disposition of last resort; and how the resulting sensitivities are reported under IFRS 13 §93(h)(ii). The output of this methodology is a set of modeled, illustrative scenarios, not a prediction of future performance — actual coverage, net asset value, and distribution outcomes will differ from every assumption stated here.

## Before you read this

This article assumes familiarity with the interest-coverage covenant itself — see Interest Coverage Ratio for what the 1.20x floor is and why it is set where it is; this article does not re-explain the covenant, it walks through how the covenant is stress-tested. It also assumes familiarity with net asset value (NAV) and the other non-IFRS measures this methodology reports against — see [[non-ifrs-measures-explained]]. No modeling software or account access is required beyond that: this article describes a methodology, not a tool.

## How the scenarios are constructed

The methodology tracks a $100.00 capital-preservation reference unit across every scenario, from the base case through to the maximal combined shock. The base case is the un-stressed 10-year forecast: financing rate, occupancy, and development yield are all held at their expected values, and interest coverage is checked against the 1.20x covenant at every point across the horizon.

From that base case, the coverage-driver stress-scenario methodology flexes a single driver at a time — interest rate, occupancy, or development yield — while holding every other assumption at base. This isolates that one driver's effect on minimum interest coverage and on the pace of build-out, before any drivers are combined with one another.

What each single-driver stress scenario shows is not a static projection but the issuer's adaptive build-out lever responding in real time. As financing costs or operating conditions worsen during construction, the issuer constrains new debenture issuance and scales back the build-out program to hold interest coverage at the covenant rather than let it breach. A static, no-response projection is treated as unrealistic in this methodology, because a sustained covenant breach would transfer asset control to secured lenders — the adaptive response is the modeled behavior, not an optimistic overlay on top of it.

Once a Direct-Hold Solution is stabilised post-construction, interest coverage runs well above the 1.20x floor, and the methodology's stress scenarios show that a large increase in the financing coupon is required before the covenant threshold is approached again.

The maximal combined shock scenario departs from the single-driver approach by applying simultaneous adverse moves to financing rate, capitalization rate, and occupancy all at once. It is calibrated to historical severe-downturn evidence — 2008-09 and 2022-23-scale office cap-rate expansion and refinancing-rate moves — and is used to size the downside case for capital preservation. Under this combined shock, a minimum fraction of the portfolio is sold at its stressed, orderly-transaction value to restore interest coverage to the covenant threshold — a market-value sale designed to preserve NAV per unit while compressing, not eliminating, distributions.

Alongside these coverage-driver scenarios, the presentation methodology tracks NAV-per-unit trajectories under a base case, a bear case (adverse cap rate and occupancy), and a bull case (favourable cap rate), all measured against the $100 capital-preservation reference over the 10-year forecast horizon.

Separately, the IFRS 13 §93(h)(ii) sensitivity table applies a ±25 basis-point one-way sensitivity across cap rate, interest rate, occupancy, and development yield, measured against Year-8 NAV per unit, income yield, and minimum coverage. This table is a fair-value-measurement disclosure requirement, distinct from the forward-looking scenarios described above.

## How to tell which scenario you're reading

Any given exhibit in this methodology can be placed correctly by checking two things. First, which of the three coverage drivers is being flexed, and whether the exhibit is a single-driver stress or the maximal combined shock — this comes down to whether two of the three drivers are held at base (a single-driver stress) or whether financing rate, cap rate, and occupancy are all moved together (the combined shock).

Second, which side of the disclosure boundary the exhibit sits on. The management-response and corrective-disposition exhibits described above are forward-looking illustrative scenarios, while the IFRS 13 table is a fair-value-measurement sensitivity disclosure. The two are prepared to different standards — the forward-looking exhibits carry caution language consistent with NI 51-102 and ISAE 3400, and the IFRS 13 table follows that standard's own ±25 bps reasonably-possible-alternative-assumption convention. A figure that cannot be placed on one side or the other of that boundary has not been correctly located within the methodology.

Every stress and shock scenario in this methodology is modeled and illustrative. None of the coverage, NAV, or distribution figures it produces is a prediction, an assurance, or a guarantee of actual future performance; actual results will differ from every assumption used to construct these scenarios.

## Next steps

Read Interest Coverage Ratio for the covenant this methodology stress-tests, and [[non-ifrs-measures-explained]] for how NAV and the other supplementary measures used throughout this methodology are defined and reconciled to IFRS. See also [[forward-looking-statements-advisory|the Forward-Looking Statements Advisory]] for the caution language that governs every illustrative scenario in this article.
