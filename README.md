# EDA-on-Vehicle-Insurance-Data

live Project  link on google Collaboratory :- https://colab.research.google.com/drive/1MTjp4SXBvzJiTiIUHcAAZqRG9_40siy1#scrollTo=7XDOYEwVf8uS

**Vehicle Insurance Data Exploratory Data Analysis (EDA)** 

This repository contains code for performing Exploratory Data Analysis (EDA) on vehicle insurance data. The aim of this project is to provide insights into the customer and policy data of a vehicle insurance company, enabling informed decision-making for future growth and premium discount offers.


**Project Overview** 

A company possesses customer data with various details and another table containing policy details of the customers. The data science team has been tasked with extracting valuable information to offer discounts on premiums to certain customers. The tasks involved in this project are:


Adding column names to both datasets.

Checking and cleaning data quality, including handling null values, outliers, white spaces, case correction, and converting categorical data into dummy variables.

Creating a master table by joining the customer and policy tables.

Extracting important information for decision-making, such as gender-wise and age-wise average annual premiums, balancing data between genders, and analyzing the relationship between person age and annual premium.


**Tasks**

1.	Add Column Names:
   
•	Assign column names to both datasets according to the specified order.


2.	Checking and Cleaning Data Quality:

•	Handle null values by dropping them for customer_id, replacing null values for numeric columns with mean, and replacing null values for categorical columns with mode.


•	Identify and treat outliers using the Interquartile Range (IQR) method.

•	Remove white spaces and perform case correction.

•	Convert categorical data into dummy variables for future modeling.

•	Drop duplicate rows.

3.	Create Master Table:

•	Join the customer details table and policy table using customer_id to create a master table.

4.	Generate Important Information:

•	Calculate gender-wise and age-wise average annual premiums.

•	Determine if the data is balanced between genders.

•	Calculate vehicle age-wise average annual premiums.

6.	Explore Relationships:

•	Analyze the correlation between person age and annual premium to identify any potential relationship.

How to Run the File on Jupyter Notebook

To run the analysis on Jupyter Notebook, follow these steps:

1.	Clone the Repository:

Copy code

git clone <repository_url> 

2.	Install Dependencies:

Copy code

pip install pandas matplotlib 

3.	Open Jupyter Notebook:

Copy code

jupyter notebook 

4.	Navigate to the Project Directory:

Copy code

cd Exploratory_Data_Analysis_Vehicle_Insurance 

5.	Open the Jupyter Notebook File:

•	Launch Jupyter Notebook in your web browser and navigate to the project directory.

•	Open the Exploratory_Data_Analysis.ipynb file.

6.	Run the Notebook:

•	Execute each cell in the notebook sequentially by pressing Shift + Enter.

•	Follow the instructions and comments within the notebook to perform each task.

7.	View Results:

•	After running all cells, analyze the results and visualizations generated within the notebook.


**Dependencies**

•	pandas

•	matplotlib

**Contributors**

•	Mishkat Ahsan 


Feel free to contribute to this project by opening issues or submitting pull requests!

mdmishkatahsan02@gmail.com 

