# Lending Club
This is a lending club project, which is created to avoid the credit loss of the  investors.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Many a times the borrowers fails to repay the principal money and interest, and fall under defaulters list 
which causes creadit loss to inverstors. This project is an attempt to identify the defaulters and thereby 
reduce the credit loss.
We have used the loan data from 2007 to 2011 for the analysis . These data include the list of people who fully paid , or currently paying and dafaulters.We considered the faully paid and defaulters list for analysis . 

## Technologies Used
Explanatory Data Analysis(EDA) is the methos used for analysis. This includes data understanding,data cleaning and analysis of data using univariate, bivariate and multivariate  analysis.
Libraries Used : numpy, pandas, Seaborn, matplotlib

## Conclusions
Data Frame contains 39717 data with 111 columns.After data cleaning and analysis we arrived at below conclusions:
Term:
People prefer 36 months loan.
Both 60 and 36 months has defaulters. But 36 has more since more people prefer 36 month loan.

Annual income:
Normally people tend to take loan in lower range of annual income 2000 to 12000
Annual income even it its high or low defaulters are there. It doesnt have much influence in defaulters. 

Employement Length:
People with 10 or more years of experience take more loan.
Defaulters as well as non defaulters are also high with more than 10 yrs of experience.

Verification Status:
People with more non verified status are getting loan.
And non verified people are slightly higher in defaulters list.
and Source verified people are a little less compared to non verified people. Hence verification should be mandatory.

Purpose:
More for debt consolidation.
But debt consolidation has more defaulters too.

Grade:
A and B has more loan requests.
F and G has more defaulters.

Sub Grade:
People in A4, B3 , A5 , B4 and B5 are mostly requesting for loan.
Category more : F5 and G3 has more defaulters  

DTI:
Dti with 10 to 16 take more loan.
Dti 15 to 21 has high chances of deafulting.
Less dti less chances of defaulting.

Home Ownership:
People with home ownership Mortage and Rent request for more loan.
And people with mortage and rent has high defaulters list too. People with own house has less defaulter rate.

Loan Amount:
Number of loans are more with less ,loan amount.
And deafaulters are there with every loan amount margin. But there is a rise in defaulter top most loan value ie. aroung 35000.

State:
People from california has taken more loans and are amoung the highest defaulters.

Recommendation:
Verification should be mandatory. 
Grades F and G has high chance of defaulting. And Sub grades F5 and G3 has more defaulters . So should be very carefull when loan is given to this category.
DTI above 15 has to 21 high chance of defaulting. Loan amount in the highest margin should be given with proper consideration.
People with own high tend to have a higher chances of repayment is full. So need to come up with plans which will promote this amoung these category of people. Also need to be care full when loan is given to people without own house.
Loan Amount for high amount should be given very carefully. But still defaulters can be expected in every margin. So needs to be carefull in issuing loan.
People from California tend to take more loan also there are in the defaulters list to. So social and economic condition of place needs to be verified.    


## Acknowledgements
Upgrad- Team
This project is based on Upgrade -Executive PG Programme in Machine Learning Course - Case Study

## Contact
Shishira Shastri - https://github.com/shsgithub4
Jerin James      - https://github.com/JerinJK
