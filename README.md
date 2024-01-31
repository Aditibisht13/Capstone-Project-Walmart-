# Capstone-Project-Walmart-
# 1. Problem Statement:
A retail store that has multiple outlets across the country are facing issues in managing 
the inventory - to match the demand with respect to supply. You are a data scientist, who 
has to come up with useful insights using the data and make prediction models to forecast 
the sales for
X number of months/years.
# 2. Project Objective:
Project objective is to:
1. Present useful insights by using the given data that can be used to solve the 
problem of inventory management or in other words matching the supply to 
demand ratio.
2. Creating a prediction model in order to forecast the sales for coming 
months/years.
# 3. Data Description:
For this project we are using Walmart.csv data (containing 6435 rows and 8 columns.)
and table given below gives the description of the features present!
[Screenshot (217)](https://github.com/Aditibisht13/Capstone-Project-Walmart-/assets/154453925/19a8b192-1658-42f6-aeee-231c544e4742)

# 4. Data Pre-processing Steps and Inspiration
Following are the steps used for data pre-processing:
 Necessary libraries were imported for EDA of the data such as Pandas, Numpy,
 Matplotlib, Seaborn etc.
 The data csv file was loaded in the jupyter notebook and checked for info.
 The object datatype of Date was changed to datetime datatype as we are dealing with the 
Time related data
 Checking if data contains any missing values so that can be dealt before proceeding 
further. We concluded that the given data contains no missing values.
 Using Date column three separate columns were generated namely Day, Month and Year
so that we can study the weekly sales based on them.
