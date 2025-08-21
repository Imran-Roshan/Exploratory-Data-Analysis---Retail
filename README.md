
# Exploratory Data Analysis (EDA) – Retail

## 📌 Project Overview

This project was completed as part of **The Sparks Foundation – Data Science and Business Intelligence Internship (Task 3)**.
The objective was to perform **Exploratory Data Analysis (EDA)** on a retail dataset (Sample Superstore) to identify **weak areas, key patterns, and business opportunities** that can help increase profitability.

Dataset: [Sample Superstore](https://bit.ly/3i4rbWl)

---

## 📊 Problem Statement

As a business manager, the goal is to analyze sales and profit across different categories, states, and customer segments to answer:

* Which categories and sub-categories drive the most sales and profit?
* Which states and regions are profitable, and which are causing losses?
* What is the relationship between discounts, sales, and profit?
* Where can business strategies be improved to minimize losses and maximize growth?

---

## 🛠️ Tools & Libraries Used

* **Python** – Data analysis & visualization
* **Pandas** – Data manipulation & cleaning
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plots & heatmaps

---

## 📂 Data Information

* Rows: **9,994** → cleaned to **9,977** (after removing duplicates)
* Columns: **13** → reduced to **12** (Postal Code dropped as noise)

Key Features:

* **Ship Mode, Segment, Country, City, State, Region, Category, Sub-Category**
* **Sales, Quantity, Discount, Profit**

---

## 📈 Key Analysis & Insights

1. **Data Cleaning**

   * Removed 17 duplicate records
   * Converted *Postal Code* to categorical, then dropped (not useful for analysis)

2. **Correlation**

   * Weak correlation between *Discount* and *Profit* → discounts don’t necessarily improve profit
   * High sales do not always lead to high profit

3. **Customer Segmentation**

   * Maximum sales & profit from **Consumer segment**
   * **Home Office segment** contributed the least

4. **Regional Analysis**

   * **West region** generated maximum profit
   * **South region** contributed least profit

5. **State-Level Analysis**

   * **California & New York** → highest profit
   * **Texas, Pennsylvania, and Ohio** → losses

6. **Category & Sub-Category Analysis**

   * **Technology & Office Supplies** → profitable categories
   * **Furniture** → low profit margins
   * **Phones** → highest sales
   * **Chairs** → high sales but low profit
   * **Tables & Bookcases** → major losses

---

## 📊 Visualizations

* Correlation heatmap for numerical features
* Pairplots by Ship Mode, Segment, and Category
* Count plots of Category, Segment, and Ship Mode
* Pie charts of Region and Sub-Category distributions
* Bar charts of Sales vs Profit (State, Region, Category, Sub-Category)
* Scatter plots for Sales vs Profit & Discount vs Profit

---

## 🚀 Business Insights & Recommendations

* **Reduce discounts**: High discounts do not guarantee higher profit.
* **Focus on Furniture segment**: Especially **Tables & Bookcases** which cause huge losses.
* **Expand in profitable states**: California, New York.
* **Reevaluate operations in loss states**: Texas, Pennsylvania, Ohio.
* **Increase investment in Technology & Office Supplies**: Higher profit margins compared to Furniture.

---

## 📌 How to Run the Notebook

1. Clone this repository

   ```bash
   git clone https://github.com/<your-username>/EDA-Retail-TSF.git
   cd EDA-Retail-TSF
   ```
2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Download dataset from [here](https://bit.ly/3i4rbWl) and place it in the project folder.
4. Open the Jupyter Notebook and run:

   ```bash
   jupyter notebook EDA_Retail.ipynb
   ```

---

## 📜 Author

👨‍💻 **Imran Roshan**

* Data Science & Business Intelligence Intern @ *The Sparks Foundation*
* [LinkedIn](#) | [GitHub](#)

