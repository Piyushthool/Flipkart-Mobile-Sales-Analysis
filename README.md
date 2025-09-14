# 📱 Flipkarts – Mobile Dataset SQL Project

## 📌 Project Overview

This project simulates a **Flipkart mobiles database** for practicing SQL queries and data analysis.
It includes **1 CSV file (`mobiles.csv`)** containing real-world-like smartphone data with attributes such as brand, pricing, discounts, ratings, and reviews.

The project is designed to:

* Analyze mobile phones across different price ranges.
* Find top-performing brands based on ratings, discounts, and reviews.
* Explore customer trends in smartphone purchases.
* Provide practice with grouping, aggregation, and filtering in SQL.

---

## 📂 Dataset (CSV Table)

The repository contains the following dataset:

* **mobiles.csv** – Includes mobile phone details such as:

  * **Brand** – Mobile brand (e.g., Samsung, Apple, Xiaomi, etc.).
  * **MRP** – Maximum Retail Price of the mobile.
  * **MSP** – Market Selling Price (after discount).
  * **Discount** – Discount percentage offered.
  * **Ratings** – Average customer rating.
  * **No\_of\_Reviews** – Number of customer reviews.

---

## ⚙️ Features Demonstrated

* **Brand-wise Analysis**:

  * Mobile distribution across different price ranges.
  * Identifying brands with maximum discounts.
  * Finding brands with the highest average ratings.
  * Ranking brands by total customer reviews.

* **Product Insights**:

  * Filtering mobiles with **ratings above 4.5**.
  * Identifying phones with **high discounts (>40%)**.
  * Listing top mobiles by discount.

* **Aggregations & Rankings**:

  * Average ratings per brand.
  * Total reviews per brand.
  * Top brands based on popularity and performance.

---

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/flipkarts.git
   cd flipkarts
   ```

2. Import the **`mobiles.csv`** dataset into your database (MySQL, PostgreSQL, or SQLite).

3. Create a database named **`flipkarts`** and load the dataset as a table named **`mobiles`**.

4. Run SQL queries to explore and analyze the data.

---

## 🎯 Example Use Cases

* Identify **best brands under different price segments**.
* Find the **brand with the biggest discount gap (MRP - MSP)**.
* Rank brands based on **ratings and reviews**.
* Analyze **customer preferences** for mobiles.

---

## 🛠️ Tools & Technologies

* **SQL (MySQL/PostgreSQL/SQLite compatible)**
* **CSV file** for structured data storage
* **GitHub** for version control

---

## 📌 Future Enhancements

* Add more attributes (e.g., storage, RAM, camera specs, battery).
* Visualize results using Python (Matplotlib, Pandas) or BI tools.
* Implement dashboards for brand performance analysis.
* Expand dataset to include other Flipkart product categories.

---

## 👨‍💻 Author

Developed by **[Piyush Thool]** ✨
This project is for **educational purposes**, focusing on SQL practice with e-commerce datasets.

