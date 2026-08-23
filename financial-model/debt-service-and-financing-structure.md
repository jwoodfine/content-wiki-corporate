---
schema: foundry-doc-v1
title: "Debt service and financing structure"
slug: debt-service-and-financing-structure
category: financial-model
index_group: financing-discipline
type: topic
content_type: topic
quality: complete
short_description: "How commercial mortgage financing is structured within direct-hold limited partnerships: loan-to-value conventions, interest rate risk, and the interaction between debt structure and the ICR distribution gate."
status: active
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-07-11
editor: woodfine-editorial
paired_with: debt-service-and-financing-structure.es.md
---

Two constraints govern the financing structure in each direct-hold
[[limited-partnership-structure|limited partnership]]: the loan-to-value limit set by the
lender, and the 1.2× [[cre-financial-metrics|Interest Coverage Ratio]] (ICR) floor
established as a covenant in the partnership's governing agreement. Commercial real estate
acquisitions are routinely financed with a combination of equity and mortgage debt. These two constraints determine the maximum mortgage quantum for a given asset,
the interest obligation that the ICR distribution gate must clear, and the interest rate
risk profile of the investment.

## Key takeaways

- The mortgage debt in each direct-hold LP is secured against that LP's specific property;
  lenders have no recourse to the properties of other LPs or to the equity of the parent
  holding company absent specific guarantees.
- Debt size is constrained by the lender's loan-to-value (LTV) limit and by the 1.2× ICR
  floor established as a covenant in the partnership's governing agreement.
- Fixed-rate mortgage debt reduces income statement volatility during the fixed term but
  creates refinancing exposure at maturity; floating-rate or variable-rate debt creates
  immediate income sensitivity to benchmark rate changes.

## Loan-to-value constraint

Commercial mortgage lenders set a maximum loan as a percentage of the property's appraised
value. At 65% LTV, for example, a property appraised at $10,000,000 supports a mortgage of
$6,500,000; the remaining $3,500,000 of value must be funded with equity from the LP unit
holders. The LTV ratio is assessed at origination and may be tested again at refinancing or
covenant review dates.

## Amortisation and interest-only periods

Commercial mortgages are structured with varying combinations of principal amortisation and
interest-only periods. An interest-only loan requires no principal repayment during its term;
on maturity, the full original principal is due (a "bullet" repayment). An amortising loan
requires scheduled principal repayment during the term, reducing the outstanding balance over
time and building equity in the property through debt paydown.

Interest-only periods — common in commercial real estate at origination — reduce the annual
cash outflow during stabilisation or lease-up phases, when occupancy is building toward
stabilised levels and NOI may not yet fully support amortising debt service. When the property
reaches stabilised occupancy, the mortgage terms typically shift to amortising; the higher
cash requirement of the amortising schedule is accommodated by the higher stabilised NOI.

The direct-hold LP's ICR calculation uses total interest obligations, not total debt service
(principal plus interest). An interest-only mortgage with a given interest cost produces the
same ICR test result as an amortising mortgage with the same interest rate and a lower
outstanding principal; the principal repayment portion of a fully amortising mortgage is not
included in the denominator of the ICR test.

## Interest rate risk

The interest rate on a commercial mortgage can be fixed for the term or floating based on a
benchmark rate plus a credit spread. Fixed-rate mortgages protect the LP from interest rate
increases during the term and lock in a predictable debt service cost. At maturity, the
mortgage must be refinanced at the then-current market rate, which may be materially higher
or lower than the original rate.

Floating-rate mortgages expose the LP to immediate changes in debt service cost as benchmark
rates move. An upward movement in benchmark rates increases interest expense and reduces the
ICR, potentially triggering the distribution suspension protocol if the rate increase is
sufficient to breach the 1.2× floor.

## Refinancing risk

At mortgage maturity, the LP must either repay the outstanding principal or refinance with
a new mortgage. Refinancing risk arises when credit conditions, property values, or lender
appetite have deteriorated since the original financing: the available mortgage quantum may
be lower (due to LTV compression or a decline in the property's ICR), and the interest rate
may be higher.
If the available refinancing proceeds are insufficient to repay the maturing mortgage, the LP
must inject equity capital from its unit holders or sell the asset to repay the lender.

This refinancing risk is a structural feature of time-limited mortgage financing and is not
specific to direct-hold structures; it applies to all commercially financed real estate assets.

## See also

- [[distribution-declaration-mechanics]] — how the ICR constraint interacts with the
  distribution declaration process
- [[asset-vehicle-isolation]] — how mortgage creditors are limited to the asset of the LP
  in which they lend
