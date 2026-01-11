# KPI

## 🧠 STEP 1: Learn KPI Frameworks in 2 HOURS (Not Days)

### Use ONLY this structure (memorize it):

```
1. Growth KPIs
2. Revenue KPIs
3. Cost KPIs
4. Efficiency KPIs
5. Quality KPIs
6. Customer KPIs
```

That’s it.
Every KPI in the world fits here.

---

## ⚡ STEP 2: Master the **TOP 30 KPIs** (80/20 Rule)

### 🔥 Growth & Product

* DAU / MAU
* Retention Rate
* Churn Rate
* Conversion Rate
* Funnel Drop-off

### 💰 Revenue

* GMV
* Net Revenue
* ARPU
* LTV

### 💸 Cost

* CAC
* Cost per Order
* Fulfillment Cost
* Marketing Spend %

### ⚙️ Operations (VERY IMPORTANT)

* SLA
* TAT
* Order-to-Delivery Time
* Fill Rate
* Cancellation Rate
* Escalation Rate
* Defect Rate

### 😊 Customer

* CSAT
* NPS
* Repeat Rate
* Refund Rate

👉 **These 30 KPIs cover 90% of interviews & jobs**

---

## 🧮 STEP 3: Learn KPIs the ONLY WAY Analysts Use Them (SQL-first)

### KPI learning template (use this every time):

```sql
-- KPI name
-- Business meaning
-- Formula
SELECT
    date,
    COUNT(DISTINCT order_id) AS total_orders,
    COUNT(CASE WHEN status = 'delivered' THEN 1 END) * 1.0 
        / COUNT(*) AS delivery_rate
FROM orders
GROUP BY date;
```

If you can:

* Explain **why**
* Write **SQL**
* Interpret **trend**

👉 You KNOW the KPI.

---

## 📊 STEP 4: Learn KPIs by Industry (4 HOURS TOTAL)

### Focus only on these industries:

#### 🍔 Food / E-commerce (Swiggy, Zomato, Amazon)

* Order volume
* AOV
* Delivery time
* Cancellation %
* Partner utilization

#### 📦 Operations

* Throughput
* Backlog
* SLA breach %
* Cycle time

#### 📱 Product

* Activation
* Retention
* Engagement

---

## 🎥 STEP 5: Use **FAST VIDEO SOURCES** (No Books)

### YouTube (Targeted only):

* Search:
  **“KPI for data analyst interview”**
  **“Product metrics explained simply”**
  **“Operations KPIs dashboard”**

👉 Watch at **1.5x speed**

---

## 📄 STEP 6: Use READY-MADE KPI LIBRARIES (Cheat Codes)

### Bookmark these:

* Klipfolio KPI Library
* Tableau Public dashboards
* Google: *“<industry> KPI list pdf”*

Don’t memorize — **scan & map to your framework**.

---

## 🧠 STEP 7: Interview-Ready KPI Answer Formula (MEMORIZE)

When asked:

> “What KPIs would you track?”

Answer like this:

```
1. Outcome KPI (what business cares about)
2. Driver KPIs (what influences it)
3. Guardrail KPIs (what can break)
4. Action if KPI drops
```

Example (Delivery delay):

* Outcome: On-time delivery %
* Drivers: Rider availability, distance, prep time
* Guardrails: Cancellation rate, cost per order
* Action: Increase supply / reroute orders

🔥 Interviewers LOVE this.

---

## 🗓️ 10-DAY CRASH PLAN (REALISTIC)

| Day | What to do               |
| --- | ------------------------ |
| 1   | Learn KPI framework      |
| 2   | Growth + Product KPIs    |
| 3   | Revenue KPIs             |
| 4   | Cost KPIs                |
| 5   | Ops KPIs                 |
| 6   | Write SQL for KPIs       |
| 7   | Python KPI aggregation   |
| 8   | Dashboard logic          |
| 9   | Case-style KPI questions |
| 10  | Mock interviews          |

---

# 🚀 STEP 1: KPI FOUNDATIONS (30–45 minutes)

## 🎯 Objective of Step 1

By the end of this step, you should be able to:

* Classify **any KPI in 5 seconds**
* Know **why** a KPI exists
* Avoid vanity metrics
* Speak KPIs confidently in interviews

---

## 1️⃣ First: Kill the Confusion (VERY IMPORTANT)

### ❌ Common confusion

* KPI = metric ❌
* KPI = dashboard ❌
* KPI = chart ❌

### ✅ Reality

* **Metric** → Any number
* **KPI** → A metric that drives a **decision or action**

👉 If no action changes → **NOT a KPI**

---

## 2️⃣ KPI vs Metric vs OKR (1-minute clarity)

### Metric

* Total orders
* Total users
* Page views

📌 *Informational only*

### KPI

* On-time delivery %
* Conversion rate
* Churn rate

📌 *Decision-making*

### OKR

* **Objective**: Improve delivery experience
* **Key Results**:

  * On-time delivery ≥ 95%
  * Cancellation ≤ 3%

📌 *Strategic goal*

---

## 3️⃣ The ONLY KPI FRAMEWORK You Need (MEMORIZE THIS)

Every KPI fits into **one of these 6 buckets**:

### 🟢 1. Growth KPIs

👉 *Is the business growing?*

* Users
* Orders
* Traffic
* GMV growth %

---

### 💰 2. Revenue KPIs

👉 *Is the business making money?*

* Revenue
* ARPU
* AOV
* LTV

---

### 💸 3. Cost KPIs

👉 *How much does it cost to run?*

* CAC
* Cost per order
* Delivery cost

---

### ⚙️ 4. Efficiency KPIs

👉 *How well do things run?*

* SLA
* TAT
* Utilization
* Throughput

---

### 🔍 5. Quality KPIs

👉 *How good is the output?*

* Defect rate
* Error rate
* Cancellation %
* Refund %

---

### 😊 6. Customer KPIs

👉 *Are customers happy?*

* Retention
* Churn
* NPS
* CSAT

📌 **If you remember ONLY this → you win interviews**

---

## 4️⃣ The Golden Rule of KPIs (MUST REMEMBER)

> **Outcome KPI → Driver KPIs → Guardrail KPIs**

### Example: Late deliveries

* **Outcome**: On-time delivery %
* **Drivers**:

  * Prep time
  * Rider availability
  * Distance
* **Guardrails**:

  * Cost per order
  * Cancellation rate

🔥 This thinking = senior analyst thinking.

---

## 5️⃣ Vanity KPI vs Action KPI (INTERVIEW FAVORITE)

### ❌ Vanity KPIs

* Total downloads
* Total users
* Total revenue (without context)

### ✅ Action KPIs

* Week-4 retention
* Conversion rate
* Revenue per active user

👉 Always ask: **“What will I do if this drops?”**

---

## 6️⃣ 5-Second KPI Classification Drill (DO THIS)

Classify these:

| KPI          | Bucket     |
| ------------ | ---------- |
| DAU          | Growth     |
| ARPU         | Revenue    |
| CAC          | Cost       |
| SLA breach % | Efficiency |
| Defect rate  | Quality    |
| Churn rate   | Customer   |



---

## 7️⃣ How Interviewers EXPECT You to Speak KPIs

❌ “I will track many KPIs like revenue, users, growth…”

✅

> “I’d start with **Outcome KPIs** aligned to the business goal, then track **Driver KPIs** to understand levers, and **Guardrails** to control cost and quality.”

---

## 🧠 Your 5-Minute Homework (IMPORTANT)

Take **any app you use** (Swiggy, Amazon, Netflix):

1. Write **1 Outcome KPI**
2. Write **3 Driver KPIs**
3. Write **2 Guardrail KPIs**

Do NOT skip this.


---

# 🚀 STEP 2: The TOP 30 KPIs (80/20 Rule)

## 🎯 Objective of Step 2

By the end of this step, you should be able to:

* Name the **right KPIs instantly**
* Explain **what they mean**
* Know **when to use which KPI**
* Sound confident in interviews

❗ No formulas yet. No SQL yet.
Just **what + why + when**.

---

## 🟢 A. Growth & Product KPIs (7)

### 1️⃣ DAU / MAU

* **What**: Daily vs Monthly Active Users
* **Why**: Engagement health
* **When**: Apps, products, platforms

---

### 2️⃣ User Growth Rate

* **What**: % increase in users
* **Why**: Growth momentum
* **When**: Startups, scaling teams

---

### 3️⃣ Conversion Rate

* **What**: Users who complete desired action
* **Why**: Funnel efficiency
* **When**: Signup, checkout, lead flow

---

### 4️⃣ Funnel Drop-off

* **What**: Where users leave
* **Why**: Find friction points
* **When**: Any multi-step flow

---

### 5️⃣ Activation Rate

* **What**: Users reaching “aha” moment
* **Why**: Early product success
* **When**: New user onboarding

---

### 6️⃣ Retention Rate

* **What**: Users who return
* **Why**: Long-term value
* **When**: Subscription, apps

---

### 7️⃣ Churn Rate

* **What**: Users lost
* **Why**: Leakage
* **When**: Paid products, services

---

## 💰 B. Revenue KPIs (6)

### 8️⃣ Revenue

* **What**: Money earned
* **Why**: Business survival
* **When**: Always (but never alone)

---

### 9️⃣ ARPU

* **What**: Revenue per user
* **Why**: Monetization strength
* **When**: Apps, SaaS

---

### 🔟 AOV

* **What**: Average order value
* **Why**: Basket optimization
* **When**: E-commerce, food-tech

---

### 1️⃣1️⃣ LTV

* **What**: Revenue from a user over lifetime
* **Why**: Long-term profitability
* **When**: Subscriptions, loyalty models

---

### 1️⃣2️⃣ GMV

* **What**: Total transaction value
* **Why**: Scale measurement
* **When**: Marketplaces

---

### 1️⃣3️⃣ Net Revenue

* **What**: Revenue after refunds/discounts
* **Why**: Real earnings
* **When**: Finance reporting

---

## 💸 C. Cost KPIs (5)

### 1️⃣4️⃣ CAC

* **What**: Cost to acquire a customer
* **Why**: Growth efficiency
* **When**: Marketing-heavy businesses

---

### 1️⃣5️⃣ Cost per Order

* **What**: Ops cost per transaction
* **Why**: Margin control
* **When**: Logistics, delivery

---

### 1️⃣6️⃣ Fulfillment Cost

* **What**: Delivery + ops cost
* **Why**: Unit economics
* **When**: E-commerce, food delivery

---

### 1️⃣7️⃣ Marketing Spend %

* **What**: Spend as % of revenue
* **Why**: ROI check
* **When**: Campaign analysis

---

### 1️⃣8️⃣ Discount Burn

* **What**: Revenue lost to discounts
* **Why**: Profit leakage
* **When**: Growth-at-all-costs phase

---

## ⚙️ D. Efficiency KPIs (6)

### 1️⃣9️⃣ SLA Compliance %

* **What**: On-time delivery %
* **Why**: Service reliability
* **When**: Ops, logistics

---

### 2️⃣0️⃣ TAT

* **What**: Time to complete process
* **Why**: Speed
* **When**: Ops, support, workflows

---

### 2️⃣1️⃣ Utilization Rate

* **What**: Capacity usage
* **Why**: Resource efficiency
* **When**: Agents, riders, machines

---

### 2️⃣2️⃣ Throughput

* **What**: Output per unit time
* **Why**: Scale efficiency
* **When**: Ops, manufacturing

---

### 2️⃣3️⃣ Backlog

* **What**: Pending work
* **Why**: Bottleneck signal
* **When**: Support, supply chain

---

### 2️⃣4️⃣ Order-to-Delivery Time

* **What**: End-to-end cycle time
* **Why**: Customer experience
* **When**: Delivery businesses

---

## 🔍 E. Quality KPIs (3)

### 2️⃣5️⃣ Defect Rate

* **What**: Errors per unit
* **Why**: Process health
* **When**: Ops, manufacturing

---

### 2️⃣6️⃣ Cancellation Rate

* **What**: Orders cancelled %
* **Why**: Demand-supply mismatch
* **When**: Marketplaces

---

### 2️⃣7️⃣ Refund Rate

* **What**: Refunds issued %
* **Why**: Quality & trust
* **When**: E-commerce

---

## 😊 F. Customer KPIs (3)

### 2️⃣8️⃣ CSAT

* **What**: Customer satisfaction score
* **Why**: Service quality
* **When**: Support, delivery

---

### 2️⃣9️⃣ NPS

* **What**: Recommendation likelihood
* **Why**: Loyalty signal
* **When**: Brand health

---

### 3️⃣0️⃣ Repeat Rate

* **What**: Returning customers %
* **Why**: Loyalty & LTV
* **When**: Consumer businesses

---

## 🧠 HOW to Speak These KPIs (Interview Gold)

When asked:

> “What KPIs would you track?”

Answer like this:

> “I’d start with **Outcome KPIs** like revenue or on-time delivery, then track **Driver KPIs** such as conversion or utilization, and finally **Guardrails** like cost per order and cancellation rate.”

---

## 📝 10-Minute Homework (DO THIS)

Pick **ONE company** (Swiggy / Amazon / Netflix):

1. Choose **3 Outcome KPIs**
2. Choose **5 Driver KPIs**
3. Choose **2 Guardrails**

Write them down.

---

---

# 🚀 STEP 3: KPI FORMULAS + SQL LOGIC (ANALYST MODE)

## 🎯 Objective of Step 3

By the end of this step, you should be able to:

* Write **SQL for KPIs**
* Explain **formula + business meaning**
* Answer **“how did you calculate this?”** confidently

❗ This is where **most candidates fail**.
If you master this → you’re job-ready.

---

# 🧱 The ONLY KPI SQL Pattern You Need

Almost **every KPI** follows one of these patterns:

1. **Ratio KPIs** → numerator / denominator
2. **Average KPIs** → total / count
3. **Time KPIs** → end_time − start_time
4. **Rate KPIs** → condition_count / total

Keep this in mind while learning.

---

# 🟢 A. Growth & Product KPIs (with SQL)

---

## 1️⃣ DAU (Daily Active Users)

### Formula

```
DAU = Count of distinct users active per day
```

### SQL

```sql
SELECT
    activity_date,
    COUNT(DISTINCT user_id) AS dau
FROM user_activity
GROUP BY activity_date;
```

### Interview Tip

👉 Always ask **“what defines active?”** (login, order, click)

---

## 2️⃣ Conversion Rate

### Formula

```
Conversion Rate = Converted users / Total users
```

### SQL

```sql
SELECT
    COUNT(DISTINCT CASE WHEN converted = 1 THEN user_id END) * 1.0
    / COUNT(DISTINCT user_id) AS conversion_rate
FROM funnel_data;
```

### Common Mistake ❌

* Using total events instead of users

---

## 3️⃣ Retention Rate

### Formula

```
Retention = Returning users / Original cohort
```

### SQL (Day-7 retention example)

```sql
SELECT
    COUNT(DISTINCT r.user_id) * 1.0
    / COUNT(DISTINCT c.user_id) AS retention_rate
FROM cohort c
LEFT JOIN returns r
    ON c.user_id = r.user_id
   AND r.day = 7;
```

### Interview Gold

👉 Mention **cohort-based retention**

---

## 4️⃣ Churn Rate

### Formula

```
Churn = Users lost / Total users
```

### SQL

```sql
SELECT
    COUNT(DISTINCT user_id) FILTER (WHERE churned = 1) * 1.0
    / COUNT(DISTINCT user_id) AS churn_rate
FROM users;
```

---

# 💰 B. Revenue KPIs (with SQL)

---

## 5️⃣ Revenue

### Formula

```
Revenue = Sum of order value
```

### SQL

```sql
SELECT
    order_date,
    SUM(order_amount) AS revenue
FROM orders
GROUP BY order_date;
```

❗ Never say revenue without **time granularity**

---

## 6️⃣ AOV (Average Order Value)

### Formula

```
AOV = Total revenue / Total orders
```

### SQL

```sql
SELECT
    SUM(order_amount) * 1.0 / COUNT(order_id) AS aov
FROM orders;
```

---

## 7️⃣ ARPU

### Formula

```
ARPU = Revenue / Active users
```

### SQL

```sql
SELECT
    SUM(order_amount) * 1.0 / COUNT(DISTINCT user_id) AS arpu
FROM orders;
```

---

## 8️⃣ LTV (Simple version)

### Formula

```
LTV = ARPU × Average customer lifetime
```

### SQL (simplified)

```sql
SELECT
    AVG(user_revenue) AS ltv
FROM (
    SELECT
        user_id,
        SUM(order_amount) AS user_revenue
    FROM orders
    GROUP BY user_id
) t;
```

---

# 💸 C. Cost KPIs (with SQL)

---

## 9️⃣ Cost per Order

### Formula

```
Cost per Order = Total cost / Total orders
```

### SQL

```sql
SELECT
    SUM(delivery_cost + packaging_cost) * 1.0
    / COUNT(order_id) AS cost_per_order
FROM orders;
```

---

## 🔟 CAC (Customer Acquisition Cost)

### Formula

```
CAC = Marketing spend / New customers
```

### SQL

```sql
SELECT
    SUM(marketing_spend) * 1.0
    / COUNT(DISTINCT user_id) AS cac
FROM campaigns
WHERE is_new_customer = 1;
```

---

# ⚙️ D. Efficiency KPIs (with SQL)

---

## 1️⃣1️⃣ SLA Compliance %

### Formula

```
SLA % = Orders delivered on time / Total orders
```

### SQL

```sql
SELECT
    COUNT(CASE WHEN delivered_on_time = 1 THEN 1 END) * 1.0
    / COUNT(*) AS sla_compliance
FROM orders;
```

---

## 1️⃣2️⃣ TAT (Turnaround Time)

### Formula

```
TAT = End time − Start time
```

### SQL

```sql
SELECT
    AVG(delivery_time - order_time) AS avg_tat
FROM orders;
```

---

## 1️⃣3️⃣ Utilization Rate

### Formula

```
Utilization = Busy time / Available time
```

### SQL

```sql
SELECT
    SUM(busy_minutes) * 1.0 / SUM(available_minutes) AS utilization
FROM agents;
```

---

# 🔍 E. Quality KPIs (with SQL)

---

## 1️⃣4️⃣ Cancellation Rate

### Formula

```
Cancellation % = Cancelled orders / Total orders
```

### SQL

```sql
SELECT
    COUNT(CASE WHEN status = 'cancelled' THEN 1 END) * 1.0
    / COUNT(*) AS cancellation_rate
FROM orders;
```

---

## 1️⃣5️⃣ Defect Rate

### Formula

```
Defect rate = Defective orders / Total orders
```

### SQL

```sql
SELECT
    COUNT(CASE WHEN defect_flag = 1 THEN 1 END) * 1.0
    / COUNT(*) AS defect_rate
FROM orders;
```

---

# 🧠 INTERVIEW POWER MOVE (MUST USE)

When explaining KPIs, always say:

> “I validated the KPI by checking trends over time and slicing by city/store/user segment to ensure it’s not driven by outliers.”

🔥 This sounds **senior-level**.

---

## 📝 15-Minute Homework (DO THIS)

Pick **ONE KPI**:

* Conversion rate OR
* SLA compliance OR
* Retention rate

Then:

1. Write **formula**
2. Write **SQL**
3. Answer: **What action will you take if it drops?**

---

# 🚀 STEP 4: KPI ANALYSIS IN PYTHON (FAST + PRACTICAL)

## 🎯 Goal of Step 4

After this step, you will be able to:

* Calculate KPIs in **Python (pandas)**
* Do **trend analysis**
* Use **rolling metrics**
* Answer: *“Is this KPI actually getting better or worse?”*

This is **exactly what analysts do after SQL extraction**.

---

## 🧠 Standard Analyst Workflow (MEMORIZE)

```
SQL → pandas → KPI → trend → insight → action
```

SQL gives raw data.
Python gives **thinking + insight**.

---

## 1️⃣ Load Data (baseline)

```python
import pandas as pd

df = pd.read_csv("orders.csv")
df["order_date"] = pd.to_datetime(df["order_date"])
```

Always:

* Convert dates
* Sort by time

---

## 2️⃣ Basic KPI Calculation in Python

### 🔹 Revenue (Daily)

```python
daily_revenue = (
    df.groupby("order_date")["order_amount"]
      .sum()
      .reset_index()
)
```

---

### 🔹 Orders per Day

```python
daily_orders = (
    df.groupby("order_date")["order_id"]
      .nunique()
      .reset_index(name="orders")
)
```

---

### 🔹 AOV

```python
daily_kpi = daily_revenue.merge(daily_orders, on="order_date")
daily_kpi["aov"] = daily_kpi["order_amount"] / daily_kpi["orders"]
```

📌 **Interview line**
“I calculate AOV after aggregating, not row-level.”

---

## 3️⃣ Ratio KPIs (VERY IMPORTANT)

### 🔹 SLA Compliance %

```python
sla = (
    df.groupby("order_date")["delivered_on_time"]
      .mean()
      .reset_index(name="sla_pct")
)
```

Why `.mean()` works?

* 1 = on-time
* 0 = late
  ➡️ mean = %

🔥 Interviewers love this trick.

---

### 🔹 Cancellation Rate

```python
df["is_cancelled"] = (df["status"] == "cancelled").astype(int)

cancel_rate = (
    df.groupby("order_date")["is_cancelled"]
      .mean()
      .reset_index(name="cancel_rate")
)
```

---

## 4️⃣ Rolling Metrics (THIS IS BIG)

Raw KPIs are noisy.
**Analysts smooth data.**

---

### 🔹 7-Day Rolling Average

```python
daily_kpi = daily_kpi.sort_values("order_date")

daily_kpi["aov_7d_avg"] = (
    daily_kpi["aov"]
    .rolling(7)
    .mean()
)
```

📌 Use cases:

* Identify trend
* Ignore daily spikes

---

### 🔹 Rolling SLA %

```python
sla["sla_7d_avg"] = (
    sla["sla_pct"]
    .rolling(7)
    .mean()
)
```

---

## 5️⃣ Week-over-Week (WoW) Change

### 🔹 Revenue WoW %

```python
daily_revenue["rev_wow"] = (
    daily_revenue["order_amount"]
    .pct_change(7)
)
```

📌 Interview gold:

> “I use WoW to detect structural change.”

---

## 6️⃣ Cohort-style Retention (FAST VERSION)

```python
df["order_week"] = df["order_date"].dt.to_period("W")
```

```python
cohort = (
    df.groupby(["user_id", "order_week"])
      .size()
      .reset_index(name="orders")
)
```

Retention logic:

* First week = cohort
* Check presence in future weeks

(Deep cohort analysis comes later — this is enough for interviews.)

---

## 7️⃣ KPI Segmentation (VERY IMPORTANT)

Never trust overall KPIs.

### 🔹 By City

```python
city_kpi = (
    df.groupby("city")["order_amount"]
      .sum()
      .reset_index()
)
```

### 🔹 By Store

```python
store_sla = (
    df.groupby("store_id")["delivered_on_time"]
      .mean()
      .reset_index(name="sla_pct")
)
```

📌 Interview line:

> “Overall KPIs can hide local failures.”

---

## 8️⃣ KPI DROP → RCA Thinking (CRITICAL)

When a KPI drops, always check:

```
Volume → Mix → Process → External
```

Example: SLA drops

* Volume spike?
* City-wise issue?
* Rider availability?
* Weather / holiday?

This thinking > code.

---

## 🧠 3 POWER STATEMENTS (USE THESE)

1️⃣

> “I always validate KPIs using rolling averages.”

2️⃣

> “I segment KPIs before drawing conclusions.”

3️⃣

> “I focus on actionability, not just reporting.”

---

## 📝 15-Minute PRACTICE (DO THIS)

Pick **ONE KPI**:

* Revenue
* SLA %
* Cancellation %

Do in Python:

1. Daily KPI
2. 7-day rolling avg
3. One segmentation (city/store)

---
Excellent.
This is the **FINAL STEP that separates analysts from report makers**.

---

# 🚀 STEP 5: KPI STORYTELLING & DASHBOARD THINKING (INTERVIEW GOLD)

You can know SQL + Python — but **if you can’t tell the story**, you won’t grow fast.

---

## 🎯 Goal of Step 5

After this step, you will be able to:

* Design **clear KPI dashboards**
* Decide **what to show vs hide**
* Explain **what happened, why, and what to do**
* Impress in interviews & stakeholder meetings

---

## 🧠 The ONLY Dashboard Framework You Need

Every good dashboard answers **3 questions**:

```
WHAT happened?
WHY did it happen?
WHAT should we do?
```

If a dashboard doesn’t answer these → it’s useless.

---

## 1️⃣ WHAT happened? (Top layer)

### Show ONLY:

* 3–5 **Outcome KPIs**
* Trends (not raw numbers)
* Comparisons (WoW / MoM)

### Examples

* Revenue trend
* SLA %
* Conversion rate
* Cancellation %

❌ Don’t show:

* 20 KPIs
* Raw tables
* Single-day numbers

---

## 2️⃣ WHY did it happen? (Drill-down layer)

This is where analysts add value.

### Break KPIs by:

* City
* Store / Partner
* Customer segment
* Time of day

Example:

> SLA dropped 3% WoW, driven mainly by **Bangalore (−7%) during dinner hours**

---

## 3️⃣ WHAT should we do? (Action layer)

Every dashboard MUST end with actions.

### Example

* Add riders in Bangalore evenings
* Reduce prep time for top 10 delayed stores
* Pause discounts in low-utilization zones

📌 If no action → KPI is decoration.

---

## 📊 Dashboard KPI Hierarchy (MEMORIZE)

```
Outcome KPIs
↓
Driver KPIs
↓
Guardrail KPIs
```

### Example (Delivery Business)

* Outcome: SLA %
* Drivers: Prep time, Rider utilization
* Guardrails: Cost per order, Cancellation %

---

## 🎯 KPI PER DASHBOARD RULE

| Level     | KPIs |
| --------- | ---- |
| Executive | 3–5  |
| Manager   | 5–8  |
| Analyst   | 8–12 |

If you show more → you confuse.

---

## 🧠 The CEO Slide Rule (IMPORTANT)

Ask yourself:

> “If I had 30 seconds with the CEO, what would I show?”

That’s your **top row**.

---

## 🧩 KPI STORYTELLING TEMPLATE (USE THIS)

Use this exact structure when explaining dashboards:

> “Overall, **[KPI]** changed by **X%** WoW.
> The primary driver was **[dimension]**, especially **[segment]**.
> Secondary impact came from **[factor]**.
> I recommend **[action]**, and will monitor **[guardrail KPI]**.”

🔥 This is **promotion-level communication**.

---

## ❌ Common Dashboard Mistakes (AVOID)

* Showing totals without trends
* Mixing outcome & driver KPIs
* No time comparison
* No segmentation
* No recommendation

---

## 🧠 Real Interview Question & PERFECT Answer

**Q:** *How do you design a KPI dashboard?*

**A:**

> “I first clarify the business goal, then identify outcome KPIs. I add driver KPIs to explain movement and guardrails to control risk. I focus on trends, segmentation, and end every dashboard with actions.”

---

## 📝 FINAL PRACTICE (VERY IMPORTANT)

Choose **ONE business** (Swiggy / Amazon / Netflix):

1. Pick **3 Outcome KPIs**
2. Pick **4 Driver KPIs**
3. Pick **2 Guardrails**
4. Write **1 clear recommendation**

Do this once → you’ve learned KPIs FAST.

---
