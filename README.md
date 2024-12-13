# Python for Data Science  
## Final Project  

---

## 1. Raw Dataset  

This folder contains raw datasets for 10 companies.

---

### Key Information

1. Each company's data is stored in a `.csv` file.
2. These files are the starting point for cleaning and preparing the data.
3. We will use Python and the `pandas` library to read these files and clean the data.
4. We then save and export cleaned .csv files for each company's dataset to another folder.

---

## 2. Data Cleaning  

These notebooks focus on cleaning and preprocessing data for better analysis. Below are the steps we followed for each dataset:

---

### Key Steps  

1. **Importing Dataset**  
   - Loaded the raw dataset into the notebook using `pandas`.

2. **Inspecting the DataFrame**  
   - Examined the structure of the data using methods like `.head()`, `.info()`, and `.describe()`.  
   - Gained insights into the data types, column values, and overall quality of the dataset.

3. **Cleaning the Dataset**  
   - **a) Sorting the Dataset**  
     - Organized the data based on specific columns for easier analysis.  
   - **b) Identifying and Removing Duplicate Rows**  
     - Checked for duplicate entries and removed them to ensure data accuracy.  
   - **c) Visualizing the Dataset to Identify Outliers**  
     - Created visualizations to detect potential outliers in the dataset.  
   - **d) Removing Outliers**  
     - Applied techniques to filter out extreme values that could skew the analysis.  
   - **e) Imputing Missing Values**  
     - Handled missing data using appropriate imputation strategies.

4. **Exporting the Cleaned Dataset**  
   - Saved the cleaned dataset to a file for future use.

---

## 3. Cleaned Datasets  

This folder contains the cleaned and processed data for 10 companies.

---

### Key Information

1. The raw datasets were cleaned using Python and saved here as `.csv` files.
2. We will use these cleaned files to solve all the exercises for each dataset.

---

## 4. Exercises  

This Workbook is focused on exploring, analyzing, and visualizing financial datasets using Python. The workbook includes various visualizations and statistical analyses to understand trends, spreads, and relationships between variables for different companies.

---

### **1. Overview**

This workbook performs data analysis on financial datasets to study key metrics such as:
- Monthly trends in financial performance.
- Relationship between trading volume and stock price.
- Average spreads over time.
- Comparative analysis across multiple companies.

### **2. Visualizations**

The following types of visualizations are included in the notebook:

- **Bar Charts**: Compare average spreads across companies.
- **Line Charts**: Spot overall trends and relative perfomance across companies.
- **Joint Plots**: Analyze relationships between variables like volume and close price.
- **Boxplots**: Visualize monthly spread distributions for a detailed view.

### **3. Insights**

Key insights derived from the visualizations:
- **Trends Over Time**: Observes historical and recent behavior of financial metrics.
- **Relationships**: Explores correlations between trading volume and stock price.
- **Market Volatility**: Highlights periods of high volatility and their possible causes.
- **Comparative Spreads**: Identifies companies with the largest and smallest average spreads.
---

### **List of Exercises**

1. **Exercise 1: Dataset Overview**
    - Printed the number of rows and columns for each dataset.
    - Displayed the column names and their data types to understand the structure.
2. **Exercise 2: Extract 2023 Data**
    - Filtered rows where the date is in 2023.
    - Counted the rows and visualized the Close price trend for that period.
3. **Exercise 3: Highest Close Price**
    - Found the day with the highest Close price for each company.
    - Displayed the date along with the highest price.
4. **Exercise 4: Monthly Average Close Prices**
    - Grouped the data by month and calculated the average Close price for each company.
    - Plotted monthly averages for three companies and compared them, with a justification for the chart selection.
5. **Exercise 5: Yearly Average Close Prices**
    - Calculated the yearly average Close price for each company.
    - Plotted a comparison of yearly averages across all companies and provided justification for the chosen chart.
6. **Exercise 6: Monthly Price Ranges**
    - Created a plot for each company showing the range of prices (highs and lows) for each month.
    - Justified the chart selection used to highlight price variability.
7. **Exercise 7: Volume vs. Close Price**
    - Plotted the relationship between trading volume and Close price for a selected company.
    - Added insights about the observed pattern and justified the choice of chart.
8. **Exercise 8: Highest Monthly Trading Volume**
    - Identified the month with the highest total trading volume for each company.
    - Displayed the results in a summary table, showing the month and the total volume.
9. **Exercise 9: Merged Dataset**
    - Combined the datasets for all companies into a single dataset (one for each year).
    - Printed the structure of the combined dataset, ensuring proper alignment and handling of missing values.
10. **Exercise 10: Price Spreads and Analysis**
    - Calculated the daily spread (High - Low) for each company.
---
