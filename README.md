# 🛒 Retail Customer Segmentation & Tiered Loyalty Strategy

## 📊 Project Overview
In a grocery market defined by intense price competition and economic downturn, sustaining customer loyalty is critical. This project explores how a major grocery retailer can maximize holiday profitability by designing a targeted, data-driven tiered membership campaign. 

By analyzing transaction records, demographics, and behavioral data, this project utilizes RFM segmentation to identify the most profitable customer groups. The analysis bridges the gap between raw data and business strategy, delivering actionable recommendations across product focus, channel marketing, and personalized communication to protect market share and drive revenue.

**[👉 View the full interactive HTML Data Report here](https://anhdao-github.github.io/Loyalty-Strategy-for-a-Major-Grocery-Retailer/)**

## 🛠️ Tech Stack & Methodology
* **Language:** R
* **Libraries:** `tidyverse` (dplyr, tidyr), `ggplot2`, `scales`, `corrplot`
* **Segmentation Models:** RFM Analysis (Recency, Frequency, Monetary), 2x2 Value Matrix (Total Spend vs. Income)
* **Statistical Analysis:** Correlation Analysis, Demographic & Behavioral Profiling
* **Business Frameworks:** STP (Segmentation, Targeting, Positioning), The 4Ps of Marketing

## 💡 Key Data Insights
1. **The "Star" Imbalance:** The most valuable segments (Champions, Loyal Customers, Potential Loyalists) make up less than a third of the customer base but account for ~45% of total revenue. They are typically older, affluent, and prefer in-store shopping for premium categories (wine and meat).
2. **The Digital Disconnect:** The largest segment pool (>35% of the base) consists of "Light" or "At Risk" customers. They are highly active digitally (visiting the website frequently) but contribute very little to actual revenue, indicating they are budget-conscious comparison shoppers.
3. **The Complaint Paradox:** Correlation analysis reveals zero linear relationship between customer value (income/spend) and complaint rates. Dissatisfaction is spread evenly across all segments, highlighting a systemic operational challenge rather than a segment-specific issue.

## 🎯 Strategic Recommendations (The 4Ps)
* **Product:** Leverage high-margin strengths by creating exclusive premium bundles (e.g., wine and meat pairings) for top-tier members, while highlighting budget-friendly essentials for lower-tier segments.
* **Price & Promotion (Tiered Loyalty):** 
  * **Gold (Stars):** Exclusive access, 20% premium discounts, and VIP services.
  * **Silver (Disengaged/New):** Targeted mid-range discounts (10-15%) to accelerate their path to the premium tier.
  * **Bronze (Light/At-Risk):** Everyday savings and accumulative points to defend against deep-discount competitors like Lidl.
* **Place (Channel Strategy):** Deploy in-store high-touch events for older, affluent demographics, while utilizing aggressive digital and app-based touchpoints for younger, budget-conscious shoppers.

## 📂 Repository Contents
* `/data`: The raw transaction and demographic datasets.
* `/notebooks`: The R Markdown (`.Rmd`) script detailing the RFM modeling and visualizations.
* `/docs`: The knitted interactive HTML report.
