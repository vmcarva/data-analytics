# Project Guide

The task is given in the file: [berka.pdf](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/berka.pdf)

Since the task was about cleaning, transforming, translating the DB to analyze it with Python, the primary and foreign keys were assumed to be consistent already, since the files were probably exported from an original working DB. Therefore, they were not recreated for this task. 

### 1) Most of the tables were imported to MySQL by using the Import Wizard. This includes the tables:
- Account
- Client
- Card
- Disp
- District
- Loan
- Order

### 2) However, the table *Trans* can't be imported using the Import wizard so fast. This is why the Python code was written: to read the CSV with the trans information and to record it in a table on the Berka DB. 
- [Trans table creation.ipynb](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Trans%20table%20creation.ipynb)

### 3) Following this step, the scripts below were executed to clean, transform and translated information on the DB:
- [Basic Data Cleaning and Transformation.sql](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Basic%20Data%20Cleaning%20and%20Transformation.sql)
- [Translating Categorical Values.sql](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Translating%20Categorical%20Values.sql)

### 4) The scripts for new table creations are the ones below:
- [Creating Table Balance_Account.sql](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Creating%20Table%20Balance_Account.sql)
- [Creating Table Account_Profile.sql](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Creating%20Table%20Account_Profile.sql)

### 5) A dump of the financial database called berka was generated and can be executed with the script:
- [Dump DB - Financial Data Set 20190803.sql](https://github.com/vmcarva/python/blob/master/Financial%20Data%20Set%20Project%20-%20SQL%20Cleaning%20and%20Transforming%20and%20Exploratory%20Data%20Analysis/Dump%20DB%20-%20Financial%20Data%20Set%2020190803.sql)
