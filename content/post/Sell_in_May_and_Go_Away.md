---
date: 2020-05-17
description: "Does it pay off to leave the financial markets during summertime?"
featured_image: "uploads/Sell_in_May_and_Go_Away/Sell_in_May_and_Go_Away_Cover.jpg"
tags: ["Money", "Financial Markets"]
title: "Sell in May and Go Away"
author: "Vasco Laranjo"
---
Every year when May comes, people start dreaming of summer holidays. Also, for those who follows the financial markets, it marks the date when writers remind us of the old saying: “Sell in May and Go Away”. The underlying is relative straightforward as during the summer months there is, typically, less trading activity. On the other hand, some of the late market crashes seem to have happened precisely after the summer holidays: the crash of 2008-2009 started in mid-September and the 2018 Global Stock Market Downturn started at the beginning of October. This year I decided to put this sentence to the test and to analyze if this was indeed reflected in the past and how the overall trend has been evolving.

### The meaning of “Sell in May and Go Away”

The full sentence of “Sell in May and Go Away” is actually: “Sell in May and Go Away, and come on back on St. Leger's Day”. More exactly, St. Leger’s Day refers to the St. Leger's Stakes, which is a horse race event held in England in mid-September, usually on the second Saturday of this month. 

In that sense, in plain terms the saying would suggest that an investor would be better off being invested during the period between mid-September and the end of April, rather than the full calendar year. Alternatively, another version of this <abbr title="Situation when a security performs contrary to the notion of efficient markets">market anomaly</abbr> is known as "The Best Six Months Strategy", where instead of re-entering the market in the middle of September, an investor would enter at the beginning of November. 

Now that the saying is explained and the two strategies are defined, let’s analyze if this is indeed represented in the financial markets. 

In order to complete this analysis, I decided to use the S&P 500 which is by far the most followed index in the world. 

### Sell in May and Go away. But when to come back?

In the graph below, I present a comparison between 3 strategies:

* **Long**: be the full year invested in the stock market,
* **SMGA**: stands for Sell in May and Go Away. 
* **BSM**: stands for the Best Six Months.

Here the underlying is the same, the S&P 500, therefore, the only difference between the two strategies is that in SMGA and BSM there are no returns between May and the <abbr title="The Monday after the second Saturday of September">middle of September</abbr> and end of October, respectively. 

The strategies assume an initial investment of 100$ and the information presented is from the beginning of 1970 until the end of 2019.

Note: If you are interested in how the graph was generated, the code source is found at the page’s bottom. You are also reminded that there are functionalities that may help in the graphical analysis below, such as the zoom or the range tool underneath the graph.

{{<Sell_in_May_and_Go_Away_Article/Full_Gaph>}}

The first idea I get, after looking into the graph, is that all strategies returned approximately to the same total portfolio values in the aftermath of the dot.com bubble and the GFC crash. In fact, in September of 2008 the Long strategy lost all the additional returns it had over the SMGA and the BSM strategies.

Another interesting point to notice is that during the 70’s, the SMGA and BSM strategies seemed to have outperformed the Long one. This may indicate that these strategies were profitable in the past and they were exploited to a point where they no longer deliver abnormal returns over the Long strategy. 
Additionally, it is important to notice that the “Stock Trader's Almanac” published in 1967 originated "The Best Six Months Strategy", which may have led to the abnormal gains observed in the 70’s.

All in all, we see that in the last 50 years being always invested in the market delivered higher returns than following either the Sell in May and Go Away or “The Best Six Months” strategy: around $3500 versus $2200 final portfolio value. 

Finally, it is interesting to note that the SMWA and BSM strategies have been moving very closely, apart from the 7 years between 2009 and 2016. This may indicate that there is little overall market movement between mid-September and end of October. One may be wondering about the Flash Crash of October 87’, however, the truth is that when zooming-in this period, one can see that it had been a summer of particularly high returns.

I admit that 50 years is a long time and that the stock markets are constantly changing, so let’s see how these strategies played out during the last 20 years.

{{<Sell_in_May_and_Go_Away_Article/Last20Year_Gaph>}}

If the previous graph left us doubtful on the strength of the “Sell in May and Go Away” and “The Best Six Months” strategies, the second did not provide much clarity on these market anomalies either. Overall, both the SMGA and BSM strategies outperformed the Long strategy, namely due to the lower drawdowns, during the periods of market meltdown: dot.com crisis, the Great Financial Crisis and the 2018 Global Stock Market Downturn. Still, in the end, both strategies have delivered similar final returns with a final balance of $220 with a starting point of $100. 

On a different note, it is also interesting to observe the contrast in the returns obtained in the last 20 years (120%) and the last 50 years (2,100%) for the SMGA strategy, the one with the lower returns.

#### Strategies' Yearly Returns Table

Finally, for a clearer view on the overall returns of both strategies, below I present a table with the yearly returns on the Long, SMGA and BSM strategies. In addition, I decided to include the returns of the “Opposite” of the “Sell in May and Go Away” strategy, which seems to be definitely the one not to follow.

{{<Sell_in_May_and_Go_Away_Article/Historical_Comparison_Table>}}

Finally, it is interesting to note that despite having been more profitable than the Long strategy during the first decade of the 2000’s, the BSM strategy average returns in the last 10 years was lower than the average of the Long strategy.

---
### Sources

**Data Source:** [Yahoo Finace] (https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Sell%20in%20May%20and%20Go%20Away)

**Cover Image Credits:**  © Image credited to [Wallpaper List] (http://wallpaperlist.com/summer-and-winter-over-the-road-wallpaper-2337.html)