# Project Name
> This project of Lending club EDA analysis is used to analyse the factor/features which affect the default of laons.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Used EDA technices to analyse the Loan defaults.
- Used the loan.csv with features to perform the EDA analyse
- To find the Charged Off/Default of the customes in the dataset.
- Loan dataset was used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have taken data only for Charged Off
1) We can observe that it follows a Negative scked data plot for Loan Amount. Max data lies around 5000 units.
2) We can observe that it follows a Negative scked data plot for funded Amount. Max data lies around 5000 units.
3) We can observe that it follows a Negative scked data plot for funded Amount Inv. Max data lies around 5000 units. Also we can note that min amount funded Inv is 0. While for Loan & funded amount it is greater than 0.
4) All data for loan_amt, funded_amt, funded_amt_inv shows that data greater than 30,000 is outliers. But these data are very important, so we keep them.
5) Interest rates vary from 5.42% to 24.59%
6) Data shows that all grades have the same kind of loans till 25000. Grades have fewer data at higher loan. While grade G has few data at higher end.
7) There is a scattered data for sub_grades for loan_amnt
8) Trend shows that People with 10+ years of expereince has loan amount greater than 30K. While lesser experience has lower Loan amount.
9) Trend shows that RENT have more exposure to higher amount. OWN house have less exposure. While MORTAGAGE have high exposure.
10) Lesser Annual Income has high exposure to higher loans and default chances.
11) Trend shows that Not Verified status shows lot of Defaults.
12) Trend shows that debt_consolidation has higher chance of default.followed with home_improvement.
13) Title and Addr_state have impact on defaulters.
14) Various states of USA have trends for default. All states have default at lower and Mid segment than higher loan.
15) delinq_2yrs with 0 has highest defaulters while it reduces as delinq_2yrs increases. delinq_2yrs = 8 has 1 defaulters. This is an important parameter.
16) inq_last_6mths with 0 has defaulters, while higer value has less defaulters. It increases as inq_last_6mths increases. This is an important parameter.
17) mths_since_last_delinq - This variable had lot of NaN, so imputed. It doesn't provide much information.
18) mths_since_last_record - The feature had lot of NaN. So we imputed with mode. But the information is not useful.
19) open_acc - Least values & Very High Values defaulters have same trend. High and Moderate have same kind of distribution.
20) pub_rec value with 0 has high defaulters. So its a good parameter.
21) revol_bal revol_bal with High and Very High values shows more defaults for lesser loan amount. While as it decreases there is a slight decrease in defaults.
22) Trend shows that revol_util with High and moderate shows more defaults. But Least shows trend at less loan amount. Similary for Very High and Moderate.
23) Trend shows that total_pymnt with Least values have more defaulters at lower end. While the value increases the defaulters also increases.
24) total_pymnt_inv - Same trend as total_pymnt.
25) total_rec_prncp - Trend shows that Very High and High total_rec_prncp has defaulters at the Higher loan amount and less at lower loan amount.
26) Older Year's have less defaults compared to recent Years.
27) All month's have same kind of defaults.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python 3.x
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- By the techniques explained by the Online classes.
- References if any...
- This project was based on dataset provied by UpGrad..


## Contact
Created by [@vijayzone] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->