# class-project-using-sqlite
Building R-shiny App using SQL database
# 🛠 **Shiny SQL Activity: Importing & Querying Data in SQLite**

## **📌 Goal**
Students will **download the Online Retail dataset**, store it in a **SQLite database**, and write an **R script** to query the data using SQL. The goal is to practice **basic SQL operations** within R.

---

## **🚀 Step 1: Download & Import Data**

### **1️⃣ Download the Dataset**
1. Download the **Online Retail dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail).
2. Save it as `online_retail.csv`.

### **2️⃣ Import into SQLite**
Students can choose **one of two methods** to import the dataset:

🔹 **Using R:**  
- Use `DBI` and `RSQLite` to connect to an SQLite database.
- Read the CSV file and write it as a table inside SQLite.

🔹 **Using DB Browser for SQLite:**  
1. Open **DB Browser for SQLite**.
2. Click **File > New Database**, name it `retail_db.sqlite`.
3. Click **Import > Import CSV**, select `online_retail.csv`.
4. Name the table `transactions`.

✅ **Result:** The dataset is now stored in an SQLite database.

---

## **🚀 Step 2: Write an R Script for SQL Queries**

### **📌 Task**
Students will create an R script (`queries.R`) to **answer business-related questions** using SQL.

### **1️⃣ Setup the R Script**
- Load the required R packages.
- Connect to the SQLite database in the script.

### **2️⃣ Answer the Following Questions Using SQL**

#### **🔹 Query 1: Total Revenue**
📌 **How much total revenue was generated?**

#### **🔹 Query 2: Best-Selling Product**
📌 **Which product generated the highest revenue?**

#### **🔹 Query 3: Top 5 Countries by Sales**
📌 **Which countries had the highest total sales?**

#### **🔹 Query 4: Monthly Sales Trend**
📌 **What are the total sales per month?**

#### **🔹 Query 5: Customer with Most Transactions**
📌 **Which customer placed the most orders?**

🔍 **Students must write the SQL queries themselves!**

---

## **🚀 Step 3: Submission Instructions**

📌 **Students must submit:**
1. `retail_db.sqlite` – The SQLite database file with imported data.
2. `queries.R` – The R script with SQL queries and results.
3. **Bonus:** Write at least **one additional SQL query** answering another business-related question.

✅ **Goal:** Gain hands-on experience using **SQL in R** to analyze data for business insights.

---

🚀 **Have fun querying!**
