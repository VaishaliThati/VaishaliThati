<h1 align="center">Hi, I'm Vaishali Thati 👋</h1>
<h3 align="center">Data Analyst · SQL · Power BI · Python · Excel</h3>

<p align="center">
  <i>"Data doesn't speak for itself. Someone has to ask it the right questions."</i><br>
  That's the part I love. 🔍
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to_Work-2ea44f?style=for-the-badge" alt="Open to Work">
  <img src="https://img.shields.io/badge/Hyderabad_%C2%B7_Open_to_Relocate_%C2%B7_Remote-0A66C2?style=for-the-badge" alt="Location">
  <img src="https://img.shields.io/badge/B.Tech_Data_Science_2025-6f42c1?style=for-the-badge" alt="Education">
</p>

# 💫 About Me

I take messy data, clean it, question it, and turn it into answers a business can act on. My projects cover credit risk, food delivery operations, and retail and sales analytics.

### 👀 In 10 seconds
- 🎯 **Looking for:** Data Analyst, BI / Power BI Analyst and MIS / Reporting Analyst roles
- 🏦 **Credit risk:** Compared 4 models on 8,505 Lending Club loans, and diagnosed why two of them failed
- 🍔 **Operations:** Analyzed 21,321 Zomato orders and found that wrongly marked "ready" orders doubled rider wait time
- 📊 **Dashboards:** Power BI and Excel (Power Pivot, DAX) reporting on sales, retail and workforce data

### 🧠 How I work
- **I ask "so what?" after every chart.** A number only matters if it leads to a decision.
- **I report what didn't work.** My Random Forest and XGBoost models scored 0 recall on loan defaults, so I diagnosed why instead of hiding it.
- **I check data quality first.** Clean data comes before any dashboard.

### 💬 Ask me about
- How I approach a brand-new dataset
- Why accuracy can be a misleading metric on imbalanced data
- My SQL, Excel and Power BI dashboards

😄 **Fun fact:** Give me a dataset and I'll start asking questions before I even open the dashboard.

## 🌐 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaishali-thati-7830332a9/) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@thativaishali12) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:thativaishali12@gmail.com)

# 🚀 Featured Projects

### 🏦 [Loan Default Risk Prediction](https://github.com/VaishaliThati/loan_default_risk_prediction) | Python, Machine Learning
- Predicted loan default on 8,505 Lending Club applications (only 1.7% defaulters) using application-time data only, with no data leakage.
- Ran 5 hypothesis tests and compared Logistic Regression, Decision Tree, Random Forest and XGBoost; diagnosed why Random Forest and XGBoost scored 0 recall on imbalanced data.
- Selected Logistic Regression (64% recall, 0.69 ROC-AUC) as an underwriter pre-screening flag, and documented its limits: 4% precision and a 5-fold CV recall of 50.4% ± 11.5%.

### 🍔 [Food Delivery Operations Analysis](https://github.com/VaishaliThati/Food-Delivery-Operations-Analytics) | Python
- Analyzed 21,321 Zomato orders (Delhi NCR, Sep 2024 to Jan 2025): 99.1% delivery rate, ₹683 average order value, and 8.5% of orders over a 35-minute prep + rider-wait threshold.
- Found that orders incorrectly marked "ready" had double the rider wait (8.7 vs 4.4 min) and delay rate (15.3% vs 7.9%).
- Peak hours carried 58.6% of orders with a higher delay rate (9.1% vs 7.7%). Built with Pandas, NumPy, Matplotlib and Seaborn.

### 🛍️ [Indian Retail Performance Analysis](https://github.com/VaishaliThati/Indian-retail-performance-analysis-using-excel) | Excel, Power Pivot, DAX
- Built a star-schema data model (sales fact table plus date, item, outlet and customer tables) in Excel Power Pivot.
- Created KPIs with DAX: net sales, profit, profit margin %, quantity, invoices and average discount %.
- Designed a one-page interactive dashboard with slicers covering profit by product, outlet performance and discount vs profitability.

### 🚗 [Automobile Sales Dashboard](https://github.com/VaishaliThati/automobile-sales-analysis-powerbi) | Power BI, Power Query, DAX
- Built a 3-page Power BI dashboard (Sales, Product, Customer) on 2,747 order lines from 298 orders (public sample dataset).
- Cleaned data in Power Query and created DAX measures for sales, AOV, order counts and customer metrics.
- Found that Classic Cars drive 39% of 9.76M total sales, November alone accounts for 21%, and the USA contributes 34%.

### 🛒 [E-Commerce Retail Insights](https://github.com/VaishaliThati/ecommerce-retail-insights-sql) | SQL Server, Excel
- Designed a SQL Server schema and analyzed 17K+ transaction records from 5,000 customers (public sample dataset).
- Built cohort, RFM and customer lifetime value analyses on purchase behavior and retention.
- Found that the top 20% of customers account for 59% of total spend; used Excel for visual reporting.

### 👥 [HR Analytics Dashboard](https://github.com/VaishaliThati/HR-Analytics-Dashboard-PowerBI) | Power BI (Team Project)
- College team project (4 members) analyzing employee attendance and workforce presence patterns.
- My role: team leader, analyst and dashboard developer.
- Built interactive dashboards using Power BI, Power Query and DAX.
- Tracked Presence %, WFH % and Sick Leave %.

# 🔍 Lessons My Projects Taught Me

- **Accuracy can lie, and so can a single split.** My Random Forest and XGBoost models were 98% accurate on loan defaults yet caught 0% of defaulters, and my Logistic Regression's 64% recall dropped to 50.4% ± 11.5% under 5-fold cross-validation.
- **A process problem can matter more than volume.** In my food delivery data, orders wrongly marked "ready" had a 15.3% delay rate vs 7.9%, a bigger gap than peak vs off-peak hours (9.1% vs 7.7%).
- **A big number isn't automatically an insight.** In my e-commerce data, Electronics drove 48% of revenue from 12% of orders, but that mostly reflects higher prices, so I focused on customer-level patterns instead, like the top 20% of customers driving 59% of spend.

# 🧭 How I Approach a Dataset

1. **Start with the decision.** What would someone do differently because of this answer?
2. **Audit before analyzing.** Check row counts, nulls, duplicates, join keys and date logic.
3. **Clean what the audit finds.** Fix data types, handle nulls and duplicates, and document every decision I make.
4. **Define the metric.** Revenue per order or per customer? Rates or counts?
5. **Analyze.** Use SQL, Python, Excel or Power BI to answer the question, and look for patterns, trends and outliers along the way.
6. **Sanity-check the result.** Do totals still match after the joins? Does the number make business sense?
7. **End with a recommendation and its limits.** Say what the data can't support.

# 🧠 Core Competencies

- **Data Analysis:** Data Cleaning, Exploratory Data Analysis (EDA), Data Manipulation, KPI Development
- **Data Visualization:** Interactive Dashboards (Power BI, Excel), KPI Reporting
- **Business Analytics:** Trend Analysis, Customer Analysis (RFM, Cohort, CLV), Performance Monitoring
- **SQL & Databases:** Queries, Joins, Aggregations, CTEs, Window Functions, Data Extraction
- **Statistics & Modeling:** Hypothesis Testing, Feature Engineering, Classification (Logistic Regression, Random Forest, XGBoost)

# 💻 Tech Stack

### 📂 Data Analysis & Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

### 🗄️ Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

### 📊 Business Intelligence & Visualization
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logoColor=white)

# 🌱 Beyond the Data

- 🧭 **Who am I:** Introspective, curious, a lifelong learner, level-headed, empathetic and a friendly collaborator
- 💡 **What pulled me into data:** I came across data analysis in my first year of college and loved the idea of finding the story behind the numbers. My final-year team project, which I led, confirmed it. Later, through my personal projects, I found I enjoy the unglamorous parts like cleaning messy data and digging for patterns. That's where the real insight comes from.
- 🎯 **Outside of work I enjoy:**
  - 📚 **Reading:** I only recently started, after noticing I spent more time in a mall's bookstore than anywhere else. Now I look for books that make me think.
  - 🎬 **Films:** I like ones with a deeper meaning, and I tend to pick up on the emotions in them quickly.
  - 🎧 **Music:** My quiet escape and my way of resetting.
  - 🌱 **Learning something new:** I like learning things that help me grow professionally and personally. I keep building my domain knowledge, I'm working on my English communication, and I'm learning Korean as a beginner 🇰🇷.
  - 🧠 **Easter egg:** I'm an introspective person, so analysis really is in my blood. 😄
- 🗣️ **Languages:** English · తెలుగు · हिन्दी
