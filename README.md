# Loan Data Exploration
## by Owan Ayuk Daisy A.


## Dataset

 This document explores a data set containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, amongst several others.


## Summary of Findings

- LoanStatus has a long-tailed distribution, with a lot of loans being completed and current, and very few being due past 15 days. The distribution looks roughly bimodal, with one peak at the current status, and a second peak a chargedoff.
- BorrowerRate has a short-tailed distribution, with the fewest loans on the low BorrowerRate end,increasing as the rate increases to the mid BorrowerRate end and then decreasing as the BorrowerRate increases but yet having an exceptionally high count at 0.3 before decreasing again as the rate increases. When plotted on a linear-scale, the Rate distribution looks roughly bimodal, with one peak between 0.1 and 0.2, and a second peak a little above 0.3. Interestingly, there's a steep jump in frequency almost at 0.3, rather than a smooth ramp up.
- Most loan takers have a ProsperScore lower than average with a greater proportion of users have a score above 5.
- Loans with really high BorrowerRates are either completed,charged off or defaulted.
- Most Loans have a term of 36 months
- A strong positive correlation was observed between BorrowerRate and BorrowerAPR, with a mild relation between BorrowerRate and LoanStatus
## Key Insights for Presentation
- I chose to depict these findings because of the ample time spent on them to properly analyse and visualise the relationship observed with the concerned variables i.eBorrowerRate, BorrowerAPR, LoanStatus, Term and ProsperScore