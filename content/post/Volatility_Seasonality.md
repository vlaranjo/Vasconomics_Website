---
date: 2023-08-18
description: "How does this year’s stock market volatility compare with the average year? What months experience higher volatility?"
featured_image: "uploads/Volatility_Seasonality/Volatility_Seasonality_Cover.jpg"
tags: ["Financial Markets", "Volatility"]
title: "Stock Market Volatility Seasonality"
author: "Vasco Laranjo, CFA"
---
Despite the headwinds expected in 2023, this year has been great for the stock market, with the S&P 500 posting a year-to-date return of 14.28%.<sup>1</sup>  Still, there were a number of events that could have derailed the stock market this year, from the U.S. regional banking crisis in March to the debt ceiling dispute that was settled in June. Despite all this, there was no significant increase in volatility as the VIX index did not rise above 27.<sup>2</sup>  In this article, I will compare the trajectory of the VIX index in 2023 with its average and examine its monthly seasonal patterns.

## The VIX Index

The VIX index, also known as the fear gauge, is one of the most widely used measures of stock market volatility. VIX is the ticker for the CBOE Volatility Index and is a calculation that provides a measure of the constant, 30-day expected volatility of the U.S. stock market, derived from real-time, mid-quote prices of S&P 500® Index (SPX℠) call and put options.<sup>3</sup> 

That is, the VIX measures expected volatility over the next 30 days. However, it is important to emphasize that the VIX is presented in annualized terms. Since the VIX is currently at 18, this means that market participants expect a movement of 5.2% (up or down) in the next 30 days, with a probability of 68% (one standard deviation):

<img src="https://latex.codecogs.com/svg.image?\inline&space;\frac{18}{\sqrt{12}}=5.2" title="\frac{18}{\sqrt{12}}=5.2" />

## The VIX Index: 2023 vs. Average

So far in 2023, there have been a number of events that could have driven volatility higher. First, the Federal Reserve, the ECB and the BoE continue their monetary policy tightening campaign, which began in 2022. In March, the world experienced a flashback to the Global Financial Crisis with the regional banking crisis in the US. Then in May and early June, the U.S. debt ceiling made headlines. More recently, in August, Fitch shook the markets with its downgrade of the U.S. debt rating to AA + from AAA. 

Despite all those negative events, volatility has been consistent with the average so far in 2023. As we can see from the chart below, apart from the heightened values at the start of the year and the spike in March, the VIX Index in 2023 has been in line with the average and even below during June and August.

{{<Volatility_Seasonality_Article/Volatility_Seasonality_Curve_graph>}}

###### Source: Yahoo Finance. Period: 1/1/1990 – 8/17/2023. Past performance is not a reliable indicator of future performance.

It is also interesting to note that volatility has increased recently, which is consistent with the average. As we can see, there is a tendency for the VIX index to increase after the end of the summer period. In the next section, the focus will be on identifying some seasonal trends in market volatility.

## VIX Seasonality Patterns

In a previous article ([Stock Market Returns Seasonality](https://vasconomics.com/post/stock_market_returns_seasonality/)), we saw that the worst average returns for the S&P 500 Index were in August and September. The increasing volatility mentioned in the last chart prompted me to look at the monthly averages of the VIX index.

In the chart below we can see the averages of the VIX index by month and year. As we can see, during the Global Financial Crisis in 2008, the highest values were registered in October and November, with the market remaining in “fear mode” until mid-2009. Apart from that, only during the Covid 19 outbreak in 2020 was there another really sharp increase in volatility. That being said, we can see some yellow or light green regions around the end of summer in 1990, 1998, 2001, 2002, and 2011, which explains the spike in volatility in the second half of the year seen in the previous chart.

{{<Volatility_Seasonality_Article/Volatility_Seasonality_Regular_heatmap>}}

###### Source: Yahoo Finance. Period: 1/1/1990 – 8/17/2023. Past performance is not a reliable indicator of future performance.

I also find it interesting that the bursting of the dotcom bubble in 2020 did not lead to a sharp increase in volatility in the S&P 500 Index (from which VIX's is calculated). There was some turbulence in the second half of 2001 and 2002 but far from the orders of magnitude registered in 2008 and 2020.

To better understand the seasonality of stock market volatility, the last chart shows some statistics (average, maximum and minimum values) for the VIX index. 

The earlier indication of increased volatility after the summer is well seen here, as the three months with the highest average volatility are October, September and November, respectively. Moreover, the maximum value for the VIX index was recorded in November (62.64) during the Global Financial Crisis in 2008. On the other hand, it is intriguing to see that the lowest value for the VIX was recorded in October (10.13), which is in stark contrast to the high maximum and average values in that month.

{{<Volatility_Seasonality_Article/Volatility_Seasonality_Statistics_heatmap>}}

###### Source: Yahoo Finance. Period: 1/1/1990 – 8/17/2023. Past performance is not a reliable indicator of future performance.

It is also interesting to observe that the VIX index has relatively high minimums at the start of the year, while the average volatility in these months being rather “average” (no pun intended). At the start of the year, this limited fluctuation range may suggest a cautious stance from investors who anticipate neither significant nor minor moves in the stock market. Then, summertime comes, and the living is easy as volatility clearly edges lower. Finally, the September blues seem to cause volatility in the stock market to rise again.

---
### Sources

<sup>1</sup> Source: Yahoo Finance, as of August 17, 2023

<sup>2</sup> Source: Yahoo Finance, as of August 17, 2023

<sup>3</sup> Source: Cboe Global Indices

**Data Source:** 

[Yahoo Finance](https://www.yahoofinance.com/)

**Code Source:** [GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Volatility%20Seasonality)

**Cover Image Credits:**  © izoo3y / ID: 8737004628 / Flickr.com

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.