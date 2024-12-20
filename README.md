# Pandas Challenge: E-commerce Data Analysis

This repository contains a Jupyter Notebook that demonstrates data analysis and transformation using Python's Pandas library. The analysis focuses on an **e-commerce dataset** from a fictional company, showcasing real-world business scenarios such as customer insights, revenue calculations, and profitability analysis.

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Analysis Breakdown](#analysis-breakdown)
  - [Part 1: Explore the Data](#part-1-explore-the-data)
  - [Part 2: Transform the Data](#part-2-transform-the-data)
  - [Part 3: Confirm Your Work](#part-3-confirm-your-work)
  - [Part 4: Summarize and Analyze](#part-4-summarize-and-analyze)
- [Results](#results)

---

## **Project Overview**

This project demonstrates the power of the Pandas library for data analysis and transformation. By working through an **e-commerce dataset**, the notebook guides users through:
- Exploring raw data to identify key insights.
- Transforming data for easier analysis and visualization.
- Verifying calculations to ensure accuracy.
- Summarizing and presenting results in a meaningful way.

---

## **Dataset**

The dataset, located at [`Resources/client_dataset.csv`](https://github.com/jesseparent/pandas-challenge-1/blob/main/Resources/client_dataset.csv), contains information about clients, product categories, quantities, pricing, and other relevant details for an e-commerce company.

---

## **Requirements**

To run the notebook, you need the following:
- **Python**: Version 3.10 or later
- **Jupyter Notebook** or **JupyterLab**
- Installed Python libraries:
  - `pandas`

---

## **Usage Instructions**

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/jesseparent/pandas-challenge-1.git
   cd pandas-challenge-1
   ```
2. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
3. Open the notebook file (`pandas_challenge.ipynb`).
4. Run the cells in order, or select **Run All** from the menu to execute the entire notebook.

---

## **Analysis Breakdown**

### **Part 1: Explore the Data**
- Import the dataset and examine its structure.
- Answer key exploratory questions:
  - What are the top item categories and subcategories by entries?
  - Who are the top 5 clients by entries, and how many total units did they order?

### **Part 2: Transform the Data**
- Add calculated columns:
  - Subtotal for each line (`unit_price * qty`).
  - Shipping price, based on weight.
  - Total price (including sales tax).
  - Line cost and line profit.
- Prepare the data for easier analysis.

### **Part 3: Confirm Your Work**
- Verify calculations against known totals for specific orders:
  - Order ID `2742071`: $152,811.89
  - Order ID `2173913`: $162,388.71
  - Order ID `6128929`: $923,441.25

### **Part 4: Summarize and Analyze**
- Calculate spending by the top 5 clients (by quantity).
- Create a summary DataFrame with:
  - Total units purchased.
  - Total shipping price.
  - Total revenue.
  - Total profit.
- Format monetary values into millions for presentation.
- Sort results by profitability and summarize findings.

---

## **Results**

The notebook provides a summary of the top-performing clients and product categories, with insights into profitability and spending patterns. Users can:
- See detailed transformations of raw data into actionable insights.
- Present data in a format suitable for business intelligence and decision-making.

---

Feel free to reach out with questions or suggestions about this project. Happy analyzing!

