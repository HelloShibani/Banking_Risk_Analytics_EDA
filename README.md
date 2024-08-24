# Banking Risk Analytics EDA Case Study
## Project Overview

This repository contains a case study aimed at applying Exploratory Data Analysis (EDA) techniques to a real business scenario in the banking and financial services sector. The objective is to develop a fundamental understanding of risk analytics and how data can be leveraged to minimize financial risks associated with lending to customers.

## Objective
-    Primary Goal: To perform EDA on banking and financial data to understand risk factors and develop insights that can help mitigate financial losses when lending to customers.
-   Secondary Goal: To apply risk analytics principles and explore how data can be used to make informed decisions in banking.

## Dataset
The dataset is divided into three files:

1. application_data.csv: Contains information about the client at the time of the loan application, including whether the client had payment difficulties. The key scenarios are:

-   Client with payment difficulties: Had late payments of more than X days on at least one of the first Y instalments of the loan.
-   All other cases: Payments were made on time.
2. previous_application.csv: Contains information about the client's previous loan applications. The loan application could fall into one of four categories:

-   Approved: The loan application was approved.
-   Cancelled: The client cancelled the application during the approval process.
-   Refused: The loan application was rejected.
-   Unused offer: The loan was cancelled by the client at different stages of the process.
3. columns_description.csv: A data dictionary that describes the meaning of each variable in the datasets.

## Methodology

1. Exploratory Data Analysis (EDA):

    -   Analyzed distributions and relationships between features in the application_data.csv and previous_application.csv files.
    -   Identified patterns and correlations that may indicate risk factors for loan defaults.
    -   Visualized key metrics to gain insights into client behavior and loan attributes.

2. Data Preprocessing:

    -   Handled missing values and outliers.
    -   Performed feature engineering to create new variables that could improve the analysis.
    -   Encoded categorical variables and scaled numerical features.

3. Risk Analysis:

    -   Assessed risk factors associated with loan defaults using statistical methods.
    - Developed visualizations to illustrate how different attributes impact the likelihood of default.



## Repository Structure

All files related to this project are located in the master branch of this repository:

-   application_data.csv: Contains client information at the time of the loan application.
-   previous_application.csv: Contains data on previous loan applications and their outcomes.
-   columns_description.csv: Data dictionary describing the variables in the datasets.
-   CREDIT_EDA_CASE_STUDY.pdf: A PDF document containing the complete flow of analysis and the inferences derived.
-   EDA_Analysis.ipynb: Jupyter notebook with Exploratory Data Analysis and risk analytics.
-   README.md: Project overview and details (this file).

## Usage Instructions

1. Clone the Repository:

    - git clone https://github.com/HelloShibani/Banking_Risk_Analytics_EDA.git

2. Navigate to the project directory:
    -   cd Banking_Risk_Analytics_EDA

3. Set up a Python environment with the necessary libraries. If you don't already have the required packages installed, you can install them using:
    -   pip install pandas numpy matplotlib seaborn 

4. Run the Jupyter notebook:
    -   jupyter notebook

5. Open the EDA_Analysis.ipynb notebook to explore the analysis and model development.

## Future Work
-   Explore additional features and external data sources for more comprehensive risk analysis.
-   Validate findings with different datasets to ensure robustness and generalizability.