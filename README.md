# pandas-numpy-data-cleaning-project
End-to-end data analytics project covering data cleaning, feature engineering, EDA, and business insights using Python, Pandas, and NumPy.
# Customer Orders Analytics Project Using Pandas & NumPy

## Project Overview

This project demonstrates an end-to-end data analytics workflow using Python, Pandas, and NumPy. The dataset contained multiple real-world data quality issues including missing values, invalid records, inconsistent formatting, duplicate entries, and business rule violations.

The objective was to clean the data, engineer meaningful business features, perform exploratory data analysis (EDA), and generate business insights from the dataset.

---

## Project Workflow

Raw Dataset → Data Cleaning → Feature Engineering → EDA → Business Insights

---

## Dataset Information

Initial Dataset Size: 310 Records

Final Dataset Size: 268 Records

Total Features After Engineering: 25 Columns

---

## Data Cleaning Using Pandas

The following data quality issues were identified and resolved:

### Customer Information

* Removed extra spaces from customer names
* Standardized gender values
* Cleaned city and state names
* Validated email addresses
* Validated phone numbers

### Data Validation

* Handled missing values
* Corrected invalid age values
* Removed invalid quantity records
* Validated ratings
* Recalculated and validated revenue values

### Date Processing

* Converted Order Date and Delivery Date into datetime format
* Validated date consistency
* Checked delivery timelines

### Quality Checks

* Duplicate record detection
* Revenue validation
* Phone validation
* Data type corrections

---

## Feature Engineering Using NumPy

Created business-focused features for analysis:

### Age Group

Customers segmented into:

* Young
* Adult
* Senior

### VIP Customer

Identified high-value customers based on revenue contribution.

### High Rating Customer

Classified customers based on satisfaction levels.

### Delivery Days

Calculated delivery duration between order and delivery dates.

### Delayed Order

Flagged delayed deliveries for operational analysis.

---

## Exploratory Data Analysis (EDA)

Performed analysis on:

* Revenue by Category
* Revenue by City
* Customer Segmentation
* Payment Method Usage
* Product Performance
* VIP Customer Contribution
* Customer Ratings

---

## Key Business Insights

* Electronics generated the highest revenue among all categories.
* Ahmedabad emerged as the highest revenue-generating city.
* UPI was the most preferred payment method.
* Data cleaning reduced the dataset from 310 records to 268 high-quality records.
* Feature engineering enabled customer segmentation and operational performance analysis.

---

## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Data Validation
* Missing Value Treatment
* Feature Engineering
* Exploratory Data Analysis
* Business Rule Validation
* Data Transformation
* Customer Segmentation
* Revenue Analysis
* Data Quality Assessment

---

## Project Files

* customer_orders_cleaned.csv
* customer_orders_feature_engineered.csv
* customer_orders_final.csv
* Data_Cleaning.ipynb
* README.md

---

## Author

Amit Kumar

Aspiring Data Analyst

Skills: SQL | Excel | Power BI | Tableau | Python | Pandas | NumPy | Data Analytics
