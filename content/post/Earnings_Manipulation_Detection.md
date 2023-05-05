---
date: 2023-05-05
description: "How can I assess the probability that a firm is manipulating earnings?"
featured_image: "uploads/Earnings_Manipulation/Earnings_Manipulation_Cover.png"
tags: ["Financial Markets", "Economy"]
title: "Earnings Manipulation Detection with Beneish M-Score"
author: "Vasco Laranjo"
---
The earnings quarterly reporting of publicly-listed companies puts enormous pressure on them to deliver continuously better results. Investors and analysts look at these figures very closely in expectation of continued growth. This pressure may lead to creative accounting practices called “earnings management”.  As we know, these practices can escalate into earnings manipulation, as in the infamous Enron and Bernie Madoff accounting scandals. In this article, I will look at a metric that assesses the likelihood of a company manipulating its earnings and apply it to the Russell 3000 Index.

## Investment Universe

Similar to the previous [article] (https://vasconomics.com/post/bankruptcy_prediction_with_altman_zscore/), I will use the Russell 3000 Index for my analysis. The Russell 3000 Index contains large-cap as well as mid- and small-cap stocks. I believe that this choice provides a more detailed view of the US market and allows for the examination of more companies that may be subject to earnings manipulation practices.

To obtain the members of the Russell 3000 Index my suggested approach is to look at an ETF that tracks that index. I propose to use the largest ETF, in terms of assets under management, that tracks the index under analysis. In this case, we will use the holdings of the iShares Russell 3000 ETF (IWV) available on iShares’ website. <sup>1</sup>


### Beneish M-Model

In order to estimate the probability that a company is misstating earnings, we will use the Beneish model. However, one drawback of the model is that it does not apply to companies in the financial services sector, so I excluded them from the analysis. 

The Beneish model provides an M-score which is then used to calculate the probability of earnings manipulation. 

So, the first step is to calculate the M-score, which is the result of a model with 8 variables:

#### DSR (Days Sales Receivable Index):

<img src="https://latex.codecogs.com/svg.image?DSR&space;=&space;&space;\frac{Receivables_{t}&space;/&space;Sales_{t}}{Receivables_{t-1}&space;/&space;Sales_{t-1}}" />

#### GMI (Gross Margin Index):

<img src="https://latex.codecogs.com/svg.image?GMI&space;=&space;&space;\frac{Gross&space;Margin_{t-1}}{Gross&space;Margin_{t}}"/>

#### AQI (Asset Quality Index):

<img src="https://latex.codecogs.com/svg.image?AQI=&space;&space;\frac{[1&space;-&space;(PPE_{t}&space;&plus;&space;Current&space;Assets_{t})/Total&space;Assets_{t}]}{[1&space;-&space;(PPE_{t-1}&space;&plus;&space;Current&space;Assets_{t-1})/Total&space;Assets_{t-1}]}"/>

#### SGI (Sales Growth Index):

<img src="https://latex.codecogs.com/svg.image?SGI&space;=&space;&space;\frac{Sales_{t}}{Sales_{t-1}}"/>

#### DEPI (Depreciation Index):

<img src="https://latex.codecogs.com/svg.image?DEPI&space;=&space;&space;\frac{Depreciation&space;Rate_{t-1}}{Depreciation&space;Rate_{t}}"/>

,where:

<img src="https://latex.codecogs.com/svg.image?Depreciation&space;Rate&space;=&space;&space;\frac{Depreciation_{t}}{(Depreciation_{t}&space;&plus;&space;PPE_{t})}"/>

#### SGAI (Sales, General, and Administrative Expenses Index):

<img src="https://latex.codecogs.com/svg.image?SGAI&space;=&space;\frac{SGA_{t}&space;/&space;Sales_{t}}{SGA_{t-1}&space;/&space;Sales_{t-1}}"/>

#### Accruals:

<img src="https://latex.codecogs.com/svg.image?Accruals&space;=&space;\frac{Income&space;from&space;Current&space;Operations_{t}&space;-&space;Cash&space;from&space;Operations_{t}}{Total&space;Assets_{t}}"/>

#### LEVI (Leverage Index):

<img src="https://latex.codecogs.com/svg.image?LEVI&space;=&space;\frac{Leverage_{t}}{Leverage_{t-1}}"/>

,where:

<img src="https://latex.codecogs.com/svg.image?Leverage&space;=&space;\frac{Total&space;Debt_{t}}{Total&space;Assets_{t-1}}"/>

To obtain the score of the model for each company, the values for these ratios must be input in the following formula:

<img src="https://latex.codecogs.com/svg.image?M-Score&space;=&space;-4.84&space;&plus;&space;0.920&space;\times&space;DSR&space;&plus;&space;0.528&space;\times&space;GMI&space;&plus;&space;0.404&space;\times&space;AQI&space;&plus;&space;0.892&space;\times&space;SGI&space;&plus;&space;0.115&space;\times&space;DEPI&space;-&space;0.172&space;\times&space;SGAI&space;&plus;&space;4.679&space;\times&space;Accruals&space;-&space;0.327&space;\times&space;LEVI"/>

Since the M-score is a normally distributed random variable, we need to use the cumulative probabilities for the standard normal distribution to obtain the probability of earnings manipulation:

<img src="https://latex.codecogs.com/svg.image?&space;Probability&space;of&space;Earnings&space;Manipulation&space;=&space;N(&space;X&space;<=&space;Beneish&space;M-Score)"/>

Finally, the threshold for a high probability of earnings manipulation is 3.8%. That is, if the probability is higher than 3.8%, then it is likely that the company is manipulating earnings.

### From Theory to Practice

Now that we know how the Beneish M-Score is calculated, it is time to get the data and calculate it for each company in the Russell 3000 Index. We will use Yahoo Finance to gather the data and base the analysis on the latest available annual data as many data points are calculated based on the annual change in variables. Since not every company has released March 2023 results yet, we will most likely be using December 2022 financial data, so it makes more sense to use the members of Russell 3000 Index at that time. This is not a problem as iShares still has the 30 December2022’s IWV holdings available on its website.

Let’s start with the analysis of the top 10 holdings, the 10 largest companies (excluding Financials) in our defined universe:

{{<Earnings_Manipulation_Article/Beneish_MScore_Top10_Companies>}}

In this table we see that none of the companies exceeds the 3.8% threshold for the probability of manipulation. Not even close to it! So it appears that none of the largest companies in the Russell 3000 Index are manipulating their earnings results.

### Were the Bankrupt Companies Manipulating their Earnings Results? <sup>2</sup>

To obtain the list of bankruptcies, I used the Stock Analysis website. <sup>3</sup> Below is the table of companies that have filed for bankruptcy, with the corresponding Beneish M-score and probability of manipulation. Note that the number of companies in this table is limited compared to the Stock Analysis table because the Beneish M-score requires many data points that were probably not available in Yahoo Finance for these companies.

{{<Earnings_Manipulation_Article/Beneish_MScore_Bankrupt_Companies>}}

Here we see that 5 of the 18 companies in the table present a probability of manipulation above 3.8%. This represents only 28% of the companies, and much less than the 64% that reported a high probability of default in the last article. Therefore, it does not seem necessary for companies heading for default to be manipulating their earnings figures. Even more interesting is the dispersion in the results. We see that companies either have a very high probability of manipulation (2 companies with 100%) or a low probability of manipulation (11 companies with less than 1%).

### The Manipulators

In this concluding section, I present a table of all companies classified as having a high probability of earnings manipulation (>3.8%).

{{<Earnings_Manipulation_Article/Beneish_MScore_High_Prob_Manipulation_Companies>}}

Out of the entire universe of 1,813 companies, 222 of them are classified as having a high probability of earnings manipulation, which corresponds to 12%. That is in stark contrast to the probability of default (excluding financials) we obtained in the last article, which corresponded to 36%. Accordingly, it looks like the propensity for earnings manipulation is 3 times lower than that for default. These figures should be reassuring in that we as analysts can trust the financial results presented by companies.

Overall, given the recognition in the financial industry and the results achieved, I believe that the Beneish M-score can be a good tool to identify red flags and support risk management in investment decisions.

### Table with All Companies and corresponding Beneish M-score values 

{{<Earnings_Manipulation_Article/Beneish_MScore_All_Companies>}}

---
### Sources

<sup>1</sup> Source: iShares. https://www.ishares.com/us/products/239714/ishares-russell-3000-etf

<sup>2</sup> According to the Beneish M-score.

<sup>3</sup> Source: Stock Analysis. https://stockanalysis.com/actions/bankruptcies/2023/

**Data Source:** 

[Yahoo Finace] (https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Earnings%20Manipulation%20Detection%20with%20Beneish%20M-Score)

**Cover Image Credits:**  © messomx / ID: 1244459 / Pixabay.com