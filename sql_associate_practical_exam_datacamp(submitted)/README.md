# DataCamp SQL Associate Certification - Practical Exam Submission 🎓

![Status](https://img.shields.io/badge/Status-Passed-success) ![Certification](https://img.shields.io/badge/Certification-DataCamp_SQL_Associate-orange) ![SQL](https://img.shields.io/badge/Language-PostgreSQL-blue)

## 📄 Overview
This repository contains the **original SQL script submitted** to pass the practical assessment for the **DataCamp SQL Associate Certification**.

The assessment required solving a real-world data engineering problem within a timed environment. The objective was to clean, validate, and analyze a dataset of hotel operations to answer specific business questions defined by the exam requirements.

**Date of Certification:** January 29, 2026

## 🗂️ Database Schema
The following diagram illustrates the structure and relationships between the tables in the hotel operations database utilized in this assessment.

![Database Schema Visual](images/hotel_operations.png)

## 🎯 The Challenge
The exam simulated a dirty dataset scenario. The solution addresses the following four mandatory tasks:

### Task 1: Data Cleaning & Imputation
* **Challenge:** The raw data contained intentional typos (e.g., 'B.'), inconsistent casing, and missing values.
* **Solution:** Applied `TRIM`, `UPPER`, and pattern matching (`LIKE`) to standardize categorical text. Used `COALESCE` for imputation and Regex to validate integer types.

### Task 2: Metrics Aggregation
* **Challenge:** Summarize service times by branch.
* **Solution:** Calculated `AVG` and `MAX` time metrics, grouped by service and branch ID.

### Task 3: Relational Modeling
* **Challenge:** Connect disjointed datasets to find specific service details.
* **Solution:** Performed `INNER JOIN` operations across the `request`, `branch`, and `service` tables to create a unified view for European (EMEA) and Latin American (LATAM) branches.

### Task 4: Performance Analysis
* **Challenge:** Identify underperforming operational units.
* **Solution:** Used the `HAVING` clause to filter aggregated groups, identifying branches with an average rating below the benchmark of 4.5.

## 📂 File Contents
* `notebook.ipynb`: Jupyter notebook with the exact SQL query code used to pass all automated test cases in the exam environment.
* `hotel_operations.png`: The database schema.
* `images/hotel_operations.png`: Visual representation of the database schema used in the project.
* `SQL_Associate_Certificate.pdf`: The official certification PDF issued by DataCamp upon passing the exam.

### ⚠️ Note on Data Access
**The raw datasets (CSV files) are not included in this repository.**
The assessment was conducted within DataCamp's secure cloud environment (IDE), which does not provide an option to export or download the raw source files for this specific certification. The schema image above serves as the sole reference for the data structure used during the exam.

---
*This repository serves as a record of the practical skills validated during the certification process.*
