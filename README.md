# Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

## Project Overview
This project aims to analyze the relationship between payment type and fare amount in NYC Yellow Taxi data. The main goal is to provide actionable insights for taxi drivers to maximize revenue by understanding which payment methods generate higher fares.

---

## Problem Statement
In the fast-paced taxi industry, maximizing revenue is crucial for driver profitability and customer satisfaction. This study investigates whether payment type (Card vs Cash) impacts fare amounts and explores strategies to encourage higher revenue payment methods without negatively affecting customer experience.

---

## Objective
- Perform Exploratory Data Analysis (EDA) to understand trends and distributions.
- Analyze the impact of payment type on fare amounts.
- Conduct hypothesis testing (T-test) to determine if there is a statistically significant difference between card and cash fares.
- Provide insights to increase revenue for drivers.

---

## Dataset
- Source: NYC Yellow Taxi Trip Records 
-  [👉 Download Dataset from Google Drive](https://drive.google.com/file/d/1hilVGbkrRep-hb8U2QXgpw7MgKgEmVPz/view?usp=sharing)
- Key Columns Used:
  - `passenger_count` — Number of passengers
  - `trip_distance` — Distance of the trip
  - `fare_amount` — Fare paid
  - `payment_type` — Payment method (Card or Cash)
  - `duration` — Trip duration in minutes

> Note: Large dataset; only filtered and cleaned data is used for analysis.  

---

## Libraries / Tools Used
- **Python** — Main programming language
- **pandas** — Data loading, cleaning, manipulation
- **matplotlib / seaborn** — Data visualization (histograms, pie charts, stacked bar plots, boxplots)
- **scipy.stats** — Statistical testing (T-test)
- **statsmodels** — QQ plot for normality check
- **Jupyter Notebook** — For analysis and visualization

---

## Methodology
1. **Data Cleaning**
   - Removed unnecessary columns
   - Filtered out trips with negative fare, distance, or duration
   - Removed duplicates and missing values
2. **Data Transformation**
   - Converted payment type codes to meaningful labels (`Card` / `Cash`)
   - Calculated trip duration in minutes
3. **Exploratory Data Analysis**
   - Distribution of fare amount, trip distance, and passenger count by payment type
   - Visualized payment type preference with pie charts and stacked bar plots
   - Identified and removed outliers using IQR method
4. **Hypothesis Testing**
   - Null Hypothesis: No difference in average fare between card and cash payments
   - Alternative Hypothesis: There is a difference in average fare between card and cash payments
   - Performed T-test → p-value < 0.05 → Reject null hypothesis

---

## Key Findings
- Card payments have **higher average fare** than cash payments.
- Most trips have 1–2 passengers, and higher fares are generally associated with card payments.
- Encouraging customers to pay with **credit cards** can generate more revenue for taxi drivers.

---

## Conclusion
The analysis clearly shows that **payment type impacts fare amounts**, with card payments providing higher revenue. Taxi companies and drivers can leverage this insight to nudge passengers toward card payments, optimizing revenue without compromising customer experience.


