# Loan Data Exploration

## by Ting Yang


## Dataset

> The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. This project investigates the factors that could effect borrowers' APR rate and the amount of money they can borrow. The dataset can be downloaded here: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv



## Summary of Findings

> In the exploration, I found that the borrower APR is negatively correlated with ProsperScore. The borrower APR decreases with the increasingly score. Also borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Interestingly, the relationship between borrower APR and ProsperScore changes from positive to slightly negative when the Prosper ratings changes from HR to A or better. I also looked at if loan term effects on loan amount, it shows that with better Prosper rating, the loan amount increases acorss all three terms.

> Outside of the main variables of interest, I found that the loan amount is postively correlated with the loan term, the longer loan term, the more money people can borrow. I also found that borrowers with better Prosper rating have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. 




## Key Insights for Presentation

> My main interest is to find what factors matter to borrowers APR, after exploring all possible variables related to BorrowerAPR, I found that ProsperScore has the strongest relationship. The borrower APR is negatively associated with the ProsperScore, which mean the higher the score, the lower the APR. 

>I also investigated the effect of Propser rating on ralationship between APR and ProsperScore, as well as the effect of Prosper rating on relationship between loan amount and term. It shows that with better Prosper rating, the loan amount increases acorss all three terms.

## Resources

https://seaborn.pydata.org/generated/seaborn.FacetGrid.html
https://dataxujing.github.io/Python%E7%94%BB%E5%9B%BE%E4%B9%8Bseaborn-1/

