---
date: 2023-06-08
description: "Is the S&P 500 Index concentrated? How has its concentration risk changed over time?"
featured_image: "uploads/Diversification_Effective_Number_Stocks/Diversification_Effective_Number__Stocks_SP500_Cover.jpg"
tags: ["Financial Markets", "Diversification"]
title: "Diversification Part II: An Analysis of the S&P 500 Index Effective Number of Stocks"
author: "Vasco Laranjo, CFA"
---
Diversification is one of the most important rules of investing and sometimes investors believe their allocations are more diversified than they are. In the previous article, I introduced the topic of diversification using the top 10 largest stocks in the S&P 500® Index. Now I will introduce a more formal measure of concentration risk, the effective number of stocks, and examine its historical evolution. In addition, this article will present an index weighting method that is an alternative to market capitalization to reduce concentration risk. 

## The S&P 500® Equal-Weighted Index

As described in the previous [article](https://vasconomics.com/post/diversification_top_10_holdings_sp500/), the S&P 500® Index is a market capitalization weighted index, which means that the weighting of its holdings (stocks) is determined based on their market capitalization. As a result, significant outperformance of stocks with the highest market capitalization relative to their smaller counterparts leads to higher concentration in the former. 

An alternative to market capitalization is equal weighting. In this case, each stock is given equal weight. One of the complications associated with this weighting method is that as stock prices change, so do their weights, requiring rebalancing. Accordingly, the index is rebalanced at a certain frequency (e.g. quarterly), meaning that the weighting of the stocks in the index is changed so that all stocks have the same weight again. In the case of the S&P 500® Index, this would mean that each stock is given a weight of 1/500 = 0.20%.

With this in mind, after the index rebalancing, we expect the top 10 stocks to account for 2% (0.2% x 10) of the total index weight. This is in stark contrast to the cumulative weight over 30% that the top 10 stocks currently have in the S&P 500® Index. To obtain the current holdings for these indexes, ETFs will be used. Accordingly, the following table shows the top 10 stocks of IVV and RSP, which are ETFs that track the S&P 500® Index and the S&P 500® Equal Weight Index, respectively.

{{<Diversification_Effective_Number_Stocks_Article/Current_IVV_RSP_Top10_Companies>}}

###### Source: iShares.com, Invesco.com as of June 6, 2023.

Note: The S&P 500® Equal Weight Index Methodology is rebalanced on a quarterly basis<sup>1</sup>

### Market Breadth

Market breadth is a way of describing the _extent of a move_ in an index when looking at the number of stocks moving in the same direction. There are several indicators of market breath, such as the Advance-Decline (A/D) line, the New Highs-Lows Index, the Percent of Companies Trading Above 200-DMA, etc. However, a simple way to measure market breadth for the S&P 500® Index is to calculate the relative performance of its market cap index versus the equal weight one.

{{<Diversification_Effective_Number_Stocks_Article/RSP_vs_IVV_Graph>}}

###### Source: Yahoo Finance as of June 6, 2023. Past performance is not indicative of future results.

In this chart, we see the one-year performance of IVV, RSP and the relative performance of IVV over RSP. As we can see, the performance of both ETFs was consistent until early March, as the maximum difference was about ±2%. However, from March onward the market cap weighted version (IVV) started a period of strong outperformance, which is now around 6%. Overall, RSP is still posting one-year losses, while IVV is already more than 5% above its level of one year ago. This result is in line with current claims that the current market rally lacks breath, leading to higher concentration in the S&P 500® Index.

### Effective Number of Stocks

The effective number of stocks is a measure that can be used to estimate the degree of stock concentration in a portfolio. An index that has a low effective number of stocks may be considered less diversified than one with a higher number.

To calculate the Effective Number of Stocks, we need first to have calculate the Herfindahl-Hirschman Index (HHI):

<img src="https://latex.codecogs.com/svg.image?&space;HHI&space;=&space;\sum_{k=1}^{n}w_{i}^{2}"/>

Then the Effective Number of Stocks is:

$$Effective Number of Stocks = \frac{1}{HHI}$$

<img src="https://latex.codecogs.com/svg.image?Effective&space;Number&space;of&space;Stocks&space;=&space;\frac{1}{HHI}"/>

As we can see from the equations above, in the case of the equally weighted index, we expect the effective number of stocks to be the same as the underlying stocks in the index. In practice, the effective number of stocks for RSP is currently 492, just under 500, while this figure for IVV is 61, illustrating the high level of concentration exhibited that the S&P 500® Index currently has.
Similar to the previous article, I think it is important to look at this value from a historical perspective, so we compare the current effective number of stocks for IVV with the values from previous years.


{{<Diversification_Effective_Number_Stocks_Article/Historical_Effective_Number_Stocks>}}

###### Source: iShares, U.S. Securities and Exchange Commission EDGAR database, as of June 6, 2023.

This chart shows the historical trend in the effective number of stocks for IVV from 2005. As we can see, there was a period of increasing concentration in 2008 during the global financial crisis, when the number fell from 122 in 2007 to 103 in 2008. Thereafter, the S&P 500® Index returned to its previous level of concentration and remained relatively stable between 2009 and 2017. However, starting in 2018, we observed a steep decline in the effective number of stocks which currently stands at 61. This is less than half of the 131 at the end of 2005, thus, advising additional caution!

### Concluding Remarks

Diversification is one of the most important rules in investing. It is important to understand that investing in an index with a large number of stocks does not equate to great diversification, as we have just seen. This is not to say that the S&P 500 Index is not diversified, as 61 stocks is more than most investors would own on an individual basis. Nevertheless, it is important to note that the recent outperformance of the largest cap stocks has resulted in the index being more concentrated than in the past.

Many speak of secular changes developing in the wake of the Covid-19 pandemic, climate change agreements (e.g. Paris Agreement), etc. Will this allow other companies to take the stage or will giants, like Apple, continue to dominate the global arena? Leave your opinion and assessment in the comment section below!

---
### Sources

<sup>1</sup> Source: S&P Dow Jones Indices. S&P 500 Equal Weight Index Methodology

**Data Source:** 

[Yahoo Finance] (https://finance.yahoo.com/)

[iShares.com] (https://www.ishares.com/us/products/239726/ishares-core-sp-500-etf)

[Invesco.com] (https://www.invesco.com/us/financial-products/etfs/product-detail?audienceType=Investor&ticker=RSP)

[U.S. Securities and Exchange Commission EDGAR database] (https://www.sec.gov/edgar)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Diversification%20-%20Effective%20Number%20of%20Stocks)

**Cover Image Credits:**  © QuoteInspector.com/ ID: 41296774515 / Flickr.com

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.