# 📂 Self Projects

Welcome to my personal portfolio of data science and analytics projects.  
This repository acts as a **hub**, showcasing all my projects in one place.  

Each project has its own repository containing:
- **Raw Data** 
- **Code / Notebooks** 
- **Presentation** 
- **Project README** with details and insights  

---

## 📌 Projects

### 1. [Airbnb Market Analysis (France & Germany)](https://github.com/MukkiV/AirBnb-Market-Intelligence)
- **Goal:** Analyze Airbnb listing and host data to understand pricing behavior, demand patterns, and key factors influencing listing performance across France and Germany.  
- **Dataset:** Airbnb listings data for France and Germany, including pricing, host details, property features, reviews, and booking-related attributes.  
- **Steps Taken:**  
  - Performed **data cleaning and preprocessing** to handle missing values, inconsistent formats, and outliers.  
  - Conducted **exploratory data analysis (EDA)** to study pricing distribution, demand trends, and host behavior.  
  - Analyzed **seasonality and location-based patterns** to compare market behavior between France and Germany.  
  - Evaluated the impact of **property attributes, amenities, and accommodation capacity** on pricing and demand.  
  - Applied **statistical analysis and machine learning techniques** (regression, clustering) to identify key drivers and segment listings.  
  - Created **visual summaries and dashboards** to compare insights across both countries.  
- **Tools:** Python, Pandas, NumPy, SQL, Machine Learning, Tableau  
- **Highlights:**  
  - Demonstrates an end-to-end **data analysis workflow** from raw data to insights.  
  - Provides a **comparative market view** showing differences in pricing and demand between France and Germany.  
  - Combines **analysis, modeling, and visualization** to support data-driven decision-making.
 
### 2. [Computer Sales Analysis (Python & Statistics)](https://github.com/MukkiV/Computer-Sales-Analysis)
- **Goal:** Analyze computer sales data to understand pricing behavior, product features, and market patterns using statistical methods.  
- **Dataset:** Computer sales dataset containing product features, pricing details, and classification attributes (premium vs non-premium).  
- **Steps Taken:**  
  - Cleaned and prepared the dataset for analysis using Python.  
  - Performed **descriptive statistical analysis** to study price distribution and feature adoption.  
  - Applied **sampling techniques** to compare sample means with the population mean and validate data reliability.  
  - Used the **Central Limit Theorem (CLT)** to analyze how sample size impacts the stability of price estimates.  
  - Conducted **hypothesis testing (Z-test and T-test)** to evaluate pricing differences and validate market assumptions.  
  - Compared **premium and non-premium systems** to identify differences in average pricing and feature configuration.  
- **Tools:** Python, Pandas, NumPy, Statistics (Sampling, CLT, Hypothesis Testing)  
- **Highlights:**  
  - Confirms that the **average market price is stable around $2,200**.  
  - Shows that **premium systems are feature-driven rather than higher priced**.  
  - Demonstrates strong application of **statistical reasoning** for data-driven decision-making.  


### 3. [Python Gaming Hub](https://github.com/MukkiV/Python-Game-Hub)
- **Goal:** Create a terminal-based gaming hub in Python that allows users to play multiple mini-games from a single interface.  
- **Dataset:** No external dataset used — games are implemented using Python logic.  
- **Steps Taken:**
  - Designed a **modular structure** using Object-Oriented Programming (OOP).  
  - Implemented an **abstract base class (ABC)** to define the structure for all mini-games.  
  - Built multiple games (e.g. Rock-Paper-Scissors, Number Guessing, etc.).  
  - Developed a **main menu system** to let users select and play games interactively.  
  - Ensured **code reusability and scalability** so new games can be added easily.  
- **Tools:** Python, OOP principles, `abc` module, random module  
- **Highlights:**  
  - Showcases understanding of **polymorphism** and **inheritance** in Python.  
  - A single hub where players can switch between games without restarting the program.  
  - Structured as a learning + fun project to practice clean code and modular design.  

---

### 4. [Retail Project](https://github.com/MukkiV/Retail-Project)
- **Goal:** Analyze retail transaction, product, and demographic data to identify sales patterns and customer insights.  
- **Dataset:** Transaction data (`transactions.csv`), product details (`product.csv`), and customer demographics (`hh_demographic.csv`).  
- **Steps Taken:**
  - Imported and optimized large datasets by selecting relevant columns and reducing data types for efficiency.  
  - Performed **time-based analysis**:
    - Aggregated sales by month and compared trends across 2016 and 2017.  
    - Identified weekday vs weekend sales differences.  
  - Conducted **demographic analysis**:
    - Grouped sales by customer age and income categories.  
    - Analyzed average sales per household composition.  
  - Integrated product-level data:
    - Linked products with demographics to study department-wise sales preferences.  
    - Identified which product categories were most popular among younger demographics.  
  - Exported final pivot tables and insights to Excel for reporting.  
- **Tools:** Python, Pandas, Matplotlib, Seaborn, Excel (for exporting).  
- **Highlights:**  
  - Found that sales were **growing over time** but varied seasonally.  
  - High-income households contributed significantly more to total sales.  
  - Younger customers showed strong preferences in specific product categories. 

---

### 5. [Hotel Booking Analysis](https://github.com/MukkiV/Hotel-Booking-Analysis)
- **Goal:** Analyze hotel booking data to uncover customer booking patterns, cancellation behavior, and factors influencing reservations.  
- **Dataset:** Hotel booking dataset containing details such as hotel type, booking dates, lead time, number of guests, market segment, cancellations, and special requests.  
- **Steps Taken:**
  - Performed **data cleaning** (handled missing values, corrected data types, and removed duplicates).  
  - Analyzed **booking patterns**:
    - Distribution of bookings across city hotels and resort hotels.  
    - Seasonal trends in bookings and peak months.  
    - Lead time analysis to understand advance booking behavior.  
  - Conducted **cancellation analysis**:
    - Explored factors contributing to cancellations (lead time, deposit type, market segment).  
    - Compared cancellation rates between city hotels and resort hotels.  
  - Studied **guest demographics**:
    - Family vs solo bookings.  
    - Impact of repeated guests on hotel bookings.  
  - Created meaningful visualizations using Matplotlib and Seaborn.  
- **Tools:** Python, Pandas, Matplotlib, Seaborn  
- **Highlights:**  
  - Found that **city hotels had higher bookings but also higher cancellations**.  
  - Longer **lead times were strongly correlated with cancellations**.  
  - Peak booking periods aligned with summer and holiday seasons.  
  - Insights can help hotels improve **marketing strategies and reduce cancellations**.

---

### 6. [Modern Cars Analysis (SQL)](https://github.com/MukkiV/Model-Cars-Analysis)
- **Goal:** Perform end-to-end analysis of customer, office, product, employee, and order data for a modern car dealership using SQL.  
- **Dataset:** Relational database with tables such as `customers`, `orders`, `products`, `employees`, `offices`, and `orderdetails`.  
- **Steps Taken:**
  - **Customer Analysis:**
    - Identified top 10 customers by credit limit.  
    - Calculated average credit limit per country and number of customers per state.  
  - **Office Analysis:**
    - Counted employees per office and identified offices with low or no staff.  
    - Found the most profitable office and offices with highest credit limits.  
  - **Product Analysis:**
    - Counted products per product line and identified low-inventory products.  
    - Calculated total sales per product line and top-selling products.  
  - **Employee Analysis:**
    - Counted employees by job title and identified those without managers.  
    - Calculated sales per employee and identified the most profitable representatives.  
  - **Order Analysis:**
    - Measured average order amounts, order frequencies by month, and pending shipments.  
    - Identified high-value and profitable orders.  
- **Tools:** SQL (Joins, Aggregations, Stored Procedures, Triggers, Subqueries).  
- **Highlights:**  
  - Delivered **360° insights** into customer, product, office, and employee performance.  
  - Implemented **dynamic procedures and triggers** to handle real-time updates and validations.  
  - Identified top customers, most profitable offices, and key product lines.  
  - Simulated a real-world database management scenario for a modern car dealership.  

---

### 7. [Customer Churn Analysis](https://github.com/MukkiV/Bank-Churn-Analysis)
- **Goal:** Analyze customer churn in a bank dataset and identify key factors that influence whether customers leave or stay.  
- **Dataset:** Bank churn dataset (`DS1_C5_S1_BankChurn_Data_Concept.csv`) containing demographics, income, spending behavior, engagement, and card details.  
- **Steps Taken:**
  - **Churn Distribution:**
    - Measured churn rate and compared attrited vs existing customers.  
  - **Demographic Analysis:**
    - Explored churn trends by age, gender, marital status, and education.  
    - Found younger customers and certain marital groups churn more frequently.  
  - **Income & Spending Behavior:**
    - Compared churn rates across income categories.  
    - Studied credit limits, total transaction amounts, and number of transactions.  
  - **Customer Engagement:**
    - Analyzed churn vs tenure (`Months_on_book`), inactivity, and contact frequency.  
    - Investigated the effect of relationship count on churn.  
  - **Card Analysis:**
    - Distribution of card categories (Blue, Silver, Gold, Platinum).  
    - Churn rate by card type and premium vs standard cardholders.  
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn  
- **Highlights:**  
  - Overall churn rate identified and segmented by customer groups.  
  - **Low engagement** customers (inactive, fewer contacts, fewer relationships) were more likely to churn.  
  - **High utilization with low activity** was a strong churn indicator.  
  - Premium cardholders were less likely to churn compared to standard cardholders.

---

### 8. [Bird Strike Analysis](https://github.com/MukkiV/Bird-Strike-Analysis)
- **Goal:** Analyze global bird strike incidents (2000–2013) to identify safety risks, wildlife patterns, operational impact, and cost-related insights for aviation safety improvement.  
- **Dataset:** FAA Wildlife Strike Database (2000–2013) containing aircraft details, species information, flight phases, sky conditions, location data, and cost metrics.  
- **Steps Taken:**  
  - **Safety Analysis:**  
    - Identified high-risk flight phases such as Approach and Landing.  
    - Compared strike frequency by damage severity and flight impact.  
  - **Wildlife Species Analysis:**  
    - Examined top species involved and frequency of small-bird strikes.  
    - Analyzed species count, bird size, and number of birds struck.  
  - **Operational Impact:**  
    - Found top affected states and airports (California, Texas, Florida).  
    - Studied delays, inspections, and operational disruptions.  
  - **Cost Analysis:**  
    - Calculated annual and total damage costs.  
    - Compared airline-wise and aircraft-wise financial impacts.  
  - **Reporting & Environmental Analysis:**  
    - Analyzed sky and weather conditions during strikes.  
    - Observed that 47% of strikes occurred under clear/no-cloud conditions.  
- **Tools:** Tableau, Excel/CSV, Gamma App  
- **Highlights:**  
  - Over **68,000 strikes** analyzed across **345 species**.  
  - Approach and Landing phases show **highest strike vulnerability**.  
  - Clear-sky strikes highlight the need for radar-based detection systems.  
  - Major hotspots identified in high-traffic airports.  
  - Built **6 interactive dashboards** covering safety, wildlife, cost, and operations.
    
---
## 🔧 Tech Stack

### **Languages**
- **Python** – data analysis, statistics, machine learning, automation, and application logic  
- **SQL** – querying, aggregations, joins, subqueries, stored procedures, and data analysis  

---

### **Libraries & Frameworks**
- **Data Analysis & Statistics:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn (Regression, Classification, Clustering)  
- **Visualization:** Matplotlib, Seaborn  
- **Programming Concepts:** Object-Oriented Programming (OOP), `abc` module  

---

### **Data Visualization & BI**
- **Tableau** – interactive dashboards  
- **Power BI** – dashboarding and reporting  
- **PowerPoint** – business presentations and storytelling  

---

### **Cloud & Data Engineering**
- **Azure Data Factory** – ETL pipeline orchestration  
- **Azure Blob Storage** – cloud data storage  
- **Azure Monitor** – pipeline monitoring and logging  
- **PostgreSQL** – source and staging databases  

---

### **Tools & Platforms**
- **Jupyter Notebook** – analysis, experimentation, and reporting  
- **Git & GitHub** – version control and project portfolio  
- **Excel** – data export, summaries, and reporting  

---

### **Database Management**
- **Relational Databases:** PostgreSQL, MySQL  
- **SQL Concepts:**  
  - Joins & Subqueries  
  - Aggregations & Window Functions  
  - Stored Procedures & Triggers  
  - Schema Design & Data Validation  

---

## 📬 Contact
If you’d like to connect or discuss these projects:  
- 📧 Email: mukeshv2999@gmail.com 
- 💼 LinkedIn: www.linkedin.com/in/mukesh-v-a4797a339 
---
