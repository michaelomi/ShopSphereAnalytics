# ShopSphere Business Performance Report 📊

## Introduction 📝
This report analyzes the 2021 performance of ShopSphere, an e-commerce platform, using data from its Overview, Orders, Customers, and Products dashboards, supplemented by SQL-based order fulfillment and inventory analysis. The goal is to identify key trends, strengths, and areas for improvement, followed by actionable recommendations to enhance business outcomes. The data provides insights into revenue, orders, customer demographics, product performance, traffic sources, shipping efficiency, and inventory management, offering a comprehensive view of ShopSphere’s operations.

Interact with the Power BI dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiZGJjMGY3NDktZjIxOS00NzBjLWFjZjUtNjgwYzkzODc3N2FkIiwidCI6IjA1ODU3NTFmLTRiNDctNDUzOS04YmMzLWJmODNlMmVlMWQzZiJ9&pageName=e6d655bfd3aa13559542)

## Executive Summary 🚀
In 2021, ShopSphere achieved significant growth in key metrics:
- **Revenue** 💰: $1,450,111.71, a 93.72% year-over-year (YoY) increase.
- **Orders** 📦: 24,306, up 91.48% YoY.
- **Customers** 👥: 14,659, with a balanced gender distribution (50.75% male, 49.25% female).
- **Profit** 📈: $752,819.93, up 93.6% YoY, though the profit margin slightly declined by 0.07% to 51.91%.

The business excelled in categories like Outerwear & Coats (28% revenue share) and Jeans (27%), with strong order volumes in locations like Memphis, TN, and Chicago, IL. Shipping performance showed an average of 1 day to ship and 3 days to deliver, though distribution center inefficiencies (e.g., Chicago IL with 51.51% late orders) and high returns in categories like Jumpsuits & Rompers (11.42%) indicate operational challenges. Recommendations focus on optimizing product offerings, improving fulfillment, diversifying traffic sources, and targeting high-potential customer segments.

## Data Analysis 🔍

### 1. Financial Performance (Overview Dashboard) 💸
![Dashboard showing financial metrics](https://imgur.com/zvfCYbW.png)
- **Revenue** 💵: $1,450,111.71, up 93.72% YoY.
- **Cost** 💳: $697,291.80, up 93.86% YoY.
- **Profit** 📈: $752,819.93, up 93.6% YoY.
- **Profit Margin** 📉: 51.91%, down 0.07% YoY.
- **Revenue Trend** 📅: Revenue peaked in November, likely due to holiday shopping, with a steady upward trend throughout the year.

**Insight** 💡: The near-identical growth rates in revenue and cost (93.72% vs. 93.86%) indicate that expenses are scaling proportionally with revenue, which has led to a slight decline in profit margin. This suggests potential inefficiencies in cost management or pricing strategies.

### 2. Orders and Customer Trends (Orders Dashboard) 📦👥
![Dashboard showing orders and customer metrics](https://imgur.com/ynUY225.png)
- **Total Orders** 📦: 24,306, up 91.48% YoY.
- **Total Customers** 👥: 14,659.
- **Orders by Location** 🌍:
  - Memphis, TN: 3.2K orders.
  - Chicago, IL: 3.2K orders.
  - Houston, TX: 3.0K orders.
  - Mobile, AL: 2.5K orders.
  - Philadelphia, PA: 2.2K orders.
- **Orders by Gender** ⚥: 50.51% male, 49.49% female.
- **Orders by Age Group** 👶🧑‍🦳:
  - Young: 24.05%.
  - Middle: 38.93%.
  - Old: 37.02%.
- **Order Status** 📋:
  - Shipped ✅: 4.3K.
  - Complete ✔️: 3.5K.
  - Processing ⏳: 2.9K.
  - Cancelled 🚫: 2.1K.
  - Returned 🔄: 1.4K.

**Insight** 💡: The high cancellation (2.1K) and return (1.4K) rates suggest potential issues with product quality, sizing, or customer expectations. The balanced gender split and higher order volumes from middle and older age groups indicate a broad appeal, but the young demographic (24.05%) is underrepresented.

### 3. Customer Demographics and Traffic Sources (Customers Dashboard) 👥🌐
![Dashboard showing customer demographics and traffic sources](https://imgur.com/hEuQpEC.png)
- **Total Customers** 👥: 14,659.
- **Top 5 Customers** 🏆:
  - Highest spender: $1,172.97 (Male, Middle-aged, United States, Search traffic).
- **Customers by Country** 🌍: Significant presence in the United States, China, Australia, Spain, and Japan.
- **Customers by Gender** ⚥: 50.75% male, 49.25% female.
- **Customer Distribution by Age** 👶🧑‍🦳:
  - Young: 23.77%.
  - Middle: 38.87%.
  - Old: 37.36%.
- **Traffic Source Breakdown** 🌐:
  - Search 🔍: 69.40%.
  - Organic 🌱: 15.42%.
  - Facebook 📘: 6.09%.
  - Email 📧: 5.01%.
  - Display 📺: 4.08%.

**Insight** 💡: The heavy reliance on search traffic (69.40%) poses a risk, as changes in search engine algorithms or increased competition could impact customer acquisition. The balanced gender distribution and international presence (e.g., China, Australia) highlight opportunities for global expansion.

### 4. Product Performance (Products Dashboard) 🛍️
![Dashboard showing product performance metrics](https://imgur.com/hk3JPB2.png)
- **Total Available Products** 🛒: 7,992.
- **Category Breakdown** 📋:
  - **Outerwear & Coats** 🧥: 770 orders, 742 customers, 55.92% profit, $118,404.62 revenue, 116.75% YoY growth.
  - **Jeans** 👖: 1,063 orders, 1,008 customers, 46.71% profit, $108,457.07 revenue, 117.45% YoY growth.
  - **Suits & Sport Coats** 🕴️: 715 orders, 683 customers, 55.71% profit, $91,968.98 revenue, 100.83% YoY growth.
  - **Sweaters** 🧣: 873 orders, 834 customers, 47.68% profit, $66,192.48 revenue, 65.50% YoY growth.
  - **Pants** 👖: 979 orders, 931 customers, 53.98% profit, $58,370.59 revenue, 86.94% YoY growth.
  - **Hoodies & Sweatshirts** 🏂: 905 orders, 882 customers, 45.01% profit, $55,444.76 revenue, 108.42% YoY growth.
  - **Tops & Tees** 👕: 1,084 orders, 1,025 customers, 44.06% profit, $45,482.10 revenue, 121.94% YoY growth.
  - **Shorts** 🩳: 856 orders, 819 customers, 50.08% profit, $43,817.01 revenue, 89.30% YoY growth.

**Insight** 💡: Outerwear & Coats and Jeans lead in revenue share (28% and 27%, respectively), but categories like Tops & Tees (121.94% YoY growth) and Hoodies & Sweatshirts (108.42% YoY growth) show the highest growth potential. Sweaters, despite decent order volume, have the lowest YoY growth (65.50%) and a relatively low profit margin (47.68%).

### 5. Order Fulfillment and Inventory Optimization 📦🔧
```sql
-- Percentage of orders delayed beyond the expected delivery date by distribution center
WITH avg_delivery_time AS (
    SELECT AVG(DATEDIFF(DAY, shipped_at, delivered_at)) AS avg_delivery_time
    FROM order_items
    WHERE delivered_at IS NOT NULL AND shipped_at IS NOT NULL
),
late_delivery_counts AS (
    SELECT inventory.product_distribution_center_id, COUNT(*) AS late_order_count
    FROM order_items
    JOIN inventory_items AS inventory ON order_items.inventory_item_id = inventory.id
    CROSS JOIN avg_delivery_time
    WHERE delivered_at IS NOT NULL AND shipped_at IS NOT NULL
      AND DATEDIFF(DAY, shipped_at, delivered_at) > avg_delivery_time.avg_delivery_time
    GROUP BY inventory.product_distribution_center_id
),
total_order_counts AS (
    SELECT inventory.product_distribution_center_id, COUNT(*) AS total_order_count
    FROM order_items
    JOIN inventory_items AS inventory ON order_items.inventory_item_id = inventory.id
    WHERE delivered_at IS NOT NULL
    GROUP BY inventory.product_distribution_center_id
)
SELECT late_counts.product_distribution_center_id,
       CAST(late_counts.late_order_count * 100.0 / NULLIF(total_counts.total_order_count, 0) AS DECIMAL(10, 2)) AS percentage_of_late_orders
FROM late_delivery_counts AS late_counts
JOIN total_order_counts AS total_counts
    ON late_counts.product_distribution_center_id = total_counts.product_distribution_center_id
ORDER BY percentage_of_late_orders DESC;
```
#### Order Fulfillment
- **Average Time to Ship and Deliver** ⏱️:
  - Average days to ship: 1 day.
  - Average days to deliver: 3 days.
- **Percentage of Orders Returned by Product Category** 🔄:
  - Jumpsuits & Rompers: 11.42% (highest return percentage).
- **Percentage of Orders Delayed Beyond Expected Delivery Date by Distribution Center** ⏳:
  - Chicago IL: 51.51% (highest percentage of late orders).
- **Best Performing Distribution Centers (Ranked by Average Delivery Time)** 🏆:
  - Charleston SC and Chicago IL: Tied at 3 days average delivery time (ranked first).

#### Inventory Optimization
- **Aging Inventory (Unsold > 90 Days)** 📦:
  - Intimates: Highest count of unsold items.
  - Jeans: Second highest count of unsold items.

**Insight** 💡: Shipping efficiency is strong (1 day to ship, 3 days to deliver on average), but Chicago IL’s high late order rate (51.51%) despite its 3-day average delivery time suggests inconsistent performance. High return rates in Jumpsuits & Rompers (11.42%) indicate quality or fit issues, while aging inventory in Intimates and Jeans points to overstocking or low demand.


## Key Insights 🧠
1. **Financial Growth with Margin Concerns** 📉:
   - Revenue and profit growth are strong, but the slight decline in profit margin (0.07%) indicates that costs are rising almost as fast as revenue, potentially due to increased shipping or sourcing expenses.
   
2. **Order and Customer Behavior** 📦👥:
   - High cancellation (2.1K) and return (1.4K) rates, compounded by an 11.42% return rate in Jumpsuits & Rompers, suggest issues with product quality, sizing, or customer expectations.
   - The middle and older age groups dominate orders (38.93% and 37.02%), while the young demographic (24.05%) is underrepresented, potentially missing a key market segment.
   - Top locations like Memphis, TN, and Chicago, IL, show strong demand, but Chicago’s 51.51% late order rate is a concern.

3. **Customer Acquisition Risks** 🌐:
   - Heavy reliance on search traffic (69.40%) poses a risk from algorithm changes or competition. Diversifying traffic sources could mitigate this.
   - International markets (e.g., China, Australia) show promise for expansion.

4. **Product Performance Disparities** 🛍️:
   - Outerwear & Coats and Jeans lead in revenue, but Tops & Tees (121.94% YoY growth) and Hoodies & Sweatshirts (108.42% YoY growth) show high growth potential. Sweaters underperform (65.50% YoY growth, 47.68% profit margin).
   - High returns in Jumpsuits & Rompers and aging inventory in Intimates and Jeans signal category-specific challenges.

5. **Fulfillment and Inventory Issues** 📦🔧:
   - Average shipping (1 day) and delivery (3 days) times are efficient, but Chicago IL’s 51.51% late order rate indicates operational inefficiencies.
   - Aging inventory in Intimates and Jeans suggests overstocking or misaligned demand forecasting.


## Recommendations 💡

### 1. Improve Profit Margin 📈
- **Cost Optimization** 💸: Analyze shipping and inventory costs, especially in Chicago IL, where late orders (51.51%) may increase expenses. Negotiate better supplier rates or optimize logistics.
- **Pricing Strategy** 💰: Increase prices slightly in high-demand categories like Outerwear & Coats (e.g., 5% = ~$5,920 additional revenue) to offset costs.
- **Bundle Offers** 🎁: Pair Jeans with Tops & Tees to boost order value and reduce aging inventory.

### 2. Reduce Cancellations and Returns 🚫🔄
- **Enhanced Product Descriptions** 📜: Add detailed sizing guides and reviews, especially for Jumpsuits & Rompers (11.42% returns), to set accurate expectations.
- **Quality Control** ✅: Strengthen checks for high-return categories like Jumpsuits & Rompers and Hoodies & Sweatshirts (45.01% profit margin).
- **Return Policy Optimization** 🔄: Offer free size exchanges to retain customers and analyze return data for patterns.

### 3. Target the Young Demographic 👶
- **Marketing Campaigns** 📣: Use Instagram and TikTok to promote Tops & Tees and Hoodies & Sweatshirts, targeting the underrepresented young demographic (24.05%).
- **Product Expansion** 🛍️: Introduce youth-oriented items like graphic tees to reduce reliance on aging categories like Intimates.
- **Influencer Partnerships** 🌟: Partner with young influencers to boost brand appeal.

### 4. Diversify Traffic Sources 🌐
- **Increase Organic and Social Media Presence** 🌱📘: Boost organic traffic (15.42%) with content marketing and enhance Facebook (6.09%) campaigns with targeted ads.
- **Email Marketing** 📧: Use the 14,659-customer base for personalized offers, driving repeat purchases.
- **Partnerships** 🤝: Collaborate with fashion blogs to increase display traffic (4.08%).

### 5. Optimize Product Offerings and Inventory 🛒
- **Focus on High-Growth Categories** 🚀: Allocate more budget to Tops & Tees (121.94% YoY growth) and Hoodies & Sweatshirts (108.42% YoY growth).
- **Reevaluate Underperformers** 🧣: Refresh Sweaters (65.50% YoY growth) and clear aging Intimates and Jeans inventory through promotions.
- **Address High Returns** 🔄: Investigate Jumpsuits & Rompers (11.42% returns) for quality or fit issues and adjust offerings.
- **Seasonal Promotions** 🎄: Leverage November peaks with promotions on Outerwear & Coats (55.92% profit margin).

### 6. Enhance Fulfillment Efficiency 📦
- **Improve Chicago IL Operations** ⏳: Address the 51.51% late order rate with staffing or process improvements, despite its 3-day average delivery ranking.
- **Optimize Distribution Centers** 🏆: Benchmark Chicago IL and Charleston SC (3-day delivery) to improve other centers’ performance.
- **Inventory Management** 🔧: Reduce aging stock (e.g., Intimates, Jeans) with targeted sales or adjusted procurement.

### 7. Expand in High-Potential Markets 🌍
- **Regional Focus** 📍: Boost marketing in Memphis, TN, and Chicago, IL, while addressing Chicago’s fulfillment issues. Research barriers in Philadelphia, PA.
- **International Expansion** 🌎: Target China and Australia with localized offerings based on top customer data.

## Conclusion 🎯
ShopSphere’s 2021 performance reflects robust growth (93.72% YoY revenue increase, 24,306 orders), but challenges like a declining profit margin, high return rates (e.g., Jumpsuits & Rompers at 11.42%), fulfillment delays (e.g., Chicago IL at 51.51%), and aging inventory (e.g., Intimates) require attention. By optimizing costs, targeting younger customers, diversifying traffic, enhancing fulfillment, and refining product offerings, ShopSphere can sustain growth and improve profitability in 2022 and beyond.

## Appendix 📋
- **Data Source** 📊: Link to Kaggle Dataset [here](https://www.kaggle.com/datasets/daichiuchigashima/thelook-ecommerce/data)
- **Tools Used** 🛠️: SQL, Power BI, AI, Figma
- 
