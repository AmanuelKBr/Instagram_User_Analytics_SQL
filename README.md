

# 📸 Instagram Clone – User Analytics using SQL

## 📌 Project Overview

This project performs **end-to-end user analytics** on an **Instagram-like relational database** using **SQL**.
The goal is to extract **actionable product and business insights** from user behavior data, similar to what a **Data Scientist or Product Analyst** would do at a social media company.

Using structured SQL queries, the project analyzes:

* User growth and engagement
* Posting and interaction behavior
* Platform health metrics
* Suspicious or abnormal user activity
* Content and hashtag performance

This project demonstrates strong **analytical thinking, SQL proficiency, and business intuition**, not just query writing.

---

## 🎯 Objectives

* Analyze user behavior and engagement patterns
* Support product and growth decision-making using SQL
* Identify power users, inactive users, and potential bots
* Translate raw relational data into meaningful KPIs
* Simulate real-world analytics tasks for a social media platform

---

## 🧰 Tech Stack

| Category      | Tools                                   |
| ------------- | --------------------------------------- |
| Language      | SQL                                     |
| Database      | MySQL / PostgreSQL (ANSI-compliant SQL) |
| Analysis Type | Descriptive & Diagnostic Analytics      |
| Dataset       | Instagram-like relational schema        |
| Environment   | SQL Script / RDBMS                      |

---

## 📂 Project Structure

```bash
├── instagram dataset.sql                     # Database schema & sample data
├── Instagram_User_Analytics.sql     # Analytical SQL queries
├── README.md                                 # Project documentation
```

---

## 🗂️ Database Schema Overview

The dataset simulates a **real Instagram backend**, consisting of multiple related tables.

### Core Tables

| Table      | Description                         |
| ---------- | ----------------------------------- |
| users      | User profile and registration data  |
| photos     | User-uploaded posts                 |
| likes      | User likes on photos                |
| comments   | User comments on posts              |
| follows    | Follower–following relationships    |
| tags       | Hashtags                            |
| photo_tags | Mapping between photos and hashtags |

This relational design enables **multi-table joins**, **window functions**, and **aggregation-based insights**.

---

## ⚙️ Analytical Questions Addressed

### 🔹 1. User Growth & Onboarding

* How many users have registered over time?
* Which users never posted after signup?
* Identify early adopters vs late joiners

### 🔹 2. Engagement Analysis

* Average number of posts per user
* Users with the highest engagement
* Distribution of likes across photos

### 🔹 3. Power Users & Influencers

* Users with the most followers
* Users with consistently high interaction
* Top content creators by engagement

### 🔹 4. Content & Hashtag Performance

* Most commonly used hashtags
* Hashtags driving the highest engagement
* Photo-to-hashtag effectiveness

### 🔹 5. Platform Health Checks

* Users who liked every photo (bot-like behavior)
* Inactive users
* Engagement imbalance detection

---

## 🧠 Data Science & Analytics Skills Demonstrated

* Advanced SQL (JOINs, GROUP BY, HAVING, subqueries)
* Analytical problem framing
* KPI design for social platforms
* Behavioral analytics
* Fraud / bot pattern identification
* Translating business questions into SQL logic

---

## 🧪 Example Metrics Generated

* DAU-like engagement proxies
* Average likes per post
* Follower-to-following ratios
* Engagement per hashtag
* User activity segmentation

---

## 🚀 How to Run the Project

### 1️⃣ Load the Dataset

```sql
SOURCE instagram dataset.sql;
```

### 2️⃣ Run the Analytics Queries

```sql
SOURCE Solution_Instagram_User_Analytics.sql;
```

> Compatible with **MySQL**, **PostgreSQL**, and most ANSI SQL databases (minor syntax adjustments may be needed).

---

## 📈 Key Insights (High-Level)

* A small percentage of users generate most engagement
* Many users register but never post
* Certain hashtags disproportionately drive interactions
* Abnormal engagement patterns may indicate bot activity
* Follower count alone does not guarantee engagement

---

## 🔮 Future Enhancements

* Add time-based analysis (cohort retention)
* Convert SQL outputs into dashboards (Power BI / Tableau)
* Build engagement scoring models
* Add sentiment analysis on comments
* Simulate A/B testing metrics

---

## 👤 Author

**Amanuel Birri**
Data & Analytics Engineer | Data Scientist
🔗 [LinkedIn](https://www.linkedin.com/in/amanuel-birri)
💻 [GitHub](https://github.com/AmanuelKBr)

---

## 📄 License

This project is for **educational and portfolio purposes only**.
The dataset is a simulated Instagram-style schema for analytics practice.

---


