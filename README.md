# Lending Club DEfault Analysis - Case Study  
> Using EDA to find out how consumer attributes and loan attributes influence the tendency of default.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project aims to do find attributes that influence the tendency of default. 
- Money Lending business makes money by lending loans to its customer. Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

- This case study aims at identifying such applicants, discover various insights using the data provided, unfold key scenarios so that lending company can identify such risky loan applicants and reduce their credit loss. 
- loan.csv is used as the dataset for this analysis. File included in the repo for reference.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Fully paid population is way more than Charged off Population. 

- Business purpose -  debt consolidation tops as the major reason for loan default among population who defaulted. therefore keeping high interest rate or lowering the loan amount  for such business purpose helps company for credit loss.

- If Verification Status is Not Verified; it is more likely to default. compare to verification status of source verified, they are less prone to default.

- Interest rate over 10% is more likely to default compared to low interest rates.  

- 10 years or more experience have more debt-to-Income ratio compared to other experience range. It implies if 10 or above experience has higher dti( means more debt compared to their income) will default compared to other lower experience or lower dti.  

- Middle Income Group(MIG) pays high interest compared to other income group for complete population. 

- In Defaulters Category 10 years and above experience takes higher loan compared to other experience range. This may act as red flag when combining other factors like, purpose, loan amount, dti. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Pandas
- Numpy
- Matplot library 
- Seaborn library

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sbksum] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->