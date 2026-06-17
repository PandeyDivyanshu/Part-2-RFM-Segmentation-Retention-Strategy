# Manual Review Cases
Generated: 2026-06-17
Snapshot date: 2025-09-30

## Overview

These top 15 customers have conflicting signals (mixed high/low engagement/value) and merit manual review for segment reassignment or targeted intervention.

**Conflict Score Legend:**
- **+2 points:** High spend (>75th percentile) + 2+ support tickets (unhappy high-value)
- **+2 points:** High discount usage (>40%) + moderate recency 31-90d (lapsed but price-sensitive)
- **+2 points:** High engagement (≥5 sessions) + old recency >60d (active but long time since purchase)
- **+1 point:** High returns (>30%) + frequent buyer (quality concern)

## Top 15 Manual Review Cases

| Customer ID | Segment | Recency | Frequency | Spend (₹) | Tickets | Return % | Discount % | Sessions | Churn | Score |
|---|---|---:|---:|---:|---:|---:|---:|---:|:---:|---:|
| CUST00194 | Loyal_Slipping | 80d | 3 | ₹2968 | 1 | 33% | 41% | 13 | 0 | 5 |
| CUST00438 | Loyal_Slipping | 64d | 3 | ₹2466 | 2 | 100% | 16% | 6 | 1 | 5 |
| CUST00095 | New_Customers | 65d | 1 | ₹373 | 1 | 0% | 41% | 10 | 1 | 4 |
| CUST00130 | Mid_Tier_At_Risk | 88d | 1 | ₹1272 | 0 | 0% | 48% | 9 | 0 | 4 |
| CUST00138 | Mid_Tier_At_Risk | 61d | 1 | ₹905 | 0 | 0% | 46% | 5 | 0 | 4 |
| CUST00174 | Mid_Tier_At_Risk | 86d | 1 | ₹169 | 0 | 0% | 42% | 14 | 0 | 4 |
| CUST00177 | Mid_Tier_At_Risk | 82d | 1 | ₹255 | 0 | 0% | 42% | 12 | 0 | 4 |
| CUST00440 | Mid_Tier_At_Risk | 64d | 1 | ₹325 | 1 | 0% | 56% | 5 | 1 | 4 |
| CUST00632 | Mid_Tier_At_Risk | 61d | 1 | ₹1079 | 0 | 0% | 45% | 11 | 1 | 4 |
| CUST00652 | Loyal_Slipping | 75d | 2 | ₹2138 | 0 | 0% | 50% | 13 | 0 | 4 |
| CUST00691 | Loyal_Slipping | 61d | 2 | ₹1223 | 0 | 0% | 52% | 14 | 0 | 4 |
| CUST00771 | Mid_Tier_At_Risk | 90d | 1 | ₹457 | 1 | 0% | 41% | 8 | 1 | 4 |
| CUST00833 | Mid_Tier_At_Risk | 67d | 1 | ₹1143 | 0 | 0% | 49% | 6 | 1 | 4 |
| CUST00853 | New_Customers | 61d | 1 | ₹319 | 1 | 0% | 47% | 9 | 1 | 4 |
| CUST01026 | Mid_Tier_At_Risk | 65d | 1 | ₹221 | 0 | 0% | 43% | 9 | 1 | 4 |

## Recommended Actions by Conflict Type

### Type 1: High-Value + Support Issues (upgrade to "Support Priority")
Customers with high spend but 2+ support tickets.
**Action:** Pro-active support outreach; offer loyalty credit; assess satisfaction.
**Expected Outcome:** Convert to Champions or stabilize in High_Value_Unhappy.

### Type 2: Price-Sensitive with Lapsed Recency (reactivation offer)
Customers with high discount usage but 31-90 days since last purchase.
**Action:** Limited-time bundle or milestone offer; re-engagement campaign.
**Expected Outcome:** Move to Loyal_Slipping or back to active buying.

### Type 3: Engaged but Long Recency (conversion friction?)
Customers with 5+ recent sessions but >60 days since purchase.
**Action:** Exit-intent survey; check cart abandonment; product rec email.
**Expected Outcome:** Understand conversion barrier; improve offer relevance.

### Type 4: Quality Concern (high returns + repeat buyer)
Customers with >30% return rate but multiple repeat purchases.
**Action:** Quality/fit issue investigation; product education; size guide/review.
**Expected Outcome:** Reduce returns; improve CLTV; lower churn.

