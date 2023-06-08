---
date: 2023-05-29
description: "How has the top 10 companies in the S&P 500 Index changed over time? What does that say about diversification?"
featured_image: "uploads/Diversification_Top_10_Holdings_SP500/Diversification_Top_10_Holdings_SP500_Cover.jpg"
tags: ["Financial Markets", "Diversification"]
title: "Diversification Part I: An Analysis of the S&P 500 Index Top 10 Holdings"
author: "Vasco Laranjo, CFA"
---
Diversification is the number one rule of portfolio management for many investors. Ray Dalio goes even further calling it the Holy Grail of investing. Colloquially, this is expressed by the idiom “do not put all your eggs in one basket”. In the stock market, this year’s returns in the S&P 500® Index appear to have been concentrated in the stocks with the highest market capitalization. Consequently, these stocks exhibit a higher weight in the index, making it more concentrated, which is contrary to the diversification objective. In this article, I will analyze the historical evolution of the 10 largest companies in the S&P 500® Index to get an idea of its diversification characteristics. In the next article, I will present a more formal metric to measure portfolio concentration.

## Year-to-Date Performance

So far, we have heard that this year has been particularly good for mega-cap stocks. By mega-cap, I mean the companies with particularly large market capitalization such as Apple, Microsoft, Amazon, and the late darling of investors, Nvidia. 

To get an idea of the outperformance of these largest companies in the S&P 500® Index, I decided to compare the performance of an ETF made up of the 50 largest companies in the index – XLG – with that of an ETF that includes all companies – IVV. As you can see from the chart below, XLG has outperformed IVV by more than 10% so far, which is more than double the return (20.32% vs. 9.82%).<sup>1</sup>

{{<Diversification_Top_10_Holdings_SP500_Article/XLG_vs_IVV_Graph>}}

###### Source: Yahoo Finance as of May 26, 2023. Past performance is not indicative of future results.

### The Current Top 10 Picture

The S&P 500® Index is arguably the most widely followed stock index in the world and is commonly referred to as the market. Because it contains the 500 largest U.S. companies from all sectors of the economy, one of its perceived qualities is that of diversification. However, since the weighting of its holdings (stocks) is determined based on their market capitalization, significant outperformance of the stocks with the highest market capitalization relative to their smaller counterparts leads to a higher concentration in the former.

With this in mind, the recent outperformance of the 50 largest stocks in the S&P 500® Index led me to wonder about the weighting of its 10 largest stocks. Accordingly, the next table shows the top 10 stocks in IVV, an ETF that tracks the S&P 500® Index.

{{<Diversification_Top_10_Holdings_SP500_Article/Current_SP500_Top10_Companies>}}

###### Source: iShares.com, Yahoo Finance as of May 26, 2023. Past performance is not indicative of future results.

Here we see that the combined weight of the 10 largest companies in the index is 31.5%, nearly one-third of the total allocation.<sup>2</sup> Moreover, the performance of these 10 companies contributed to about 15.5% of the index’s return meaning that the remaining companies had a negative contribution of roughly -5.7%, given that IVV’s YTD return was 9.82%.<sup>3</sup>

In my opinion, this result suggests a concentrated portfolio rather than a diversified one. But has the S&P 500® Index always been like this?

### Evolution of the Top 10 Weighting in the S&P 500®

Surprised by the results of the previous section, I decided to look at them from a historical perspective. If it is already not easy to gather the current holdings of an index (and that is why I resort to the holdings of ETFs), it is even more difficult to get historical holdings. EDGAR, however, the database that collects the data companies are required to file with the SEC, has IVV’s holdings data from the end of 2005 onward. While this is good news, obtaining data from EDGAR is quite time consuming, so I have limited this analysis to annual data.

{{<Diversification_Top_10_Holdings_SP500_Article/Historical_Top10_Weights>}}

###### Source: U.S. Securities and Exchange Commission EDGAR database, as of May 26, 2023.

This chart shows the historical evolution of the weighting of the top 10 holdings in IVV. As can be seen from the chart, the combined weighting hovered around the 20% mark until the end of 2016. However, from 2016 onwards, a relentless increase in the combined weighting was observed, reaching 30% only in 2021 and then again now, currently standing at 31.16%. 

In 2022, with the bear market that followed the start of the Fed’s monetary tightening campaign, there was a significant drop in the combined weight of the top 10 holdings to 25.5%. This contrasts with the results from 2008, when the combined weight increased from 20% to 22.34% in the wake of the global financial crisis. Thus, it seems difficult to establish a link between performance and concentration, considering not only what has just been said, but also the fact that the year with the highest returns in this period was 2013 (29.60%),<sup>4</sup> in which concentration decreased by about -1.5%.

### Historical S&P 500® Top 10 Weighting

In this final section, I present a dynamic table of the top 10 holdings in IVV for each year since 2005. What I find most interesting is the ongoing battle between Apple and Amazon for the top spot on the podium and Exxon’s return to the top 10 after a three year absence (2019-2021). Can Exxon steal the show and take the top spot once again? 

Leave your opinion and assessment in the comment section below and stay tuned for the next article where I will discuss a more formal measure of concentration in a portfolio!

{{<Diversification_Top_10_Holdings_SP500_Article/Historical_SP500_Top10_Companies>}}

###### Source: iShares.com, U.S. Securities and Exchange Commission EDGAR database, as of May 26, 2023.

---
### Sources

<sup>1</sup> Source: Yahoo Finance as of May 26, 2023. Past performance is not indicative of future results.

<sup>2</sup> Source: iShares.com as of May 26, 2023.

<sup>4</sup> Source: Yahoo Finance as of May 26, 2023. Past performance is not indicative of future results. Please note that the results presented correspond to an approximation. These returns were calculated based on the weighted average returns of each stock. For a more correct calculation of the contribution of the returns, it is usually recommended to use linking and smoothing methods.

<sup>4</sup> Source: Macrotrends LLC as of May 26, 2023.

**Data Source:** 

[Yahoo Finance] (https://finance.yahoo.com/)

[iShares.com] (https://www.ishares.com/us/products/239726/ishares-core-sp-500-etf)

[U.S. Securities and Exchange Commission EDGAR database] (https://www.sec.gov/edgar)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Diversification%20-%20Top%2010%20Holdings%20SP500)

**Cover Image Credits:**  © lincolnblues / ID: 5778327625/ Flickr.com

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.