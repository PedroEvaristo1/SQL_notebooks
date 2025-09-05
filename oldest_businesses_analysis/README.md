# Analysis of the World's Oldest Businesses

## 📖 Project Overview

![Staffelter Hof Winery](https://github.com/PedroEvaristo1/SQL_notebooks/blob/main/oldest_businesses_analysis/images/MKn_Staffelter_Hof.jpeg)

Staffelter Hof Winery is Germany's oldest business, established in 862 under the Carolingian dynasty. It has continued to serve customers through dramatic changes in Europe, such as the Holy Roman Empire, the Ottoman Empire, and both world wars. This raises the question: **What characteristics enable a business to stand the test of time?**

To help answer this question, this project analyzes a dataset from BusinessFinancing.co.uk, which researched the oldest company still in business in almost every country.

---

## 🎯 Goal

The primary goal is to analyze data from multiple CSV files to better understand the world's oldest businesses. This involves using SQL to join and manipulate the data to uncover insights into business longevity.

---

### 🛠️ Tech Stack

- **Language:** SQL (PostgreSQL)
- **Tools:** Jupyter Notebook, pgAdmin 4, GitHub
  
---

### 📂 pgAdin 4 Database Schema (ERD)

Here is the Entity-Relationship Diagram for the tables used in this analysis. It shows how the "businesses", "countries", and "categories" tables are linked.

![ERD for the Oldest Businesses Project](https://github.com/PedroEvaristo1/SQL_notebooks/blob/main/oldest_businesses_analysis/images/oldest_business_datacamp_ERD.png)

---

## 🔎 Key Questions & Insights

This analysis answered several key questions:

1.  **What is the oldest business on each continent?**
    * **Insight:** The oldest businesses are often tied to fundamental human needs (Construction) or essential government services (Postal Services, Mints).

2.  **How complete is the dataset?**
    * **Insight:** The data has significant gaps, especially in Oceania. This is an important limitation to consider.

3.  **Which business categories are the most resilient?**
    * **Insight:** Foundational industries like Food & Beverage, Agriculture, and Banking & Finance are among the most enduring business models globally.

---

## 🗂️ File Structure

- **/data**: Contains the raw CSV files for the analysis.
- **/images**: Contains the ERD and any other images used in the project.
- **notebook.ipynb**: The main Jupyter Notebook with the SQL queries and analysis.

---

### Acknowledgments

This project was completed as part of the DataCamp curriculum. The project idea, dataset, and guiding questions were provided by the DataCamp platform.

My personal contribution includes:
* Designing and creating the database schema and ERD.
* Writing all of the SQL queries for the analysis.
* Interpreting the results and generating key insights.
* Documenting the entire process in this repository.
