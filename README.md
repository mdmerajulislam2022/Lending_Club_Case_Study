# Lending Club Case Study

## Project Introduction/Objective
This will contain an Exploratory Risk Analysis for an online marketplace specializing in Personal Loans, business loans, and financing of medical procedures. The company likes to do an Exploratory Credit Risk Analytics on the lending data available to them, the main objective of this task is to understand the 'risky' applicants that can cause Credit loss due to default. If the analysis can be used to identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss due to defaults.

The aim of this EDA(Exploratory Data Analysis) is to find the driving factors behind the loan default, variables that are strong indicators will be presented

## Methods Used for EDA (Exploratory Data Analysis):
* Data Handling and Cleaning
* Sanity Checks and Outlier Analysis
* Univariant Analysis
* Bivariant Analysis


#### Project Version : V1
#### Project Status  : Completed
#### Release Data    : 15/08/2022

### Language : 
* Python

### IDE: 
* jupyter Notebook

### Libraries Used :
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2

### Files: 
* .pynb file -- jupyter file containing the code
* .pdf file -- power point  in PDF format
* .csv file --- containing original data (1 csv and 1 xlsx file)

#### Analysis and Findings :
	Grade, SubGrade    -- As grade changes there are defaulters changing, G being the highest
	Purpose of the loan -- Small business has more defaulters
	Interest rate      -- As interest rate increases defaulters are moe 
	Term -- There are more defaulters with 60 months term than 36 months
	Annual income -- If the annual income is more then high possibility that he pays the loan
	Debt to Income -- Percentage of default rises with dti ratio. As the dti ratio rises above 20, the loans become risky

#### Recommendations 
	1. Stop – approving loans where amount/income is higher than 30%.
	2. Reduce – number of approvals where purpose is small business.
	3. Stop – approving high-value loans when revolving line utilization rate greater than 75%.
	4. Stop – approving loans to people with prior bad record. Or at least stop approving high-value loans.
	5. Start – charging higher interest rates for loans with dti greater than 20.


#### Loan State Wise Distribution
![alt text](git remote add origin https://github.com/mdmerajulislam2022/Lending_Club_Case_Study.git)
 
## Acknowledgements 
 - Upgrad/IITB
 - Online Sources : Stackoverflow, Pandas , seaborn , plotly, numpy , matplotlib
