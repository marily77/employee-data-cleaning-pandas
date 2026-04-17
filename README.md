# Employee Data Cleaning with Pandas

## Overview

This project demonstrates a complete data cleaning workflow using Python and Pandas.

The goal was to clean and standardize a messy employee dataset provided as a CSV file. The dataset contained inconsistent formats, missing values, duplicates, and logical errors.

This project simulates a real-world task of a data analyst working with HR data.

---

## Key Skills Demonstrated

* Data cleaning and preprocessing
* Handling missing values (imputation)
* Data type conversion
* Working with datetime
* Feature engineering
* Removing duplicates
* Data merging and transformation
* Data validation

---

## Dataset

The dataset includes employee-related information such as:

* Name
* Age
* Salary
* Department
* Joining date
* Other attributes

The original dataset was intentionally messy and required multiple cleaning steps.

---

## Workflow

### 1. Data Loading

* Loaded CSV file from Google Drive

### 2. Initial Exploration

* Checked data types
* Identified missing values
* Detected duplicates and inconsistencies

### 3. Column Cleaning

* Renamed unclear column names
* Standardized naming conventions

### 4. Name Processing

* Split full names into:

  * First name
  * Last name

### 5. Age Cleaning

* Removed invalid values
* Applied imputation
* Converted to integer

### 6. Date Processing

* Standardized formats
* Converted to datetime objects

### 7. Salary Cleaning

* Handled missing values
* Converted to integer

### 8. Feature Removal

* Dropped irrelevant column (Parking)

### 9. Department Cleaning

* Standardized categories (FI, OP, HR, IT)
* Applied imputation

### 10. Duplicate Removal

* Based on first and last name

### 11. Feature Engineering

* Years since joining
* Salary category:

  * Low (< 30,000)
  * Medium (30,000–59,999)
  * High (≥ 60,000)

### 12. Data Merging

* Joined additional building information dataset

### 13. Sorting & Indexing

* Sorted by joining date
* Reset index

### 14. Final Structure

* Reordered columns for clarity

### 15. Export

* Saved cleaned dataset to CSV

---

## Output

Cleaned and structured dataset ready for analysis or machine learning.

---

##  How to Run

1. Open the notebook in Google Colab
2. Mount your Google Drive
3. Update file path if needed:

```python
Dataset is included in this repository.
```

4. Run all cells

---

## Future Improvements

* Add data validation pipeline
* Convert notebook into reusable Python script
* Add visualizations
* Build a simple dashboard

---

## 👤 Author
marily77

---

## 🇪🇪 Eesti kirjeldus

See projekt keskendub töötajate andmete puhastamisele Pandase abil.
Eesmärk oli korrastada vigane CSV fail ning valmistada see ette edasiseks analüüsiks.
# employee-data-cleaning-pandas
