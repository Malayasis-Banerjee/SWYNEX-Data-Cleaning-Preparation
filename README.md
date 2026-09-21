# SWYNEX-Data-Cleaning-Preparation
# Sales_transactions_2022_2025 Data Cleaning & Preparation
## SWYNEX Technologies — Data Analyst Internship | Task 1

This project was completed as part of my **Data Analyst Internship at SWYNEX Technologies**.

The objective of this task was to identify and resolve common data quality issues in a real-world dataset and prepare the data for further analysis.

The dataset was cleaned and transformed using **Microsoft Excel and Power Query**.

## 📊 Dataset

**Dataset:** Sales_transactions_2022_2025  - Dirty Data for Cleaning Training  
**Source:** Kaggle
**Period:** 2022–2025
**Rows:** 18,045 
**Columns:** 36
**Data type:** Raw, uncleaned transaction data
**About this file**
It is a Multi-Channel Retail & B2B Sales Transaction Dataset simulating sales of office equipment, electronics, furniture, appliances, and office supplies across multiple sales channels.
The dataset contains sales transactions with intentionally introduced data quality issues such as missing values, invalid entries, inconsistent values, and incorrect data types.

## Data Quality Issues Identified

The following issues were identified during the initial inspection:

- Missing values
- 'UNKNOWN' and 'ERROR' entries
- Incorrect data types
- Missing values in numeric and categorical fields
- Invalid or missing transaction dates
- Duplicate records check
- 

## 🧹 Data Cleaning Process

The dataset was cleaned and transformed using **Power Query**.

### Invalid Values

`UNKNOWN` and `ERROR` entries were identified and replaced with null values where applicable.

### Missing Values

Missing numeric values were handled using logical calculations wherever the required information was available.

For example, missing values were derived using the relationship between **Quantity,  Unit Price, and Sales Amount**.

Where a value could not be reliably determined, it was retained as Unknown rather than making assumptions.

Categorical missing values were also reviewed and retained as Unknown or Not Avl where no reliable value could be inferred.

### Data Types

Incorrect data types were identified and corrected to ensure that the dataset was properly structured and ready for analysis.

### Data Consistency

Categorical values were reviewed to ensure that invalid entries were removed and only valid values remained.

### Duplicate Records

The dataset was checked for duplicate records.

**Result**: 45 duplicate records were found.

### Transaction Date

The existing date values were already in the correct format, and the column data type was corrected to ensure it was properly recognized for analysis.

## 🛠️ Tools Used

- Microsoft Excel
- Power Query

## 📁 Project Files

**Sales_transactions_2022_2025.csv**  
Final cleaned dataset.
**Sales_transactions_2022_2025 cleaned.csv**  
Excel workbook containing the original Raw Data, cleaned data, and preserved Power Query transformation steps for review.

---

## 📈 Final Outcome

The dataset was successfully cleaned and prepared for further analysis by improving data quality, consistency, and structure.

## Key Learning

Through this task, I gained practical experience in:

- Identifying data quality issues
- Handling missing and invalid values
- Cleaning and transforming data using Power Query
- Applying logical calculations to recover missing information
- Validating data consistency
- Preparing a dataset for further analysis


## Author
**Malayasis Banerjee**

Data Analyst Intern | Data Analytics Enthusiast
#SWYNEX #DataAnalytics #DataAnalyst #Excel #PowerQuery #DataCleaning #Internship
