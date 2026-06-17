# Retention Strategy
Generated: 2026-06-17
Snapshot date: 2025-09-30
Overall churn rate: 46.96%

## Segment Overview

| Segment | Count | Churn % | Avg Recency | Avg Spend | Action Priority |
|---|---:|---:|---:|---:|:---:|
| Dormant | 177 | 90.4% | 211d | 327 | **4** |
| Mid_Tier_At_Risk | 1194 | 58.7% | 105d | 742 | **3** |
| Loyal_Slipping | 287 | 48.1% | 94d | 1952 | **2** |
| New_Customers | 274 | 24.5% | 25d | 727 | **6** |
| High_Value_Unhappy | 188 | 21.8% | 31d | 2267 | **1** |
| Discount_Sensitive | 11 | 9.1% | 36d | 1693 | **3** |
| Champions | 269 | 7.1% | 27d | 2541 | **5** |

## Segment-wise Retention Playbook

### High_Value_Unhappy

**Description:** High spend but support issues or high returns

**Action:** Proactive support call to resolve issues FIRST, then retention offer (account credit/loyalty points)

**Priority:** 1 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** URGENT: Highest churn + highest spend = greatest revenue loss risk

### Loyal_Slipping

**Description:** Good RFM but recency declining (inactive recently)

**Action:** Personalized re-engagement email + product category recommendations based on purchase history

**Priority:** 2 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** Second highest impact; can reverse trend quickly with right nudge

### Discount_Sensitive

**Description:** Frequent buyers but heavily discounted, price-conscious

**Action:** Bundle offers, tier-based discounts (reward loyalty), avoid flat % discounts

**Priority:** 3 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** Large segment; must avoid margin erosion while retaining volume

### Mid_Tier_At_Risk

**Description:** Moderate RFM, mixed signals, majority of customer base

**Action:** Value-led personalized nudge (product recommendations from preferred_category), seasonal campaigns

**Priority:** 3 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** Largest segment; generic retention efforts; segment by category affinity for better results

### Dormant

**Description:** Old recency (>120d), low engagement, at high churn risk

**Action:** 3-touch win-back sequence: email (day 0) → SMS (day 5) → retargeting ad (day 10), then suppress

**Priority:** 4 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** High churn rate; only cost-effective for high-value dormant; suppress low-value after 3 touches

### Champions

**Description:** High RFM, low support issues, brand advocates

**Action:** VIP perks, early product access, exclusive community, referral rewards

**Priority:** 5 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** Maintain loyalty in highest-value segment; low churn but high revenue impact

### New_Customers

**Description:** Tenure ≤ 90 days, onboarding phase

**Action:** Automated onboarding series, first-purchase follow-up, milestone reward (first repeat, 3rd order)

**Priority:** 6 (1=URGENT, 5=maintain, 6=nurture)

**Rationale:** Lower churn in cohort; focus is habit formation, not retention


## Implementation Timeline

1. **Week 1:** Launch High_Value_Unhappy support recovery calls
2. **Week 1-2:** Deploy Loyal_Slipping re-engagement email campaign
3. **Week 2:** Design bundle offers for Discount_Sensitive segment
4. **Week 3:** Launch Mid_Tier_At_Risk personalized campaign
5. **Week 3-4:** Win-back sequence for Dormant customers
6. **Ongoing:** VIP program for Champions, onboarding for New_Customers
