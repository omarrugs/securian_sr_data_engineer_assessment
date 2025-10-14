
# 🧪 Senior Data Engineer Interview Challenge

Welcome to the hands-on technical challenge for the Senior Data Engineer position. This exercise is designed to evaluate your ability to build a robust data pipeline using Python and real-world data.

---

## 📁 Dataset Overview

You are provided with three CSV files:

- `customers.csv`: Contains customer information including personal details and location.
- `policies.csv`: Contains insurance policy data linked to customers.
- `claims.csv`: Contains insurance claims linked to policies.

---

## 🎯 Objective

Build a data pipeline that ingests, cleans, transforms, and analyzes the provided insurance datasets.

---

## 🛠️ Tasks

### 1. Data Ingestion
- Load the three CSV files using `pandas`.
- Validate schema consistency and handle missing or malformed data.

### 2. Data Cleaning
- Normalize inconsistent formats (e.g., dates, phone numbers).
- Handle missing values appropriately.
- Deduplicate records where necessary.

### 3. Data Transformation
- Join datasets using `customer_id` and `policy_id`.
- Derive new fields:
  - Time between policy start and first claim.
  - Total and average claim amount per customer.
  - Flag policies with suspicious values (e.g., negative premiums).

### 4. Data Analysis
- Generate summary metrics:
  - Total claim amount by policy type (last 12 months).
  - Average time to first claim by province.
  - Top 5 customers by total claim amount.

### 5. Bonus (Optional)
- Write the cleaned and transformed data to a PostgreSQL or Redshift database.
- Create visualizations using `Matplotlib` or `Plotly`.

---

## ✅ Evaluation Criteria

- Code readability and modularity.
- Handling of edge cases and data quality.
- Efficiency and scalability of the pipeline.
- Use of logging, configuration, and testing (bonus).
- Clarity of insights and analysis.

---

## 📦 Submission Instructions

- Submit your Python script(s) and any supporting files.
- Include a brief README explaining your approach and assumptions.
- If you use a database or visualization, include setup instructions.

---

Good luck! We look forward to reviewing your solution.
