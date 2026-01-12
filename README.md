# 🛒 Superstore Sales Analysis & Business Forecasting

## 📌 Project Overview
In the highly competitive retail sector, understanding the correlation between **Sales**, **Profit**, and **Discount** is crucial for sustainability. This project analyzes a 4-year dataset of a US-based Superstore to identify high-performing categories, underperforming regions, and seasonal sales trends. The goal is to provide data-driven recommendations to minimize losses and maximize profitability.

## 📂 Project Files
* **`Superstore sales.ipynb`**: The Python notebook containing data cleaning, detailed EDA, correlation analysis, and time-series visualization.
* **`Superstore_Complete_Report.pdf`**: A professional business report summarizing key insights, visual trends, and strategic recommendations for stakeholders.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Analysis Techniques:** Correlation Heatmaps, Time-Series Resampling, Pareto Analysis

## 📊 Key Workflow & Analysis

### 1. Data Cleaning & Preprocessing
* Removed duplicate entries to ensure data integrity.
* Handled unnecessary columns (`Row ID`, `Country`) to streamline the dataset.
* Verified data types, specifically converting `Order Date` for time-series analysis.

### 2. Exploratory Data Analysis (EDA)
* **Category Performance:** Analyzed the "Technology," "Furniture," and "Office Supplies" categories. discovered that while Furniture generates high revenue, it often suffers from low profit margins due to excessive discounting.
* **Regional Analysis:** Mapped sales and profits across West, East, Central, and South regions to identify underperforming markets.
* **Customer Segmentation:** compared "Consumer," "Corporate," and "Home Office" segments to understand purchasing behavior.

### 3. Business Insights
* **Discount Impact:** A strong negative correlation was observed between Discount and Profit. Products with discounts >20% often resulted in net losses.
* **Seasonality:** Sales consistently spike in Q4 (November/December), indicating a need for inventory optimization during holiday seasons.
* **Shipping Modes:** "Standard Class" is the most preferred shipping mode, but "Same Day" shipping yields the highest profit margin per order.

## 💡 Strategic Recommendations
Based on the data, the following strategies are proposed:
1.  **Discount Strategy Revision:** Limit discounts on "Furniture" items to a maximum of 15% to prevent profit erosion.
2.  **Regional Focus:** The Central region shows the lowest profitability; a targeted marketing campaign or logistics review is required.
3.  **Inventory Planning:** Increase stock levels for "Technology" products in October to prepare for the end-of-year surge.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone :  https://github.com/amit95ranjan/Superstore-Sales-Analysis-Business-Forecasting
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook "Superstore sales.ipynb"
    ```

---
*Created by Amit Ranjan - Data Analyst*
