# bigcommerce-analysis
Analysis for an ecommerce company on marketing channels, operational efficiency and sales trends.

## Advanced Excel
- **CLEANING DATA**:![image](https://github.com/projecttiffany/bigcommerce-sql-analysis/assets/51961132/6cd6bdb9-68cd-42d1-9f41-23b3db9550f7)
  - used date function to recalculate and reformat dates
  - calculated month start for pivot tables
  - calculated purchase year for pivot tables
  - checked whether refund date is before today and removed
  - added binary field to calculate number of refunds
  - manually cleaned names by filtering to bad categories and overwriting


- **CONDITIONAL FORMATTING**: ![image](https://github.com/projecttiffany/bigcommerce-sql-analysis/assets/51961132/c41ade8d-5f9b-415f-9252-80f7741a4c06)<BR>
- **PIVOT TABLES**: ![image](https://github.com/projecttiffany/bigcommerce-sql-analysis/assets/51961132/04566c2d-da2e-4323-80f2-ab6948c6b334)</br>

## SQL

Utilized LEFT JOIN, GROUP BY, ORDER BY, HAVING, QUALIFY to assess sales performance in BigQuery. Examples:
- What are the monthly and quarterly sales trends for Macbooks sold in North America across all years?<br>
    ![image](https://github.com/projecttiffany/bigcommerce-sql-analysis/assets/51961132/b95932f3-e886-469b-bb15-31d85c0ba83a)
- AOV and count of new customers by account creation channel in first 2 months of 2022
  ![image](https://github.com/projecttiffany/bigcommerce-sql-analysis/assets/51961132/5f016be2-3593-4eb6-8208-276f5a0b822a)

## Tableau 


## Key Insights & Recommendations
- Sales:
  - Desktop monitors, Bluetooth headphones and Macbooks generated 85% of revenue and 70% of all orders in order to recover sales.
  - **Recommenedation:** In the same way Apple products are favored because of their "just-in-time" inventory system,  evaluate ways to reduce the amount of time and money spent on storing and shipping parts for your non-Apple products (we get some insight by analyzing refund rates, but could dive deeper with more relevant data).  For example, Bose Soundsport Headphones contribute less than 1% of total sales. Determine if the cost is worth this stream of revenue, otherwise consider removing it from the company's product line.
- Marketing:
  - The top account creation method is via desktop (2.5K new customers). The company's previous marketing investments in their direct and email marketing channels were effective. 
  - **Recommendation:** Focus ad spending to social media sites that are often viewed more on desktop, such as LinkedIn, Facebook, Pinterest, and YouTube; use this approach to bolster the company's existing marketing strategies.
- Loyalty Program:
  - The sharp decline in sales in 2022(46%), which coincides with the re-opening during the pandemic, was mitigated by the loyalty program. Loyalty program customers make more purchases and contribute to higher sales. Loyalty members are twice as responsive to email campaigns than non-loyalty members for the company's 4 largest markets.
  - **Recommendation:** Implementing a retention strategy, particularly through email marketing campaigns, utilizing loyalty members-only incentives will pay off over time. 
