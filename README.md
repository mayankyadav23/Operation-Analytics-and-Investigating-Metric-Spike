# 📊 Operation Analytics and Investigating Metric Spike

This repository contains SQL-based solutions for analyzing operational data and investigating metric spikes. The project focuses on deriving insights for business-critical metrics, such as user engagement, growth, and throughput. The case studies below outline key tasks that simulate real-world data analyst responsibilities.

---

## ✨ **Project Overview**

Operation Analytics involves analyzing end-to-end operations to uncover areas of improvement and help businesses optimize workflows. This project dives deep into operational data to answer key questions, focusing on understanding daily trends, investigating metric spikes, and providing detailed reports for cross-functional teams.

As a **Data Analyst**, you will derive insights from various datasets and report key metrics to answer questions posed by different departments.

---

## 📂 **Case Study 1: Job Data**

### Data Table: `job_data`
- **job_id**: Unique identifier of jobs
- **actor_id**: Unique identifier of the actor
- **event**: Event type (decision/skip/transfer)
- **language**: Language of the content
- **time_spent**: Time spent reviewing the job (in seconds)
- **org**: Actor's organization
- **ds**: Date in `yyyy/mm/dd` format (text)

### 📝 **Tasks**
1. **Jobs Reviewed**: Calculate the number of jobs reviewed per hour per day for November 2020.
2. **Throughput**: Calculate the 7-day rolling average of throughput (events per second). Determine if you prefer daily or rolling metrics, and explain why.
3. **Percentage Share of Languages**: Calculate the percentage share of each language in the last 30 days.
4. **Duplicate Rows**: Identify duplicate rows in the `job_data` table and display them.

---

## 📂 **Case Study 2: Investigating Metric Spike**

### Data Tables:
- **`users`**: Contains user account details.
- **`events`**: Tracks user actions (login, messaging, search, etc.).
- **`email_events`**: Similar to the `events` table but focused on email interactions.

### 📝 **Tasks**
1. **Weekly User Engagement**: Calculate the weekly engagement rate to measure user activeness.
2. **User Growth**: Analyze the growth rate of users over time.
3. **Weekly Retention**: Calculate weekly retention for the sign-up cohort.
4. **Weekly Engagement per Device**: Measure weekly engagement broken down by device.
5. **Email Engagement Metrics**: Calculate engagement metrics related to email services.

---

## 🛠️ **Technologies & Tools**
- **SQL (Presto)**: For querying and analyzing data
- **Python**: For additional data analysis and automation
- **Excel**: For report generation and metric presentation

---

## 📧 **Contact**
Mayank Yadav - [LinkedIn](https://www.linkedin.com/in/mayankyadv)
