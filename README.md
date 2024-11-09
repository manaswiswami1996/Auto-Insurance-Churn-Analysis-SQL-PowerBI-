# Auto Insurance-Churn-Analysis(PowerBI)
(Work-in-progress) The objective of this project is to identify the main factors affecting customer churn and provide insights to enhance customer retention in auto-insurance company. It analyses patterns and trends in customer demographics and behavior to identify high-risk churn segments and guide business strategy.
# Dataset Description
The dataset used in the project has been taken from <https://www.kaggle.com/datasets/merishnasuwal/auto-insurance-churn-analysis-dataset?select=termination.csv>. The provided dataset is relational and consists of four distinct data files.

1. address.csv: contains address information

2. customer.csv: contains customer information.

3. demographic.csv: contains demographic data

4. termination.csv: includes customer termination information.

5. autoinsurance_churn.csv: includes merged customer churn data generated from this notebook.
   

All data sets are linked using either ADDRESS_ID or INDIVIDUAL_ID. The ADDRESS_ID pertains to a specific postal service address, while the INDIVIDUAL_ID is unique to each individual. It is important to note that multiple customers may be assigned to the same address, and not all customers have demographic information available.

### Size of the data set
The data set includes 1,536,673 unique addresses and 2,280,321 unique customers, of which 2,112,579 have demographic information. Additionally, 269,259 customers cancelled their policies within the previous year.

### Tools Used:
- MySQL Workbench for Data Preprocessing
- PowerQuery for Data Analysis
- Microsoft PowerBI for Data Visualisation

# Data Pre processing


