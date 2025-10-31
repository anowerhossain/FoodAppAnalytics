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

## 🧩 How to Use This Document
- ✅ As a **reference guide** for analytics onboarding or dashboard design.  
- 📊 To design **data models** aligned with each KPI.  
- 🧭 As a **decision framework** for prioritizing product or business improvements.  

---

### 👨‍💻 Author
*Business & Product Analytics Documentation — Food Vertical*  
Maintained by: **[Your Name]**  

---
