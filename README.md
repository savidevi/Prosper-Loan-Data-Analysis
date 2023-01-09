# (Prosper Loan Data)
## by (Savita Devi)


## Dataset

> Prosper Loan Data


## Summary of Findings

> During investing the ProsperRating (Alpha) and the ProsperScore as it relates to the BorrowerRate I could know an explanation for why the ProsperScore wasn't as highly correlated to the BorrowerRate. It is opposite the other risk features must use different criteria in coming up with its value

>A surprising interaction is that the borrower's APR and loan amount is negative correction when the Prosper ratings are from HR to B, but the correlation is turned to be positive when the ratings are A and AA. Another interesting thing is that the borrower APR decreases with the increase of borrow term for people with HR-C ratings. But for people with B-AA ratings, the borrower's APR increase with the borrowing term.

>BorrowerRate increases for longer Term loans when split up by ProsperRating. The opposite relationship would be expected as longer-term loans generally carry a lower risk profile and have a longer time to accrue interest

>In exploring how the interest rate of a loan is affected by the loans Term (length of loan) I discovered that under every ProsperRating shorter term loans had a lower interest rate. Unsurprisingly those with a higher/better ProsperRating had a lower interest rate.


## Key Insights for Presentation

>For my presentation, I am focusing on features that would impact the loan amount and borrower. I have selected key plots which effectively convey the information. These plots show the distribution of key variables such as Loan Amount, Term, Prosper Rating, and Borrower Rate. I have attempted to illustrate the major predictors of Loan Amount using the Prosper Rating and Borrower Rate variables. My goal is to tell a story about these factors and how they influence the loan data and borrower.

>The visualization shows that long term (60 month) and medium term (36 month) loans are popular among borrowers. Among these, 36 month loans are the most popular. 12 month loans are the least common among all borrowers. Rated A borrower in top position, more than 10000, in mid term loan.

>In the bivariate plot, it can be seen that borrowers with the lowest Prosper Rating (HR) have the highest Borrower Rate, which ranges from 0.3 to 0.35, with a few above 0.35. On the other hand, borrowers with the highest Prosper Rating (AA) have a Borrower Rate that ranges from 0.05 to 0.1 in most cases, but can reach up to 0.2, which is still significantly lower than the rates for the lower rated borrowers

>As the Prosper Rating improves, the Loan Amount tends to increase. At the same time, the Borrower Rate decreases. There is an inverse relationship between the Borrower Rate and the Loan Amount when the Prosper Ratings are increased from HR to A or higher. It is clear that low Prosper Ratings have an adverse effect on both the Loan Amount and the Borrower Rate. Borrowers with Ratings of B and A are among the top borrowers with low Borrower Rates.