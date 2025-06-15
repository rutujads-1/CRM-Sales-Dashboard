# Coreline Hardware | B2B CRM Sales Pipeline Analysis

## Project Background and Overview

This Power BI dashboard was developed for **Coreline Hardware**, a computer hardware company, to provide strategic insights into its sales performance across regions, teams, and products.
Coreline operates in a competitive environment with a focus on enterprise clients, supported by regional sales teams and a broad product catalog. The underlying dataset — sourced from **Maven Analytics** — simulates CRM data and includes detailed records of customer accounts, products, sales agents, opportunity stages, and team structures.

The objective of this project is to transform raw CRM data into actionable insights that support business decision-making for Coreline's executive leadership, regional sales managers, and sales strategy teams. The analysis was guided by the following key business questions:

*- How is each sales team performing compared to the rest?*

*- Are any sales agents lagging in performance?*

*- Can quarter-over-quarter trends in revenue and opportunity volume be identified?*

*- Do any products have significantly better win rates?*

The dashboard answers these questions through carefully structured data models, DAX-driven KPIs—including **total opportunities, won deal count, win rates, and revenue**—and dynamic visuals tailored for executive-level reporting.

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

In 2017, Coreline Hardware generated $10.01M in total revenue, closing 4,238 out of 8,800 sales opportunities. Sales performance fluctuated throughout the year, peaking in June with $82.2K in closed deals and dipping to a low of $2.8K in July. Among all products, GTX Pro delivered the highest revenue at $3.51M, while MG Special contributed the least at $44K. Regionally, the Central office handled the most opportunities (3,512), while the Eastern region saw the lowest volume at 2,291.



<img width="572" alt="image" src="https://github.com/user-attachments/assets/5dfb8246-8dad-449d-a19c-f0942cf04776" />





## Insights Deep Dive

**How is each sales team performing compared to the rest?**

1. Revenue Performance by Region
   
In 2017, the West region led in total revenue, generating approximately $3.6 million, followed by the Central region with $3.3 million, and the East region with $3.1 million.
Throughout the year, the West region showed strong early performance with a 143% revenue increase from Q1 to Q2, followed by slight declines of 9.2% in Q3 and 1.9% in Q4.
The East region experienced the highest growth in Q2 with a 208.92% increase from Q1, but then saw consecutive decreases of 9.5% and 10.31% in Q3 and Q4 respectively.
The Central region displayed a more stable trend — it grew by 175.10% from Q1 to Q2, continued to rise by 10.01% in Q3, and then saw a modest 6.21% decline in Q4.

*While the West and East regions followed a surge-then-decline pattern after Q2, the Central region showed sustained growth through three quarters before tapering off at the end of the year.*



<img width="311" alt="image" src="https://github.com/user-attachments/assets/1bb5c792-0eeb-4271-bccf-8943779c2062" />





2. Opportunity and Win Rate Insights
   
The Central region handled the highest number of opportunities (3,512), followed by the West (2,997) and East (2,291).
Despite having the fewest leads, the East region had the highest win rate at 51.11%, indicating strong performance in converting opportunities into closed deals.
The West region followed with a win rate of 47.98%, while the Central region, despite handling the most leads, had the lowest win rate at 46.38%.

*The East region outperformed expectations, converting a smaller volume of opportunities more effectively than the other two regions.*



<img width="309" alt="image" src="https://github.com/user-attachments/assets/26e514e7-44df-4dda-b430-d182a7a5f617" />



<img width="302" alt="image" src="https://github.com/user-attachments/assets/551db6cf-556c-4222-b496-d5fccd459e6b" />




**Are any sales agents lagging?**

Among all sales agents in 2017, Reed Clapper achieved the highest win rate at 65.4%, while Lajuana Vencill recorded the lowest win rate at 40.84%.

By region and manager-

•	In the Central region, Cecily Lampkin led with a win rate of 52.71% under manager Dustin Brinkmann.

•	In the Eastern region, Reed Clapper, reporting to Rocco Neubert, had the top overall win rate.

•	In the Western region, Hayden Neloms achieved a win rate of 52.97% under manager Celia Rouche.

Closing Revenue-

•	Darcel Schlecht generated the highest total closing revenue for the year, reaching $1,153,214.

•	Violet McLelland reported the lowest total closing revenue, at $123,431.

Quarter-wise Agent Performance-

•	Q1:

o	Highest win rate: Corliss Cosme – 95.83%, winning 23 out of 24 opportunities

o	Lowest win rate: Wilburn Farren – 60%, winning 3 out of 5 opportunities

•	Q2:

o	Highest win rate: Wilburn Farren – 73.68%, with 14 wins out of 19

o	Lowest win rate: Gladys Colclough – 52.31%, with 34 wins from 65 opportunities

•	Q3:

o	Highest win rate: Rosie Papadopoulos – 74.19%, converting 23 of 31 opportunities

o	Lowest win rate: Lajuana Vencill – 49.32%, with 36 wins out of 73

•	Q4:

o	Highest win rate: Versie Hillebrand – 70.83%, with 51 wins from 72 opportunities

o	Lowest win rate: Garret Kinder – 45.71%, with 16 wins from 35

Repeated Appearances in Bottom Performers-

•	Lajuana Vencill appeared in the bottom five in both Q2 and Q3.

•	Anna Snelling was among the bottom five in Q1 and Q3.

•	Danniel Hammack was in the bottom five in Q1 and Q4.



<img width="332" alt="image" src="https://github.com/user-attachments/assets/8ed150ad-ac04-44c2-805b-d9699e6582a3" />





**Can quarter-over-quarter trends in revenue and opportunity volume be identified?**

Revenue-

•	Q1: Revenue totaled $1.13M, led by the West ($457K), followed by the Central ($348K) and East ($329K) regions.

•	Q2: Revenue saw a sharp increase to $3.09M, with June contributing the highest closing values across all regions. There was a slight dip in May before the peak.

•	Q3: Revenue slightly declined to $2.98M, with a dip in July followed by consistent growth in August and September.

•	Q4: Revenue further decreased to $2.80M.

o	The East region showed steady growth across all three months.

o	The Central region dipped from October to November but recovered in December.

o	The West increased from October to November but declined slightly in December.


<img width="271" alt="image" src="https://github.com/user-attachments/assets/d1ea010e-06ac-47e3-bf8d-ba34b968c0c6" />




**Overall, revenue peaked in Q2 and showed a gradual decline through the remainder of the year, indicating that most high-value deals closed in the second quarter.**

Opportunity Volume-

•	Q1 recorded 647 closed opportunities, with the Central region leading (242), followed by the West (231) and East (174).

•	Q2 saw a sharp rise to 2,032 opportunities closed, showing an upward trend across all regions from April to May, followed by a decline in June.

•	Q3 had the highest number of closures (2,047), driven by growth from July to August before a slight drop in September.

•	Q4 experienced a dip to 1,985 closed opportunities, with volumes increasing from October to November and declining through December.

*The highest opportunity volumes were recorded in Q2 and Q3, reflecting a strong and active pipeline.*

*There are currently 2,089 open opportunities, indicating substantial future potential still in the pipeline.*



<img width="194" alt="image" src="https://github.com/user-attachments/assets/326620fa-4f16-47ed-adee-cce0ddb8c470" />


**Do any products have significantly better win rates?**

In 2017, GTX Plus Pro achieved the highest overall win rate at 49.48%, while GTK 500 had the lowest at 37.5%.
In terms of revenue, GTX Pro contributed the highest share, generating $3.5 million, whereas MG Special accounted for the lowest total revenue, totaling $43,768.

Quarter-wise Product Win Rate Trends-

•	Q1:

o	GTK 500 recorded the highest win rate, though with a low number of opportunities.

o	MG Special followed with a win rate of 84.92% across 126 opportunities, indicating strong early performance.

•	Q2:

o	GTX Plus Pro achieved the highest win rate at 64.55%, with 220 total opportunities.

•	Q3:

o	GTK 500 again had the highest win rate at 66.67%, but this was based on only 6 opportunities.

o	GTX Plus Basic had a strong win rate of 64.24%, with a significantly larger base of 330 opportunities.

•	Q4:

o	GTX Plus Pro led again with a win rate of 63%, across 227 opportunities.

Regional Product Performance-

•	Central Region:

o	Highest win rate: GTX Plus Pro – 49.13%, based on 346 opportunities

o	Lowest win rate: MG Advanced – 42.31%, based on 579 opportunities

•	East Region:

o	Highest win rate: GTX Pro – 56.24%, based on 473 opportunities

o	Lowest win rate: GTX Plus Basic – 47.68%, from 388 opportunities

•	West Region:

o	Highest win rate: GTX Plus Pro – 50.16%, across 319 opportunities

o	Lowest win rate: GTK 500 – 40.54%, from 37 opportunities

In the West region, all closed GTK 500 deals for the year were recorded, with no GTK 500 wins outside of that region.

*Overall, GTX Plus Pro consistently demonstrated higher win rates across quarters and regions, making it the best-performing product in terms of conversion efficiency in 2017.*



<img width="569" alt="image" src="https://github.com/user-attachments/assets/020b409d-e7e4-438e-81fa-0422e8dc47d1" />





