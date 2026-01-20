# European Retail Sales Performance Analysis

A comprehensive data analytics project investigating retail performance, profitability, and logistics efficiency across the European market. This project integrates multiple data sources to identify high-value regions and product category trends.

---

## Project Overview
This analysis combines order details with geographical data to provide a 360-degree view of retail operations. It focuses on the relationship between shipping logistics, regional demand, and bottom-line profitability.

**Key Metrics Analysed:**
- **Financial Health:** Total Sales, Net Profit, and Profit Margins.
- **Logistics Efficiency:** Shipping modes (Economy vs Priority) and their impact on delivery volume.
- **Product Hierarchy:** Performance across Furniture, Technology, and Office Supplies.
- **Geographic Segmentation:** Market dominance across Central, North, and South European regions.

---

## Data Engineering and Integration
A significant portion of this project involved preparing the data for analysis:
- **Relational Data Modelling:** Joined the `ListOfOrders` and `OrderBreakdown` datasets using a unique 'Order ID' primary key.
- **Geocoding:** Utilised Latitude and Longitude coordinates to map sales density at the city and state levels.
- **Schema Cleaning:** Standardised date formats and currency values to ensure cross-border financial accuracy.

---

# Key Visualisations and Insights

### 1. Regional Profitability Map (Geospatial)
**Purpose:** Identifying which European cities and countries generate the highest revenue.

<img width="410" height="380" alt="image" src="https://github.com/user-attachments/assets/d49b5817-939c-46a3-856d-19c873c66938" />

**Analytical Insight:**
* **Central Hubs:** Central Europe (particularly Germany and France) shows the highest order volume, suggesting a more mature logistics network.
* **Profitability Pockets:** While some regions have high sales, others like Northern Europe show superior profit margins due to lower shipping complexities.
* 
---

### 2. Category and Sub-Category Performance (Matrix)
**Purpose:** Breaking down sales volume by product type to identify "Hero Products".

<img width="474" height="360" alt="image" src="https://github.com/user-attachments/assets/3f95bfd0-75e4-4b8e-abc0-99b3c298686c" />

**Analytical Insight:**
* **Technology Dominance:** Technology products (such as Copiers and Phones) drive the highest revenue per unit.
* **Office Supplies Volume:** While lower in price, Office Supplies account for the highest transaction frequency, acting as a steady foundation for the business.

---

### 3. Shipping Mode and Customer Segment Analysis
**Purpose:** Understanding how different customer types (Corporate vs Home Office) prefer their items to be shipped.

<img width="545" height="378" alt="image" src="https://github.com/user-attachments/assets/ad3234b3-a94d-4187-ae9c-c1b192ea3284" />

**Analytical Insight:**
* **Consumer Behaviour:** The "Consumer" segment heavily prefers Economy shipping, whereas "Corporate" clients show a higher tolerance for Priority shipping costs to ensure speed.

---
### 4. Sales and Profit Trends
**Purpose:** Tracking the growth of the business from 2011 to 2014 to identify seasonal peaks and long-term viability.

<img width="426" height="354" alt="image" src="https://github.com/user-attachments/assets/0f3f790d-56cb-4bcc-a0ac-d24ff7a42204" />

**Analytical Insight:**
* **Steady Growth:** Both sales and profit show a consistent upward trend, with a notable surge in late 2014.
* **Seasonal Peaks:** The business experiences high activity in the final quarter (Q4) of each year, suggesting a strong holiday retail influence.

---

### 5. Profit Margin by Category
**Purpose:** Evaluating which product sectors are the most "efficient" at converting revenue into actual profit.

<img width="345" height="379" alt="image" src="https://github.com/user-attachments/assets/96894fb8-c9e3-4647-ad79-9751ae3948ab" />

**Analytical Insight:**
* **Efficiency Leader:** **Office Supplies** maintains the highest profit margin (approx. 15.2%), making it the most stable sector despite lower individual item prices.
* **High Revenue, Lower Margin:** **Technology** generates the most total revenue, but its margin (12.3%) is lower than Office Supplies due to higher sourcing costs.
* **Furniture Challenges:** This category shows the lowest margin (approx. 7.8%), likely due to high shipping costs and bulky logistics for large items.

---

## Business Insights
1. **Operational Efficiency:** Integrating shipping data reveals that "Economy" shipping accounts for the majority of volume, but "Economy Plus" offers a potential upsell opportunity for better service margins.
2. **Product Strategy:** Furniture often sees higher discount rates which can erode profit; a shift toward Technology accessories could improve overall net margins.
3. **Geographic Focus:** Italy and Spain show emerging growth patterns, suggesting these are prime markets for targeted marketing campaigns.

---

## Skills Demonstrated

### Data Modelling and BI
* **Relational Database Design:** Successfully linking disparate tables to create a unified data model.
* **Power BI / Tableau Proficiency:** Building interactive dashboards with cross-filtering capabilities.
* **DAX / Calculated Expressions:** Creating custom measures for Profitability and Growth rates.

### Business Intelligence
* **Supply Chain Analytics:** Analysing shipping modes and delivery segments.
* **Strategic Storytelling:** Converting transactional data into geographic and category-based business recommendations.

---

##  Dashboard Preview

<img width="1313" height="792" alt="image" src="https://github.com/user-attachments/assets/c21a49ef-487f-44eb-87e0-6077d95c5a4a" />

## If you find this project useful or insightful, feel free to ⭐ star the repository!
