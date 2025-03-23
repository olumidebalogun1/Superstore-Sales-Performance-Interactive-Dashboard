# **📊 Tableau Project: Superstore Sales Performance Interactive Dashboard**

![4  Sales Performance Dashboard](https://github.com/user-attachments/assets/f659d52f-f3b2-4fdf-9fd2-08bb918693f3)

## **Introduction**
Welcome to the **Tableau Superstore Sales Performance Dashboard Project**, where raw data transforms into dynamic, automated, and visually compelling dashboards that **fuel smarter decision-making, strategic growth, and business success**.

In today’s fast-paced, data-driven world, information isn’t just numbers, it’s the **heartbeat of every decision**. This project is designed to empower stakeholders with **real-time, interactive insights** that drive:

- **Smarter decision-making through in-depth data analysis**
- **Stronger customer relationships by understanding behaviours and preferences**
- **Informed strategic planning with data-driven foresight**
- **Proactive risk management to identify and mitigate challenges**

With this **Tableau-powered Sales Performance Dashboard**, the Superstore business can move beyond static reports and embrace **real-time analytics, visual storytelling, and automated workflows, ultimately turning data into a powerful competitive advantage**.

### **Why This Project Matters**
Understanding **sales performance, profitability, and customer behaviour** is essential for businesses that want to stay ahead of the competition. This project focuses on building an **intuitive and automated Sales Performance Dashboard** that enables:

**1.  Performance Tracking** – Gain precise insights into year-over-year sales and profit trends.

**2.  Customer Insights** – Uncover key customer behaviours, preferences, and segments to drive engagement.

**3.  Projection Insights** – Forecast performance for the next three years, offering a clear outlook for planning.

**4.  Data-Driven Strategies** – Equip management and marketing teams with **actionable insights** to optimise sales, improve customer satisfaction, and maximise profitability.

By leveraging interactive dashboards, stakeholders, including sales managers, executives, and marketing teams, can analyse critical metrics, identify trends, and make faster, smarter decisions that drive business growth.

### **Dashboard File**
**🔗 Access the final dashboard here**: [Dashboard](https://public.tableau.com/app/profile/olumide.balogun1/viz/SmithRobbinsSuperstore-SalesPerformanceDashboards/SalesDashbord?publish=yes)

### **Tableau Skills Used**
The following Tableau skills were utilised for analysis:

- **🧮 Calculated Fields** 

- **🚫 Bans** 

- **📉 Charts** 

- **📊 Table** 

- **❎ Data Validation** 

### **Dataset Overview**
The dataset used for this project is a **fictional yet realistic sales performance dataset covering 2020 to 2023**, providing a **comprehensive** view of:

- **Products** 

- **Customers**  

- **Locations**  

- **Orders**

**🔗 Access the dataset here**: [Raw Data](https://github.com/olumidebalogun1/Superstore-Sales-Performance-Interactive-Dashboard/tree/main/1.%20Dataset)

## **📊 Sales Performance Dashboards | Key Requirements**
### **📈 Sales Dashboard**

**🎯 Purpose:**

The **Sales Dashboard** provides a **comprehensive overview** of key sales metrics and trends, enabling stakeholders to track year-over-year performance and uncover actionable insights.

**🔑 Key Requirements:**

**1. KPI Overview**
-	Display a **summary of current and previous years' total sales, profit, and quantity**.

**2. Sales Trends**
-	Present the data for each KPI on a **monthly** basis for both the **current year and the previous year**.
-	Highlight months with **the highest and lowest sales** for easy recognition.

**3. Product Subcategory Comparison**
-	Compare sales performance by **product subcategory** for the current and previous years.
-	Include a **sales-to-profit comparison** for deeper insights.

**4. Weekly Sales & Profit Trends**
-	Display **weekly sales and profit data** for the current year.
-	Show **average weekly values** and highlight weeks that are **above or below average** to identify trends.

### **👥 Customer Dashboard**

**🎯 Purpose:**

The **Customer Dashboard** offers an in-depth view of **customer trends, behaviours, and engagement**, helping marketing teams and management refine strategies and **improve customer satisfaction**.

**🔑 Key Requirements:**

**1.  KPI Overview**
-	Display the total **number of customers**, total **sales per customer**, and total **number of orders** for the current and previous years.

**2.  Customer Trends**
-	Present the data for each KPI on a **monthly basis** for both the **current year and the previous year**.
-	Identify months with **the highest and lowest customer activity**.

**3.  Customer Segmentation**
-	Represent the distribution of **customers** based on the **number of orders** they have placed to provide insights into **customer behavior, loyalty and engagement**.

**4.  Top 10 Customers by Profit**
-	Rank the **top 10 customers** generating the **highest profit**.
-	Display additional insights such as **number of orders, current sales, current profits, and last order date**.

### **📅 Seasonality & Forecast Dashboard**

**🎯 Purpose:**

The **Seasonality & Forecast Dashboard** offers an in-depth view of **seasonal sales, profit trends, and demand fluctuations**, while providing **3-year sales and profit forecasts** to support strategic planning. The **Business Impact Insights** will help the teams anticipate **market shifts** and adjust **inventory, marketing, and operations strategies**.

🔑 Key Requirements:

**1. KPI Overview**
-	Display a **summary of current and previous years' total sales, profit, and quantity**.

**2. Seasonality Analysis**
-	Identifies **seasonal trends** impacting sales, profit, and quantity performance by using **months moving average**

**3. Future Forecasting** 
-	Use **historical data to project future sales, profit, and demand for the next three (3) years**.

## **🎨 Design & Interactivity Features**

### **Dashboard Dynamics**

**1.  Historical Data Analysis** – Users can select any desired year to analyse past performance.

**2.  Seamless Navigation** – Easy switching between dashboards for an **intuitive user experience**.

**3.  Interactive Visuals** – Interactive charts and graphs, and clickable filter for **real-time and in-depth data exploration**.  

### **Data Filters**

**1.  Product-Based Filters** – Filter data by **product category & subcategory**.

**2.  Location-Based Filters** – Segment data by **region, state, and city**.


# **📊 Sales Performance Interactive Dashboard**

## **Data Source Build**

**1.  Data Extraction**: Extract into the Tableau Public.
![1  Data Extraction   Conection](https://github.com/user-attachments/assets/9e13db9a-2aab-4038-81d8-ed56534573ba)

**2.  Data Integration**: Connected the **Dimension tables** to the **Fact table**.
![2   Data Modeling - Data Connection](https://github.com/user-attachments/assets/56eca0f6-4583-4cd2-95b9-289c5194893d)

**3.  Field Renaming**: Changing Region from string (text) to country/region.
![3  Renaming Fields   Tables](https://github.com/user-attachments/assets/4b45a0a2-34cd-48dc-b4f1-fffa5170e944)


## **📈 Sales Dashboard**

![1 0 Sales Dashboard](https://github.com/user-attachments/assets/5bd07cf0-385e-4ea2-b508-2dba775c83d2)

### **1.  KPI Overview**

To display the total **number of customers**, total **sales per customer**, and total **number of orders** for the current and previous years, I need to create Bans. To achieve these, first I need to create parameter and (new) calculated fields:

### **Order Date Parameter & Calculated Field**
![1 0  Selected Year Parameter](https://github.com/user-attachments/assets/cf211090-5f38-43fc-a22d-be47510ac7b5)

![1 1  Calculated Field - Selected Year](https://github.com/user-attachments/assets/92a593b6-0c8c-4597-9b18-0fd643252a17)


### **Total Sales** - Calculated Fields 
![2 0  Calculated Field - Current Year Sales(CY Sales)](https://github.com/user-attachments/assets/11cf11fa-eb15-4709-aa56-0664a34c3f24)

![2 1 Calculated Field - Previous Year Sales (PY Sales)](https://github.com/user-attachments/assets/fec08f11-e987-41ad-b79d-81be5d54f9cc)

![2 2 Calculated Field - % Diff Sales](https://github.com/user-attachments/assets/2bb5818a-fc0e-4e49-819f-e371c2c873dc)


### **Total Profit** - Calculated Fields
![3 0 Calculated Field - Current Year Profit (CY Profit)](https://github.com/user-attachments/assets/4f327f01-325a-4b2f-aca7-1f71a26f2526)

![3 1 Calculated Field - Previous Year Profit (PY Profit)](https://github.com/user-attachments/assets/8db91ac0-803e-4bd3-a1f6-da4cd3380361)

![3 2 Calculated Field - % Diff Profit](https://github.com/user-attachments/assets/32cc8c55-4271-414d-97a1-9e63fa5fe111)


### **Total Quantity** - Calculated Fields
![4 0 Calculated Field - Current Year Quantity(CY Quantity)](https://github.com/user-attachments/assets/2e1e139e-cc21-470c-bce5-49b58c6f6641)

![4 2 Calculated Field - Previous Year Quantity (PY Quantity)](https://github.com/user-attachments/assets/b427a8d7-7139-403b-b9bd-7a59524991e4)

![4 1 Calculated Field - % Diff Quantity](https://github.com/user-attachments/assets/a46271fc-e666-4d4f-a1db-d901314815f6)


### **2. Sales Trends**
To track **monthly sales performance** for both the current and previous year, highlight months with **the highest and lowest sales** for easy recognition, I need to build Sparkline charts. To achieve these, first I need to create **maximum and minimum values** calculated fields:

### **Total Sales Calculated Field**
![2 3 Calculated Field - MAX   MIN Sales](https://github.com/user-attachments/assets/4411192f-f19e-4ff4-81b4-7df2be1d1c62)

### **Total Sales Ban & Sparkline Chart**
![1 0 Total Sales - BANS   Sparkline](https://github.com/user-attachments/assets/2bb1c06e-1de7-478f-b6bf-1f2ccd1d6904)

### **Total Profit Calculated Field**
![3 3 Calculated Field - MAX   MIN Profit](https://github.com/user-attachments/assets/28c211c2-5632-4639-a69a-e41c3ef3e15a)

### **Total Profit Ban & Sparkline Chart**
![1 1 Total Profit - BANS   Sparkline](https://github.com/user-attachments/assets/3a922cae-d06a-4b7d-87cf-3c457e015d96)

### **Total Quantity Calculated Field**
![4 3 Calculated Field - MAX   MIN Quantity](https://github.com/user-attachments/assets/f07997a1-a494-4477-9c2a-2042dbd0232c)

### **Total Quantity Ban & Sparkline Chart**
![1 2 Total Quantity - BANS   Sparkline](https://github.com/user-attachments/assets/a12625dd-e632-489d-8ad9-ca36f39c5d50)


### **3. Product Subcategory Comparison**
To compare sales performance by **product subcategory** for the current and previous years and include a **sales-to-profit comparison** for deeper insights, I need to build Bar-in-Bar. To achieve this, first I need to create a new calculated field:

### **Calculated Field**
![5 0 Calculated Field - KPI CY Less PY](https://github.com/user-attachments/assets/c63a463b-4df8-48ba-bd1a-80734f3529da)

### **Profit by Sub-Category**
![1 3 CHART - Sales   Profit by Sub-Category](https://github.com/user-attachments/assets/66a0e54c-7592-434c-946b-8a2396b32389)


### **4. Weekly Sales & Profit Trends**
To present **weekly sales and profit data** for the current year, display the **average weekly values** and highlight weeks that are **above or below average** to draw attention to sales and profit performance, I need to build Line Charts. To achieve these, first I need to create new calculated fields:

### **Calculated Fields**
![5 1 Calculated Field - KPI Sales Avg](https://github.com/user-attachments/assets/493fe000-f329-4085-87af-ea3878ebaaea)

![5 2 Calculated Field - KPI Profit Avg](https://github.com/user-attachments/assets/ab896b34-7817-428d-b0a7-7bd25c38be7a)

### **Weekly Sales & Profit Trends**
![1 4  CHART - Weekly Sales   Profit Trends](https://github.com/user-attachments/assets/f5d0286e-1e3e-4c02-912f-560643a1ec49)

### **Dashboard**
![1 1 Sales Dashboard](https://github.com/user-attachments/assets/5e70a295-2330-43b1-a472-0e4845172284)


## **👥 Customer Dashboard**

![2 0 Customer Dashboard](https://github.com/user-attachments/assets/dced7c0d-04f4-4907-b6c0-0c2a90f027d3)

### **1.  KPI Overview**
To display the total **number of customers**, total **sales per customer**, and total **number of orders** for the current and previous years, I need to create Bans. To achieve these, first I need to create (new) calculated fields:

### **Total Customers** - Calculated Fields 
![6 0 Calculated Field - CY Customers](https://github.com/user-attachments/assets/604a2a9d-89d7-423d-8dc4-537ad6ddc4ea)

![6 1 Calculated Field - PY Customers](https://github.com/user-attachments/assets/35967946-c62c-4aac-b786-5b4e2ae8d111)

![6 2 Calculated Field - % Diff Customers](https://github.com/user-attachments/assets/e4f48a46-bf4a-47fa-ab71-78e40f30cb50)

### **Total Sales per Customer** - Calculated Fields
![7 0 Calculated Field - CY Sales per Customer](https://github.com/user-attachments/assets/8e98821b-7396-4edf-abb0-639b66cac437)

![7 1 Calculated Field - PY Sales per Customer](https://github.com/user-attachments/assets/839aa17e-e65d-4673-b988-791480df5db6)

![7 2 Calculated Field - % Diff Sales per Customer](https://github.com/user-attachments/assets/84f4d3a3-944b-4623-82b8-d3892d2f2653)

### **Total Orders** - Calculated Fields
![8 0 Calculated Field - CY No Orders](https://github.com/user-attachments/assets/8498b8a8-7163-4b75-9eac-95001370d362)

![8 1 Calculated Field - PY No Orders](https://github.com/user-attachments/assets/9cdec683-da14-41a1-8d4b-21fac596239e)

![8 2 Calculated Field - % Diff No Orders](https://github.com/user-attachments/assets/ba29529f-9350-4f91-9d08-c7e5c6d14f05)

### **2.  Customer Trends**
To track **monthly trends** for customer-related KPIs and Identify months with **the highest and lowest customer activity**, I need to build Sparkline charts. To achieve these, first I need to create **maximum and minimum values** calculated fields:

### **Customers Calculated Field**
![6 3 Calculated Field - MIN   MAX Customers](https://github.com/user-attachments/assets/108e22ad-ec21-457d-958d-96353def3736)

### **Total Customers Ban & Sparkline Chart**
![2 0 Total Customers - BANS   Sparkline](https://github.com/user-attachments/assets/1108d2d9-f9c1-46df-85fd-bf2d3e56ea5a)

### **Total Sales per Customer Calculated Field**
![7 3 Calculated Field - MIN   MAX Sales per Customer](https://github.com/user-attachments/assets/0b3363fd-a2de-41d9-8ab8-c9b75f69bafb)

### **Total Sales per Customer Ban & Sparkline Chart**
![2 1 Total Sales per Customer - BANS   Sparkline](https://github.com/user-attachments/assets/9e42917f-dcb8-4738-9df2-a2ebb35a86a1)

### **Total Orders Calculated Field**
![8 3 Calculated Field - MIN   MAX No Orders](https://github.com/user-attachments/assets/296250f4-fb00-4875-a4a1-a8d427c16091)

### **Total Orders Ban & Sparkline Chart**
![2 2 Total Orders  - BANS   Sparkline](https://github.com/user-attachments/assets/f8e973bb-f330-4048-ba73-a0b570630960)

### **3.  Customer Segmentation**
To analyse **customer distribution** based on the number of orders placed and gain insights into **customer behaviour, loyalty, and engagement levels**, I need to build a Bar Chart. To achieve this, first I need to create the **No. of Orders per Customer** calculated field:

### **Calculated Field**
![9  Calculated Field - No Orders per Customer](https://github.com/user-attachments/assets/209d36a3-a5e3-4e4d-90cf-58b80945c503)

### **Customer Distribution by the No of Orders**
![2 3 CHART - Customer Distribution by the No of Orders](https://github.com/user-attachments/assets/a82e9223-233b-443e-8836-e35ac4598cb5)


### **4.  Top 10 Customers by Profit**
To rank the **top 10 customers** generating the highest profit and display additional insights such as **number of orders, sales, profits, and last order date**. To achieve this, I need to build a Table.

### **Top 10 Customers by Profit**
![2 4 CHART - Top 1o Customers by Profit](https://github.com/user-attachments/assets/bdb9ac1f-7292-41ae-854c-c0774751ee6c)

### **Dashboard**
![2 1 Customer Dashboard](https://github.com/user-attachments/assets/bb14f866-4762-4395-b23a-5117f487377f)


## **📅 Seasonality & Forecast Dashboard**

![3 0 Seasonality   Forecast](https://github.com/user-attachments/assets/5006346c-d7b7-4037-a6c6-a13d625abdf1)

### **1.  KPI Overview**
This is just a repeat of the Sales Dashboard KPI. 

### **2. Seasonality Analysis**
To identify **seasonal trends** impacting sales, profit, and quantity performance by using **months moving average**, I need to build a Line chart. To achieve these, first I need to create a parameter and calculated field:

### **Monthly Parameter & Calculated Field**
![10 0 Monthly Moving Average Parameter ](https://github.com/user-attachments/assets/0e312501-41ed-4be7-b9d6-467003344567)

![10 1 Calculated Field - Moving Average](https://github.com/user-attachments/assets/117a55df-5250-4d3d-826d-230a6061935a)

### **Seasonality Analysis & Moving Average** 
**- Note that the Monthly Moving Average is in grey colour**

![3 0 CHART - Monthly Moving Average](https://github.com/user-attachments/assets/d115ff99-4120-438d-9ae8-00dff7f89485)

### **3. Forecasting** 
To use **historical data to project future sales, profit, and demand for the next three (3) years**, I need to build Line charts. To achieve these, first I need to create a parameter and calculated field:

### **Selected Measure Parameter & Calculated Field**
![10 2 Selected Measure Parameter](https://github.com/user-attachments/assets/16948085-eaa8-4928-a5ca-dc4737269125)

![10 3 Calculated Field - Forecast](https://github.com/user-attachments/assets/b9dd5750-32e7-475d-b5d6-c9aa2876aa2d)

### **Projection**
![3 1 CHART - Forecasting](https://github.com/user-attachments/assets/313d7669-c6c7-4521-bafe-605dedeca50e)


### **Dashboard**
![3 1 Seasonality   Forecast Dashboard](https://github.com/user-attachments/assets/d1b627ca-70bb-49a1-bc3a-e6324788c7a5)


## **Conclusion**
This **Tableau-powered Sales Performance Dashboard** goes beyond visuals, it’s a **data-driven powerhouse** that transforms raw data into **strategic insights, actionable decisions, and measurable business impact**. By uncovering **key trends, challenges, and opportunities**, it enables the Superstore to **identify high-performing regions, top-selling products, and valuable customer segments** while pinpointing underperforming areas that need improvement. These insights empower the business to make **smarter, data-driven decisions, optimize operations, and implement targeted strategies that drive sustainable growth and long-term success** in a competitive market.


## **Closing Thought**
Data is the new oil, but insights are the fuel that powers business growth. As a Business/Data Analyst, I am passionate about transforming raw data into actionable strategies that create real impact. Let’s turn data into decisions and challenges into opportunities!

**Feel free to explore, share, and connect!** Together, we can harness the power of data to drive meaningful results.


## **Connect with Me**
- **📞 +234-8065060691**
- **📧 Email: krisbalo11@gmail.com**
- **🔗 LinkedIn**: [Connect with me on LinkedIn](https://www.linkedin.com/in/olumide-balogun1/)
- **🔗 Medium**: [Explore my Data Storytelling articles](https://medium.com/@Olumide-Balogun)

