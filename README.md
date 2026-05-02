# 🧹 Data Cleaning in Excel – End-to-End Project

##  Project Overview

This project focuses on cleaning and transforming raw data using **Microsoft Excel**.
The goal is to convert unstructured, inconsistent data into a clean, reliable dataset ready for analysis and visualization.

---

##  Objectives

* Handle missing values and inconsistencies
* Remove duplicate records
* Standardize data formats
* Create calculated columns
* Prepare data for analysis and reporting

---

##  Dataset Description

The data initially contained:

* Missing values
* Inconsistent naming (e.g., "Tea", "tea", "TEA")
* Duplicate entries
* Incorrect data types

---

## 🛠️ Data Cleaning Steps

The following operations were performed:

### 1. Removing Duplicates

* Used Excel’s **Remove Duplicates** feature to eliminate redundant rows

### 2. Handling Missing Values

* Filled or removed null values based on business logic

### 3. Standardizing Text

* Converted text fields to consistent format (lowercase/uppercase)
* Cleaned unwanted spaces using `TRIM()`

### 4. Data Type Conversion

* Ensured numeric columns (Quantity, Price) are correctly formatted

### 5. Feature Engineering

* Created new columns such as:

  * **Total Price = Quantity × Price per unit**
  * Conditional pricing based on item categories

### 6. Error Handling

* Identified and fixed invalid or inconsistent entries

---

##  Tools Used

* **Microsoft Excel**

  * Functions: `IF`, `TRIM`, `LOWER`, `UPPER`
  * Data Cleaning Tools
  * Basic transformations

---

##  Key Outcomes

* Clean and structured dataset
* Improved data consistency and accuracy
* Ready for further analysis in tools like **Power BI, SQL, or Python**

---

##  Use Cases

* Sales analysis
* Business reporting
* Dashboard creation
* Data visualization

---

##  Project Structure

```
📦 Data-Cleaning-Excel
 ┣ 📄 raw_data.xlsx
 ┣ 📄 cleaned_data.xlsx
 ┗ 📄 README.md
```

---

## 👨‍💻 About Me

I am a **Data Science student** with skills in:

* Python
* SQL
* Excel
* Power BI
* Data Cleaning & Visualization

I am actively seeking opportunities to apply my skills in real-world data projects.

---

##  Future Improvements

* Automate cleaning using Power Query
* Integrate with Power BI dashboards
* Apply advanced data validation techniques

---

## 📬 Contact

Feel free to connect for collaboration or opportunities.
