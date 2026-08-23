---
schema: foundry-doc-v1
title: "Holding-Company Valuation Methodology"
slug: holding-company-valuation-methodology
aliases:
  - topic-holding-company-valuation-methodology
short_description: "The three-method framework — price/earnings, earnings-yield, and book value — used to model a composite fair-value-per-share estimate for the parent holding company, distinct from asset- and vehicle-level valuation."
category: financial-model
index_group: valuation-and-forecasting-methodology
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-07-15
editor: pointsav-engineering
paired_with: holding-company-valuation-methodology.es.md
cites: []
---

**Holding-Company Valuation Methodology** is the three-method framework Woodfine Capital Projects Inc. (WCP) applies, in its financial modeling, to derive an illustrative fair-value-per-share estimate at the parent holding-company level. This is distinct from the asset-level and vehicle-level valuation methods — [[cre-financial-metrics|net operating income, capitalization rate, net asset value]] — applied within each individual [[direct-hold-framework|Direct-Hold]] vehicle. The methodology combines a price/earnings method, an earnings-yield method, and a book-value method into a single composite figure across a ten-year modeled forecast horizon. Every figure that follows — the 10.72x multiple, the 4.5% yield, the 10% beneficial-ownership interest, and the 27% statutory tax rate — is a modeled, illustrative parameter used in a forecast exercise; none is a disclosed current metric, a projection of actual results, or a guarantee of any kind.

## The price/earnings method

Under the price/earnings method, WCP's projected annual earnings for a given forecast year are multiplied by a fixed price/earnings multiple — 10.72x in this model — to derive an implied per-share equity value for that year. The multiple is held constant across the ten-year forecast, so period-over-period movement in the implied value comes entirely from the earnings line rather than from a re-rating of the multiple itself. The method reflects a standard equity-market convention: a holding company's value is treated as a function of its earnings stream, capitalized at the multiple the model assumes the market would pay for it.

## The earnings-yield method

The earnings-yield method inverts the same earnings line against a fixed target yield — 4.5% in this model — dividing projected annual earnings by that rate to produce a second, independent implied per-share value. Run alongside the price/earnings method rather than in place of it, the earnings-yield calculation serves as a cross-check: because a price/earnings multiple and an earnings yield are reciprocal expressions of the same relationship, any material divergence between the two implied values in a given forecast year signals that the modeled multiple and the modeled yield are not internally consistent with each other for that period.

## The book-value method and the beneficial-ownership NAV build

The book-value method builds a per-share value from the balance sheet rather than from the income statement. Book value is constructed as cumulative free cash flow — financing proceeds plus retained earnings, accumulated across the forecast — plus WCP's proportional beneficial-ownership interest in the forecast net asset value of each affiliated Direct-Hold vehicle in the portfolio. That beneficial-ownership interest is fixed at 10% in this model. The NAV build applies the same 10% figure to each affiliated vehicle's own forecast NAV individually, then aggregates the resulting interests across the full portfolio of vehicles before adding the total to WCP's cumulative free cash flow. The combined figure is divided by shares outstanding to produce a book-value-per-share result.

## The fair-value composite

The fair-value composite averages the three per-share results — price/earnings, earnings-yield, and book-value — into a single blended fair-value-per-share estimate for each year of the ten-year forecast. Averaging across three methods with different underlying drivers — a market multiple, a target yield, and a balance-sheet build incorporating a portfolio-wide NAV interest — is intended to reduce the model's sensitivity to any one method's assumptions. The composite does not assert that any single method alone is the correct measure of value; it is a triangulation exercise applied to modeled, forward-looking figures.

## Revenue and income-statement modeling

The earnings figure that feeds all three valuation methods is itself produced by a modeled ten-year holding-company income statement. Revenue is built from three lines: advisory-fee revenue earned across the portfolio of affiliated Direct-Hold vehicles, distributions received from those vehicles, and reimbursement of offering costs. The advisory-fee line is modeled per vehicle — each vehicle's fee stream is scaled by a relative size factor and phased in beginning in that vehicle's own launch year — then aggregated into a single consolidated fee-revenue figure at the holding-company level.

Against that revenue, the model nets operating expenses, including multi-jurisdiction general-and-administrative costs and an affiliated promoter/consultant compensation arrangement. This article does not further specify or quantify that arrangement. A flat statutory tax rate — 27% in this model — is then applied to the resulting pre-tax figure to arrive at modeled net earnings, which in turn drives the per-share metrics used in each of the three valuation methods above.

## The bottom line

Holding-company valuation at WCP is modeled through three independent methods — price/earnings, earnings-yield, and book value with its beneficial-ownership NAV build — averaged into a single fair-value composite across a ten-year horizon. All three methods draw on the same underlying earnings figure, itself built from a modeled advisory-fee revenue line across the affiliated vehicle portfolio, netted against operating expenses and a flat statutory tax rate. Every input — the 10.72x multiple, the 4.5% yield, the 10% beneficial-ownership interest, and the 27% tax rate — is a modeled, illustrative parameter, not a disclosed metric or a forecast of actual results.

## See also

- [[narrow-bank-financial-model|Narrow Bank Financial Model]] — the financing discipline governing the affiliated Direct-Hold vehicles whose NAV feeds the book-value method
- [[cre-financial-metrics|Commercial Real Estate Financial Metrics]] — the asset- and vehicle-level valuation metrics (NAV, capitalization rate) this holding-company methodology builds on but does not replace
- [[non-ifrs-measures-explained|Non-IFRS Measures Explained]] — the disclosure treatment applicable to supplementary, non-IFRS financial measures
- [[direct-hold-framework|Direct-Hold Framework]] — the vehicle-level ownership structure whose beneficial-ownership interest is aggregated into the book-value method
