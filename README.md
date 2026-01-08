#### Retail Sales Power BI Dashboard



##### Overview



This Power BI dashboard provides a comprehensive view of sales performance for a retail dataset. It tracks key metrics such as total sales, quantity sold, sales trends over time, top-performing products, and top-performing markets. The dataset contains only positive sales transactions, so all insights focus on revenue generation and business growth.



The dashboard is designed for interactive exploration, enabling users to analyze sales by product, geography, time, and customer behavior.



###### Tools \& Technologies

###### 

Power BI – Interactive dashboard and visualizations



DAX – Measures and KPIs



Dataset – Retail sales transaction dataset with cleaned positive sales only

-----------------------------------------------------------------------------------------------------------------------------------------------



###### Dataset



\*\*Dataset:\*\* Original CSV contains all transactions but is not included due to file size limitations. Sample dataset can be requested.





The dataset contains the following fields:



1. Invoice – Unique invoice identifier
   
2. StockCode – Product identifier
   
3. Description – Product name/description
   
4. Quantity – Units sold
   
5. Price – Unit price
   
6. InvoiceDate – Transaction date
   
7. Customer ID – Unique customer identifier
   
8. Country – Country of sale



###### Measures Created



The dashboard leverages Power BI measures created with DAX:



* Total Sales – Revenue per transaction, product, or customer



* Total Quantity – Units sold



* Sales YTD – Cumulative sales from the start of the year to a selected date



* Sales MTD – Month-to-date sales



* Sales Last Year – Comparison with previous year’s sales



* Other basic DAX measures – for KPIs, totals, and averages



##### Dashboard Features



###### Key Performance Indicators (KPIs):

Total Sales, Total Quantity, Distinct Customers, Invoice Count



###### Visualizations:



Column chart: Total Sales by Product



Donut chart: Total Sales by Top 5 Countries



Line chart: Total Sales \& Sales YTD over time



###### Interactive Slicers: 

Date, Country, Product (StockCode/Description)





--------------------------------------------------------------------------------------------------------------------------------------------------------------------------



##### KEY INSIGHTS



1. **Overall Sales Performance** 



Total Sales- 20.97 M 

Total Quantity- 11M 



Sales show a steady upward trend, indicating strong business growth.





2\. **Geographic Dependency** 



TOP 5 countries 



Country	           Sales	Contribution(%)



United Kingdom 	   17.87 M	  89.9

Ireland (EIRE)	   664.43 K       3.34

Netherlands	   554.23 K       2.79

Germany	           431.26 K       2.17

France	           356.94 K       1.8



Sales are heavily concentrated in the UK, which accounts for approximately 89.9% of total revenue. The remaining top countries each contribute less than 4%, indicating strong dependency on a single market and limited revenue diversification across regions.

This level of concentration suggests potential risk exposure if demand declines in the UK and highlights opportunities for expansion in other European markets.



3\. **High Sales**

Stock Code - 22423

Description- Regency Cakestand 3 Tier

Total Sales- 344.56K 



**Low Sales** 

Owls Charolette bag, Pink heart Christmas decoration, happy birthday ginger cat card

These products contribute minimally to overall revenue, indicating low demand.





4\. **Top products by top 5 countries** 



Country           Product Description     Sales 



United Kingdom    Dotcom Postage          322.66K

Ireland           Manual                  23.86K

France            Postage                 25.03K

Germany           Postage                 39.23K

Netherlands       Round Snack Boxes       13.32K

&nbsp;                 Set of 4 Woodland 



Top-selling products vary by country, but the UK dominates overall revenue, highlighting both geographic dependency and differences in regional product preferences.



5\. **Customer Behavior Insight**



Customers- 5876

Invoice Count- 40k



Over the complete analysis period, the dataset contains 5,876 distinct customers and approximately 40,000 invoices. This indicates that each customer placed multiple orders on average, highlighting strong repeat purchase behavior and customer retention rather than one-time transactions.



6\. **Sales Trends/YTD**



Sales YTD increased steadily from 13,481.25 (Jan 2010) to 10.3M (Dec 2010), reset at the start of 2011 (16,026.08 on 04-01-2011) and reached 9.84M by Dec 2011, showing sustained growth across years.



7\. **Daily Sales Volatility and Year-End Pattern**



Total Sales exhibit significant day-to-day volatility, with sharp spikes such as 118,909.67 on 27-09-2010 and 199,236.40 on 07-12-2010, followed by lower sales days such as 38,789.98 on 29-09-2010.



A noticeable decline in sales occurs toward the end of December 2010, with Total Sales dropping to 6,199.97 on 22-12-2010, followed by a low-activity period through early January 2011 (16,026.08 on 04-01-2011), during which Sales YTD remained constant at approximately 10.30 million.

Sales activity resumes thereafter with continued fluctuations, concluding on 09-12-2011 with Total Sales of 200,938.60 and cumulative Sales YTD of 9,842,956.40, indicating sustained but slightly lower annual performance compared to 2010.







##### Daily Sales Volatility \& Year-End Pattern (Summary Table)



Date	       Total Sales (TS) 	Sales YTD	    Observation

27-09-2010	118,909.67	        Increasing	High-value sales spike indicating bulk or large transactions

29-09-2010	38,789.98	        Increasing	Sharp drop from previous spike, showing daily sales volatility

07-12-2010	199,236.40	        Increasing	One of the highest daily sales values, driving YTD growth

22-12-2010	6,199.97	        ~10,304,325	Significant decline in daily sales near year-end

04-01-2011	16,026.08	        ~10,304,325	Low activity period with flat YTD during year transition

09-12-2011	200,938.60	        9,842,956.40	High daily sales toward end of period; 2011 closes slightly below 2010 YTD





\*\*\*\*\*\*END OF REPORT\*\*\*\*\*\*\*\*\*\*\*

