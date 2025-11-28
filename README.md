# 🧭 1. Background & Project Goals*

The AdventureWorks dataset, created by Microsoft, represents the e-commerce operations of a global bicycle company. This project focuses on developing dashboards that provide actionable, data-driven insights to support both strategic and operational decision-making. 

AdventureWorks serves over **18,484** customers and contains more than **60,400** transactions, offering **606** products and generating over **$307M** in sales revenue. The available e-commerce dataset spans 2005 to 2008, offering a comprehensive four-year view of sales performance, customer behavior, product trends, and regional demand.

This comprehensive review provides valuable insights by developing two interactive Excel dashboards that internal cross-functional teams will use to streamline processes and enhance AdventureWorks’ commercial performanceThe key insights and recommendations focus on following areas: 
1.	**Product & Customer Insights Dashboard** – provides detailed product performance and customer behavior analysis.
2.	**Time-Based Trends Dashboard**– uncovers seasonal and cyclical patterns across the four-year period to support long-term planning.

**Key Metrics**
-  📅  **Sales Trends:** Track core KPIs including total sales revenue, number of orders, and overall profit to assess business performance by year, quarter, month, weekday, and week type.
- 📦 **Product performance:** Analyze product trends to identify best-sellers, evaluate individual product profitability, and understand how pricing changes impact margins.
- 🌍 **Regional Sales Analysis:** Evaluate regional demand and assess product performance within each region to identify opportunities for improvement and targeted growth strategies. Visualize performance across global regions and identify top- and low-performing markets.
- 👥 **Customer Segmentation:** Categorize customers based on demographics, revenue contribution, and purchasing behavior to identify top customers and gain insights into their buying patterns.

# 🗂️ 2. Data Structure and ERD (Entity Relationship Diagram)

The dataset structure as seen below consists of 6 tables: DimProduct, DimGeography, DimDate, DimSalesTerritories, FactInternetSales, DumCustomer, with a total row count of 108,127 records. 

![ERD ](https://github.com/user-attachments/assets/619ee2cc-afd5-4457-8cf2-2aa1ec40de93)

# 📋 3. Executive Summary 

The multi-year analysis of Adventure Works’ sales, product performance, regional trends, and customer behavior highlights a period of strong growth in 2007–2008, followed by early indicators of a downward trend in late 2008. Despite this, the business demonstrates healthy margins, strong customer loyalty, and clear opportunities for strategic expansion in both products and markets.

![generel](https://github.com/user-attachments/assets/d83601cf-1eca-43e6-9d96-850e3a089ff0)

**Financial Performance and Growth Trends**
Adventure Works generated $307M in total revenue, supported by $180M in COGS and producing $126M in profit, resulting in a robust 41% profit margin.
The strongest growth occurred between 2007 and 2008, where revenue increased from $69.48M to $102.38M, marking the most successful period in the dataset. Despite this momentum, a decline in late 2008 revenue halted year-over-year improvement and signaled the beginning of a softening trend that warrants further examination.

**Seasonality, Weekday Patterns, and Quarterly Insights**
Over all years, Q2 consistently delivers strong performance, likely influenced by seasonal demand for bicycles and increased marketing efforts. Although Q2 2007 experienced a slight profit margin dip—from $3M down to $2M, full-year revenue still significantly outperformed 2006, demonstrating resilient consumer demand and operational effectiveness.
Purchasing behavior is highly weekday-driven: over 75% of bicycle sales occur Monday through Friday, with Monday, Thursday, and Friday emerging as peak days. These patterns suggest that consumer routines, targeted promotions, or pre-weekend purchases are key drivers of weekday sales.

**Regional and Customer Insights**
North America and Australia remain the dominant markets, contributing the majority of sales and profit, while Canada significantly underperforms across all product categories. Customer demographics reveal that loyalty and premium positioning are core strengths: the average customer is 46, customers aged 50+ contribute over half of total profit, and loyalty program members account for 97% of total revenue. Younger buyers favor hybrid bikes and online purchasing channels, suggesting a clear opportunity for targeted digital expansion.

**Key Takeaways & Recommendations**
- Investigate the causes of the 2008 decline 
Analyze market conditions, competition, supply chain disruptions, and operational issues contributing to the revenue downturn and lack of recovery after 2007’s exceptional growth.
- Capitalize on Peak Periods and Buying Patterns
Strengthen marketing and promotional campaigns during high-performing quarters (Q1 and Q2) and leverage weekday purchase peaks—especially Monday, Thursday, and Friday—to drive conversions.
- Reinforce Strategies That Drove 2007 Success
Reassess pricing, promotions, distribution, and customer engagement tactics that contributed to 2007’s strong financial results to regain momentum.
- Expand Premium Product Focus and Inventory Optimization
As premium products deliver the majority of profit, continue investing in high-value offerings while optimizing or retiring low-performing SKUs.
- Enhance Regional Penetration and Customer Segmentation Efforts
Improve Canadian market performance through localized promotions and partnerships while maintaining strong support for high-growth markets. Tailor marketing to high-value 50+ customers and digitally driven campaigns for younger segments.

# 🔍 4. Insights Deep Dive
![generel 2](https://github.com/user-attachments/assets/8daad31d-a15f-454f-853d-873499e44ec5)

**1. Sales Trends** : Key performance indicators—including total sales revenue, order volume, and overall profit—show consistent growth over the multi-year period, with one notable exception.
   - Over the four-year period, revenue and profit growth remained relatively stable, suggesting minimal variation in product pricing.
   -  Historically, 2007 and 2008 were the strongest revenue years, supported by year-over-year growth and new product launches. However, Q4 2008 saw an unexpected and substantial decline.
   -  In June 2008, sales revenue reached $8M (compared to $2M–$3M in prior years), yet by Q4 2008 revenue dropped by approximately 70–80%, representing an even sharper fall compared to Q4 2007.
   -  Despite the Q4 downturn, 2008 recorded the highest annual profit at $8M.
   -  Sales contribution patterns shifted between 2007 and 2008. In 2007, the highest sales occurred on Tuesday, Wednesday, and Thursday, whereas in 2008 the strongest days were Thursday, Wednesday, and Sunday. This offers guidance for scheduling targeted marketing campaigns on high-traffic days.

**2. Product Performance**: Analyze product trends to identify best-sellers, evaluate individual product profitability, and understand how pricing changes impact margins.
   -  Bikes remain a core product, contributing 36.1% of total sales, followed by accessories and other categories which make up 60.9%.
   -  Black products are the top-selling color option (17M in sales), followed by Silver (10M) and Yellow (7M). This trend provides actionable insights for both production planning and marketing strategy.
   -  There are 133 products with little to no sales. These items may benefit from promotional campaigns or repositioning to increase visibility and demand.
   -  Profitability is heavily skewed toward premium-priced items: 94.4% of total profit ($40.16M) comes from high-priced products, indicating strong customer demand for premium offerings.

**3. Regional Sales Analysis:**
    - North America and Australia generate the majority of revenue across product categories, accounting for an average of 62.7% of total sales per product and $79.24M in total profit.
    - In contrast, Canada underperforms significantly, contributing only 6.9% of product-level sales and $8.78M in total profit, with many products showing near-zero sales penetration. This indicates an opportunity for targeted marketing or distribution improvement.

**4. High-Value Customer Segmentation:** Customer demographic and behavioral patterns reveal a strong base of loyal, high-spending customers.
   - The average customer age is 46.
   - Customers aged 50+ generate 50.5% of total profit ($19.54M), making them the most valuable demographic segment.
   - Younger customers show a clear preference for hybrid bikes and online purchasing channels.
   - Loyalty program members account for 97.1% of all sales revenue, with purchases typically exceeding $150. Only 2.9% of customers buy products priced below $150, reinforcing the company’s positioning as a premium brand with a highly loyal customer base.

# ✅ 5. Recommendations
Based on the analysis, these recommendations focus on stabilizing revenue, leveraging peak performance periods, optimizing product strategies, strengthening regional markets, and expanding customer engagement. By combining historical successes with data-driven insights, Adventure Works can increase profitability, enhance market penetration, and build long-term customer loyalty.

**1. Sales Optimization**
   - 	Investigate Q4 2008 Sales Drop: Review supply chain issues, stock outs, marketing reductions, or economic factors that may have caused the sharp decline. Implement preventive controls for future Q4 seasons.
   - 	Boost Promotions on High-Performing Days: Increase targeted marketing, email pushes, and limited-time offers on Wednesday, Thursday, and Sunday to capitalize on peak purchase behavior.
   - 	Seasonal Sales Strategy: Develop Q4-specific product bundles and loyalty promotions to stabilize historically volatile seasonal performance.
    
**2. Product & Pricing Strategy**
   - Prioritize Premium Products: Since 94% of profit comes from higher-priced products, invest in more premium variations, enhanced features, and limited editions.
   - Increase Inventory for High-Demand Colors: Ensure adequate supply of Black, Silver, and yellow products, which show consistently high customer preference.
   - Revitalize Low-Performing Products: Promote the 133 low-visibility products through bundles, discounts, rebranding, or retiring items that consistently underperform.
   - Enhance Cross-Selling: Bundle popular bikes with accessories to increase average order value.
     
**3. Regional Market Strategy**
   - Strengthen Canada Market Penetration: Conduct a root-cause analysis for near-zero sales. Increase local advertising, partner with regional retailers, and run Canada-specific pricing or promotions.
   - Increase Investment in High-Performing Regions: Maintain strong marketing presence and optimized inventory in North America and Australia to sustain revenue and profit growth.
  
**4. Customer Strategy**
   -  Target High Value 50+ Customers:Offer premium service packages, maintenance plans, and tailored messaging that highlights comfort, durability, and quality. Introduce loyalty tiers with exclusive benefits for this segment.
   -  Growing Customer Base: Promote hybrid bikes, online exclusives, and influencer partnerships. Offer entry-level premium options or installment payments to make high-price items more accessible.
   -  Expand Loyalty Program: Since loyalty customers drive 97% of revenue, they introduce referral bonuses, personalized product recommendations, and early-access sales to retain and grow this segment. Encourage non-members to join with a simple signup incentive.








