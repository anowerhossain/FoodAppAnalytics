# FoodAppAnalytics

# 🍴 Food Delivery Business & Product Analytics — KPI Reference Guide

### 🎯 Objective  
This document outlines key **Business & Product Analytics KPIs** for a food delivery platform.  
It covers **Supply**, **Demand**, **Delivery Operations**, **Product**, and **Financial** segments — describing what each metric means, how to interpret its changes, and how it impacts business decisions.

---

## 🍽️ 1. Supply Side (Restaurants)

| KPI | Definition / Formula | 📈 If It Increases | 📉 If It Decreases | 💼 Business Impact | 🚀 Actionable Steps |
|------|----------------------|-------------------|-------------------|--------------------|--------------------|
| **Active Restaurants** | Number of restaurants receiving ≥1 order in a given period. | More variety & availability → higher orders. | Limited options → fewer customer choices. | Drives customer satisfaction & market coverage. | Onboard new partners, engage inactive restaurants. |
| **Restaurant Retention Rate** | `(Restaurants active this month & last month ÷ Restaurants active last month) × 100` | Stable partner base. | Restaurant churn risk. | Impacts consistency of supply & revenue. | Build loyalty programs, improve support experience. |
| **Commission Rate** | `Total commission earned ÷ GMV` | Higher profitability. | Lower margins. | Affects revenue & partner satisfaction. | Adjust tiered commissions based on volume. |
| **Promotion Participation Rate** | `(Restaurants in promos ÷ Active restaurants) × 100` | Greater promo visibility & sales. | Missed campaign opportunities. | Drives temporary sales uplift. | Educate restaurants on promo ROI, offer tailored campaigns. |

---

## 🛍️ 2. Demand Side (Customers)

| KPI | Definition / Formula | 📈 If It Increases | 📉 If It Decreases | 💼 Business Impact | 🚀 Actionable Steps |
|------|----------------------|-------------------|-------------------|--------------------|--------------------|
| **DAU/MAU Ratio** | `Daily Active Users ÷ Monthly Active Users` | Strong engagement & stickiness. | Weak engagement, occasional use. | Reflects habit formation & app dependence. | Improve UX, add push engagement campaigns. |
| **Order Frequency** | `Total Orders ÷ Active Customers` | Users ordering more often. | Fewer repeat orders. | Affects LTV and retention. | Introduce loyalty programs, subscriptions. |
| **Customer Retention Rate** | `(Returning customers ÷ Total customers) × 100` | Healthy repeat user base. | High churn. | Core growth sustainability metric. | Improve onboarding, personalization, retention campaigns. |
| **CAC (Customer Acquisition Cost)** | `Marketing spend ÷ New customers acquired` | If too high → inefficient spend. | Efficient user acquisition. | Impacts profitability. | Focus on referrals, organic & retention marketing. |
| **LTV (Lifetime Value)** | `AOV × Frequency × Retention × Margin` | Long-term loyal customers. | Low value or poor retention. | Determines marketing ROI & strategy. | Boost retention, cross-sell, and upsell. |
| **Conversion Rate** | `(Orders ÷ App sessions) × 100` | Better user flow & UX. | Funnel friction. | Direct revenue impact. | Simplify checkout, improve offers, reduce errors. |
| **AOV (Average Order Value)** | `GMV ÷ Orders` | Users spending more per order. | Smaller baskets or low-value items. | Affects GMV & profitability. | Encourage bundling, upselling, or minimum thresholds. |

---

## 🚴 3. Delivery Operations

| KPI | Definition / Formula | 📈 If It Increases | 📉 If It Decreases | 💼 Business Impact | 🚀 Actionable Steps |
|------|----------------------|-------------------|-------------------|--------------------|--------------------|
| **On-Time Delivery Rate** | `(Orders delivered within SLA ÷ Total delivered) × 100` | Reliable service, satisfied customers. | Late deliveries. | Impacts customer satisfaction & NPS. | Optimize dispatch & route logic. |
| **Average Delivery Time** | `Sum of delivery times ÷ Total delivered` | (If too high) Inefficient ops. | Faster delivery → happy customers. | Affects retention & perception. | Improve restaurant prep time & routing. |
| **Cancellation Rate** | `(Cancelled orders ÷ Orders placed) × 100` | Operational or UX issues. | Stable service reliability. | Impacts trust, GMV, and user experience. | Identify root causes (rider, restaurant, user). |
| **Rider Utilization Rate** | `(Delivery time ÷ Available time) × 100` | Efficient workforce usage. | Idle riders → cost inefficiency. | Affects delivery cost per order. | Demand forecasting, zone optimization. |
| **Failed Delivery Rate** | `(Failed deliveries ÷ Attempted deliveries) × 100` | Poor address quality or ops issues. | Reliable completion. | Impacts cost and experience. | Address verification, improve comms tools. |

---

## 📱 4. Product & Feature Engagement

| KPI | Definition / Formula | 📈 If It Increases | 📉 If It Decreases | 💼 Business Impact | 🚀 Actionable Steps |
|------|----------------------|-------------------|-------------------|--------------------|--------------------|
| **Feature Adoption Rate** | `(Users using feature ÷ Active users) × 100` | Feature adds value. | Poor discoverability or fit. | Determines product-market success. | Promote via banners, tutorials, or incentives. |
| **Funnel Drop-off Rate** | `(Users not proceeding ÷ Users starting step) × 100` | (High) Journey friction. | Smooth checkout process. | Affects conversion & revenue. | Optimize UX, reduce cart abandonment. |
| **Retention Rate (Day 7 / 30)** | `(Active after N days ÷ New users) × 100` | Users find recurring value. | Product not engaging. | Critical for long-term growth. | Personalization, reactivation, loyalty perks. |
| **Engagement Rate** | `(Feature interactions ÷ Active users) × 100` | High engagement & loyalty. | Users losing interest. | Drives higher LTV. | Gamify app, improve push strategy. |
| **DAU/MAU** | `Daily Active ÷ Monthly Active` | Sticky, habitual usage. | Irregular use. | Key retention signal. | Create daily rewards, streaks, or offers. |

---

## 💰 5. Financial & Strategic KPIs

| KPI | Definition / Formula | 📈 If It Increases | 📉 If It Decreases | 💼 Business Impact | 🚀 Actionable Steps |
|------|----------------------|-------------------|-------------------|--------------------|--------------------|
| **GMV (Gross Merchandise Value)** | `Sum of total order value` | Growth in transactions. | Lower activity. | Core growth metric. | Drive user acquisition & order frequency. |
| **Net Revenue** | `GMV × Commission + Delivery Fee - Discounts` | Healthy income. | Margin pressure. | Reflects true profitability. | Balance promotions vs commissions. |
| **Profit Margin per Order** | `(Revenue - Cost) ÷ Revenue` | Strong unit economics. | High costs, unsustainable model. | Indicates financial efficiency. | Optimize logistics, reduce variable costs. |
| **ROI (Feature/Campaign)** | `(Gain - Cost) ÷ Cost` | Positive return. | Inefficient investment. | Justifies scaling of initiatives. | A/B test new features before rollout. |

---

## 🔄 KPI Interrelationships

- **GMV** = f(**AOV**, **Orders**)  
- **Orders** depend on **Retention**, **Frequency**, and **Active Restaurants**  
- **Retention** improves when **On-Time Rate** ↑ & **Delivery Time** ↓  
- **Profitability** depends on **Commission**, **CAC**, and **LTV** balance  

**Key Insight:** improving one metric (e.g., retention) often has a cascading effect on others (e.g., CAC efficiency, GMV, LTV).

---

## 🧠 Example Scenarios

| Scenario | Insight | Action | Impact |
|-----------|----------|--------|--------|
| On-Time Delivery dropped by 7% in Dhaka | Delay during lunch peak hours | Add rider incentives for 12–3 PM | Improved SLA, +5% retention |
| Feature adoption (Favorites) only 20% | Users unaware of it | Add in-app banner promotion | Adoption ↑ 60%, repeat orders ↑ 10% |
| CAC increased by 20% | Over-reliance on ads | Boost referral program | CAC ↓ 15%, LTV ↑ |

---

# 🍔 Food Delivery App – Analytical Questions & KPIs

This document contains analytical questions, key metrics, and example analytical thinking scenarios for a **Food Delivery App**.  
It’s designed for **Business & Product Analytics** professionals preparing for analytical roles or building dashboards and insight frameworks.

---

## 📊 1. Orders & GMV

| # | Analytical Question | Related Metric | Why It Matters |
|---|----------------------|----------------|----------------|
| 1 | How is the trend of daily active orders (YoY, MoM, WoW)? | **Orders / Day** | Helps track business growth and demand seasonality. |
| 2 | What is the average order value (AOV) trend across different cities and cuisines? | **AOV = GMV / Orders** | Identifies upsell/cross-sell opportunities. |
| 3 | How much GMV is contributed by repeat vs new customers? | **GMV Share** | Evaluates retention and acquisition balance. |
| 4 | Which restaurants contribute most to GMV and their avg. delivery time? | **GMV per Restaurant** | Pinpoints top partners and operational performance. |
| 5 | What % of GMV is lost due to cancellations/refunds? | **Cancelled GMV %** | Quantifies revenue leakage and service reliability. |

---

## 👥 2. Customer Behavior & Retention

| # | Analytical Question | Related Metric | Why It Matters |
|---|----------------------|----------------|----------------|
| 6 | What is the Day 7 and Day 30 retention of new users? | **Retention Rate = Returning Users / New Users** | Indicates stickiness and long-term growth. |
| 7 | What % of users churn after their first order? | **Churn Rate = Lost Users / Active Users** | Highlights onboarding or experience gaps. |
| 8 | How does order frequency differ for loyal vs casual users? | **Orders per User** | Helps segment customers and plan loyalty programs. |
| 9 | What is the conversion rate from browse → order? | **Conversion = Orders / Visitors** | Shows funnel efficiency. |
| 10 | Which user segment has the highest LTV? | **LTV = AOV × Frequency × Duration** | Identifies high-value cohorts for targeting. |

---

## 🍽️ 3. Restaurant Performance

| # | Analytical Question | Related Metric | Why It Matters |
|---|----------------------|----------------|----------------|
| 11 | Which restaurants have high rejection/cancellation rates? | **Restaurant Cancellation %** | Affects customer satisfaction and reliability. |
| 12 | How does restaurant rating correlate with order volume? | **Correlation (Rating, Orders)** | Measures the impact of quality on sales. |
| 13 | Do promoted restaurants show better conversion or AOV? | **AOV / Conversion** | Tests effectiveness of promotion spend. |
| 14 | What’s the GMV impact of restaurant onboarding? | **Δ GMV / New Restaurants** | Measures supply-side growth efficiency. |

---

## 🚴 4. Delivery Operations

| # | Analytical Question | Related Metric | Why It Matters |
|---|----------------------|----------------|----------------|
| 15 | What’s the average delivery time by city/time of day? | **Avg Delivery Time = Drop-off - Pickup** | Detects bottlenecks in logistics. |
| 16 | How many orders face rider unavailability or late pickups? | **Delayed Orders %** | Highlights supply-demand mismatches. |
| 17 | How does restaurant-to-customer distance affect cancellations? | **Correlation (Distance, Cancellation)** | Optimizes dispatch & delivery zone logic. |

---

## 💸 5. Marketing & ROI

| # | Analytical Question | Related Metric | Why It Matters |
|---|----------------------|----------------|----------------|
| 18 | What’s the CAC for each acquisition channel? | **CAC = Spend / New Users** | Evaluates marketing efficiency. |
| 19 | What’s the ROI of first-order discounts? | **ROI = Incremental Revenue / Spend** | Determines profitability of promos. |
| 20 | Do campaign-driven users show better engagement? | **Engagement Rate, LTV** | Tests marketing quality, not just volume. |

---

## 🧮 Key Metric Formulas

| Metric | Formula | Interpretation |
|--------|----------|----------------|
| **GMV (Gross Merchandise Value)** | Σ(Order Value) | Overall sales volume. |
| **AOV (Average Order Value)** | GMV / Orders | Avg spend per order. |
| **CAC (Customer Acquisition Cost)** | Marketing Spend / New Customers | Cost of acquiring a new customer. |
| **LTV (Lifetime Value)** | AOV × Frequency × Duration | Value of a user over time. |
| **Conversion Rate** | Orders / Visitors | Funnel efficiency. |
| **Churn Rate** | Lost Users / Active Users | Customer loss rate. |
| **Retention Rate** | Returning Users / Total Users | Customer loyalty. |
| **On-time Delivery %** | On-time Deliveries / Total Deliveries | Logistics reliability. |
| **Cancellation %** | Cancelled Orders / Total Orders | Quality and service level indicator. |
| **Avg Delivery Time** | Drop-off - Pickup | Speed and efficiency. |

---

## 🧠 Analytical Thinking Example

### ❓ Question: Why is customer churn high after their first order?

### 🔍 How to Analyze It

| Step | What to Do | Tools / Data Needed |
|------|-------------|--------------------|
| 1 | Identify churned users (placed 1 order, no activity after X days). | SQL cohort analysis, retention table. |
| 2 | Segment by **region, cuisine, delivery time, order rating, promo use**. | User tables, order metadata, feedback logs. |
| 3 | Compare churned vs retained users on key dimensions: AOV, delivery delay, satisfaction score. | Exploratory data analysis, BI dashboard. |
| 4 | Conduct funnel drop-off analysis (App Open → Browse → Add to Cart → Checkout → Order). | Product analytics / Amplitude / Mixpanel. |
| 5 | Analyze NPS or CSAT feedback for complaints (cold food, late delivery, wrong items). | Text mining or survey data. |
| 6 | Check if first-order experience was **discount-driven** (high promo dependency). | Campaign attribution data. |
| 7 | Quantify financial impact: lost LTV × churned users = revenue leakage. | SQL + Financial model. |

### 📈 Possible Findings

- Long delivery times or order rejections cause dissatisfaction.  
- Discount-only customers didn’t find long-term value.  
- Poor first-order UX or app bugs reduced conversion to repeat.  
- Limited restaurant options in new cities.  

### 💡 Actionable Insights

- Introduce **“Second Order Offers”** to retain first-time users.  
- Launch **delivery quality monitoring** dashboard (alerts for >45 min).  
- Improve **onboarding & discovery UX** (show popular restaurants first).  
- Implement **feedback-driven recovery** (auto-compensate poor experience).  

---


# 🧠 Diagnostic Analysis Guide — Food Delivery App

This section focuses on **“Why” analytical questions** that help uncover the root causes of metric changes.  
Each scenario assumes you’re monitoring KPIs (GMV, Orders, AOV, Retention, etc.) and notice a change — either up 📈 or down 📉.  
The goal: **translate metrics into business actions.**

---

## 1. Why has customer churn increased by 12% this month?
**Possible Causes**
- Delivery delays or poor first-order experience.  
- Reduced discounts or promo offers expired.  
- Service downtime or fewer active restaurants.

**How to Analyze**
- Run retention cohort by order week.  
- Compare delivery time, ratings, and refund rates for churned vs retained users.  
- Review promo campaign calendar overlap.

**Data Needed:** user_orders, delivery_logs, campaigns, feedback.

---

## 2. Why has Average Order Value (AOV) dropped by 8%?
**Possible Causes**
- More low-priced menu items ordered.  
- Discounts increased or smaller order baskets.  
- Shift toward budget restaurants.

**How to Analyze**
- Segment orders by restaurant type, category, and city.  
- Check campaign data for high discount usage.  
- Trend item count per order and price mix.

**Data Needed:** order_items, restaurants, promotions.

---

## 3. Why has Gross Merchandise Value (GMV) declined by 10%?
**Possible Causes**
- Drop in total orders or AOV.  
- Fewer active users or higher churn.  
- Reduced restaurant availability.

**How to Analyze**
- Break down GMV = Orders × AOV.  
- Compare week-over-week growth by city or restaurant.  
- Identify external factors (weather, events, outages).

**Data Needed:** orders, user_sessions, restaurant_status.

---

## 4. Why did total orders drop by 15% compared to last month?
**Possible Causes**
- Seasonal change or festival period ended.  
- Decrease in marketing campaigns.  
- App performance or checkout issues.

**How to Analyze**
- Funnel analysis: App Visit → Cart → Checkout → Order.  
- A/B test logs or system downtime records.  
- Marketing spend vs order correlation.

**Data Needed:** funnel_events, marketing_spend, app_logs.

---

## 5. Why did user retention rate decrease by 5%?
**Possible Causes**
- Poor re-engagement campaigns.  
- Service inconsistency (late deliveries, stockouts).  
- Lack of loyalty or referral incentives.

**How to Analyze**
- Track reactivation campaign performance.  
- Compare experience scores for retained vs churned users.  
- Segment by customer acquisition source.

**Data Needed:** retention_table, campaign_logs, csat_scores.

---

## 6. Why has customer acquisition cost (CAC) increased by 20%?
**Possible Causes**
- Increased ad competition or higher CPC.  
- Inefficient targeting or low conversion.  
- Fewer organic installs.

**How to Analyze**
- Track CAC by channel (Facebook, Google, Referrals).  
- Measure conversion funnel performance.  
- Evaluate creative performance and CTR.

**Data Needed:** marketing_channels, user_acquisition, conversions.

---

## 7. Why did lifetime value (LTV) per user fall by 10%?
**Possible Causes**
- Lower order frequency or smaller baskets.  
- Shorter retention duration.  
- Promo-heavy acquisition leading to low-quality users.

**How to Analyze**
- Compute LTV decomposition: AOV × Frequency × Duration.  
- Cohort users by acquisition source and track 90-day value.  
- Compare revenue vs marketing cost ROI.

**Data Needed:** user_orders, retention_data, acquisition_source.

---

## 8. Why has conversion rate from browse → order dropped by 6%?
**Possible Causes**
- App performance lag or checkout issues.  
- High delivery fees or unavailable restaurants.  
- Poor product discovery.

**How to Analyze**
- Funnel analysis in Amplitude / Mixpanel.  
- Compare session duration, add-to-cart rate.  
- Check app error logs and A/B experiment data.

**Data Needed:** funnel_events, app_errors, pricing_tables.

---

## 9. Why has the on-time delivery rate dropped by 9%?
**Possible Causes**
- Rider shortages or peak-hour congestion.  
- Restaurant preparation delays.  
- Poor route optimization.

**How to Analyze**
- Compare delivery times by zone and shift.  
- Map late deliveries vs weather or traffic data.  
- Monitor rider supply-demand ratio.

**Data Needed:** delivery_logs, rider_availability, weather_api.

---

## 10. Why have order cancellations increased by 11%?
**Possible Causes**
- Restaurant stockouts or delayed preparation.  
- Rider unavailability.  
- Customer-side cancellations due to high wait times.

**How to Analyze**
- Categorize cancellation reasons.  
- Check average time to assign riders.  
- Identify top cancelling restaurants.

**Data Needed:** cancellation_logs, restaurant_data, rider_dispatch.

---

## 11. Why has repeat purchase rate declined by 7%?
**Possible Causes**
- First-order disappointment.  
- Lack of personalized re-engagement.  
- High competition or alternative platforms.

**How to Analyze**
- Track 2nd order conversion per user.  
- Analyze satisfaction scores for 1st order.  
- Compare repeat rates across promo cohorts.

**Data Needed:** user_orders, csat, promotions.

---

## 12. Why has delivery time increased by 6 minutes on average?
**Possible Causes**
- Traffic congestion or weather issues.  
- Reduced rider capacity.  
- Longer restaurant preparation times.

**How to Analyze**
- Time-series delivery duration vs rider supply.  
- Split by city, shift, cuisine type.  
- Compare to SLA thresholds.

**Data Needed:** delivery_time_logs, rider_shift_data.

---

## 13. Why has A/B tested feature adoption decreased by 10% after release?
**Possible Causes**
- Feature not clearly visible in UI.  
- Poor user education or relevance.  
- Technical issues on mobile devices.

**How to Analyze**
- Compare adoption across device types and cohorts.  
- Check crash/error logs.  
- Run user journey heatmaps.

**Data Needed:** ab_test_results, user_events, device_logs.

---

## 14. Why have restaurant ratings dropped by 0.3 stars on average?
**Possible Causes**
- Quality decline due to rush hours.  
- Packaging or temperature issues.  
- Delivery experience impacting restaurant rating.

**How to Analyze**
- Sentiment analysis on review comments.  
- Segment by cuisine, time of day, order volume.  
- Cross-check delivery delays vs rating drops.

**Data Needed:** reviews, sentiment_scores, delivery_logs.

---

## 15. Why has the promo redemption rate fallen by 25%?
**Possible Causes**
- Ineffective communication or expired codes.  
- Reduced promo visibility in app.  
- Target audience mismatch.

**How to Analyze**
- Promo impressions vs redemptions.  
- Analyze campaign reach and timing.  
- Check promo eligibility filters.

**Data Needed:** campaign_logs, user_segments, promo_events.

---

## 16. Why has the refund rate increased by 5%?
**Possible Causes**
- Incorrect or missing items.  
- Payment gateway issues.  
- Delivery failures.

**How to Analyze**
- Categorize refunds by cause.  
- Check restaurants with repeated refund cases.  
- Identify logistic hotspots causing failures.

**Data Needed:** refund_logs, restaurant_data, payment_records.

---

## 17. Why has new restaurant onboarding slowed down by 18%?
**Possible Causes**
- Delays in approval process.  
- Reduced acquisition efforts or incentives.  
- Market saturation.

**How to Analyze**
- Track funnel: signup → approval → active.  
- Compare partner acquisition campaign budgets.  
- Interview sales/ops teams.

**Data Needed:** restaurant_onboarding, partner_sales, crm_logs.

---

## 18. Why has rider churn increased by 10%?
**Possible Causes**
- Low incentive payments.  
- Long idle time between deliveries.  
- Poor support or app issues.

**How to Analyze**
- Calculate earnings/hour trends.  
- Correlate churn with low-earning shifts.  
- Review feedback surveys.

**Data Needed:** rider_activity, payouts, survey_feedback.

---

## 19. Why has delivery success rate dropped by 3%?
**Possible Causes**
- More failed deliveries or address mismatches.  
- System bugs in assignment algorithm.  
- Poor weather conditions.

**How to Analyze**
- Review failure codes by city.  
- Check GPS mismatches and address formats.  
- Audit delivery app logs.

**Data Needed:** delivery_logs, gps_tracking, error_events.

---

## 20. Why has app engagement (DAU/MAU) decreased by 8%?
**Possible Causes**
- Reduced push notification effectiveness.  
- Feature fatigue or poor UX.  
- Competing apps or external factors.

**How to Analyze**
- Monitor session frequency and duration.  
- Evaluate push open rate & CTR.  
- Review product release impact on engagement.

**Data Needed:** user_sessions, push_notification_logs, feature_flags.

---

## 🔍 How to Use These Questions

1. **Detect KPI Movement:** Monitor dashboards daily/weekly.  
2. **Trigger Root Cause Analysis:** Ask “Why?” when change > ±5%.  
3. **Segment & Correlate:** Use SQL, BI, and product analytics tools.  
4. **Communicate Findings:** Convert metrics into actionable business recommendations.

# Possible Causes of High Cart Abandonment
1️⃣Pricing & Cost Issues
Unexpected delivery fees, taxes, or service charges.
Cart value too high or perceived as expensive.
Lack of discounts or offers.
2️⃣ Checkout Process Friction
Too many steps to complete the order.
Forced account creation.
Complex forms (address, payment, contact info).
Slow app or website performance.
3️⃣ Payment Issues
Limited payment options.
Failed payment transactions.
Security concerns or lack of trust badges.
4️⃣ User Behavior & Intent
Browsing without intent to buy (window shopping).
Comparison with competitors.
Decision fatigue from too many menu options.
5️⃣ Delivery & Logistics Concerns
Long estimated delivery times.
Lack of clarity on delivery charges or schedules.
No live order tracking.
6️⃣ Technical & UX Problems
App crashes or slow loading pages.
Bugs in the cart or checkout flow.
Poor mobile responsiveness.
7️⃣ External Distractions
Users get interrupted during checkout.
Users abandon cart while switching devices or sessions.
