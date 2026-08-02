# Customer Support SLA & CSAT Analytics Dashboard

![Dashboard Preview](Visualization/dashboard_screenshot_1.png)

## 📌 Executive Summary
This project analyzes **customer support performance**, evaluating **24-hour SLA compliance rates**, **Resolution Times**, and **Customer Satisfaction (CSAT)** scores across products and ticket priorities.

The goal was to transform raw timestamp and survey data into an interactive, executive-ready Excel dashboard to identify support bottlenecks and actionable service improvements.
## 🛠️ Technical Implementation & Data Pipeline

### 1. Data Cleaning & Feature Engineering
* Handled missing and invalid timestamps using logical validation.
* Calculated exact resolution hours: `(Resolution_Time - Response_Time) * 24`.
* Categorized performance using clean `IFS` dynamic conditional logic.

### 2. Tools Used
* Microsoft Excel: Data Cleaning, Feature Engineering (IFS, OR, ISBLANK), Pivot Tables, Pivot Charts, Slicers, Dashboard UI Design.
