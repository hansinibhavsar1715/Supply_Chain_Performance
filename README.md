# Supply Chain Performance Analysis & Late Delivery Risk Prediction

## Overview
This project focuses on analyzing supply chain operations to identify delivery delays, profitability patterns, operational bottlenecks, and factors affecting late deliveries. The goal is to transform raw business data into actionable insights using data analysis, machine learning, and interactive Power BI dashboards.

The project combines Python, SQL, Machine Learning, and Power BI to build an end-to-end analytics solution for improving delivery performance, reducing losses, and supporting better business decisions.

## Objectives
* Analyze overall supply chain performance
* Identify major causes of late deliveries
* Detect operational bottlenecks across regions, shipping modes, and customer segments
* Measure profitability impact caused by delayed deliveries
* Track seasonal and hourly delay patterns
* Predict late delivery risk before shipment occurs
* Build an interactive dashboard for business decision-making

## Tech Stack
### Programming & Analysis
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Database
* SQL

### Visualization
* Power BI

### Development Environment
* Jupyter Notebook
* VS Code
  
## Dataset
### Dataset Used
**DataCo Supply Chain Dataset**

The dataset contains supply chain transaction details such as:
https://drive.google.com/file/d/18M9UyeGr1K8spFMFQDwZOqqtfHloG84X/view?usp=drive_link

* Order ID
* Order Region
* Customer Segment
* Shipping Mode
* Order Status
* Type
* Department Name
* Category Name
* Order Date
* Shipping Date
* Days for Shipment (Scheduled)
* Days for Shipping (Real)
* Sales
* Order Profit Per Order
* Late Delivery Risk

This dataset helps analyze logistics efficiency, customer delivery performance, and profitability.

## Key Metrics
### KPI Cards

* Total Orders
* Late Deliveries
* On-Time Delivery %
* Late Delivery %
* Total Profit
* Total Loss Due to Delays
* 90% Delay Days
* Peak Delay Month
* Peak Delay Weekday
* Peak Delay Hour
* Predictive Late Delivery Risk %
  
## Dashboard Highlights
### Page 1 – Executive Performance Dashboard

* Profitability Distribution
* Delay Distribution by Delay Days
* Profit Analysis by Delay Days
* Late Delivery Percentage
* Executive KPI Cards
  
### Page 2 – Bottleneck Detection Dashboard
* Delay % by Region
* Delay % by Customer Segment
* Delay % by Shipping Mode
* Top Drivers of Late Delivery
* Root Cause Analysis

### Page 3 – Time Trend + Predictive Intelligence
* Delay % Trend Over Month
* Delay % by Day of Week
* Delay % by Hour
* Late Delivery Risk Prediction
* Time-Based KPI Monitoring

## Key Insights
* Delivery delays significantly reduce profitability and increase operational losses
* Certain regions show consistently higher late delivery percentages
* Home Office customer segment faces the highest delay risk
* Standard Class shipping mode contributes heavily to delayed deliveries
* Specific months and peak working hours show strong delay spikes
* Delay trends reveal operational bottlenecks in logistics planning
* Predictive modeling helps identify high-risk orders before dispatch

## Conclusion
This project demonstrates how data analytics and machine learning can improve supply chain efficiency and business performance. By identifying late delivery drivers, monitoring operational bottlenecks, and predicting delivery risks early, organizations can reduce losses, improve customer satisfaction, and make smarter strategic decisions.
The Power BI dashboard provides a complete decision-support system for supply chain managers, making this project highly practical for real-world business applications.
