# Coreline Hardware | B2B CRM Sales Pipeline Analysis

## Project Background and Overview

This Power BI dashboard was developed for **Coreline Hardware**, a computer hardware company, to provide strategic insights into its sales performance across regions, teams, and products.
Coreline operates in a competitive environment with a focus on enterprise clients, supported by regional sales teams and a broad product catalog. The underlying dataset — sourced from **Maven Analytics** — simulates CRM data and includes detailed records of customer accounts, products, sales agents, opportunity stages, and team structures.

**The objective of this project is to analyse sales performance across products, agents, and time in order to identify the key drivers of revenue, conversion efficiency, and sales effectiveness, and to surface actionable opportunities to improve overall sales performance using the North Star KPIs- Total Opportunities, Win Rate, Total Revenue and Average Deal Size.**

## Data Structure and Overview

Data Tables-

**Accounts** – A dimension table containing organizational attributes for client companies, used to enrich sales opportunity data with industry, size, and geographic context.

**Products** – A dimension table listing Coreline’s hardware offerings, including product names, associated series, and suggested sales prices, used to analyze product-level performance and win rates.

**Sales Teams** – A dimension table detailing the organizational structure of Coreline’s sales force, including agent names, reporting managers, and regional office assignments.

**Sales Pipeline** – A fact table capturing individual sales opportunities, including details on agents, products, accounts, deal stages, timelines, and revenue outcomes.

**Date Table** – A custom date dimension table created to support time-based analysis. It includes continuous dates and derived fields such as Month, Quarter, and Year-Month, enabling accurate trend analysis, time filtering, and period-over-period comparisons.


**ERD**

<img width="320" alt="image" src="https://github.com/user-attachments/assets/7c0580ba-779b-4daf-b14e-620b8df916fb" />




## Executive summary

In 2017, Coreline Hardware earned a revenue of ~$10M closing 4,238 out of 8,800 sales opportunities with a win rate of ~48% . Approximately 24% of opportunities still open,indicating an active and ongoing sales pipeline.

Quarterly analysis of the win rate and total opportunities shows that a sharp increase in opportunity volume from Q1 to Q3 coincided with declining win rates. The parallel movement suggests a volume-driven conversion trade-off rather than agent- or product-specific issues. Win rates stabilised in Q4 as opportunity volumes moderated.

Analysing product performance reveals that GTXPro gets the highest revenue- $ 3511K followed by GTX PLus Pro and MG Advance. In terms of order volume- GTX Basic followed by MG Special and GTX Pro have the highest number of opportunities.Despite having a higher opportunity count,these products have a lesser average deal size, thus generating less total revenue inspite of having a good win rate. 

Products can be thus segmented into High revenue products- GTX PRO, GTX PRO PLUS, MG ADVANCE and High volume, low revenue- GTX BASIC, MG SPECIAL.
GTK 500 is the product with the lowest number of total opportunities but has the highest average deal size. 

This analysis further looks into the High revenue product segment as they contribute to ~60% of the total revenue earned so far. 



<img width="572" alt="image" src="https://github.com/user-attachments/assets/5dfb8246-8dad-449d-a19c-f0942cf04776" />









## Insights Deep Dive

### Product Performance



#### Product x Agent Performance 

**GTX Plus Pro**


**High-value performing combinations (High Opportunity Exposure)**

1. James Ascencio handles the highest opportunity volume (81) while maintaining a strong win rate (69%) and stable average deal size. He demonstrates high efficiency under significant workload, making him a strong high-value agent–product fit.


2. Darcel Schlecht manages a similarly high workload (66 opportunities) with an even higher win rate (70%), indicating consistent efficiency at scale.


3. Anna Snelling, with 64 opportunities, operates at a comparable workload level but shows a relatively lower win rate (59%). This may indicate capacity-related efficiency constraints and warrants further review rather than immediate performance concerns.


Overall, James Ascencio and Darcel Schlecht emerge as the top high-load, high-efficiency performers for GTX Plus Pro.

**Other strong performers in the high exposure bucket**

1. Marty Freudenburg (72%) and Maureen Marcano (81%) exhibit exceptionally high conversion rates with comparable opportunity volumes, positioning them as high-performing candidates within this segment.


**Coaching signals within high exposure**

1. Reed Clapper, Gladys Colclough, and Cassey Cress display lower win rates relative to peers with similar opportunity exposure, suggesting product-specific coaching opportunities.

**Strong performance at reasonable workload (Medium Exposure)**

1. Hayden Neloms (90%, 15 opps), Kami Bicknell (83%, 22 opps), and Niesha Huffins (80%, 19 opps) show extremely high win rates at comparable, moderate workloads, indicating underutilised high-potential agents.


2. Garrett Kinder, with a similar opportunity range (23 opps), underperforms with a lower win rate (52%), marking a coaching opportunity.


**Low Exposure Insights**

1. Elease Gluck records the lowest win rate (17%) despite low opportunity exposure (9), clearly identifying a training need for this product line.


**GTX Pro**

**High-value performing combinations (High Opportunity Exposure)**

1. Darcel Schlecht stands out with an exceptionally high opportunity volume (358) and a solid win rate (60%), indicating strong specialisation in this product. While efficiency may improve with reduced load, he clearly emerges as a key GTX Pro specialist.


2. Zane Levy, with 91 opportunities and a win rate of 67%, demonstrates high efficiency at significant scale.


**Among other high-exposure agents:**

1. Don Cantrell and Kami Bicknell show comparatively lower win rates (55%), indicating potential efficiency improvement opportunities within this workload segment.



**Medium exposure insights**

1. Rosie Papadopoulos emerges as the top performer in this segment with an outstanding win rate (81%) at 43 opportunities.


2. Gladys Colclough, with a win rate of 52%, underperforms relative to peers and may benefit from targeted coaching.



**Low exposure insights**

1. Elease Gluck shows strong efficiency with the highest win rate (80%) despite low exposure, suggesting potential underutilisation.


2. Niesha Huffins, with comparable exposure, records the lowest win rate (14%), indicating a clear coaching requirement for GTX Pro.



**MG Advanced**

**High-value performing combinations (High Opportunity Exposure)**

1. Hayden Neloms leads with the highest opportunity volume (101) and a strong win rate (77%), making him a high-efficiency, high-load performer for MG Advanced.


2. Vicki Laflamme, with similar exposure (90 opps) but a lower win rate (57%), shows signs of product-specific inefficiency, indicating a need for coaching.


**Other high-exposure agents:**

1. Lajuana Vencill (51%), Marty Freudenburg (49%), and Anna Snelling (47%) operate at comparable opportunity levels but exhibit lower conversion rates, highlighting efficiency gaps within this segment.



**Medium exposure insights**

1. Corliss Cosme, with approximately 32 opportunities and a win rate of 43%, underperforms relative to peers and represents a coaching opportunity.



**Low exposure insights**

1. Niesha Huffins, despite lower opportunity exposure (22), maintains a strong win rate (71%), suggesting latent potential.


2. Kary Hendrixson, with similar exposure (23), records the lowest win rate (44%) in this segment, indicating training and support needs.



## Recommendations

**Revenue Performance by Region**

The Central region’s sustained revenue growth through Q3, unlike the sharp fluctuations in the East and West, suggests a more consistent deal pipeline. Focused analysis should be conducted to understand regional dynamics and adjust forecasting and resource allocation accordingly.
Opportunity and Win Rate Insights

Despite handling fewer opportunities, the East region achieved the highest win rate, indicating efficient deal conversion. This suggests a potential best-practice model for sales qualification or customer engagement, which could be analyzed and adapted to enhance conversion in the Central and West regions.

**Sales Agent Performance**

Lajuana Vencill (Q2 & Q3), Anna Snelling (Q1 & Q3), and Danniel Hammack (Q1 & Q4) consistently rank among the lowest performers.Initiate targeted coaching and performance-improvement plans for these agents—focusing on deal qualification and closing techniques—to raise their win rates and lift overall team efficiency.

**Revenue quarter over quarter trend**

With revenue peaking in Q2 and gradually declining in subsequent quarters, there’s a clear concentration of high-value deal closures early in the year.Consider redistributing sales efforts or introducing staggered incentives to encourage high-value deal closures in later quarters and maintain revenue consistency throughout the year.

**Opportunity volume quarter over quarter trend**

The surge in pipeline activity during Q2 – Q3 and the 2,089 open opportunities signal substantial untapped revenue.Prioritize structured follow-up and deal-acceleration plans—e.g., regular pipeline reviews, targeted outreach, and staged incentives—to convert these open opportunities and smooth revenue flow into the coming quarters.

**Product win rates**

-**Accelerate GTX Plus Pro** – Expand sales focus and marketing support for this high-efficiency product across all regions; use its sales playbook as a benchmark for other lines.

-**Cross-train regions on GTK 500 wins** – Analyse why only the West succeeds with GTK 500, document winning tactics, and pilot targeted enablement in Central and East to lift its conversion rate.

-**Re-position or bundle MG Special** – Given its low revenue impact, evaluate bundling, price adjustment, or market repositioning to improve its contribution or phase it out if margins are weak.


## Clarifying Questions,Assumptions and Caveats

Questions to Stakeholders prior to advancement-

-Should early-stage “Prospecting” opportunities be included in total pipeline volume and trend analysis, or should they be excluded until engagement begins?

-Are sales opportunities assigned to agents or sourced individually?
(This helps determine if performance is based on assignment efficiency or agent initiative.)

-Is “GTX Pro” in the Products table the same as “GTXPro” in the Sales Pipeline table?
(Clarifies potential data entry issues that may affect product-level analysis.)

-Are there defined profit margins per product that could be used in performance analysis, or should analysis rely solely on revenue and win rates?

**Assumptions**

-All records, including those in the Prospecting stage, are considered part of the total opportunity count unless filtered explicitly.

-Win Rate and Revenue are used as primary performance KPIs due to the absence of profit or cost data.

-Each opportunity is assigned to a sales agent and evaluated based on their outcomes.

-“GTX Pro” and “GTXPro” refer to the same product and have been treated as such during data modeling.

**Caveats**

-Profit-related metrics could not be calculated due to lack of cost or margin data.

-Date inconsistencies between engagement and closing phases (e.g., blanks or out-of-sequence records) may impact timeline analysis.

-Open opportunities (with no closing date) result in blanks in quarter-based slicers and charts

-While agents may handle additional product portfolios, this analysis intentionally focuses on high-revenue products to assess performance within their specific sales dynamics.

