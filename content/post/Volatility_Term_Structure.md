---
date: 2023-08-22
description: "What is the Volatility Term Structure? What can it indicate?"
featured_image: "uploads/Volatility_Term_Structure/Volatility_Term_Structure_Cover.jpg"
tags: ["Financial Markets", "Volatility"]
title: "Volatility Term Structure"
author: "Vasco Laranjo, CFA"
---

Volatility is a significant force in financial markets. The CBOE Volatility Index (VIX) is the most well- known measure of market sentiment. The introduction of VIX futures in 2004 enabled market participants to express their estimates of market volatility at various expiration dates.<sup>1</sup> This allowed the development of a term structure curve for volatility. In this article, I introduce the topic of the volatility term structure and analyze how it can be used.

## The Volatility Term Structure

In the previous article ([Stock Market Volatility Seasonality]( https://vasconomics.com/post/volatility_seasonality/)), the topic of stock market volatility was discussed. Stock market volatility is typically measured by the VIX index that provides a measure of the constant, 30-day expected volatility of the U.S. stock market, derived from real-time, mid-quote prices of S&P 500® Index (SPX℠) call and put options.<sup>2</sup> Now, we will go one step further and examine the concept of volatility term structure. 

The volatility term structure is a curve that shows the different values for the VIX index futures on different expiration dates. The CBOE Futures Exchange℠ introduced the VIX futures in 2004, providing market participants with the ability to trade a liquid volatility product.<sup>3</sup>

A futures contract is an obligation to buy or sell an underlying asset, in this case the volatility index, at a specified expiration date. In practise, this means that an investor taking a long position (buying) in VIX index futures with a maturity of five months will buy the VIX index at the future current level in five months. Accordingly, the profit or loss is the difference between the VIX index price on the expiration date and the price of the futures contract at entering. Thus, the price of the futures contract indicates the implied volatility that market participants expect on a given date (the expiration date). Below is a chart showing the current volatility term structure curve from VIX index futures:

{{<Volatility_Term_Structure_Article/Latest_VIX_Term_Structure_Curve_Graph>}}

###### Source: Cboe Global Indices, as of August 21, 2023. Past performance is not a reliable indicator of future performance.

As we can see from the chart, the VIX index futures expiring this month imply a level of 17.85. As the curve progresses, the levels increase, with the contract expiring in eight months currently sitting at 21.1, pricing in higher implied volatility in eight months than in the short term. This is the usual shape of the volatility term structure: contango. An upward sloping volatility term structure expresses that investors expect a higher probability of disaster in the longer future than in the near future, which is common when no crisis is expected. On the other hand, in extremely bad times, such as those of crisis, it can be hard for things to get worse, so we typically see an inverted downward volatility term structure.

With this in mind, it is straightforward to assume that implied volatility is not constant across maturities, as market participants may expect volatility to be higher or lower in the future. In this sense, the volatility term structure derived from VIX index futures prices exhibits a changing slope on different trading days. Thus, an interesting aspect of the term structure of volatility is how it changes over time.

{{<Volatility_Term_Structure_Article/VIX_Term_Structure_Curve_Multiple_Graph>}}

###### Source: Cboe Global Indices. Period: 8/19/2022 – 8/21/2023. Past performance is not a reliable indicator of future performance.

As can be seen in the previous chart, the overall level of implied volatility was higher a year ago than today possibly because the market was expecting a U.S. recession in 2023. Nevertheless, today’s curve is above the curve of a month ago, showing that “fear” has increased in the market, likely triggered by Fitch’s downgrade of the U.S. debt rating from AAA to AA + and Moody's and S&P Global Ratings downgrades of the credit ratings of several U.S. banks.

Nonetheless, the slope of the curve is positive in all three cases. In the next section, we will analyze the slope of the volatility term structure over time to identify the periods when it became negative.

## Volatility Term Structure Slope

As we discussed in the previous section, the volatility term structure is likely to be upward sloping in normal times, while it is generally downward sloping in crisis periods. In the next chart, we will see when the curve is downward sloping:

{{<Volatility_Term_Structure_Article/VIX_Term_Structure_Slope_Graph>}}

###### Source: Cboe Global Indices. Period: 5/13/2013 – 8/21/2023. Past performance is not a reliable indicator of future performance.

Indeed, we see that the curve is mostly upward sloping, as its slope has been mainly above zero over the past decade. At moments of strong market dislocation, such as the pandemic Covid-19 market crash in March 2020, it turns negative. We also see two events in 2018, first in February at a time known as “Volmageddon” and then in December during the U.S. federal government shutdown.

What is more, the curve often drops  to -1 and below during an inversion, while it barely rises above 1 during positive events. This is consistent with the idea that stock markets grow slowly and steadily, while they collapse quickly and suddenly in times of crisis. To illustrate this, we can compare the slope of the VIX term structure, the value of the VIX index and the drawdown of the S&P 500® index in the next chart:

{{<Volatility_Term_Structure_Article/VIX_Term_Structure_Final_Graph>}}

###### Source: Cboe Global Indices. Period: 5/13/2013 – 8/21/2023. Past performance is not a reliable indicator of future performance.

When the VIX index crosses the 30 mark, it indicates heightened volatility due to high uncertainty and risks. As we can see, the times when the VIX index rushed above 30 coincided with those when the slope of the VIX term structure was negative and when the S&P 500® index experienced large drawdowns. In contrast, when the slope begins to turn positive again, it appears that the drawdown starts to ease. Therefore, the slope of the VIX term structure may be utilized by investors to anticipate upcoming moments of fear or calm in financial markets. As a result, it may serve as a tool in portfolio and risk management.

---
### Sources

<sup>1</sup> Source: Cboe Global Indices

<sup>2</sup> Source: Cboe Global Indices

<sup>3</sup> Source: Cboe Global Indices

**Data Source:** 

[Cboe Global Indices](https://www.cboe.com/)

[Yahoo Finance](https://www.yahoofinance.com/)

**Code Source:** [GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Volatility%20Term%20Structure)

**Cover Image Credits:**  © cra1gll0yd / ID: 3585417439 / Flickr.com

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.