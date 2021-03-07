# (Prosper Loan Dataset Exploration)
## by (Moshira Ezzat Mostafa)


## Dataset

> This is a financial dataset from Prosper marketplace inc., it contains 113,937 loans with 81 variables storing information about Loans, Borrowers, Lenders, interest rates and many others.
>
> This data analysis will focus on investigating the interrelationships between the borrower rate and the other variables in the dataset, including 
> - Features about borrowers like Employment Status, Occupation, Employment Status Duration, Income Range, Stated Monthly Income, Prosper Score, and Debt/Income Ratio.
> - Features about Loans like Loan Listing Category, Loan Original Amount, Monthly Loan Payment, Loan Term, Loan Estimated Return, and Loan Estimated Loss.


## Summary of Findings

> Loans are money borrowed and expected to be repaid within a certain time. The lenders are risking that the borrower may not repay the loan on time. Thus, they apply interest rate for bearing this risk. lenders decide the percentage of the interest rate based on several factors including the financial resources of the borrower and the loan facilities. This data analysis explores some of the variables that can influence the change of the interest rate provided by Prosper lending market through the time from 2005 to 2014.

> In Prosper market, the most common loans are debt consolidation loans, termed on 3 years with an amount that could reach to 35000 $.  Approximately 50% of loans are in progress, 33% are completed, and 4.4% are defaulted.

> In the exploration of the interest rate provided by Prosper over years, it was noticed that the borrower rate dramatically grew up in 2005 and 2006, but slightly dropped in 2007. Then, it gradually increased through the years until it reached its highest in 2011. After that, it gradually dropped again through 2012 till 2014. Furthermore, it showed a multimodal distribution with the highest spike approximately at 0.32.

> The majority of Prosper's borrowers are employed for more than a year with income range 25.000-74.999 and monthly income range 1000-20000. The debt to income ratio less than 50%, which mean consistent history of employment for the majority of borrowers.

> By investigating the factors that can influence the interest rate, the data revealed that a lower interest rate can be recieved by the customers who have high income, home owners, and who borrow high loan amount that could be repaid in a short term, these features lower the customer's risk score i.e: high Prosper score.

> On the other hand, it is worth noting that high borrower rate increases the estimated loan return, but in the opposite side, it also increases the estimated loan loss and the customer's risk i.e: low Prosper score. thus, when the market identifies a higher risk, this demands a higher rate of return.


## Key Insights for Presentation

> The presentation will start by tracking the change in the borrower rate over years, followed by a heat map showing the interactions between the borrower rate and the other numerical variables which are expected to influence it. In addition to boxplots showing the effect of the borrower income and home owning on the rate. Afterwards, the presentation will introduce multivariate plot showing the effect of the borrower rate on the estimated loss based on the risk score, in addition to a last  plot showing the association between the borrower rate, estimated return and estimated loss.


## Resources
> - www.prosper.com
> - www.investopedia.com