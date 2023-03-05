---
date: 2023-03-05
description: "Are there months when the stock market returns are higher than usual?"
featured_image: "uploads/Stock_Market_Returns_Seasonality/Stock_Market_Returns_Seasonality_Cover.jpg"
tags: ["Money", "Financial Markets"]
title: "Stock Market Returns Seasonality"
author: "Vasco Laranjo"
---
After over two years away, Vasconomics is finally back! Following an incredible January in the financial markets that reminded me of the January effect, I started wondering about stock market seasonality. From the January effect to the “Sell in May and Go Away” adage, monthly return seasonality is something that comes to investors’ mind from time to time.  In this article we will look at the S&P 500 Index and the S&P 500 Sector Indices historical monthly returns in search of seasonality patterns.

*Disclosure: The analysis presented is based on price returns, not total returns.*

### S&P 500 Index Returns Seasonality

{{<Stock_Market_Returns_Seasonality_Article/Heatmap_SPX_Historical>}}

In the chart above we can see the S&P 500 Index monthly returns for every year starting in 1988*. What catches the eye right away is the dark red color of September and October of 2008 representing the Global Financial Crisis (GFC). Nonetheless, large negative returns in September does not appear to be an event limited to the GFC as we can spot a couple more examples (2001, 2002 and 2022). I believe this effect could be related to post-summer vibes when investors return to work with a different mindset and get an urge to “face the truth” regarding underlying macroeconomic conditions, which are not always supportive to equity markets. On the positive side, we can see some dark green months both in April and November, given that in November there may be some sort of correction for September and October’s collapse.

In that sense, in the next chart we take a deep dive in statistics to look at the average, maximum, and minimum returns. Also, the percentage of positive and negative months is included so that we can take a glance at the consistency of the monthly returns over the year.

{{<Stock_Market_Returns_Seasonality_Article/Heatmap_SPX_stats_full>}}

From the first row of the chart, we confirm our previous analysis that September is the month with the poorest average returns while April and November present the highest returns. Curiously, January has the fourth lowest average return which is rather inconsistent with the buzz around the January effect anomaly. Wait… maybe these April returns are just an April Fool’s joke? Well, in fact within this timeframe, April also registered the highest monthly return (12.09%) and the second lowest negative return (-7.51%). Perhaps those consistent larger returns are the motivation to the “Sell in May and Go Away” adage, given that following April the average returns between May and September are significantly lower than those for the rest of the year, namely between October and December.**

Finally, in the last two rows we can take a shot at analyzing the consistency of the seasonality patterns. We see that indeed the last three months of the year have had more positive than negative returns, which corroborates with the previous thought. Nonetheless, April is the month with the highest percentage of positive returns, alongside December, with 3 out of every 4 years showing positive returns.

While pursuing this study, I got intrigued about the seasonality across different sectors, wondering if there were sectors that perform particularly well in a given month. To check that, I created a chart which shows the monthly average return for every S&P 500 sector.

Disclosure: The S&P 500 Real Estate Index has a different starting date (May 1, 1993) than the remaining sectors (Feb 1, 2002). Part of the performance is backtested, given that some of the returns shown are prior to the index’s inception (Ex: S&P 500 Real Estate launch date is Sep 19, 2016, while returns are used from Feb 1, 2002).


### S&P 500 Sector Indices Returns Seasonality

{{<Stock_Market_Returns_Seasonality_Article/Heatmap_Sectors_Avg>}}

From this chart we can validate our earlier takeaways: April shows the highest average returns across sectors while September is at the other end of the spectrum with the lowest average returns. However, when it comes to outliers in the sector space there is not a lot that stands out. Perhaps, it is interesting to note that Information Technology (IT) returns look particularly weak in December, only then to rebound in January. This could be a rationale for the January effect to be a feature of IT stocks. Apart from that it is hard not to notice the poor performance of Real Estate and Utilities sectors in November, which is at odds with the remaining sectors. Interestingly enough these two sectors produced the highest average returns in December, potentially showcasing some mean reversion in the last two months of the year.

To complement the analysis, below I present a chart similar to the first one with the monthly average returns for every year, but this time it is presented for every sector using a dropdown functionality. I leave the analysis of this last piece for the reader and would be glad to hear thoughts and comments on the discussion below!


{{<Stock_Market_Returns_Seasonality_Article/Heatmap_Sectors_Dropdown>}}

*The year of 1988 was chosen to avoid 1987 October’s stock market crash, which would strongly affect the properties of the heatmap.

**For more insights on the “Sell in May and Go Away” take a look at the article [Sell in May and Go Away] (https://vasconomics.com/post/sell_in_may_and_go_away/)

---
### Sources

**Data Source:** [Yahoo Finace] (https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Stock%20Market%20Returns%20Seasonality)

**Cover Image Credits:**  © Horrigans/ ID: 3499943659/Flickr.com