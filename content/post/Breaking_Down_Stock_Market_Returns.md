---
date: 2023-09-01
description: "How can I Estimate Stock Market Returns? What are the Components of Stock Market Returns?"
featured_image: "uploads/Breaking_Down_Stock_Market_Returns/Breaking_Down_Stock_Market_Returns_Cover.jpg"
tags: ["Financial Models", "Financial Markets"]
title: "Breaking Down Stock Market Returns"
author: "Vasco Laranjo, CFA"
---

Forecasting stock market returns… isn’t that the goal of every investor? Many models exist to fulfill that task: some are simple, others more complex. However, an important aspect of any model is the components it includes. Moreover, model results are preferably easy to analyze, so these components should be simple to understand and easily accessible. In this article, I will introduce the Grinold-Kroner model, which can be used to break down and estimate stock market returns.

## The Grinold-Kroner model

The Grinold-Kroner model is used to estimate expected returns for a single stock or a stock market index. The model consists of four components:

1.	Expected Dividend Yield
2.	Expected Percentage change in Total Earnings
3.	Expected Percentage change in Shares Outstanding
4.	Expected Percentage change in the Price-to-Earnings (PE) ratio

<img src="https://latex.codecogs.com/svg.image?&space;Grinold-Kroner&space;model:E(R{e})=\frac{D}{P}&plus;%\Delta&space;E-%\Delta&space;S&plus;%\Delta\frac{P}{E}" title=" Grinold-Kroner model:E(R{e})=\frac{D}{P}+%\Delta E-%\Delta S+%\Delta\frac{P}{E}" />

In practice, the second and third terms can be entered into the model together, representing the earnings per share (EPS) growth rate:

<img src="https://latex.codecogs.com/svg.image?Growth&space;Rate&space;EPS=%\Delta&space;E-%\Delta&space;S" title="Growth Rate EPS=%\Delta E-%\Delta S" />

In this sense, the Grinold-Kroner model allows the breakdown of historical returns into three components: dividend yield, growth rate of EPS, and the change in the PE ratio.

## Breaking down the S&P 500® Index Total Returns

Based on the Grinold-Kroner model seen in the previous section, the chart below shows the historical breakdown of the S&P 500® Index returns into dividend yield, the growth rate of EPS, and the change in the PE ratio for every year since 1988.

{{<Breaking_Down_Stock_Market_Returns_Article/Market_Returns_Decomposition_chart>}}

###### Source: S&P Dow Jones Indices, Yahoo Finance. Period: 12/31/1988 – 12/31/2022. Past performance is not a reliable indicator of future performance.

As can be seen, there is a lot of variation, with EPS growth and the change in the PE ratio being the dominant drivers in total return. On the other hand, the dividend yield seems to have a small impact on total returns. Moreover, an inverse relationship between EPS growth and the change in the PE ratio can be observed time and again, as when one increases, the second tends to decrease. This is not always the case, as between 1995 and 1997 both components were positive at the same time. Similarly, these two variables made a positive contribution to the total returns of the S&P 500® Index in almost every year of the last decade.

Nevertheless, the graph is difficult to read because of the high values during the 2007-2008 Global Financial Crisis and the 2020-2021 recession triggered by Covid-19. In both cases, there is a steep earnings recession and a jump in the PE ratio, accompanied by a reversal the following year when earnings recover, and the PE ratio recedes.

To get a clearer picture of the contribution of EPS growth, PE ratio change, and the dividend yield to the long-term total returns of the S&P 500® Index, I decided to aggregate these results for a 5-year period. So, the chart below shows the annual average of these variables for the S&P 500® Index on a 5-year basis.

{{<Breaking_Down_Stock_Market_Returns_Article/Market_5Year_Avg_Returns_Decomposition_chart>}}

###### Source: S&P Dow Jones Indices, Yahoo Finance. Period: 12/31/1988 – 12/31/2022. Past performance is not a reliable indicator of future performance.

Over the past decade, earnings growth has been the key driver of total return, with average growth in EPS of 6% in the five years to 2022 and 6.4% in the five years to 2017. Due to an extremely low value in EPS in 2008 as a result of the Global Financial Crisis, earnings per share growth for the S&P 500® Index averaged 114.6% from 2007-2012, contributing to an average total return of 25.6% over those five years. Overall, the best five years of total return for the S&P 500® Index were the years between 1992 and 1997, with an average return of 38.78%, driven by earnings per share growth of 14.4% and an increase in the PE ratio of 10.6% per year.

## Estimating S&P 500® Index Total Returns

It has already been mentioned that the Grinold-Kroner model can also be used to estimate the returns of stock market indices. Thus, to estimate the total return of the S&P 500® Index in 2023, we need the expected values of the three components described earlier.

In terms of earnings per share, the S&P Dow Jones Indices estimates that the S&P 500® Index will have earnings per share of $200.48 at the end of 2023. This implies a 16.05% growth in earnings per share this year.<sup>1</sup>

As for the PE ratio, the preliminary value for the end of August was 25.95, a 14.6% change from the value at the end of last year. However, as shown in the chart below, this value is well above the median of 14.93 and the 90th percentile of 22.83. While it is expected that the PE ratio will return to the norm and experience a negative change in the future, it is difficult to estimate when this will be the case, so we may assume the current 14.6% annual change in our estimate.

{{<Breaking_Down_Stock_Market_Returns_Article/PE_ratio_decomposing_stock_returns_chart>}}

###### Source: multipl.com, as of May 31, 2023. Period: 1/31/1871 – 8/31/2023. Past performance is not a reliable indicator of future performance.

Finally, the dividend yield hovered around 1.5% last month, below the 10th percentile (1.8%). As we can see in the chart below, the dividend yield has been floating around the 10th percentile line for the last two decades, except for the period of the Global Financial Crisis. This might suggest that it is more likely that the dividend yield will remain at 1.8% than that it will increase to the median of 4.2%.

{{<Breaking_Down_Stock_Market_Returns_Article/Div_Yield_decomposing_stock_returns_chart>}}

###### Source: multipl.com, as of May 31, 2023. Period: 1/31/1871 – 8/31/2023. Past performance is not a reliable indicator of future performance.

In summary, with an estimated 16% growth in EPS, a change in the PE ratio of 14.6% (current value) and a dividend yield of 1.5%, we get an estimated total return of 32.1%. So far, the total return of the S&P 500® Index on a year-to-date basis is 18.7%.<sup>2</sup> This means that the S&P 500® Index could still deliver an extra 13.4% total return by the end of this year if earnings expectations materialize, the dividend yield remains unchanged and the PE ratio does not move. However, for this to be the case, the S&P 500® Index would have to remain at its current very high valuation level.

---
### Sources

<sup>1</sup> Source: S&P Dow Jones Indices as of 1 September, 2023

<sup>2</sup> Source: Yahoo Finance, period: 12/31/2022 – 8/31/2023

**Data Source:** 

[S&P Dow Jones Indices](https://www.spglobal.com/)

[Yahoo Finance](https://finance.yahoo.com/) 

[multipl.com](https://www.multpl.com/)


**Code Source:** [GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Breaking_Down_Stock_Market_Returns)

**Cover Image Credits:**  © quoteinspector / ID: 41296775165 / Flickr.com

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.