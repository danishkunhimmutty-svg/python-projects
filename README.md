# Python Projects — Data Analysis Portfolio

Hi, I'm Danish Muhammed — a sales professional building data analytics skills in Python (Pandas, NumPy, Matplotlib, Seaborn) alongside Power BI and Excel. This repo collects hands-on projects where I practiced exploratory data analysis (EDA) on real-world-style datasets: cleaning data, answering business questions with Pandas, and pulling insights from raw numbers.

## Projects

### 📦 [E-Commerce Purchases Analysis](./E-COMMERCE-SALES-ANALYSIS)
Exploratory analysis of an e-commerce purchases dataset to understand customer buying behavior.
- Calculated average, maximum, and minimum purchase prices
- Segmented purchases by language, job title, and time of day (AM/PM)
- Filtered transactions by credit card provider and price threshold
- Identified customers with soon-to-expire credit cards
- Found the top email domains used by customers

**Tools:** Pandas, CSV data

### 💰 [Employee Salary Analysis](./EMPLOYEE-SALARY-ANALYSIS)
Analysis of San Francisco city employee salary data to surface pay trends and outliers.
- Cleaned missing values and inspected data types
- Found average base pay and maximum overtime pay
- Identified the highest- and lowest-paid employees by total pay + benefits
- Tracked average base pay by year
- Counted unique job titles and flagged "chief"-level roles
- Tested the correlation between job title length and total pay (a fun exploratory question)

**Tools:** Pandas, CSV data

### 🏦 [Failed Bank Analysis](./Failed-Bank-Analysis)
Analysis of the FDIC's official failed bank list, pulled directly from a live web source.
- Scraped and parsed the data with `pd.read_html()` from the FDIC website
- Cleaned column names and converted closing dates to datetime
- Calculated total bank failures and the earliest/latest closing dates
- Ranked states by number of failures
- Built a year-by-state pivot table of failures
- Identified top acquiring institutions
- Calculated a 3-year rolling average of failures per year to see the trend over time

**Tools:** Pandas, NumPy, live web data (FDIC)

## About Me
I work in sales and I'm building toward a data analyst / business analyst role, combining my existing client-facing experience with Python, Power BI, and Excel skills. Connect with me on [LinkedIn](https://www.linkedin.com/in/danish-muhammed-657854412/).

