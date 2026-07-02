#bussiness sales
📊 Task 1 (DS Track): Interactive Power BI dashboard analyzing ₹142M+ in revenue, sales quantities, and profit margins. Features time-series trend analysis, regional market performance breakdowns, and granular B2B customer matrix insights. Built using Power BI, DAX, and Power Query.
#Strategic Business Intelligence for Regional Sales Analytics(Interactive dashboard creation using PowerBi)
## Project Objective 
To design and build an interactive business intelligence dashboard that transforms raw transactional data into actionable financial insights. The project aims to evaluate key performance indicators (KPIs)—including revenue, sales volume, and profit margins—while tracking temporal revenue trends and regional market distributions. Ultimately, this dashboard empowers stakeholders to identify high-value B2B customers, isolate underperforming regional markets, and optimize sales strategies for maximum profitability and it is annaual sales report from 2017 to 2020
## Dataset used
- <a href = "https://github.com/mounika23991A4220/FUTURE_DS_01/blob/main/db_dump_version_2.sql">Strategic Business Intelligence for Regional Sales data</a>
## Questions(KPIs)
-What is the total revenue generated across all regions, and how does it align with the total sales quantity?
- What is the net profit margin, and does it reflect healthy business growth?
- How does revenue fluctuate month-over-month, and what triggered the sharp revenue decline in June 2020?
- Are there identifiable seasonal patterns or historical trends when filtering data by year (2017–2020)?
-  PerformanceWhich regional markets (e.g., Delhi, Mumbai) drive the highest percentage of total revenue?
-  Are high-revenue markets also driving high profit margins, or are some volume-heavy regions operating at a loss?
-  Which specific markets show a negative profit percentage, and where should leadership cut costs?
- Dashboard Intreaction <a href = "https://github.com/mounika23991A4220/FUTURE_DS_01/blob/main/bussiness%20sales%201.png ">view dashboard </a>
- Dashboard Interaction <a href = "https://github.com/mounika23991A4220/FUTURE_DS_01/blob/main/bussiness%20sales%202.png">dashboard</a>
## 🔍 Key Insights & Business Answers

Based on the interactive dashboard analysis, the project answers critical business questions regarding health, trends, and regional performance:

* **Overall Business Health**: The business generated a total revenue of **₹142.22M** across **350K units sold**. While volume is high, the final **Total Profit Margin stands at ₹2.06M**, indicating thin overall margins that require strategic cost management.
* **Temporal Revenue Trends**: Revenue peaks and valleys show clear seasonal patterns across the 2017–2020 timeline. Most notably, a **sharp revenue decline occurred in June 2020**, indicating severe market disruptions or supply chain bottlenecks during that period.
* **Regional Market Powerhouses**: The revenue is heavily concentrated in a few key zones. **Delhi is the primary volume driver**, single-handedly contributing **54.7% of total revenue**, followed by **Mumbai at 14.2%**. 
* **Profitability vs. Volume Disconnect**: High revenue does not always equal high profit. The dashboard reveals a clear mismatch—several high-volume markets contribute lower net margins, while specific smaller regional markets yield much higher return on investment (ROI %). Conversely, certain underperforming zones are identified operating at a **negative profit percentage**, draining bottom-line returns.
* **Customer Concentration Risk**: A tiny cluster of elite B2B buyers dominates the revenue pipeline. **Electricalsara Stores** and **Excel Stores** rank as the highest absolute revenue contributors, meaning overall business health is deeply tied to maintaining these specific accounts.
## 🏁 Conclusion & Future Scope

### Conclusion
This project successfully establishes a data pipeline from raw relational data in MySQL to an interactive BI layer in Power BI. By revealing that 54.7% of revenue relies entirely on a single market (Delhi) and a handful of B2B accounts, the dashboard highlights clear customer concentration risks. Furthermore, identifying markets with negative profit percentages gives leadership concrete, data-backed targets for immediate cost-cutting and pricing renegotiations. 

### Future Scope
To evolve this dashboard from a retrospective reporting tool into a forward-looking decision engine, the next iterations will focus on:
1. **Automated Data Pipeline**: Transitioning from manual SQL exports to a live, automated gateway connection linking MySQL and Power BI for real-time reporting.
2. **Predictive Analytics**: Integrating Python or Azure Machine Learning extensions within Power BI to forecast future sales demand and anticipate seasonal dips.
3. **Advanced Customer Segmentation**: Implementing RFM (Recency, Frequency, Monetary) analytics using DAX to categorize B2B customers into precise retention profiles.
4. **Granular Expense Tracking**: Incorporating detailed logistics, warehousing, and operational cost metrics to drill down into the exact root causes of negative regional profit margins.
