# Prosper Dataset Exploration
## by Lana Palmer


## Dataset

> In this project I will explore a data set provided by Prosper Marketplace, a privately-held, San Francisco-based company in the peer-to-peer lending industry. My exploration is focused on the correlation between the ProsperScore (a custom risk score built using historical Prosper data), the number of investors per loan, and loan yield.


## Summary of Findings

1. ProsperScore
 Each borrower is assigned a score ranging from 1.0 (highest risk) to 10.0 (lowest risk). Lenders may use this score when choosing loans to fund. The mean ProsperScore is 5.86. 

2. Investors

The data indicates a wide range in the number of investors per loan. While the mean is 80, the standard deviation is 103, and there are outliers above 1100, with a maximum number of 1189. However, the most frequent number of investors is 1.

3. Lender Yield
Lender yield is equal to the interest rate on the loan less the servicing fee. The mean was .19, with a maximum return of .34 and a minimum of 0.03.


## Key Insights for Presentation

My analysis revealed the following:

- The median Lender Yield is much higher for a lower ProsperScore (roughly .30) than for the highest PropserScore (around 0.06).

- LenderYield and ProsperScore have a strong negative correlation (-0.64)

- LenderYield and the number of Investors have a negative correction (-0.24)

- The ProsperScore and the number of investors have a positive correlation (0.33)


This preliminary datset exploration has revealed investors who are willing to take the risk on borrowers with lower ProsperScores and fewer lenders are rewarded by higher returns. However, these borrowers are a rarity in the marketplace, with most borrowers falling in the 4.0-6.0 score range.