---
date: 2020-01-27
description: "Who's the Leader and the Lagger in the Financial Market now?"
featured_image: "uploads/RRG/RRG_Cover.jpg"
tags: ["Money", "Financial Markets"]
title: "Relative Rotation Analysis"
author: "Vasco Laranjo"
---

### Returns

When investing, there is intrinsically a pursuit for positive returns to enhance the investor’s wealth. 

In everyday life people tend to focus on absolute values which would translate into **absolute** returns in investments: how much one investor gains in money terms in a given currency ($, €, ¥, etc.). However, financial analysts look at data with a focus on relative terms. Putting it simple, relative terms come from the comparison of two or more data points expressed in absolute terms, which in investments means **relative** change: typically this is seen as a growth rate between two periods or by the comparison between two or more instruments (stock from a company vs another). Ultimately, a ratio or an index are also based on a relative comparison.

In that sense, given the importance of relativeness in Financial Analysis, today I will introduce my readers to one of such concepts: *Relative Rotation Graph (RRG)*.

### RRG

*Note: Both “Relative Rotation Graph™” and “RRG™” are registered trademarks of RRG Research. The author is not associated with any of the entities mentioned throughout this article and the latter has purely an educational goal without any profit-driven pursuit.*

*RRG* can be seen as a Cartesian Chart and it was developed by Julius de Kempenaer (JdK). It is an especially useful tool when undertaking a Sector Rotation analysis. This tool is available in Bloomberg Terminals (*code RRG*) and can also be used in *StockCharts*, for example.

The motivation for using *RRG* charts is based on the idea of Sector Rotation, in that: i) stocks with high momentum will continue to outperform (leaders vs laggards) and ii) sectors rotate and, therefore, what was once outperforming/underperforming will eventually catch up and normalize (weakening/improving). Also notice that these movements can be anticipated and connected with business cycles. Therefore, naturally investors want to be invested in leaders and improving sectors, in opposition to laggards and weakening sectors.

Furthermore, the appeal of *RRG* charts is that they are shown in a familiar manner: Cartesian charts. The Cartesian coordinate system is shown, typically, in 2 dimensions (with an x and y axis) which display 4 quadrants. As per what was described in the previous paragraph, the reader can now guess how each of those 4 quadrants will be referred to in *RRG*: Leading, Lagging, Weakening and Improving. 

Having defined Cartesian charts and the existence of 2 dimensions, now it’s time to define each of those 2 dimensions:

* **Relative Strength - JdK RS-Ratio**: measures the **relative** performance based on the sectors’ trend. This metric is used to compare a sector’s performance **relative** to a main Index (the benchmark), thus, indicating the relative performance and its strength.

* **Momentum - JdK RS-Momentum**: measures the momentum, or the so-called Rate-of-Change (ROC), of a given metric. In this case, it will measure the momentum of the Relative Strength (RS). The importance of momentum indicators is to anticipate any changes prior to its occurrence, therefore, anticipating any changes in the *JdK RS-Ratio*.

The starting idea was that *RRG* charts’ analysis is based on sectors’ analysis and, as such, a benchmark needs to be defined. The next step is the calculation of the Relative Strength (JdK RS-Ratio) of each sector versus the benchmark. The final step is to calculate the Momentum (JdK RS-Momentum) of the Relative Strength (RS) previously calculated. 

The specific calculations details for these two metrics are not disclosed by “RRG Research”, thus, some assumptions were taken. For more details on the calculations of these 2 metrics for the purpose of this article, please refer to the Source Code on the bottom of this article.

The most common use of *RRG* charts is on Indices, such as the S&P 500 or the Euro Stoxx, where each Sector (Industry is analyzed). However, in this article I decided to compare different Global Stock Indices versus a Global Stock’s Index. Below the reader will find a table with the indices used in the analysis.

#### Table with Selected World Indices

The table describing each of the Indices including name, symbol and so on can be viewed here: [Table](https://github.com/vlaranjo/Vasconomics_Materials/blob/master/Articles/RRG/Stock_Indices.csv)

#### RRG for World Indices

*Note: data as of 24th of January end of the day.*

{{<RRG_Article/ScatterPlot_1Period>}}

As the graph shows we have indices displayed in each of the 4 quadrants, which is very enlightening for our first look at *RRG*s.

From the first quadrant we see the **Leaders**, where the strongest are S&P 500 with a high highest relative strength and IBovespa with the greatest momentum. I am sure that this won’t be a surprise for the reader, if reading financial news is part of a daily routine (as it is to me). On the third quadrant we see the **Weakening** indices, where MOEX is the furthest from the pack – think about the last outcomings in Russia?

As far as the second and fourth quadrants are concerned, these are the **Laggers** and the **Improving** sector which are of high importance in this analysis to understand where they will be moving: will they become Leaders or eventually turn to be the Weak performers. When looking at the fourth quadrant we can see Shanghai’s SSE index right above the “Momentum” line which may indicate that it is improving from the Weak sector and, therefore, become subsequently a Leader.

In order to conclude on Shanghai’s SSE track, we need to look at its historical evolution in the *RRG* chart. For this purpose, below I present a *RRG* chart comprising the monthly progression of each of the previously stated indices, which can be accessed by the dropdown list.

### RRG for World Indices Multi Period

{{<RRG_Article/ScatterPlot_Multiple_Period>}}

When selecting Shanghai’s SSE in the dropdown, we can actually see that our initial thesis of a move from the Weak to Improving sector was actually not the reality. In this case, SSE took an unusual move of coming back from the Leader quadrant to the Improving one, after being in the latter in the two previous months. Accordingly, this helped us understanding the importance of looking at the historical evolution of the markets and, in this specific case, applied to Sector Rotations by the *Relative Rotation Graph*. 

As a final note, it is important to realize that given the strong moves from one quadrant to another observed in some indices, it may be interesting to shorten this analysis from monthly to weekly data in order to smoothen this progression.

What is your take from this analysis? Don’t be scared to share your thoughts and comments on the discussion below!

---
### Sources

**Data Source:** [Yahoo Finance](https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/RRGd)