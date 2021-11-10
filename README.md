# Lending Club - Case Study
The Business Objective of this study is to identify Driving Factors (or driver variables) which are strong indicators of default and potentially use the insights in Approval/ Rejection decision making.
The Company can utilize this information for its Portfolio and Risk Assessment and can reduce the Risky Loan Approvals and hence Cutting Down the amount of its Credit Loss or Financial Loss.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Loan data was analyzed using EDA with python
- The company gives out loans to applicants and has collected data on past and current loans
- The goal was to identify factors that lead to loan default - so that it can avoid bad customers without losing business on good customers
- Dataset and its description was provided by the company
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- EDA was performed
- Univariate, Bivariate analysis were studied
- Factors affecting defaults were identified​
- Factor combinations that lead to higher defaults were identified
- No machine learning methods were used ​
- Plots were used to analyze the data better

<br>

### Data Analysis and Variables Identification  

- The target Variable Identified as Loan Status
- The dataset has some categorical variables and continuous Numeric Variables
- The categorical variables identified are:  term, emp_length, grade, sub_grade, home ownership, and verification status
- Some continuous variables like loan_amount, funded_amount, inter_rate etc. are binned and create new Categorical Variables
- The variable purpose is used for sector analysis


<br>

### Correlation Matrix upon Bivariate Analysis
- Loan amount, investor amount, funding amount are strongly correlated
- Annual income with DTI(Debt-to-income ratio) is correlated negatively(that is if annual_income is high, dti(Debt-to-income) ratio is low & vice versa)
- Positive correlation between annual income and employment years, that means the income increases with work experience


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - Version 3.8.5
- Visual Studio code - Version 1.62.1
- Git - Version 2.33.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Sajan Kedia, Ugo Beneditto and Daniel 
- This project was based on [How to perform EDA for data analysis](https://www.upgrad.com).


## Contact
Created by [@dsiubmuann] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->