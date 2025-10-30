# 🛍️ Customer Shopping Behavior Analysis

## 📘 Overview
Understanding customer behavior is essential for businesses to design better marketing strategies and improve customer engagement.  
This project explores **customer shopping behavior** through data analytics — identifying how **age, gender, income, and purchase history** influence spending patterns.  

It combines **Python (EDA)**, **SQL (data querying)**, and **Power BI (dashboard visualization)** to deliver actionable insights for business decision-making.

---

## 🎯 Project Objective
The goal of this project is to analyze customer demographics and purchasing patterns to:
- Identify customer segments based on age and spending.
- Understand the impact of income on purchasing frequency.
- Discover which customer groups contribute the most to revenue.
- Provide a visual and interactive representation of customer insights using Power BI.

---

## 📂 Project Structure

| File | Description |
|------|--------------|
| **`customer_shopping_behavior.csv`** | Original dataset containing demographic and shopping data. |
| **`customer_behavior_analysis.ipynb`** | Python notebook for data cleaning, preprocessing, feature creation (like `age_group`), and exploratory data analysis (EDA). |
| **`customer_behavior_queries.sql`** | SQL scripts for analytical queries and insight generation. |
| **`customer_behavior_dashboard.pbix`** | Power BI dashboard showing interactive visuals and KPIs. |
| **`Customer Shopping Behavior Analysis.pdf`** | Full project report covering findings and insights. |
| **`Customer-Shopping-Behavior-Analysis.pptx`** | Presentation deck summarizing key insights and visuals. |
| **`Business Problem Document.pdf`** | Initial problem definition and business understanding. |

---

## 🧠 Key Analysis & Insights

### 🔹 Demographic Insights
- The dataset reveals a balanced mix of **male and female shoppers**.
- The majority of high-value customers fall between **ages 25–45**.

### 🔹 Age Group Segmentation
A new column **`age_group`** was created to categorize customers as:
- **Young Adult** (≤ 25 years)  
- **Adult** (26–35 years)  
- **Middle-aged** (36–50 years)  
- **Senior** (> 50 years)

This segmentation helps understand which age groups are the most profitable.

### 🔹 Spending & Income Relationship
- Strong positive correlation between **annual income** and **purchase amount**.  
- Middle-aged and higher-income groups spend more frequently.

### 🔹 Gender-Based Behavior
- Female customers tend to spend slightly more per transaction.
- Male customers show higher purchase frequency.

---

## 📊 Power BI Dashboard Highlights
The **Power BI dashboard (`customer_behavior_dashboard.pbix`)** showcases:
- **Customer Overview:** Gender distribution, average spending, and income summary.  
- **Spending Score by Age Group:** Identifies top-performing segments.  
- **Purchase Trend:** Highlights frequent buyers and high-value customers.  
- **Income vs Spending Correlation:** Visual relationship between salary and spend.  
- **Demographic Breakdown:** Understands behavior across gender and age.

---

## 🧰 Tools & Technologies Used

| Category | Tools |
|-----------|--------|
| **Programming & Analysis** | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Database & Queries** | SQL (MySQL) |
| **Visualization & Reporting** | Power BI |
| **Data Source** | CSV File |
| **Documentation** | Markdown, PDF, PowerPoint |

---

## 🧩 Methodology
1. **Data Collection:**  
   Imported the dataset `customer_shopping_behavior.csv`.

2. **Data Cleaning & Preparation:**  
   - Handled missing values and inconsistent formats.  
   - Renamed columns for readability.  
   - Added new derived column `age_group` using quantile-based segmentation.

3. **Exploratory Data Analysis (EDA):**  
   - Analyzed spending patterns and correlations.  
   - Created visual insights using Python libraries.

4. **SQL Querying:**  
   - Performed customer segmentation and ranking queries.  
   - Calculated top spenders, frequent buyers, and category-wise trends.

5. **Power BI Dashboard:**  
   - Built interactive visuals and KPIs.  
   - Linked age groups, gender, and income insights dynamically.

---

## 📈 Key Metrics
| Metric | Description |
|--------|-------------|
| **Total Customers** | Total number of unique customers analyzed. |
| **Average Purchase Value** | Mean spend per transaction. |
| **Top Customer Segment** | Identified based on income and spending. |
| **Gender Ratio** | Male-to-female customer proportion. |
| **Revenue Contribution by Age Group** | Distribution of total revenue among `age_group` segments. |

---

## 🧩 Feature Engineering Example (Python)
In the Jupyter Notebook, the following Python code was used to create age-based segmentation:

```python
import pandas as pd

labels = ['Young Adult', 'Adult', 'Middle-aged', 'Senior']
df['age_group'] = pd.qcut(df['Age'], q=4, labels=labels)


🚀 How to Run This Project
Option 1 — Using Power BI


Download or clone the repository:
git clone https://github.com/jangamvivek/Customer-Shopping-Behavior.git



Open customer_behavior_dashboard.pbix in Power BI Desktop.


Interact with filters and slicers to explore insights.


Option 2 — Using Python


Open customer_behavior_analysis.ipynb in Jupyter Notebook.


Run the cells to view data cleaning, visualization, and analysis.


Option 3 — Using SQL


Open customer_behavior_queries.sql in your SQL environment.


Execute queries to generate analytical results.



💡 Business Impact
This project provides actionable insights for:


Targeted Marketing: Focused promotions for high-spending age groups.


Customer Retention: Identify loyal segments and reward them.


Revenue Optimization: Adjust pricing and discounts based on income distribution.


Data-Driven Decision Making: Improve strategic planning using dashboards.



📑 Results Summary


Segmented customers into 4 major age-based groups for targeted marketing.


Found Middle-aged customers as the highest spenders.


Identified strong income-to-spending correlation (r ≈ 0.74).


Developed a Power BI dashboard summarizing all insights visually.



📸 Project Preview

Includes visuals like:


Spending Score by Age Group


Gender-wise Average Purchase


Income vs Spending Scatter Plot


Top 10 High-Value Customers




👨‍💻 Author
Vivek Jangam
🎓 B.Tech in Data Science | 📊 Aspiring Data Analyst
💼 Experienced with Power BI, SQL, Python, and Business Analytics
🔗 [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/vivekjangam1/)
📧 [Email](mailto:jangamvivek@gmail.com)

⭐ Acknowledgment
Special thanks to open-source datasets and resources that supported this analysis.

🌟 Support
If you found this project useful, please ⭐ the repository on GitHub — it helps others discover it!


---

Would you like me to also generate a **short GitHub description + tags/keywords section** (for repo metadata like “Power BI, Data Analysis, Customer Segmentation”)?  
That improves visibility when people search on GitHub.
