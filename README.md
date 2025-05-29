# Business-Maturity-Index-Management-Dashboard

![](https://github.com/rubytechme/Business-Maturity-Index-Management-Dashboard/blob/main/BMI.jpg)

## Introduction:

In the dynamic landscape of burgeoning businesses, the journey from just an idea to building a sustainable business often comes with so many challenges. Many promising ventures falter, not from a lack of innovation, but from an incomplete understanding of their operational health and growth trajectory.

This Analysis delves into this critical aspect, moving beyond simple revenue figures to assess the business maturity index of a portfolio of four distinct startups. Just as Product Market Fit is the lifeline for a product, understanding a startup's overall maturity, encompassing its financial performance, operational efficiency, and market engagement, is paramount for long-term viability.

The essence of this analysis is to track key metrics that collectively evaluate the business maturity of each startup, providing insights into their current standing and identifying strategic pathways for optimized growth and sustainability.

## Key Metrics:

1. Total Revenue
2. Mom % change in revenue
3. Total Profit
4. MoM % change in profit
5. Avg Active App Users/Subscribers
6. % of African Ownership 

## Insights: 

1. Overview
- Revenue by Startup
- Net Profit by startup

2. Financials
- MoM Revenue
- MoM Net Profit
- Yearly Revenue

3. Customers
- Active subscribers by Startup
- Percentage of Revenue of Top customers

4. Others
- Spare Capacity Utilization


## Skills/Concepts Demonstrated:

The following Power BI features were incorporated

- Data Cleaning 
- Data Transformation
- Quick measures
- Time Intelligence
- Dashboard Automation

## Other Expertise Incorporated:

- Data Governance
- Data Quality & Standardization 


## Visualization & Analysis:

### KPIs:
### Total Revenue
The portfolio achieved a total revenue of $37.18 Million, underpinned by an impressive average month-over-month (MoM) growth rate of approximately 60%. This performance clearly indicates a significant and healthy growth trajectory for the entire portfolio.

### Total Profit
Across all four startups, the combined total net profit generated stands at approximately $12 million. This indicates a healthy level of overall profitability for the portfolio.

### % of African Ownership 
The African ownership still remains at 100% without any dilution, 

### Overview: 

![](https://github.com/rubytechme/Business-Maturity-Index-Management-Dashboard/blob/main/BMI1.png)

### Revenue by Startup
It's evident that Startup 1 and Startup 3 are significantly outperforming Startup 2 and Startup 4 in revenue generation, despite all being relatively new ventures. This substantial discrepancy warrants immediate investigation to understand the underlying factors contributing to such divergent early-stage financial performance.

### Net Profit by startup
While Startup 1 boasts of high revenue, its alarmingly low net profit indicates a thin profit margin. This suggests either a high operating costs or a significant burden from debt servicing, which are both common challenges for relatively new companies/ventures.
Contrary, Startup 3 demonstrates robust financial health with a strong net profit margin, as its net profit closely aligns with its generated revenue. This indicates efficient cost management and potentially lower debt obligations. Whereas, startup 3 and 4 are not performing so well


### Financials:

![](https://github.com/rubytechme/Business-Maturity-Index-Management-Dashboard/blob/main/BMI2.png)

### MoM Revenue
The portfolio experienced its highest revenue in February, signifying substantial growth. This peak month contributed to an impressive 60% month-over-month (MoM) growth for the entire portfolio, indicating a positive upward trend in overall performance.

### MoM Net Profit
This positive trend in February extends beyond revenue to net profit, which also experienced a tremendous increase during the same month. The substantial jump from December to February strongly suggests that the startup previously grappling with a December deficit has likely concluded its debt obligations, leading to a significantly healthier net profit.

### Yearly Revenue
The portfolio's 2025 revenue significantly outpaced that of 2024, demonstrating strong year-over-year growth. This positive trajectory suggests that with targeted intervention, strategic transformation, and support for the underperforming startups, the overall portfolio has substantial potential for even greater success, since they all play within the same industry.



### Customers:

![](https://github.com/rubytechme/Business-Maturity-Index-Management-Dashboard/blob/main/BMI3.png)

### Active subscribers by Startup
The leading position of startup 1 in active subscribers directly correlates with its highest revenue generation among the startups. This strong subscriber base appears to be a key driver, validating its superior financial performance compared to its counterparts.

### Percentage of Revenue of Top customers
A significant majority of the startups reported that between 51% and 70% of their total revenue is derived from their top customers. This highlights a considerable reliance on a concentrated customer base across the portfolio.



### Others:

![](https://github.com/rubytechme/Business-Maturity-Index-Management-Dashboard/blob/main/BMI4.png)

### Spare Capacity Utilization
All startups possess some degree of spare capacity, though at varying rates. Notably, Startup 1 and Startup 2, both strong performers, maintain approximately 10% spare capacity, while Startup 4 holds a significantly higher 30%.

## Live Dashboard:
You can interact with the live visualization [HERE](https://app.powerbi.com/groups/me/reports/48051f89-a36b-4b97-876a-c70e292092f7/ReportSection?experience=power-bi)


## Challenges:
1. Initially, my Month-over-Month (MoM) calculations were failing due to the absence of prior month's data for comparison. To resolve this, I refined the calculation logic to bypass the error using a caveat.  And thus, it now only processes MoM growth upon the first occurrence of a new month's data, ensuring accuracy and preventing erroneous calculations in initial periods.

2. I also experienced a problem in calculating the percentage change for net profit. Specifically, a prior month's negative net profit, despite a substantial positive improvement two months later, skewed the percentage difference calculation due to the negative sign's influence, resulting in misleading or overly pessimistic growth figures.
   To counteract this, I customized the DAX formula with a specific rule: if the previous month's value is negative and the current month's value is positive, the system now treats the change as positive, but reports a neutral sign. This ensures an accurate representation of the profit recovery without the distorting effect of the initial negative baseline.

4. Initially, a straightforward comparison of spare capacity month-over-month proved challenging using a standard table format. To overcome this, I implemented a matrix transformation, pivoting the row-based month values into columns, thereby enabling a clear, side-by-side month-by-month comparison of spare capacity.


5. There was also a major problem in automating the workflow via the web, due to the file size (about 200 columns with long characters in it) So I ran the automation locally to successfully process the data.

## Conclusion and Recommendations:

The portfolio exhibits promising overall growth, largely driven by the strong performance of some startups. However, to maximize its full potential, we need to address specific areas.

1. Targeted Support for Startups 2 & 4
Startup 2 and Startup 4 require immediate, focused support to improve their revenue generation and overall performance. A thorough investigation into their current strategies, market positioning, and operational efficiencies is crucial to identify and implement effective solutions.

2. Optimizing Profitability for Startup 1
Despite its high revenue, Startup 1's low net profit margin is a critical concern. We must investigate whether this is due to an excessive debt burden or unnecessary operational costs. Implementing strategies to optimize its cost structure and potentially restructure its debt financing will be essential to improve its profitability and ensure sustainable growth.


