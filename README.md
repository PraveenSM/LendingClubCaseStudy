# Lending Club Case Study
The aim of the assignment is to apply EDA (Exploratory Data Analysis) concepts to help a finance company make informed decisions on lending loans. The objectives are:
1. Determine whether to approve a loan. If approved, decide on the appropriate loan amount and interest rate, ensuring the company minimizes credit loss while retaining the customer.
2. Identify cases where loan repayment is highly unlikely and decide not to approve the loan in such instances.


## Table of Contents
* [Case Study - Lending Club](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In this case study, we analyze data from a finance firm to understand loan defaults and improve lending practices. The dataset includes various attributes related to loan applications, repayments, and customer demographics. The goal is to identify patterns that lead to defaults and make data-driven recommendations for loan approvals.- What is the background of your project?
- To perform exploratory data analysis (EDA) on the loan dataset.
- To identify factors contributing to loan defaults.
- To suggest improvements in the loan approval process based on findings

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Below are the important key takeaways.​
- Total payment made was more than expected amount(installments * term) - This can happen only on special cases where loan got compuonding interest rate. But no data is available. 11% is huge.​
- Verification process is compromised where maximum defaults are because of no strict process in the verification​
- Employment title not finding is also another case where confirms loop hole in the system​
- From all other univariate and bivariate analysis we could conclude that firm should consider moderate average rate with loan amount between 15k to 20k and avoid exceptional cases, with which helps in credit security.​
- Overall firm is not in great profit and should come with strict processes with in the firm.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python: Primary programming language for data analysis and visualization.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations and handling arrays.
- Seaborn: For statistical data visualization.
- Matplotlib: For creating static, interactive, and animated visualizations.
- Jupyter Notebook: For developing and presenting data analyses interacti

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by by Upgrad Case Study for EDA concepts.
- Data Source - Dataset is provided by upgrad.

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
