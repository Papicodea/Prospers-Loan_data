# (Prosper Loan-Data Exploration)
## by (Somto Odenigbo)


## Dataset

The data consist of information regarding 113,937 customer data with 81 variable features. This data can be found here on: 
https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub
It is a large dataset and a select few of the variables was picked(15 columns),  Some wrangling procedure was needed which ultimately took the size down to 76,224 rows. The selected columns are: (Term, LoanStatus, BorrowerAPR, BorrowerRate, LenderYield, ProsperRating, ProsperScore, ListingCategory, BorrowerState, Occupation, EmploymentStatus, IsBorrowerHomeowner, DebtToIncomeRatio, IncomeRange, Investors).
 The wrangling steps taken are:
 - change of name variable columns for simplicity
 -  Eliminating nan values in the dataset


## Summary of Findings

In the exploration, I found that there was a strong relationship between the ProsperRating and the many factors that determine a Loan to be listed. The relationship is tends to a strong linearly progressive relation between prosper Ratings and BorrowerRates, also there is little to no difference between BorrowerAPR, LenderYield and BorrowerRate which shows similar trends to Prosper rating. I found also that the investors can be bias and look to prosper Rating when choosing to invest on a loan.

From exploring the data i was able to see that certain factors affect borrowers rate on a Loan; the rate seem to be mainly affected by the prosper rating, investors and income rangeS.

Outside of the main features of interest, the income range and investors show good relationship with the prosper Score rating which indicates the borrowers with more income and good prosper rate attracts more investors. 


## Key Insights for Presentation

For the Presentation, my focus was on the 3 variable features of the analysis and a fourth variable {incomeRange, BorrowerRate, ProsperRating, investors}. I start by introducing the Borrower rate and then the investors as it correlates to the Borrower Rate, The borrower Rate distribution was polished to depict a clearer trend in the data than while exploring. I went on then to plot the borrower rate to prosper rate which was also polished with additional keyword arguments passed.

Afterward, I introduced the multivariate relationship between the 3 variables mentioned above and BorrowerRate. A col by col method was used in the exploratory analysis to explore the relationship between the Borrower Rate by investors and ProsperRation but for the purse of explanatory, a hue argument was passed. The other Multivariate relation had only a color change when plotting for explanatory basis of Borrower Rate by Income Range and Prosper Rating.