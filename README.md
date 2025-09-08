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

### 1. [Python Gaming Hub](https://github.com/MukkiV/Python-Game-Hub)
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

### 2. [Retail Project](https://github.com/MukkiV/Retail-Project)
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

### 3. [Hotel Booking Analysis](https://github.com/MukkiV/Hotel-Booking-Analysis)
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

### 4. [Modern Cars Analysis (SQL)](https://github.com/MukkiV/Model-Cars-Analysis)
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

### 5. [Customer Churn Analysis](https://github.com/MukkiV/Bank-Churn-Analysis)
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

## 🔧 Tech Stack

- **Languages:**  
  - Python (for data analysis, visualization, machine learning, and game development)  
  - SQL (for relational database queries, procedures, triggers, and analysis)  

- **Libraries & Frameworks:**  
  - **Data Analysis & ML:** Pandas, NumPy, Scikit-learn, XGBoost  
  - **Visualization:** Matplotlib, Seaborn  
  - **Programming Concepts:** OOP principles, `abc` module (for Gaming Hub)  

- **Tools & Platforms:**  
  - Jupyter Notebook (project development & reporting)  
  - PowerPoint (presentations)  
  - Git & GitHub (version control & portfolio management)  
  - Excel (exporting and reporting in Retail Project)  

- **Database Management:**  
  - SQL (Joins, Subqueries, Stored Procedures, Triggers, Aggregations)  
  - MySQL / SQL-based relational database schema for Modern Cars project
  
---

## 📬 Contact
If you’d like to connect or discuss these projects:  
- 📧 Email: mukeshv2999@gmail.com 
- 💼 LinkedIn: www.linkedin.com/in/mukesh-v-a4797a339 
---
