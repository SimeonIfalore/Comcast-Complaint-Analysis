# 📊 Comcast Customer Complaint Analysis

**Author:** Simeon Ifalore  
**Date:** October 2016 Dataset  
**Tools Used:** Python · Pandas · NumPy · Matplotlib · Seaborn · Data Visualization · Data Wrangling

---

## 🔍 Overview

This project presents a data-driven analysis of **Comcast's customer service complaints**, using real-world data to uncover pain points, trends, and service quality issues.

In light of Comcast's $2.3 million fine by authorities due to overwhelming consumer complaints, this project explores and visualizes key complaint patterns from their public complaint database. It aims to guide service improvement strategies with actionable insights.

---

## 📁 Dataset Description

The dataset contains customer complaints received via different channels and includes the following fields:

| Column              | Description                                      |
|---------------------|--------------------------------------------------|
| Ticket #            | Unique complaint identifier                     |
| Customer Complaint  | Description of the issue                        |
| Date                | Date the complaint was filed                    |
| Time                | Time the complaint was filed                    |
| Received Via        | Communication channel (Internet/Customer Care) |
| City, State, Zipcode| Location data of the customer                   |
| Status              | Complaint resolution status                     |
| Filing on Behalf    | Whether complaint was filed for someone else    |

---

## 📈 Key Tasks & Objectives

- ✅ Import and clean the dataset
- 📅 Generate trend charts of complaint volumes (daily/monthly)
- 🧾 Identify and count the most common complaint types
- 📊 Create a new binary status feature: `Open` vs `Closed`
- 🗺️ Visualize complaints by state using a stacked bar chart
- 🔎 Determine:
  - Which state has the highest number of complaints?
  - Which state has the highest percentage of unresolved complaints?
- ☎️ Compare resolution percentages between Internet and Customer Care calls

---

## 🧠 Insights & Outcomes

- Uncovered high-volume complaint states and their resolution performance
- Highlighted Internet vs Customer Care efficiency in complaint handling
- Identified complaint categories that frequently remain unresolved
- Delivered visuals that aid decision-making for customer service improvements

---

## 📌 Highlights

- 🧹 Data Cleaning & Feature Engineering (including categorical transformation)
- 📊 Exploratory Data Analysis using matplotlib and seaborn
- 🧮 Grouping, Aggregation, and Custom Metrics
- 📍 Geographic complaint breakdown by U.S. state

---

## 🚀 Getting Started

To run the notebook:

1. Clone the repository
2. Install the required packages:  
   `pip install pandas numpy matplotlib seaborn`
3. Run the Jupyter notebook:  
   `jupyter notebook Comcast\ Customer\ Complaint\ Analysis.ipynb`

---

## 💼 About the Author

Simeon Ifalore is a skilled Data Analyst with a strong focus on storytelling through data. With a passion for uncovering insights that drive strategic decisions, Simeon specializes in turning raw datasets into visual narratives.

[🔗 LinkedIn](https://www.linkedin.com/in/simeonifalore/) | [📫 Email](mailto:your_email@example.com)

---

## 📝 License

This project is released under the MIT License.

