---
schema: foundry-doc-v1
title: "How sensitivity and stress-test analysis works for Direct-Hold Solutions"
slug: sensitivity-and-stress-test-methodology
aliases: []
short_description: "How Direct-Hold Solutions model interest-rate, occupancy, and development-yield stress against the 1.20x interest-coverage covenant."
category: financial-model
type: reference
content_type: guide
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-GUIDE
last_edited: 2026-07-15
editor: pointsav-engineering
paired_with: sensitivity-and-stress-test-methodology.es.md
cites: []
---

Every Direct-Hold Solution is modeled against a $100.00 capital-preservation reference unit and a 1.20x minimum interest-coverage covenant set in its debenture financing terms. This guide walks through the sensitivity and stress-test methodology applied to that model: how a single coverage driver — interest rate, occupancy, or development yield — is flexed in isolation to observe its effect on coverage and build-out; how the issuer's adaptive build-out lever is designed to hold the covenant rather than breach it; how a maximal combined shock, sized to severe historical downturns, is absorbed through a corrective disposition of last resort; and how the resulting sensitivities are reported under IFRS 13 §93(h)(ii). The output of this methodology is a set of modeled, illustrative scenarios, not a prediction of future performance — actual coverage, net asset value, and distribution outcomes will differ from every assumption stated here.

## Prerequisites

- Familiarity with the interest-coverage covenant itself. See [[interest-coverage-ratio]] for what the 1.20x floor is and why it is set where it is — this guide does not re-explain the covenant; it walks through how the covenant is stress-tested.
- Familiarity with net asset value (NAV) and the other non-IFRS measures this methodology reports against. See [[non-ifrs-measures-explained]].
- None beyond that. No modeling software or account access is required — this guide describes a methodology, not a tool.

## Steps

1. **Start from the $100 reference unit and the base case.** The methodology tracks a $100.00 capital-preservation reference unit across every scenario, base case through maximal combined shock. The base case is the un-stressed 10-year forecast — financing rate, occupancy, and development yield are all held at their expected values, and interest coverage is checked against the 1.20x covenant at every point across the horizon.

2. **Flex one coverage driver at a time.** The coverage-driver stress-scenario methodology holds all assumptions at base while flexing a single driver — interest rate, occupancy, or development yield — to isolate that driver's effect on minimum interest coverage and on the pace of build-out, before any drivers are combined.

3. **Read the adaptive build-out lever's response, not a static projection.** As financing costs or operating conditions worsen during construction, the issuer constrains new debenture issuance and scales back the build-out program to hold interest coverage at the covenant rather than let it breach. A static, no-response projection is treated as unrealistic in this methodology, because a sustained covenant breach would transfer asset control to secured lenders — the adaptive response is the modeled behavior, not an optimistic overlay on top of it.

4. **Confirm the post-construction coverage headroom.** Once a Direct-Hold Solution is stabilised post-construction, interest coverage runs well above the 1.20x floor. The methodology's stress scenarios show that a large increase in the financing coupon is required before the covenant threshold is approached again.

5. **Combine all three drivers into the maximal combined shock.** The maximal combined shock scenario applies simultaneous adverse moves to financing rate, capitalization rate, and occupancy at once, rather than flexing one driver at a time. It is calibrated to historical severe-downturn evidence — 2008-09 and 2022-23-scale office cap-rate expansion and refinancing-rate moves — and is used to size the downside case for capital preservation.

6. **Read the corrective-disposition-of-last-resort cure.** Under the combined shock, a minimum fraction of the portfolio is sold at its stressed, orderly-transaction value to restore interest coverage to the covenant threshold. This is a market-value sale designed to preserve NAV per unit while compressing — not eliminating — distributions.

7. **Read the NAV resilience framing across base, bear, and bull cases.** The presentation methodology tracks NAV-per-unit trajectories under a base case, a bear case (adverse cap rate and occupancy), and a bull case (favourable cap rate) against the $100 capital-preservation reference over the 10-year forecast horizon.

8. **Cross-check the IFRS 13 §93(h)(ii) sensitivity table.** This table is applied as a ±25 basis-point one-way sensitivity across cap rate, interest rate, occupancy, and development yield, measured against Year-8 NAV per unit, income yield, and minimum coverage. It is a fair-value-measurement disclosure requirement, distinct from the forward-looking scenarios in steps 1–7.

## Verification

A reader has followed the methodology correctly if they can identify, for any given exhibit, which of the three coverage drivers is being flexed and whether the exhibit is a single-driver stress or the maximal combined shock. Confirm this by checking whether two of the three drivers are held at base (a single-driver stress) or whether financing rate, cap rate, and occupancy are all moved together (the combined shock).

Confirm the disclosure boundary next: the management-response and corrective-disposition exhibits (steps 3–6) are forward-looking illustrative scenarios, while the IFRS 13 table (step 8) is a fair-value-measurement sensitivity disclosure. The two are prepared to different standards — the forward-looking exhibits carry caution language consistent with NI 51-102 and ISAE 3400, and the IFRS 13 table follows that standard's own ±25 bps reasonably-possible-alternative-assumption convention. A reader who cannot say which of the two a given figure came from has not correctly located it within the methodology.

Every stress and shock scenario in this methodology is modeled and illustrative. None of the coverage, NAV, or distribution figures it produces is a prediction, an assurance, or a guarantee of actual future performance; actual results will differ from every assumption used to construct these scenarios.

## Next steps

Read [[interest-coverage-ratio]] for the covenant this methodology stress-tests, and [[non-ifrs-measures-explained]] for how NAV and the other supplementary measures used throughout this methodology are defined and reconciled to IFRS. See also [[forward-looking-statements-advisory|the Forward-Looking Statements Advisory]] for the caution language that governs every illustrative scenario in this guide.

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
