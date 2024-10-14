# Exploratory-Data-Analysis-on-Loan-data
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter.

This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

## Understanding Dataset
The given dataset of a loan providing company which has 3 files as explained below: 

1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties. 
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.

## Assumptions
- The value ‘365243’ is assumed as unemployed in the Occupation Type attribute of application dataset
- The values ‘XNA’ & ‘XAP’ are assumed to be as null values in the 	application dataset and previous dataset
- In previous dataset, Higher number of Region rating is considered higher 	rating

## Approach
- Data Loading: Read The Given Data Sets Application_data And Previous_application In Jupyter Application.
- Data Sanity Checks 
- Identification Of Missing Values & Their Handling: Drop Columns That Have More Than 35% Of Missing Data.
- Selection Of 25 Attributes Relavent To The Problem Statement In Application Data And Group them into 5 Each
- Performing Univariant, Bivariant, Segmented Univariant Analysis With These Attributes 
- Jotting Down Inferences Based On The Analysis Plots

## Conclusion
In conclusion, top 10 correlations for the Client with payment difficulties and all other cases as per the inferences of the univariant, Bivariant and Segmented univariant analysis are as follows:


<img width="225" alt="image" src="https://github.com/user-attachments/assets/e1a6b7eb-9bff-4e25-a1d2-a9c58e1034f3">
<img width="241" alt="image" src="https://github.com/user-attachments/assets/cb1ed4e4-8795-42c2-b80a-c5b953f39f5d">
<img width="241" alt="image" src="https://github.com/user-attachments/assets/5dbda1e8-c4fb-47f5-8b24-09bbe02fdd59">







