# (Prosper Loan Dataset Exploration)
## by (Amani Alfaifi)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

> it shows that the histogram has at least three peaks, it's slightly skewed to the right. The very popular Original Loan amount was around 4000 dollars, with others varying between 10,000 and slightly more than 15000 dollars.

>Multimodal with a height of 0.1 to 0.3. There are very few loans with interest rates higher than 0.35 percent. The borrower's interest rate frequency is fairly distributed around the mean interest rate (0.15%).

>The loan term figure revealed that the majority of customers were issued a 36 month loan term, with 12 month loans being the least common.

> it shows that the majority of the loans in the dataset are Current, followed by Completed, Chargedoff, and Defaulted 

>It appears that the frequency of stated income corresponds to the verifiable income. The figure, on the other hand, revealed that the majority of the income was verifiable.

>The APR distribution appears to be multimodal. A small peak at 0.06, followed by a large peak at 0.18. A small peak centered at 0.28 and a high peak between 0.35 and 0.36 are also present. Few people have an APR of more than 0.4.

> it shows that the distribution is multi-modal, with some peaks. The majority of debt-to-income ratios are less than 0.2. There aren't many people who have a high debt-to-income ratio.

>Most monthly payments are between 0 and 500 

>The income level between 25,000 and 49,999 has the most borrowers.

> the "original loan amount" and "rate" have a mildly negative correlation, showing that a larger loan amount might result in a lower interest rate.

> The scatter plot also demonstrates that the borrower APR and loan Original amount have a negative correlation of -0.322, meaning that the lower the APR, the higher the loan amount.

> A high APR will typically result in borrowers paying more interest on their loans, so the significant association between "BorrowerAPR" and "BorrowerRate" of 0.99 makes sense.

> With a longer loan term, the loan amount typically increases.

> We can see from these boxplots that the greatest median Borrower rate is in the income range of 1–24,999k. It deviates from the pattern of income ranges over $25,000, where the median borrower rate falls as income rises.

> The income range of 25,000 - 49,999 are more verifiable followed by the 50,000 - 74,999 income range.

> the loan term may be impacted by the status of the IncomeVerifiable.

>Relationship between LoanOriginalAmount and BorrowerRate while considering Term, It turns out that LoanOriginalAmount and BorrowerRate are related to each other and are slightly affected by Term


## Key Insights for Presentation

> For the presentation, I concentrated on the factors that could affect the borrower's original loan amount.

