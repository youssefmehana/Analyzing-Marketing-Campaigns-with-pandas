# Analyzing-Marketing-Campaigns-with-pandas
# 📊 A/B Testing & Marketing Analytics Project

This project uses Python and data analysis techniques to explore marketing campaign performance, specifically focusing on **A/B testing** and **customer retention**.

## 📌 Project Description

This notebook analyzes marketing data to understand:

- Conversion rates across different days of the week.
- Retention behavior over time.
- The effectiveness of an email marketing campaign using A/B testing.
- Whether personalized messages perform better than control messages.

The dataset includes user-level data such as subscription date, marketing channel, and conversion status.

---


## 📂 Dataset

The dataset used in this project is named `marketing.csv`, and contains the following key fields:

- `user_id`: Unique identifier for users
- `marketing_channel`: Email, House Ads, etc.
- `variant`: A/B testing group (control or personalization)
- `converted`: Whether the user converted (True/False)
- `is_retained`: Whether the user was retained
- `date_subscribed`, `date_canceled`, `date_served`: Timestamps of user interaction

## 🧪 Key Methods

- **Data Cleaning**: Type conversion, filtering, and formatting datetime columns.
- **Exploratory Data Analysis (EDA)**: Histograms, line charts, and bar charts.
- **Statistical Testing**: Independent two-sample t-test using `scipy.stats.ttest_ind`.

---
