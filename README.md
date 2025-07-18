# Myntra-Products-Analysis-using-Power-BI

# Myntra Products Analysis Dashboard

## Project Overview

This Power BI dashboard provides a comprehensive analysis of Myntra's product data, focusing on **product performance, customer satisfaction, pricing strategies, and discount effectiveness**. 

The dataset is sourced form Kaggle and the link for downloading the dataset is:https://www.kaggle.com/datasets/ronakbokaria/myntra-products-dataset

The dashboard is structured into three main pages, each offering distinct analytical perspectives.

---

### 1. Overview

**Objective:** To provide a high-level summary of key performance indicators and overall product/brand distribution, offering a quick understanding of Myntra's product landscape.

**Visualizations & Insights:**

* **KPI Cards (Top Left Section):**
    * **Purpose:** To highlight critical summary metrics at a glance.
    * **Metrics:** "Total Products" (1M), "Average Selling Price" (₹1.54K), "Average Rating" (1), "Total Discount Value" (₹6.43bn), "Average of Discount" (149.64), and "Hypothetical Revenue" (2bn).
    * **Insights:**
        * The "Total Products" figure indicates a very extensive product catalog, showcasing Myntra's large scale.
        * The "Average Selling Price" gives a quick sense of the typical price point for products on the platform.
        * "Total Discount Value" highlights the substantial financial commitment to promotions and price reductions.
        * "Hypothetical Revenue" offers a benchmark for potential earnings without discounts, emphasizing their impact.
       

* **"Products by Top Brands" (Bar Chart - Top Right):**
    * **Purpose:** To clearly visualize and compare the product volume offered by Myntra's leading brands.
    * **Insights:** This chart directly identifies the brands contributing the most products to the catalog (e.g., "Roadster", "HRX"). The consistent yellow/gold bars ensure easy comparison and highlight brand dominance in terms of listings.
    * **Actionable Intelligence:** Helps in understanding key brand partnerships, inventory management, and market presence for top contributors.

* **"Total Products by Brand" (Donut Chart - Bottom Right):**
    * **Purpose:** To show the proportional distribution of all products across different brands, including those with smaller contributions.
    * **Insights:** Provides a holistic view of the product portfolio breakdown by brand, complementing the "Top Brands" chart by illustrating market share visually.
    * **Actionable Intelligence:** Useful for identifying both major brand contributions and the presence of niche brands, guiding decisions on inventory diversification and brand expansion strategies.

* **"Brand" Slicer (Bottom Left):**
    * **Purpose:** To enable interactive filtering of all visuals on the dashboard by specific brands.
    * **Insights:** Allows users to dynamically narrow down the analysis to focus on one or more selected brands, providing on-demand detailed views of their performance metrics.

---

### 2. Product Performance & Customer Satisfaction

**Objective:** To delve deeper into how individual products are performing based on customer ratings and review volume, assessing overall customer satisfaction.

**Visualizations & Insights:**

* **"Brand" Slicer (Top Left):**
    * **Purpose:** Maintains the crucial filtering capability, allowing users to analyze product performance and customer satisfaction specifically for chosen brands.
    * **Insights:** Seamlessly integrates filtering across pages for a consistent analytical flow.

* **"Top 20 Products by Average Rating" (Table - Middle Left):**
    * **Purpose:** To identify specific products that customers rate highly.
    * **Insights:** The table clearly lists products by their average rating. The **conditional formatting using pink/purple to green data bars** for the "Rating" column provides an instant visual indication of customer satisfaction, with green signifying higher ratings and pink/purple indicating lower ones.
    * **Actionable Intelligence:** High-rated products can be targeted for promotion or studied to understand success factors.

* **"Top 20 Products by Total Ratings Volume" (Table - Bottom Left):**
    * **Purpose:** To highlight products that generate significant customer engagement through a large number of reviews.
    * **Insights:** This table lists products based on the sheer volume of ratings, providing insight into popularity or high sales figures. The data bars visually represent the volume of reviews, making comparisons intuitive.
    * **Actionable Intelligence:** These are often best-sellers or highly visible products. Strategies can focus on managing customer feedback for these influential items or ensuring stock availability.

* **"Product Details" (Table - Right Side):**
    * **Purpose:** To provide granular, row-level details for specific products.
    * **Insights:** This comprehensive table displays `Brand`, `Product Name`, `Selling Price`, `Rating`, and `Total Rating` for individual products, acting as a valuable lookup tool.
    * **Actionable Intelligence:** Supports detailed investigations into product attributes, allowing users to examine specific items highlighted by other visuals or filtered by the slicer.

---

### 3. Pricing & Discount Analysis

**Objective:** To analyze the effectiveness of pricing and discount strategies, understand their impact, and identify trends across different product segments.

**Visualizations & Insights:**

* **KPI Cards (Top Left Section):**
    * **Purpose:** To present essential summary statistics related to the overall pricing and discount landscape.
    * **Metrics:** These include `Total Products`, `Average Selling Price`, `Average Rating`, `Total Discount Value`, `Average of Discount`, and `Hypothetical Revenue`.
    * **Insights:** These KPIs provide an immediate context for the magnitude of discounting and its potential financial implications across the entire product catalog.

* **"Brand" Slicer (Top Left):**
    * **Purpose:** Facilitates brand-specific analysis of pricing and discount strategies.
    * **Insights:** Allows users to compare how pricing and discount approaches differ or perform for individual brands.

* **"Average Selling Price by Brand" (Bar Chart - Bottom Left):**
    * **Purpose:** To visually represent the typical selling price across different brands.
    * **Insights:** The vibrant yellow/gold bars clearly show which brands typically have higher or lower average selling prices. This helps categorize brands into premium, mid-range, or budget segments.
    * **Actionable Intelligence:** Aids in understanding brand positioning in the market and informs pricing strategy alignments.

* **"Products with Highest Discounts" (Table - Middle):**
    * **Purpose:** To pinpoint individual products that are subject to the most aggressive price reductions.
    * **Insights:** This table lists products by their discount amount, often highlighting items with significant markdowns. Conditional formatting helps visually identify these.
    * **Actionable Intelligence:** Crucial for managing profitability, identifying slow-moving inventory, or analyzing the necessity and impact of deep discounts.

* **"Total Discount Value by Brand" (Treemap - Right):**
    * **Purpose:** To visualize the proportional contribution of each brand to the total discount value across Myntra.
    * **Insights:** The size of each rectangular segment in the treemap indicates the magnitude of discount value attributed to that brand. The custom dark-themed color palette ensures clarity and aesthetic appeal.
    * **Actionable Intelligence:** Helps in understanding where the most significant promotional budgets are being allocated and can inform strategic discussions with brands regarding discount agreements.

