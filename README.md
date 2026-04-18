# E-COMMERCE SALES ANALYSIS

## Table of Contents

- [Project Overview](project-overview)
- [Objectives](objectives)
- [Tools](tools)
- [Data Structure](data-structure)
- [Data Cleaning](data-cleaning)
- [Eploratory Data Analysis](exploratory-data-analysis)
- [Results/Findings](results/findings)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)

### Project Overview

In today's competitive e-commerce landscape, data-driven decision-making is essential for sustainable growth. This project presents an interactive Power BI dashboard designed to analyze sales performance, customer behavior, and geographical trends for an e-commerce business. The dashboard consolidates key metrics, including total revenue, quantity sold, average unit price, and customer insights into a single, dynamic view. By visualizing monthly sales trends, top-selling products by quantity, and geographical sales distribution, this tool enables stakeholders to quickly identify opportunities and address performance gaps. With total revenue reaching $105M, a 16.1% increase versus the previous year, this analysis highlights areas of strength while also revealing opportunities for further optimization.

### Objectives 

- Sales performance – Total revenue, quantity sold, average unit price, and year-over-year growth
- Customer analysis – Top spending customers, spending concentration, and customer count trends
- Product performance – Top 5 units by quantity sold and product volume drivers
- Geographical insights – Sales distribution by country and high-potential markets
- Operational metrics – Transaction types, supplier contributions, and store division performance
- Monthly trends – Seasonal patterns and month-over-month sales fluctuations

### Tools

- Power BI - Data Analysis and Creating Reports
- MS Powerpoint - Dashboard Wireframe

### Data Structure

- Fact Table – Contains transactional sales records, including payment key, customer key, time key, item key, store key, quantity, unit, unit price and total price
- Customer Dimension – Contains customer information, including customer key, customer name, contact number and ID
- Item Dimension – Contains product information, including item key, item name, description, unit price, manufacturing country, supplier and unit
- Store Dimension – Contains store location information, including store key, division, district and upazila
- Time Dimension – Contains time attributes, including time key, date, hour, day, week, month, quarter and year
- Payment Dimension – Contains payment method information, including payment key, transaction type and bank name

### Data Cleaning

- Missing values in revenue, quantity, and customer fields were addressed by removing incomplete rows or flagging records for exclusion
- Duplicate transactions were identified using order ID and customer ID combinations, then removed to prevent double-counting
- Date fields were converted to a uniform format for monthly trend analysis
- Country names and product categories were consolidated to avoid fragmentation; for example, variations like "Bangladesh" and "BD" were unified under single labels
- Outliers in revenue and quantity were detected using statistical methods and either removed or capped to prevent skewed results
- Data types were validated to ensure numeric fields aggregated correctly and date fields supported time-series analysis
- Calculated columns were added for year-over-year growth, customer spending tiers, and monthly trend extraction

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

1. What are the top 5 best-selling products by revenue 
2. What payment methods are customers using for transactions
3. Who are the top 5 suppliers
4. Which store divisions generate the highest revenue
5. How does revenue vary across different store divisions
6. What is the monthly sales trend over time
7. Which customers are the top spenders, and what percentage of revenue do they represent
8. What are the top 5 units by quantity sold
9. Which countries generate the highest sales volume

### Results/Findings

The analysis results are summarized as follows:

Sales Performance

- Total revenue: $105M with 16.1% year-over-year growth
- Total quantity sold: 6M units with 16.1% year-over-year growth
- Average unit price: $17.6 with 0.0% change versus previous year

Customers

- Total customer count: 9,191 with 0.0% growth versus previous year
- Top spending: Pooja (29%), Smt (23%), Smt (18%), Jyoti (17%), Sunita (13%)

Product Performance

- Top 5 units by quantity: Ct (2.36M), cans (1.30M), bottles (0.84M), oz (0.45M), bags (0.37M)
- Ct dominates as the clear bestseller, accounting for nearly half of all units sold

Geographical Sales

- Top markets: Bangladesh ($13.34M), India ($13.16M), Lithuania ($11.75M), Poland ($10.98M), Germany ($10.96M)
- Bangladesh and India lead as the top tier, while Poland and Germany show untapped potential

Monthly Sales Trend

- Revenue fluctuates between $8.5M and $9.1M across months
- Peak months: May ($9.08M) and July ($9.05M)
- Slowest month: February ($8.07M)

Customer Concentration

- Top 5 customers drive nearly all spending
- Pooja alone accounts for 29% of total spending
- High concentration risk identified

Suppliers

- Top suppliers by quantity: DENIMACH LTD (772K), Indo Count Industries (731K), Friedola 1888 GmbH (700K), CHROMADURLIN (636K), HARDFORD AB (612K)

Store Divisions

- Top divisions: Dhaka ($41M), Chittagong ($20M), Rajshahi ($12M), Khulna ($11M), Rangpur ($8M), Barisal ($8M), Sylhet ($6M)
- Dhaka and Chittagong together account for nearly 60% of total revenue

### Recommendations

- Launch a VIP loyalty program for top spending customers like Pooja and Smt to protect against concentration risk
- Run customer acquisition campaigns to grow the customer base beyond 9,191 and reduce dependency on a few buyers
- Increase prices slightly on top-selling items like Ct to capture more value without hurting demand
- Expand the Ct product line with new variants, flavors, or bundle options
- Invest in targeted marketing campaigns in Poland and Germany to close the gap with top markets
- Study peak months like May and July and replicate those strategies in slower months like February and June
- Diversify the supplier base to reduce risk and improve negotiation leverage
- Focus growth efforts on underperforming store divisions like Sylhet, Rangpur, and Barisal

### Limitations

This analysis has several limitations that should be considered when interpreting the findings. The data is historical only and does not reflect current trends or real-time performance. External factors such as competitor activity, economic conditions, and market shifts were not included in the analysis, which means some fluctuations in sales may be explained by outside forces not captured here. Customer demographics, including age, income, and location beyond the country level, were not available, limiting the ability to segment and target customers more precisely. Profit margins by product were not calculated, so products generating high revenue may not necessarily be the most profitable. Return and refund data were not available, meaning customer satisfaction beyond transaction records could not be measured. Some countries have very few transactions, making their performance metrics less reliable for decision-making. The analysis describes past performance and does not predict future outcomes or trends. Supplier quality and delivery times were not measured, only quantity shipped. Store division analysis does not include operational costs, so high revenue divisions may not be the most profitable once expenses are considered. These limitations should be kept in mind when applying the insights from this dashboard.

### References

1. E-commerce sales data - source of all data analyzed in this project
2. Microsoft Power BI Documentaion - DAX functions and data modeling



 
 


