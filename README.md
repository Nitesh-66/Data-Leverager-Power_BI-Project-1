# 📊 Power BI ETL Project 

## 📌 Project Overview

This project demonstrates a complete **ETL (Extract, Transform, Load)** workflow in Power BI using:

* HTML (Web) data
* Multiple Excel files (Sales data)
* Employee dataset

The focus is on **data cleaning, transformation, merging, and aggregation** using Power Query.

---

## 📂 Data Sources Used

### 🌐 1. Web (HTML Data)

* Loaded using **Get Data → Web**
* Extracted table from HTML page

### 📁 2. Sales Data (Excel Files)

* Files used:

  * Sales_Jan.xlsx
  * Sales_Feb.xlsx
  * Sales_Mar.xlsx
* Combined using **Folder → Combine & Transform**

### 👨‍💼 3. Employee Data

* Excel file containing:

  * EmployeeID
  * Region
  * Other employee attributes

---

## 🔧 Steps Performed

### 1️⃣ Load HTML Data

* Get Data → Web
* Select required table
* Transform data in Power Query

---

### 2️⃣ Load Sales Files

* Get Data → Folder
* Combine Jan, Feb, Mar files
* Append all data into one table

---

### 3️⃣ Load Employee Data

* Get Data → Excel
* Load employee dataset

---

### 4️⃣ Data Cleaning

* Remove blank rows
* Remove unwanted columns
* Use first row as headers
* Rename columns
* Change data types (Date, Decimal)
* Remove duplicates
* Filter null values

---

### 5️⃣ Create Sales Category Column

Created a conditional column:

| Condition     | Category |
| ------------- | -------- |
| Sales ≥ 10000 | High     |
| Sales ≥ 5000  | Medium   |
| Sales < 5000  | Low      |

---

### 6️⃣ Append Sales Data

* Combined:

  * Jan + Feb + Mar
* Created a unified dataset

---

### 7️⃣ Merge Data

* Merged Sales + Employee data
* Join based on:

  * Region / EmployeeID

---

### 8️⃣ Transformations

* Created calculated columns
* Cleaned text data
* Applied formatting and structuring

---

### 9️⃣ Aggregations (Group By)

#### 📊 Region Wise Analysis

* Total Sales (Sum)
* Average Order Value
* Transaction Count

---

## 📈 Key Outputs

* Combined Sales Dataset
* Sales Category Column (High / Medium / Low)
* Region-wise:

  * Total Sales
  * Average Sales
  * Order Count

---

## 🎯 Key Learnings

* Working with **multiple data sources**
* Using **Power Query for ETL**
* Data cleaning techniques
* Append & Merge operations
* Grouping and aggregation

---

## 🚀 Future Improvements

* Build dashboard visuals
* Add KPIs (Profit, Growth)
* Create interactive reports

---

## 👨‍💻 Author

**Nitesh Kumar**

---

⭐ This project is ideal for beginners to intermediate learners to understand real-world Power BI workflows.
