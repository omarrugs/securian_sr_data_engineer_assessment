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
- Load the three CSV files into a data frame 
- Validate schema consistency and handle missing or malformed data.
  -  document your findings, and explain your results  

### 2. Data Cleaning
- Clean the data by doing the folloing, store any invalid records in a seperate data frame 
  - Normalize inconsistent formats (e.g., dates, phone numbers).
  - Handle missing values appropriately.
  -  Deduplicate records where necessary.
 

### 3. Data Transformation
- Merge all 3 datasets using `customer_id` and `policy_id` into a new data frame.
- Derive 3 new fields in the new data frame:
  - Time between policy start and first claim.
  - Total claim amount per customer.
  - Average claim amount per customer.


### 4. Data Analysis
- Generate summary metrics:
  - Total claim amount by policy type (last 12 months).
  - Average time to first claim by province.
  - Top 5 customers by total claim amount.

### 5. Bonus (Optional)
- Write the cleaned and transformed data from step 3 to a PostgreSQL or Redshift database.
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

- We will be booking a 30 min session to dicsuss your solution
- Be prepared to explain all steps and answer any questions we may have.

---

Good luck! We look forward to reviewing your solution.
README_DataEngineer_Challenge.md
Displaying README_DataEngineer_Challenge.md.
