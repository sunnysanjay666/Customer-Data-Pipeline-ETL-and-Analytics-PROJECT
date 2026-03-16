

---

## **Project Title:**

**Customer Data Pipeline: ETL and Analytics**

---

## **Objective:**

The goal of this project is to **create a simple data engineering pipeline** that can handle customer data, clean it, and produce meaningful insights for business decisions. This helps understand how raw data can be transformed into usable information.

---

## **Project Overview:**

The project follows a **basic ETL workflow**:

1. **Extract (E):**

   * Collect customer data from a source.
   * In this project, data is simulated in Python as a table with columns: `CustomerID`, `Name`, `Age`, `City`, and `Purchases`.

2. **Transform (T):**

   * **Clean the data:** Standardize names (capitalize), handle missing values (if any).
   * **Add new information:** Calculate `TotalPurchaseValue` for each customer assuming a fixed value per purchase.
   * **Analytics:** Calculate **average age** and **total revenue** from the dataset.

3. **Load (L):**

   * Save the cleaned and transformed data to a new CSV file.
   * This ensures the dataset is ready for further analysis, reporting, or dashboard visualization.

---

## **Tools and Technology Used:**

* **Python:** For data processing
* **Pandas library:** To handle dataframes and transformations
* **CSV files:** To store raw and cleaned data
* **Google Colab:** Optional platform to run the project online

---

## **Key Features of the Project:**

* Demonstrates **ETL pipeline** in a simple way
* Handles **data cleaning** and **transformation**
* Generates **basic analytics** (average age, total revenue)
* Produces a **reusable cleaned dataset** for future analysis
* Can be scaled to larger datasets or real-world customer data

---

## **Why This Project is Useful:**

* Businesses often have **raw customer data** that needs cleaning and structuring.
* Helps to **calculate important metrics** like revenue, average age, or purchasing patterns.
* Demonstrates the **core skills of a data engineer**: handling, cleaning, and preparing data for analytics.

---

## **Output Example:**

| CustomerID | Name    | Age | City      | Purchases | TotalPurchaseValue |
| ---------- | ------- | --- | --------- | --------- | ------------------ |
| 1          | Alice   | 25  | Mumbai    | 5         | 500                |
| 2          | Bob     | 30  | Delhi     | 2         | 200                |
| 3          | Charlie | 22  | Bangalore | 7         | 700                |
| 4          | David   | 35  | Chennai   | 3         | 300                |
| 5          | Eve     | 28  | Mumbai    | 4         | 400                |

**Insights:**

* **Average Age:** 28 years
* **Total Revenue:** 2100 units

---


