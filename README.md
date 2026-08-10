# 📊 Customer Behavior Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green?style=for-the-badge)

---

## 📌 Project Overview

The **Customer Behavior Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI** to analyze customer purchasing behavior, sales performance, revenue generation, subscription status, demographics, payment methods, shipping preferences, and customer reviews.

The dashboard transforms raw customer transaction data into an interactive and visually intuitive report that helps users identify important patterns and generate actionable business insights.

This project was developed as a **portfolio project to demonstrate practical skills in Power BI, Power Query, DAX, data visualization, data analysis, and business intelligence**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall customer purchasing behavior.
- Understand sales and revenue performance across product categories.
- Compare customer behavior across different age groups.
- Analyze customer subscription status.
- Understand customer distribution by gender.
- Analyze different payment methods used by customers.
- Analyze shipping preferences.
- Identify high-performing product categories.
- Compare revenue and sales across demographic groups.
- Develop an interactive dashboard for business decision-making.
- Convert raw customer data into meaningful business insights.

---

## 📂 Dataset

The project uses a customer behavior dataset containing information about customers, purchases, product categories, subscription status, payment methods, shipping types, and customer reviews.

### Dataset Information

| Attribute | Description |
|---|---|
| Dataset Name | `shopping_trends` |
| Source | `Kaggle` |
| Records | `3900` |
| Columns | `19` |
| File Format | CSV / Excel |
| Data Domain | Customer & Sales Analytics |

### Main Dataset Fields

| Column | Description |
|---|---|
| `Customer ID` | Unique identifier for each customer |
| `Age` | Age of the customer |
| `Gender` | Gender of the customer |
| `Category` | Product category |
| `Purchase Amount` | Amount spent on the purchase |
| `Review Rating` | Customer review rating |
| `Subscription Status` | Indicates whether the customer is subscribed |
| `Payment Method` | Payment method used for the purchase |
| `Shipping Type` | Shipping method selected by the customer |

> **Note:** Update the dataset information and column list according to the actual dataset used in the project.

### Dataset Source

**Source:** `Kaggle`

**Dataset Link:** (https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

---

# 🛠️ Tools & Technologies

The following tools and technologies were used in this project:

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Data analysis and measure creation
- **Data Modeling** — Structuring data for analytical reporting
- **Microsoft Excel / CSV** — Source data
- **GitHub** — Project documentation and version control

---

# 🔄 Data Preparation

Before developing the dashboard, the raw dataset was prepared using **Power Query**.

The data preparation process included the following steps:

### 1. Data Import

The raw dataset was imported into Power BI using Power Query.

### 2. Data Inspection

The dataset was inspected to identify:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values
- Unnecessary columns
- Formatting issues

### 3. Data Cleaning

The following cleaning activities were performed:

- Removed unnecessary columns.
- Handled missing values where required.
- Checked for duplicate records.
- Standardized categorical values.
- Corrected data types.
- Validated numerical fields.

### 4. Data Transformation

Power Query was used to transform the raw dataset into an analysis-ready structure.

> **Note:** Add or remove the transformation steps above based on the actual work performed in Power Query.

---

# 📐 Data Modeling

The dataset was structured in Power BI to support interactive analysis.

The data model allows analysis across different dimensions, including:

- Customer demographics
- Product categories
- Subscription status
- Payment methods
- Shipping types
- Age groups

### Data Model Structure

```text
                    Customer Behavior Data
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
      Customer            Product             Metrics
      Attributes          Attributes
          │                   │                   │
          ├── Age             └── Category        ├── Purchase Amount
          ├── Gender                              └── Review Rating
          ├── Subscription Status
          ├── Payment Method
          └── Shipping Type
