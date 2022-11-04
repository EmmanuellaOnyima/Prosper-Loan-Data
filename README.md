## Loan Data From Prosper Exploration

## Dataset

This dataset contains 113,937 loan entries with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This exploration will involve the use of 14 variables which will be a subset of the original dataset. The prosper loan dataset can be found [here]( https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.)


## Summary of Findings

In the exploration, I discovered the following insights:
>- Higher population (60.3%) of the Borrowers are employed.
>- The MonthlyLoanPayment is right skewed with more people paying about 170 - 200 dollars monthly.
>- 51.2% of the Borrower's collected the loan for Debt consolidation, that is taking out a new loan to pay off other liabilities and consumer debts.
>- More borrowers tend to have a prosperscore of 4, 6, and 8 of 14.84%, 14.47%, and 14.20% respectively, this means that there are few borrowers with high prosperscore.
>- 28% of the borrowers are within the income range of 25,000 - 49,999, while 27% are within the 50000-74999 range. This implies that more borrower's are in the lower income range.
>- The Debt-to-Income-ratio distribution chart shown above is right skewed, and it describes that most of the borrowers spend 20-25% of their monthly income on paying debts.
>- CA has the highest number of Borrowers.
>- After the year 2005, the BorrowerRate increased from 0.08 to 0.26 in 2010 which then started decreasing till 2014.
>- People who obtained loan for debt consolidation and are employed showed high rate of completing their loans.
>- Borrowers with completed and current loanStatus show to have lower BorrowerRate, while those of the pastDue, Defaulted, and chareged off have higher BorrowerRates.
>- Most of the Loan term appeared to be mostly within 30 - 40 months with little spread occuring at 60 months for the current loan. The Loan term does not affect the loanstatus.

From all the explorations(univariate, bivariate and multivariate) carried out, it is seen that higher loans with lower rates are been given to people with higher prosper score. These people with lower borrower rate are also seen to be homeowners. The same thing applies to the BorrowerAPR as it is strongly positively correlated to the BorrowerRate. Looking at the loanstatus, it is also observed that people who completed their loan payments are mostly people with lower borrower rate, and the LoanStatus is not affected by the term of the loan.

## Key Insights for Presentation

For the presentation, I focused on the features affecting the BorrowerRate, BorrowerAPR, and the LoanStatus. I started by  checking the pattern of distribution of the variables of interest, then I investigated their relationship with other variables which could influence their values at each point.
I made use of different chart typessuch as the boxplot, violinplot, barchart, histograms, scatter plot, and heatmaps depending on the data types of the variables I am plotting.





```
