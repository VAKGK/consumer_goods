# 🌟 Consumer Goods Ad-Hoc Insights

### **SQL Project Challenge | Atliq Hardwares**

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/powerpoint)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

## 📖 Overview

**Business doesn't always wait for a dashboard.** Sometimes, management needs immediate answers to specific questions.

This project focuses on the **Ad-Hoc Request** domain for **Atliq Hardwares** (a fictional consumer goods company). The goal was to run 10 specific SQL queries to extract critical business insights that are not readily available in standard reports. These insights were then visualized to help management make quick, data-informed decisions.

> *"Turning rapid-fire questions into actionable data answers."*

---

## 📋 The Challenge: 10 Ad-Hoc Requests

I addressed 10 distinct business questions posed by the management team:

1.  **🌏 Atliq Exclusive's Markets:** Identify specific markets where "Atliq Exclusive" operates.
2.  **📦 Unique Product Increase:** Calculate the percentage increase in unique products from 2020 to 2021.
3.  **🔢 Product Count By Segment:** Determine the number of unique products in each segment, sorted in descending order.
4.  **📈 Segment With Highest Increase:** Which product segment saw the highest jump in unique products between 2020 and 2021?
5.  **💰 Highest & Lowest Mfg Cost:** Identify the products with the highest and lowest manufacturing costs.
6.  **🇮🇳 Top 5 Indian Customers:** List the top 5 customers in the Indian market based on pre-invoice discount percentage.
7.  **💵 Atliq Exclusive's Gross Sales:** Monthly gross sales report for "Atliq Exclusive" customers.
8.  **📆 Total Sold Quantity by Quarter:** Calculate total sold quantity for 2020, broken down by quarters.
9.  **📢 Gross Sales By Channel:** Which channel contributed the most to gross sales in 2021?
10. **🏆 Top 3 Products by Division:** List the top 3 products in each division based on total sold quantity.

---

## 🛠️ Tools Used

* **🐬 MySQL:** The core engine used to write complex queries (CTEs, Window Functions, Joins) to solve the 10 requests.
* **📊 Power BI:** Used to visualize the SQL outputs for better interpretability.
* **📝 PowerPoint:** Used to present the final insights to stakeholders.

---

## 🧠 Knowledge & Skills Applied

* **🏭 Consumer Goods Domain:** Deepened understanding of ad-hoc reporting needs in a fast-paced retail environment.
* **🧮 Advanced DAX:** Applied functions like `NATURALINNERJOIN` to model data relationships effectively.
* **🎨 Visualization Techniques:**
    * Utilized **Scatter Charts** for correlation analysis.
    * Implemented **Dynamic Titles** and **Page Navigation** for a better user experience.
    * Created custom **Tooltips** to show granular data on hover.

---

## ⚙️ The Workflow

```mermaid
graph TD;
    A["❓ Management Request 
     (10 Ad-Hoc Questions)"] -->|SQL Scripting| B{"🐬 MySQL Database 
      Query Execution"};
    B -->|Data Extraction| C["📊 Power BI 
       Data Modeling & DAX"];
    C -->|Visualization| D["📈 Insights Dashboard 
       (Charts & Matrices)"];
    D -->|Presentation| E["💡 Final Report 
        PowerPoint"];

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
