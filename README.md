#  Porter Business & Operational Performance Analysis

Welcome to the **Porter Business & Operational Performance Analysis**  This project presents an end-to-end operational and revenue performance evaluation built in Microsoft Excel. The analysis explores key business drivers—including order volume dynamics, revenue distribution, SLA delivery efficiency, hourly fleet utilization, and market performance.

---

##  Overview

The objective of this analysis is to evaluate operational bottlenecks and revenue drivers across various dimensions—such as geographic markets, cuisine categories, order value brackets, time-of-day order patterns, and delivery lead times—to identify actionable optimization opportunities.

###  Key Performance Indicators (KPIs)
* **Total Revenue:** ₹52.75 Cr
* **Total Orders:** 196,402
* **Average Order Value (AOV):** ₹2,685.61
* **On-Time Delivery Rate (<45 min):** 52.0%
* **Average Delivery Time:** 47.54 Min
* **Average Partner Utilization:** 85.4%
---

##  Tools & Methods Used

###  Tools
* **Microsoft Excel**: Primary platform utilized for dataset cleaning, transformation, dynamic aggregations, formula modeling, and visual report design.

###  Analytical Methods & Features
1. **Data Cleaning & Preprocessing**:
   * Standardized data formats across currency values, timestamps, durations, and categorical labels.
   * Calculated operational metrics such as order delivery brackets, hourly time buckets, and SLA compliance flags[.

2. **Excel Formulas & Analytical Modeling**:
   * `SUMIFS`, `COUNTIFS`, and `AVERAGEIFS` for multi-condition regional, hourly, and SLA performance calculations.
   * `TEXT()` and time-based functions to parse time-of-day distributions and hourly peak trends.
   * Logical and threshold functions to group orders into price tiers (`<₹1K`, `₹1K-2K`, `₹2K-3K`, `₹3K-5K`, `₹5K+`) and delivery time windows (`0-30 min`, `31-45 min`, `46-60 min`, `61-90 min`, `>90 min`).

3. **Pivot Tables & Multi-Dimensional Data Aggregation**:
   * Aggregated market-level order volumes and total revenue to identify high-performing territories vs. expansion targets.
   * Evaluated partner fleet utilization patterns across time periods and market zones.

4. **Visual Dashboarding & Reporting**:
   * Built visual breakdowns using horizontal bar charts, doughnut distribution charts, and timeline trend layouts.
   * Formatted performance highlights to distinguish SLA breach points and revenue concentration.

---

##  Key Insights & Analytical Findings

1. **Revenue & Market Dynamics**:
   * **Top Revenue Drivers:** Market 2 (₹14.4 Cr revenue, 54.8K orders) and Market 4 (₹13.7 Cr revenue, 47.4K orders) account for over 53% of total revenue[cite: 2].
   * **Expansion Targets:** Markets 5 and 6 remain underpenetrated, representing under 10% of total order volume each[cite: 2].
   * **Consistent AOV:** Average order value is highly uniform across all regions, ranging from ₹2,414 (Market 5) to ₹2,899 (Market 4)[cite: 2].

2. **Category & Order Value Distribution**:
   * **Category Leaders:** Fast-food staples like **Pizza** (₹5.19 Cr) and **American** (₹5.14 Cr) generate over 20% of total category revenue[cite: 2].
   * **Order Concentration:** 79% of all orders sit within the ₹1,000–₹5,000 price range, led by the ₹1K–2K bracket (33% / 65.3K orders)[cite: 2].

3. **Temporal Demand & Fleet Utilization**:
   * **Late Night Dominance:** Late Night orders (143.6K orders / 73% of total volume) represent the core revenue pillar, peaking drastically around 2:00 AM (36,809 orders).
   * **Weekend Surge:** Weekend demand peaks on Saturday (34.4K orders) and Sunday (33.4K orders), showing a 44% surge compared to mid-week troughs (Tuesday: 23.9K)].
   * **Utilization Imbalance:** Partner fleet utilization drops to a low of 44% at 14:00 (2:00 PM) before surging to 90% during evening peak hours (19:00–20:00).

4. **Delivery Bottlenecks & SLA Compliance**:
   * **SLA Breaches:** On-time delivery (<45 min) is only 52%[cite: 2]. 48% of orders breach the 45-minute mark, with nearly 39,000 deliveries taking over 60 minutes.
   * **Regional Disparities:** Market 1 experiences the longest average delivery time at 51 minutes, compared to 46 minutes in Markets 2 and 5[cite: 2].

---

##  Strategic Recommendations

* **Shift Fleet Allocation to Late-Night Hours:** Reallocate partner driver schedules to match the severe 2:00 AM demand peak (36.8K orders) and introduce late-night completion incentives to enhance fulfillment speed.
* **Optimize Market 1 Logistics Protocols:** Streamline merchant dispatch procedures and update route optimization algorithms specifically within Market 1 to reduce its 51-minute average delivery time.
* **Drive Mid-Day Promotional Campaigns:** Launch targeted lunch and early afternoon promotions to boost demand during the 14:00 utilization slump (44% partner utilization) and smooth out operational load.

---

Thank you for taking the time to check out this project! Your interest, feedback, and contributions mean a lot. If you have any suggestions feel free to share. Don't forget to ⭐ this repository if you found it helpful it really helps others find it too.

Happy coding! 
