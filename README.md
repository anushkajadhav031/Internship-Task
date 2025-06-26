# Internship-Task
This Repository contain various tasks related to data cleaning ,preprocessing and Exploratory Data Analysis(EDA).here includes various real-world dataset on which various operations are perform like data cleaning and visulaization
## 📂 File Descriptions

### 1. raw_employee_data.csv

Raw dataset containing employee information including Name, Age, Gender, Email, Join Date, Salary, and Department.

Issues:
- Missing values in Age, Salary, and Department  
- Inconsistent formatting for Gender and Join Date  
- Duplicate records  
- Invalid entries like "unknown" in Age  


### 2. raw_customer_data.csv
 
Raw dataset of customer purchases with fields like Customer ID, Product, Price, Quantity, City, and Purchase Date.

Issues:
- Missing values in Price, Quantity, and Product  
- Text instead of numbers in Price (e.g., "forty-five thousand")  
- Inconsistent or invalid data entries  


### 3. data_cleaning_employee_data.ipynb

Jupyter Notebook for cleaning and preprocessing the employee dataset.
 Steps:
- Data exploration  
- Handling missing values  
- Standardizing Gender values  
- Removing duplicates  
- Fixing Join Date formatting  
- Previewing final cleaned dataset  

### 4. data_cleaning_customer_data.ipynb

Notebook for cleaning customer transaction data.

 Steps:  
- Data exploration and type inspection  
- Fixing non-numeric Price values  
- Handling missing Quantity and Product entries  
- Final output preview of cleaned data  


### 5. cleaned_employee_data.csv

Cleaned version of the employee dataset — all missing values addressed, formatting corrected, and ready for analysis.

### 6. cleaned_customer_data.csv
Final cleaned customer transaction dataset — ready for analysis and machine learning applications.
