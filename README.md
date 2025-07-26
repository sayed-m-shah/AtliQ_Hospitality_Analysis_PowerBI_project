# AtliQ Hospitality Analysis - PowerBI - Project

As part of the codebasics september month resume challenge, I have worked on this analysis project.

Link to the [Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge)

Link to [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZDBlNDczODYtMTY5NS00NzNkLWExN2QtNDAzMmVjNDUyYWRmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

Link to [Presentation Video]()

## Problem statement

Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

### Task List

You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

- Create the metrics according to the metric list. 
- Create a dashboard according to the mock-up provided by stakeholders. 
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

## Provided Mock-up Dashboard
<p align="center">
    <img src="https://github.com/sayed-m-shah/AtliQ_Hospitality_Analysis_PowerBI_project/blob/main/Dataset/mock%20up%20dashboard_atliq%20grands.png" width="600">
</p>


## Data Model

<p align="center">
    <img src='https://github.com/sayed-m-shah/AtliQ_Hospitality_Analysis_PowerBI_project/blob/main/resources/data_model.png' height="400">
</p>


## Overall Analysis View

<p align="center">
    <img src='https://github.com/sayed-m-shah/AtliQ_Hospitality_Analysis_PowerBI_project/blob/main/resources/overall_view.png' width="600">
</p>

## Monthly Analysis View

<p align="center">
    <img src='https://github.com/sayed-m-shah/AtliQ_Hospitality_Analysis_PowerBI_project/blob/main/resources/monthly_view.png' width="600">
</p>


## 🐍 Python Contribution (EDA & Pre-Analysis)

Before building the Power BI dashboard, I performed **data cleaning and exploratory data analysis (EDA) in Python** to understand key patterns in the hospitality dataset.

### ✅ Data Cleaning & Preparation
- Loaded multiple datasets:
  - `dim_date`
  - `dim_hotels`
  - `dim_rooms`
  - `fact_bookings`
  - `fact_aggregated_bookings`
- Checked for duplicates, missing values, and data types.

### ✅ Exploratory Data Analysis (EDA)
- Analyzed **city-wise hotel distribution** to identify high-revenue regions.
- Examined **booking platform trends** to understand customer preferences.
- Studied **room & hotel category distributions** to determine occupancy and cancellation trends.

These Python insights helped design relevant KPIs and guided the **Power BI dashboard creation**.

# 🐍 Python Contribution (EDA & Pre-Analysis)

Before building the Power BI dashboard, I performed **data cleaning** and **exploratory data analysis (EDA)** in Python to understand key patterns in the hospitality dataset.

---

## ✅ Data Cleaning & Preparation
- Loaded multiple datasets:  
  - `dim_date`  
  - `dim_hotels`  
  - `dim_rooms`  
  - `fact_bookings`  
  - `fact_aggregated_bookings`  
- Checked for duplicates, handled **missing values** and **outliers**.  
- Verified and corrected **data types**.

---

## ✅ Exploratory Data Analysis (EDA)
- Analyzed **city-wise hotel distribution** to identify high-revenue regions.  
- Examined **booking platform trends** to understand customer preferences.  
- Studied **room & hotel category distributions** to determine occupancy and cancellation trends.  
- **Data Transformation** – Added `occupancy%` columns.  

---

## ✅ Insights Generation – Key Questions Answered
- Identifying **occupancy rate on weekdays vs weekends**  
- Analyzing **revenue generated per city**  
- Analyzing **monthly revenue trends**


## Learnt things from this Project 
- Learnt to build a new visual (Calendar visual) using matrix table, which can be utilized for different purpose of analyze. ([Article referred](https://www.linkedin.com/pulse/calendar-matrix-syed-ahmed-ali/?trackingId=VgyLpo%2BYxVRs8tD03PXcPQ%3D%3D))
- By referring different cancellation polices followed by different hotels, understood that most of the hotels charge zero fee, only if the booking is cancelled before three months of booking date. If the booking is cancelled after that, the charge range from 60 to 90% of the booking cost.
- Learnt, how to use bookmarks and selection for different purposes. (Page navigation and clear filter button in the dashboard was achieved using bookmarks and selection. website like page navigation [YouTube tutorial](https://www.youtube.com/watch?v=xCSYLrcLW00)   )
- Tried using color palette and stick with that colors throughout the dashboard ([Color palette link](https://colorhunt.co/palette/78b3cec9e6f0fbf8eff96e2a))

## Some Important insights from the Dashboard

- Mumbai generates the highest revenue (669 M) followed by Bangalore, Hyderabad and Delhi
- AtliQ Exotica performs better compared to all 7 type of properties with 320 Million revenue, rating 3.62, occupancy percentage 57 and cancellation rate as 24.4%.
- AtliQ Bay has the highest occupancy of 66%
- Week 24 recorded the highest revenue among all, which is 139.6 Million
- Delhi tops both in occupancy and rating followed by Hyderabad, Mumbai, Bangalore
- AtliQ lost around 298 Million in cancellation 
- Elite type rooms has the most booking and as well higher cancellation rate



