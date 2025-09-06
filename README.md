# Chipotle-Data-Cleaning

## Project Description
This project showcases a complete data cleaning workflow on the Chipotle Orders dataset. It involves importing raw data, correcting inconsistencies,converting price values to numeric and filtering relevant fields to ensure the dataset is accurate, consistent, and ready for analysis.

## Resources
**File Used:**
  - chipotle.tsv
**Source:**  [Chipotle Dataset on Kaggle](https://www.kaggle.com/datasets/ayoubhafidialaoui/chipotle-dataset)

## About the Data
The dataset contains restaurant order records from Chipotle. Each row represents one item within an order.
  - Rows = 4622
  - Columns = 5

## Data Information
**Key columns:**
  - order_id - Unique order identifier
  - quantity  Quantity of the item ordered
  - item_name - Name of the menu item
  - choice_description - Additional item/ingredient choices
  - item_price - Price of the item (stored as string with $ sign)

**Cleaning Steps Performed**
  - Converted item_price from string (e.g., "$2.39") to numeric (2.39)
  - Verified dataset indexing
  - Used filtering, slicing, and indexing to select relevant subsets for analysis

**Impurities Removed**
  - Inconsistent formats - Converted prices from strings to numeric
  - Irrelevant values - Filtered out unwanted rows where needed

**Insights**
  - The most frequently ordered item is Chicken Bowl (726 orders).
  - Count of different items sold.
  - Average Revenue generated per Order.
  - Total revenue across the dataset period.
  - Most frequently ordered item in choice_description.
  - Total quantity of items ordered.
  
