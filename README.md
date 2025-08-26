# macroeconomic-data-project

Investigating the difference between safe and risky corporate borrowing rates may inform us about recessions. In this project, I obtained monthly data on two U.S. bond yields, Moody’s Aaa rate and Moody’s Baa rate, and calculated the interest rate spread between them. I combined the spreads' monthly figures with unemployment, industrial production, consumer prices, and the Federal Funds Reserve’s (FFR) main policy rate, creating a timeline from their earliest dates to December 2024. All data came from the Federal Reserve’s Economic Database (FRED), ensuring credibility and reproducibility.

Using regression analysis, I tested how each economic factor affects the spread. I also added an indicator for the 2007 to 2009 Great Recession to see whether that extreme episode altered the usual relationships.

When either unemployment rises, inflation accelerates, or the FFR lifts its policy rate, the spread widens, resulting in investors demanding a bigger premium to hold riskier debt. When the economy expands, the gap narrows again. The business cycle calculated captures this inverse relationship. The spread spiked during every post-war recession, most dramatically in 2008 and again in early 2020 when COVID-19 froze activity, then fell back as the FFR cut rates.

The model produced an R<sup>2</sup>-value of 0.63, suggesting that unemployment, inflation, factory output, and the FFR’s policy rate explain about two-thirds of the monthly movement in the spread. The remaining third reflects shifts in financial market response or global events, an area for future work that could use direct measures of market stress or a more detailed crisis timeline.

Since the spread consistently moves first, it can potentially serve as an early warning. Businesses, investors, and policymakers can observe the spread and gain advanced notice that borrowing costs are about to rise and that broad economic turmoil, like recessions or financial crises, may be developing well before official confirmation.
