---
schema: foundry-doc-v1
title: "Debt service and financing structure"
slug: debt-service-and-financing-structure
category: financial-model
index_group: financing-discipline
type: topic
content_type: topic
quality: complete
short_description: "General commercial-mortgage financing conventions — loan-to-value limits, amortisation, interest-rate and refinancing risk — and how they interact with the ICR borrowing covenant; not the Direct-Hold Solutions' own planned debenture financing."
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-09-06
editor: woodfine-editorial
paired_with: debt-service-and-financing-structure.es.md
---

External mortgage debt is not how the Direct-Hold Solutions are financed. This article describes
the general conventions of commercial-mortgage financing: the loan-to-value limit a lender sets,
amortisation and interest-only terms, interest-rate exposure, and refinancing risk. It then shows
how each interacts with the 1.20× [[cre-financial-metrics|Interest Coverage Ratio]] (ICR) floor
established as a covenant in each direct-hold
[[limited-partnership-structure|limited partnership]]'s governing agreement. It is market background, not a description of the vehicles' own capital structure. For
that — equity-funded unlevered construction, followed by First Secured Mortgage Debentures planned
to be issued by the vehicle itself rather than borrowed from an external lender — see
[[narrow-bank-financial-model|the Narrow Bank Financial Model]].

## Key takeaways

- In a conventional commercial mortgage, debt is secured against a specific property; the lender
  has no recourse to other assets or to the equity of a parent holding company absent specific
  guarantees.
- Mortgage size is constrained by the lender's loan-to-value (LTV) limit. The 1.20× ICR floor is a
  separate and independent constraint, established as a covenant in the partnership's governing
  agreement rather than imposed by a lender.
- Fixed-rate mortgage debt reduces income statement volatility during the fixed term but
  creates refinancing exposure at maturity; floating-rate or variable-rate debt creates
  immediate income sensitivity to benchmark rate changes.

## Loan-to-value constraint

Commercial mortgage lenders set a maximum loan as a percentage of the property's appraised
value. At 65% LTV, for example, a property appraised at $10,000,000 supports a mortgage of
$6,500,000; the remaining $3,500,000 of value must be funded with equity from the borrower's own
capital. The LTV ratio is assessed at origination and may be tested again at refinancing or
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

The ICR calculation uses total interest obligations, not total debt service (principal plus
interest). An interest-only mortgage with a given interest cost produces the same ICR test result
as an amortising mortgage with the same interest rate and a lower outstanding principal; the
principal repayment portion of a fully amortising mortgage is not included in the denominator of
the ICR test. The distinction matters wherever the covenant is applied, whatever the instrument
being tested.

## Interest rate risk

The interest rate on a commercial mortgage can be fixed for the term or floating based on a
benchmark rate plus a credit spread. Fixed-rate mortgages protect the borrower from interest rate
increases during the term and lock in a predictable debt service cost. At maturity, the
mortgage must be refinanced at the then-current market rate, which may be materially higher
or lower than the original rate.

Floating-rate mortgages expose the borrower to immediate changes in debt service cost as benchmark
rates move. An upward movement in benchmark rates increases interest expense and reduces the
ICR. Where an ICR covenant applies, a sufficiently large rate increase can constrain the capacity
to issue further secured debt by pushing coverage toward the 1.20× floor.

## Refinancing risk

At mortgage maturity, a borrower must either repay the outstanding principal or refinance with
a new mortgage. Refinancing risk arises when credit conditions, property values, or lender
appetite have deteriorated since the original financing: the available mortgage quantum may
be lower (due to LTV compression or a decline in coverage), and the interest rate may be higher.

Where refinancing proceeds fall short of the maturing principal, a conventionally financed
borrower must meet the difference from another source — additional equity from its sponsors, or a
sale of the asset. That exposure belongs to external mortgage financing, not to the direct-hold
vehicles: under the [[narrow-bank-financial-model|Narrow Bank Financial Model]], unit holders
cannot be required to contribute additional capital to cover debt obligations.

This refinancing risk is a structural feature of time-limited mortgage financing and is not
specific to direct-hold structures; it applies to all commercially financed real estate assets.

## See also

- [[narrow-bank-financial-model]] — the Direct-Hold Solutions' own planned two-phase financing,
  which does not use external mortgage lenders
- [[distribution-declaration-mechanics]] — how the ICR constraint interacts with the
  distribution declaration process
- [[asset-vehicle-isolation]] — how mortgage creditors are limited to the asset of the LP
  in which they lend
