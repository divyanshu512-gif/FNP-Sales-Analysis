# FNP-Sales-Analysis

This project presents a comprehensive sales analysis dashboard for FNP (Ferns N Petals). The objective is to analyze sales data using the ETL (Extract, Transform, Load) process to clean, structure, and extract meaningful insights from raw datasets.

The project focuses on data cleaning, transformation, and visualization to identify key performance indicators such as revenue trends, customer behavior, product performance, and seasonal demand patterns.

An interactive dashboard has been developed to support data-driven decision-making and help management optimize sales strategies.

---

## Problem Statement of Ferns and Petals Sales Analysis

You have been given a dataset from FNP (Ferns and Petals) that specializes in sending gifts for various occasions like Diwali, Raksha bandhan, Holi, Valentine's Day, Birthdays and Anniversaries. The dataset contains details about the products, orders, customers and relevant dates. Your task is to analyze this dataset to uncover key insights related to sales trends, customer behavior and product performance.

create a dashboard to help the company improve its sales strategy and optimize customer satisfaction.

---

## Business Questions

**1**. **Total Revenue**: Identify the overall revenue.

**2**. **Average Order and Delivery Time**: Evaluate the time taken for orders to be delivered.

**3**. **Monthly Sales Performance**: Examine how sales fluctuate across the months of 2023.

**4**. **Top Products by Revenue**: Determine which products are the top revenue generators.

**5**. **Customer Spending Analysis**: Understand how much customers are spending on average.

**6**. **Sales Performance by Top 5 Product**: Track the sales performance of top 5 products.

**7**. **Top 10 Cities by Number of Orders**: Find out which cities are placing the highest number of orders.

**8**. **Order Quantity vs Delivery Time**: Analyze if higher order quantities impact delivery times.

**9**. **Revenue Comparison Between Occasions**: Compare revenue generated across different occasions.

**10**. **Product Popularity by Occasion**: Identify which products are most popular during specific occasions.

---

## Data Summary
  | **Customer** | **Orders** | **Products** |
  | ------------ | ---------- | ------------ |
  |   **Columns**: 7 | **Columns**: 10 | **Columns**: 6 |
  |   **Rows**: 101  | **Rows**: 1001 | **Rows**: 71 |

## Columns Name
     
  | **Customer id** | **Order id** | **Product id** |
  | --------------- | ------------ | -------------  |
  |   **Name**      | **Customer id** | **Product name** |                            
  |   **City**      | **Product id**  | **Category**     |
  |   **Contact**   | **Quantity**    | **Price**        |
  |   **Email**     | **Order Date**  | **Occasion**     |
  |   **Gender**    | **Order Time**  | **Description**  |
  |   **Address**   | **Delivery Date** |                |
  |                 | **Delivery Time** |                |
  |                 | **Location**   |                   |
  |                 | **Occasion**   |                   |

---  
  
## FNP Data Analysis(Extracting Information)

![image](https://github.com/divyanshu512-gif/FNP-Sales-Analysis/blob/main/Image/FNP_Sales_Analysis.png)

**1**. The total revenue of FNP is ₹ **35,20,984.00**.

**2**. The average time taken to delivery a product is **5 days**.

**3**. In 2023, FNP’s sales were strong from January to April. This was followed by a relatively flat and lower performance from April to July. Sales then peaked between July and September, marking the highest period of the year. From September to October, sales again remained low and stable. Starting in October, sales began to increase and continued to grow through November. However, after November, sales declined and continued to decrease through December.

**4**. Top 5 products of FNP on basis revenue in descending order.

 -  Magnam set
 -  Quia gift
 -  Dolores gift
 -  Hamur Pack
 -  Deserunt Box
      
**5**. The average spending of customer is ₹ **3521**.

**6**. Top 5 products by category perfomance.

  - **Colors**: Colors are the most in-demand product category, showing exponential growth over time. This surge is likely driven by seasonal events such as Holi, along with increasing customer engagement in festive purchases.

  - **Soft Toys**: Soft toys rank second in demand, with particularly strong popularity among younger consumers. They are commonly purchased as gifts for occasions like birthdays, anniversaries, and romantic celebrations.

  - **Sweets**: Sweets hold the third position, reflecting their cultural significance in India. Demand remains consistently high due to their essential role in festivals, celebrations, and traditional gifting.

  - **Cakes**: Cakes rank fourth and have steady demand throughout the year. They are widely used for multiple occasions, including birthdays, anniversaries, and other personal celebrations.

  - **Raksha Bandhan Products**: Raksha Bandhan-related items (such as rakhis and gift hampers) occupy the fifth position. Their demand is highly seasonal, peaking during the month of August in line with the festival.

**7**. Top 10 cities on the basis of orders.

- **Imphal**
- **Dhanbad**

