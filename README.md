# Achievement-4-Project-Brief-Instacart-Grocery-Basket-Analysis
Python Achievement from Career Foundry Bootcamp

---

# Instacart Grocery Basket Analysis 🛒

## Overview

This project represents the culmination of **Achievement 4** in my data analytics training. It centers around performing an in-depth exploratory data analysis (EDA) of a real-world dataset made publicly available by [Instacart](https://www.instacart.com/datasets/grocery-shopping-2017) (with added fabricated customer data for educational purposes). Using **Python** in a **Jupyter Notebook** environment with libraries such as `pandas`, `NumPy`, `matplotlib`, and `seaborn`, I analyzed customer behavior, purchase patterns, and product trends.

### Objective

Instacart is seeking to improve their **targeted marketing strategies**. As a data analyst, my task was to uncover sales patterns and provide actionable insights to inform segmentation and advertising efforts. This involved investigating:

- Busiest shopping times (by day and hour)
- Times of highest spending
- Product popularity across departments
- Patterns in pricing groups
- Behavioral differences among customer segments based on demographics like age, region, and family status

---

## Key Findings

- **Order Volume Peaks:** The highest number of orders occur on weekends, particularly between 10 AM–2 PM.
- **Spending Peaks:** Average order value tends to peak in the evenings (around 5–8 PM), suggesting optimal ad placement timing.
- **Product Popularity:** Produce and dairy consistently rank as the most purchased categories.
- **Customer Segmentation:** Clear patterns were identified in ordering habits across different **loyalty levels**, **family statuses**, and **income brackets**.
- **Loyalty Indicators:** High-frequency users show consistent repeat behavior, offering strong candidates for loyalty program incentives.

---

## Tools & Technologies

- **Python (Jupyter Notebooks)**
- **pandas, NumPy, matplotlib, seaborn**
- **Data cleaning**, **subsetting**, **aggregation**, **visualization**
- **Customer data integration** for segmentation
- **Pickle** files used for efficient data saving

---

## Visualizations

Several types of charts were used to communicate insights, including:

- 📊 Bar charts for order frequency by department
- 📈 Line charts for hourly ordering behavior
- 📉 Histograms for age/income distributions
- 🟣 Scatterplots for customer segmentation (age vs. spend)

---

## File Structure


📁 Achievement-4-Project-Brief-Instacart-Grocery-Basket-Analysis/
├── 01_Project Management/
│   ├── A4_Data_Immersion_Project_Brief.pdf
├── 03_Scripts/
│   ├── 04.02_Task-Importing libraries and Python data types.ipynb
│   ├── 04.03_IC Data import and descriptive analysis.ipynb
│   ├── 04.03_Task-IC Data import and descriptive analysis.ipynb
│   ├── 04.04_Data Wrangling and Subsetting.ipynb
│   ├── 04.04_Task-Data Wrangling and Subsetting.ipynb
│   ├── 04.05_Data Consistency Checks.ipynb
│   ├── 04.05_Task-Data Consistency Checks.ipynb
│   ├── 04.06_Combining & Exporting Data.ipynb
│   ├── 04.06_Task-Combining & Exporting Data.ipynb
│   ├── 04.07_Deriving New Variables.ipynb
│   ├── 04.07_Task-Deriving New Variables.ipynb
│   ├── 04.08_Grouping Data and Aggregating Variables.ipynb
│   ├── 04.08_Task-Grouping Data & Aggregating Variables.ipynb
│   ├── 04.09_Intro to Data Visualization with Python.ipynb
│   ├── 04.09_Task-Pt 1-Intro to Data Visualization with Python.ipynb
│   ├── 04.09_Task-Pt 2-Intro to Data Visualization with Python.ipynb
│   ├── 04.10_Task-Coding Etiquette & Excel Reporting.ipynb
│   ├── Scratch Sheet.ipynb
├── 04_Analysis/
│   ├── 04.01_Reports/
│   ├── 04.02_Test Files/
│   ├── 04.03_Visualizations/
│   │   ├── 04.09_bar_orders_dow.png
│   │   ├── 4.9_line_price_orders_day_of_week.png
│   │   ├── 4.9_Task_pt2_age_and_n_dependents.png
│   │   ├── 4.9_Task_pt2_bar_loyalty_flag.png
│   │   ├── 4.9_Task_pt2_expenditure_over_hours_of_day.png
│   │   ├── 4.9_Task_pt2_hist_order_hour_of_day.png
│   │   ├── 4.9_Task_pt2_scatterplot_age_spending_power.png
│   │   ├── Distribution of Product Price Ranges.png
│   │   ├── Heatmap profile min mean max for orders.png
│   │   ├── Heatmap profile orders by regions.png
│   │   ├── heatmap_profile_reg_dept.png
│   │   ├── high and low spender line.png
│   │   ├── Histogram_order_hour_of_day.png
│   │   ├── Line orders based on hours of day.png
│   │   ├── Line orders per day of week base on dept id.png
│   │   ├── Line orders per hour based on price.png
│   │   ├── Number of orders per loyalty flag.png
│   │   ├── Orders per customer profile.png
│   │   ├── profile_bar.png
│   │   ├── Stacked bar graph Spending behavior based on provile.png
├── 05_Sent to Client//
│   ├── Ryan_Wick_Data Analytics Immersion_Ach 04_Final Report.xlsx
├── README.md

---

## Data Sources & Ethics

- 📎 “The Instacart Online Grocery Shopping Dataset 2017”, accessed from Kaggle.
- 🧑‍💼 Additional fabricated customer data provided by CareerFoundry.
- 🔐 All data was handled with care for privacy and ethical use, focusing only on aggregated insights.

---

## Recommendations

- **Schedule Ads** during slower hours (early mornings, late nights)
- **Segment Campaigns** based on identified customer profiles
- **Leverage Loyalty** by providing personalized recommendations and exclusive offers
- **Expand Promotion** on lesser-purchased departments to improve sales balance

---

*This project was completed as part of the CareerFoundry Data Analytics Program – Achievement 4.*
