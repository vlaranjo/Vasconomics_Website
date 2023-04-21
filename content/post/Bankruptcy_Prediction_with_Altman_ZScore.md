---
date: 2023-04-21
description: "How can I assess the probability that a firm will file for bankruptcy?"
featured_image: "uploads/Bankruptcy_Prediction_with_Altman_ZScore/Bankruptcy_Prediction_with_Altman_ZScore_Article_Cover.jpg"
tags: ["Financial Markets", "Economy"]
title: "Bankruptcy Prediction with Altman Z-Score"
author: "Vasco Laranjo"
---
“Recession” seems to be one of the most debated topics since mid-2022. As the economic slowdown concerns were gradually easing at the start of the year, last month’s global banking crisis helped refuel those fears again. While the recession doesn’t come, it might be prudent to get ready for it. And what happens when we enter a recession? Bankruptcies… In this article, I will look at a measure that assesses the probability that a firm will file for bankruptcy and apply it to the Russell 3000 Index.

### Storm Clouds Gathering?

In July of 2022, US GDP data indicated a technical recession with the real GDP contracting for two consecutive quarters. The labor market remained strong, so experts turned to GNI figures to support the notion that there was no recession. Fast forward more than half a year and the recession hasn’t arrived yet, but now banks are failing, notably Silicon Valley and Signature Bank in the US and Credit Suisse in Europe.

The Conference Board recession probability model estimates a near 99 percent likelihood of a recession in the US within the next 12 months. <sup>1</sup> The Federal Reserve Bank of New York also has a recession probability model of its own based on the Treasury spread: the 10-year bond rate minus the 3-month bill rate. <sup>2</sup> The latest values for the model, which also estimates the probability of a recession 12 months ahead, point to a 58% probability of a recession in March 2024.

{{<Bankruptcy_Prediction_Article/Bankrupcy_Article_Recession_Probability>}}

Having that in mind, I found it important to investigate which companies are more prone to file for bankruptcy so that we can protect ourselves from that risk in advance.

## Investment Universe

Typically, I use the S&P 500 Index in my analysis. However, this time I decided to broaden the analysis and include a wider range of companies, so I will use the Russell 3000 Index. Note that the S&P 500 Index only includes large-cap companies, those are the 500 largest publicly traded US companies (subject to additional criteria, including positive earnings in the most recent quarter). On the other hand, in addition to large-cap, the Russell 3000 Index also includes mid- and small-cap companies. I believe this choice will provide a more granular view of the US market and allow for the investigation of more companies that may be on the edge of having some serious financial issues.

Now, to obtain the members of the Russell 3000 Index my suggested approach is to look at an ETF that tracks that index. I suggest using the largest ETF, in terms of assets under management, that tracks the index under analysis. In this case, we will use the holdings of iShares Russell 3000 ETF (IWV) that are available on iShares’ website. <sup>3</sup> 

### Altman Z-score

One of the most widely used measures used to assess the probability that a firm will file for bankruptcy is the Altman Z-score. In his studies, Altman applied the z-score to publicly traded manufacturing companies. This score comes as a result of a model comprising 5 financial ratios:

A. Liquidity: Net Working Capital/Total Assets

B. Accumulated Profitability: Retained Earnings/Total Assets

C. Profitability: EBIT/Total Assets

D. Leverage: Market Value of Equity/Book Value of Liabilities

E. Activity: Sales/Total Assets

To obtain the score of the model for each company, the values for these ratios must be input in the following formula:

<img src="https://latex.codecogs.com/svg.image?&space;Altman&space;Z-Score&space;=&space;1.2&space;\times&space;A&space;&plus;&space;1.4&space;\times&space;B&space;&plus;&space;3.3&space;\times&space;C&space;&plus;&space;0.6&space;\times&space;D&space;&plus;&space;1.0&space;\times&space;E" />

Finally, when it comes to the interpretation: a higher Z-score is better. A score above 3.00 is considered to indicate a low probability of bankruptcy while a score below 1.81 is an indication of a high probability of bankruptcy. If the score is between 1.81 and 3.00, it is considered to be inconclusive:

<iframe src="https://latex.codecogs.com/svg.image?\inline&space;&space;Default&space;\&space;Probability&space;\left\{\begin{matrix}&space;>3&space;\rightarrow&space;Low&space;\\&space;1.81&space;>&space;and&space;<&space;3&space;\rightarrow&space;Inconclusive&space;\\&space;<1.81&space;\rightarrow&space;High&space;\\&space;\end{matrix}\right." width="400" height="75" frameborder="0" ></iframe>

### From Theory to Practice

Now that we know how the Altman Z-score is computed, it is time to get the data and calculate it for each company in the Russell 3000 Index. We will use Yahoo Finance to gather the data and base the analysis on December’s 2022 values (or the latest available before March 2023), since only a few companies have issued March 2023 results so far. Note that since we are using December’s 2022 financial data, we also need to use Russell 3000 Index members at that time. That is not a problem, since iShares has IWV’s December 30, 2022’s holdings still available on their website. 

Let’s start with analyzing the top 10 holdings, the largest 10 companies in our defined universe:

{{<Bankruptcy_Prediction_Article/Altman_ZScore_Top10_Companies>}}

From this table, we see that none of the companies, apart from financials, are classified as having a high probability of default. For example, Apple with a score of 6.47 is well above the threshold value of 3. Curiously, Amazon shows an inconclusive result but its 2.95 score is sufficiently close to 3, so I would disregard it for now. When it comes to financials, it is important to note that the Altman Z-score was developed having in mind manufacturing companies, therefore, I believe it might not be well-applied to financials. In fact, one of the measures required for the z-score calculation is net working capital which does not apply to that sector.

Let’s move on and look at how well the Altman Z-score did in predicting the bankruptcy filings that have occurred so far in 2023.

### How is 2023 Looking so Far?

In getting the list of bankruptcies, I used the Stock Analysis website. <sup>4</sup> Below is the table with the companies that filed for bankruptcy with the corresponding Altman Z-score and Probability of Default note.

{{<Bankruptcy_Prediction_Article/Altman_ZScore_Bankrupt_Companies>}}

In this table, we see that scores of 27 out of 42 companies were pointing to having a high probability of default. That is equivalent to 64% of the companies. To be honest I was expecting the model would fare a little bit better. Still, it got more than half of the instances, so I see value in it when exploring potential red flags in investments.

### Danger Zone

Finally, in this closing section, I will present a table with all the companies that are classified as having a high probability of default.

{{<Bankruptcy_Prediction_Article/Altman_ZScore_High_Prob_Default_Companies>}}

From the entire universe of 2,530 companies, 1,119 of them are classified as having a high probability of default, which corresponds to 44%. In the analysis, 86% of the financials are rated as having a high probability of failing. This is an extremely high number, and it is highly unlikely that such a high number of US financial institutions would fail, so I decided to also analyze these statistics without including this sector. In the universe excluding financials, 36% of the companies obtained a high probability of default. 

All in all, given its recognition within the financial industry and the results from the “How is 2023 Looking so Far?” section, I believe that the Altman Z-Score may provide guidance in raising red flags and help limit risk in investment decisions, especially in the upcoming uncertain times.

### Table with All Companies and corresponding Altman Z-score values

{{<Bankruptcy_Prediction_Article/Altman_ZScore_All_Companies>}}

---
### Sources

<sup>1</sup> Source: The Conference Board, April 12, 2023. “Probability of US Recession Remains Elevated”. https://www.conference-board.org/research/economy-strategy-finance-charts/CoW-Recession-Probability

<sup>2</sup> Source: Federal Reserve Bank of New York, The Yield Curve as a Leading Indicator, https://www.newyorkfed.org/research/capital_markets/ycfaq.html

<sup>3</sup> Source: iShares. https://www.ishares.com/us/products/239714/ishares-russell-3000-etf

<sup>4</sup> Source: Stock Analysis. https://stockanalysis.com/actions/bankruptcies/2023/

**Data Source:** 

[Federal Reserve Bank of New York] (https://www.newyorkfed.org/research/capital_markets/ycfaq.html)

[Yahoo Finace] (https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Bankruptcy%20Prediction%20with%20Altman%20Z-Score)

**Cover Image Credits:**  © Jernej Furman / ID: 52368890939 / Flickr.com