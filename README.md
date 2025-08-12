# Task-5-Exploratory-Data-Analysis-EDA-

# Uber Ride Analytics 2024 – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on Uber ride booking data for the year 2024.  
The dataset contains **148,770+ records** covering ride details, booking statuses, vehicle types, customer behavior, revenue metrics, and ratings.

The goal is to:
- Identify patterns in ride completions, cancellations, and revenue.
- Understand demand distribution across vehicle types.
- Extract insights on customer and driver satisfaction.
- Highlight operational improvement areas.

---

## 📂 Dataset Description
Key columns include:
- **Booking Status** – Completed, Cancelled by Customer/Driver, No Driver Found, Incomplete.
- **Vehicle Type** – Auto, Go Mini, Go Sedan, Bike, Premier Sedan, eBike, Uber XL.
- **Booking Value & Ride Distance** – Fare and distance traveled.
- **Ratings** – Driver and Customer ratings (1–5 scale).
- **Cancellation & Incomplete Ride Reasons** – Reasons for ride failures.
- **Payment Method** – UPI, Cash, Cards, Uber Wallet, etc.

---

## 📊 EDA Steps
1. **Data Cleaning**
   - Missing value handling based on business logic (e.g., keeping `NaN` for not applicable cases).
   - Date and time parsing for temporal analysis.

2. **Statistical Exploration**
   - `.info()`, `.describe()`, `.value_counts()` to understand distributions.
   - Cancellation rate calculations.
   - Average fare analysis by vehicle type.

3. **Visual Analysis**
   - Booking status and vehicle type distributions.
   - Correlation heatmap for numerical features.
   - Distance vs. value scatterplot.
   - Ratings distribution histograms.
   - Pairplot for fare, distance, and ratings.

4. **Key Insights**
   - Most rides are completed, but driver cancellations are ~2.5× higher than customer cancellations.
   - Economy rides dominate demand.
   - Pricing not strongly correlated to distance due to surge/minimum fare rules.
   - Ratings are high overall but independent of fare/distance.

---

## 📈 Tools & Libraries
- **Python** – Data analysis and visualization.
- **Pandas**, **NumPy** – Data wrangling and stats.
- **Matplotlib**, **Seaborn** – Static charts.


---

## 📑 Project Deliverables
- **EDA Jupyter Notebook** – Data cleaning, analysis, and visuals.
- **PDF Report** – Visual observations + summary findings.
- **README File** – Project documentation.

---


