
# 📦 **Logistics Performance Analysis – A Dashboard by Stark Industries**

![image](https://github.com/user-attachments/assets/ee8b0762-9aa3-4a0a-92b4-340cd7cc3479)

## 🧭 **Project Overview – Setting the Stage**

At *Stark Industries*, innovation isn’t just in the products — it’s in the systems that deliver them. As a global leader in cutting-edge technology, ensuring timely, accurate, and cost-efficient delivery of our products is a mission-critical operation. To evaluate and enhance our logistics ecosystem, our Data & Insights Division developed a dynamic, interactive **Power BI dashboard** that visualizes key logistics metrics from **August 2022 to August 2024**.

The goal? To uncover operational inefficiencies, analyze shipment trends, optimize delivery timelines, and ultimately, create a frictionless experience for our global customer base.

---

## 🎯 **Business Agenda – Why This Project Matters**

Every delayed shipment tells a story. Every return hints at a potential flaw. Every completed delivery marks success.

This project was initiated to:

* Understand the **efficiency of our supply chain**.
* Analyze which product categories are generating the most **returns or delivery delays**.
* Track how our **sales team is contributing** to successful deliveries.
* Identify which **countries and months are outliers** in performance.
* Drive **data-backed decisions** to optimize warehouse planning, resource allocation, and customer satisfaction.

We weren’t just building a dashboard — we were creating a **decision-making engine**.

---

## 🗂️ **Data at the Core – What We Analyzed**

To make informed decisions, we drew from multiple data streams:

* **Shipment Records**: Active, completed, and returned shipments with timestamps.
* **Product Categories**: Electronics, Audio, Office Equipment, Computing.
* **Revenue Metrics**: Shipment-level and monthly revenue insights.
* **Geographic Data**: Country-wise delivery analysis.
* **Sales Data**: Salesperson performance, shipment success rate, return history.

We combined, cleaned, and transformed this data within Power BI using **Power Query** and **DAX measures** to build a live, filterable dashboard.

---

## 📊 **Insights That Changed the Game**

### 🔹 **1. Shipment Status Snapshot**

Out of **5,000 total shipments**, only **60% were completed**, with **2,000 still active** and **248 returned**. This raised a red flag — why were so many shipments still in transit or being returned?

### 🔹 **2. Delivery Delays by Country**

Our average delivery time clocked in at **9.68 days**, but a closer look showed **severe lags in Australia (20 days)**, **Japan (18 days)**, and **India (15 days)**. In contrast, **USA (1 day)** and **Canada (2 days)** showed stellar performance. These insights prompted discussions on **regional fulfillment centers**, especially in the APAC region.

### 🔹 **3. Category-Wise Return Rates**

We discovered that **Electronics accounted for 68.1%** of all returns — far exceeding any other category. On the other hand, **Office Equipment had only 17.7% returns**. This sparked questions about product durability, packaging, and customer expectations. Why is our most popular segment also our most problematic?

### 🔹 **4. Revenue Trends**

Revenue analysis revealed **March, May, and November** as peak-performing months, indicating seasonality. Surprisingly, **February consistently underperformed**, likely due to its shorter cycle. This trend could help in **campaign planning and demand forecasting**.

### 🔹 **5. Sales Team Performance**

Some of our sales reps emerged as stars. **Jessica White**, for instance, handled **269 shipments**, completing **238**, with only **12 returns** — an exemplary record. Meanwhile, **Brandon Richards and Kayla Banks** had higher return percentages despite handling fewer shipments — suggesting a need for further training or process improvements.

---

## 💡 **Business Insights & Strategic Recommendations**

* **Optimize Delivery Routes** in countries with long lead times.
* **Deep-dive into Electronics** category to resolve return causes.
* **Leverage top sales performers** as mentors and benchmark best practices.
* **Align inventory and campaigns** with revenue peaks in spring and fall.
* **Implement return prediction models** to preempt high-risk shipments.

This dashboard is not just diagnostic — it lays the foundation for **predictive and prescriptive analytics**.

---

## 🛠️ **Tools & Technologies**

* **Power BI**: Dashboard development, DAX, Power Query
* **ETL Processes**: Cleaned, merged, and reshaped multi-source datasets
* **Data Modeling**: Time intelligence, performance KPIs, geographic mapping
* *(Optional)* Python/R: Can be added for future modeling and automation.

---

## 🔍 **Challenges Faced**

* Integrating inconsistent time formats and delivery statuses.
* Segmenting product-level data for deep analysis in Power BI.
* Visualizing geo-based delivery delays in a meaningful, actionable way.
* Ensuring dashboard remained responsive with complex filters applied.

---

## 🔮 **Future Scope – Turning Intelligence into Action**

This project is just the beginning.

* We plan to integrate **machine learning models** into the system to predict:

  * Delivery delays
  * Product return likelihood
  * Optimal shipping paths
* A **clustering model** could segment regions or customers based on risk or profitability.
* A **time series model** can forecast future monthly revenue and shipment volumes.
* We also aim to deploy **what-if analysis tools** within Power BI for dynamic decision-making.

---

## 🧾 **Deliverables**

* Fully interactive Power BI dashboard (available online or as a file).
* PDF report summarizing key insights and recommendations.
* Presentation slide deck for stakeholders.
* Documented DAX code and calculated measures.

---

## 🏁 **Conclusion**

Through this project, Stark Industries has gained **end-to-end visibility** into its logistics ecosystem. By transforming raw data into a story of trends, gaps, and actions, we’ve empowered leadership to make faster, smarter, and more customer-centric decisions. The dashboard is now a **living asset** — not just for monitoring the present, but for shaping the future of our operations.




## Goal:
The goal of my Power BI logistics dashboard is to provide a comprehensive, interactive view of key logistics and sales metrics to drive operational efficiency, data-driven decision-making, and improved team performance. It tracks essential logistics indicators such as **Revenue**, **Total Shipments**, **Active Shipments**, **Returned Shipments**, **Completed Shipments**, and **Average Delivery Time**, offering insights into the performance of shipments and delivery operations. 

The dashboard also includes analysis of **Product Categories**, **Country Names**, and **Average Time by Geography**, helping to pinpoint regional and product-specific inefficiencies. Additionally, it tracks **Salesperson Individual Performance**, enabling management to monitor and evaluate the effectiveness of each team member. 

The dashboard also visualizes trends such as **Revenue by Month**, **Shipments by Month**, and **Yearly Performance**, allowing for better forecasting, capacity planning, and resource allocation. Overall, this tool empowers stakeholders to identify bottlenecks, optimize resources, improve customer satisfaction, and enhance overall logistics and sales performance.


## Dataset: 
The goal of my Power BI logistics dashboard is to integrate and visualize data from four key datasets to improve logistics and sales performance. These datasets are:

Country Dataset: Includes information on Geography and Region, helping to analyze shipments across different regions and geographies.

Products Dataset: Contains Product, Category, and Cost per Box, enabling analysis of product performance, categories, and cost efficiency.

Salesperson Dataset: Tracks Salesperson, Team, and Picture, allowing evaluation of individual salesperson performance and team dynamics.

Shipments Dataset: Provides shipment-specific details like Shipment ID, Salesperson, Geography, Product, Date, Sales, Status, and Delivered On, offering insights into shipment performance, delivery timelines, and sales tracking.

By combining these datasets, the dashboard provides actionable insights on sales performance, regional trends, product efficiency, and shipment status. It enables data-driven decisions for optimizing logistics, sales efforts, and overall operational performance.
