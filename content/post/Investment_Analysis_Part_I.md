---
date: 2020-01-03
description: "What is Investment Analysis? Let's start with Technical Analysis, should we? "
featured_image: "uploads/Investment_Analysis_Part_I/trading_floor_nyse.jpg"
tags: ["Money", "Financial Markets"]
title: "Investment Analysis, Part 1: Technical Analysis"
author: "Vasco Laranjo, CFA"
---

In this article, I will discuss the topic of Investment Analysis, that is, the method used for making the decision regarding an investment in the stock market. There are two main approaches when undertaking the analysis of a stock traded in the market: Technical and Fundamental Analysis. It is important to understand that these methods use different inputs with the same goal of evaluating an investment opportunity.
The structure of the article is divided into 3 parts: an introduction defining the two mentioned approaches, a deeper examination of Technical Analysis foundations and an overview of the application of some Technical Analysis indicators’. Therefore, given the extent of the concepts under analysis, I decided to divide this topic into two articles, with the upcoming one focusing on Fundamental Analysis.

### Introduction

#### What is Fundamental Analysis?

In **Fundamental Analysis**, an investor aims to evaluate the value of a security by attempting to measure its intrinsic value. In that sense, the focus is based on the company’s Financial Statements, Management Board, as well as, the economy prospects and industry trends. 

The relevant inputs used in Fundamental Analysis are: 

* Financial Statement information: revenues, expenses and income;
* Growth prospects for the company: based on financial history and discussions with Management Boards;
* Industry trends and competitive factors: based on the previous two points and economic data.


#### What is Technical Analysis?

**Technical Analysis** aims at the study of market action for the purpose of forecasting future price trends, primarily using charts. The first and most important assumption is that market action discounts everything, that is, anything that can possibly affect the price is reflected in the price of that market. In that sense, oppositely to Fundamental Analysis, the investment goal is not to valuate a security’s intrinsic value but to identify in which direction the stock price will move in the short or long future, depending on the timeframes used.

The relevant inputs used in Technical Analysis are: 

* Price: Open, High, Low and Close;
* Volume;
* Open interest – only futures and options.

As a final note in this introduction, it is interesting to note that in Fundamental Analysis one uses the concepts of over-valued or under-valued, whereas in Technical Analysis over-bought and over-sold.

### Intro to Technical Analysis (TA)

I stated already the first premise where TA is based on: i) market action discounts everything; however, there are two more important ideas to its foundations: ii) prices move in trends and iii) history repeats itself. 
The first premise has the purpose of indicating that if anything that can affect a stock’s price is already reflected in it, then, all that is required is the study of its evolution: the price action. The second concept arises from the idea that price action of a market creates trends and the purpose of TA is to identify these trends at an early stage. Finally, the third premise is based on the belief that some trading patterns which have worked well in the past will continue to perform in the future.

As pointed out already, Technical Analysis applied to stocks uses only the price and volume as input. Thereafter, what is important is the evolution of these variables, which will lead to the instruments of Technical Analysis, which are mainly: Trend Lines, Support and Resistance Levels, Chart Patterns, Moving Averages and Oscillators. 

* **Trendline**: can be defined as in an uptrend (bullish action), downtrend (bearish) or sideways (trendless). 
* **Support**: is the though or reaction low and indicates a level on the chart where buying interest is sufficiently strong to overcome selling pressure.
* **Resistance**: is the peak or rally high and indicates a level on the chart where selling pressure overcomes buying pressure and price advance is turned back.
* **Chart Patterns**: are formations obtained from the evolution of price action which create patterns that have identified in the past, which reveal bullish or bearish psychology in the market. These chart patterns can identify continuation or reversal in a trend.
* **Moving Average (MA)**: considers a specific time-frame (number of points in time), calculates the average of prices in that time-frame for a given period and then when there’s a new close, the average is calculated with the value  of the new price (new point in time and dropping the oldest point in the time-frame).
* **Oscillators**: are indicators calculated based on formulas developed by traders to identify over-bought or over-sold conditions, more often than not, when the trend is sideways.

When it comes to Chart Patterns, it is important to note that there are two distinct classes: Japanese Candlesticks formations and the “Western” candlestick formations. I will not develop much on this concept, but it is important that the reader notes that, in my opinion, the “Western” formations imply more subjectivity. Further to that, the Python package comprising a broad range of TA indicators, TA-LIB, includes a long list of Japanese Candlestick formulas but it hasn’t a single formation from the “Western” patterns.

At this point it is important that the reader realizes that there are different ways of analysing trendlines, multiple types of Moving Averages and an almost endless list of Oscillators. Accordingly, hereinafter my goal is to share the sources and resources I use when applying TA in my Investment Analysis.

### Applying Technical Analysis (TA)

*Disclosure: at the moment of writing this article, I have no connection whatsoever with the people or institutions responsible for the developing of the mentioned resources.*

First of all, I obtain Historical Market Data via Yahoo Finance. It is possible to obtain this data in the website downloading a file in .csv format; however, I am currently using a Python package to obtain it in a faster/more convenient way. As far as TA Indicators are concerned, again I make use of a Python package to make these calculations: [TA-LIB](https://mrjbq7.github.io/ta-lib/funcs.html). Finally, for the definitions and explanations of the TA indicators, I tend to use [Stock Charts](https://school.stockcharts.com/doku.php?id=technical_indicators). Please note that in the end of this article I include the Python’s Code Source where you will find the mentioned packages.

For the final part of this article, I decided to include a table including a series of Technical Indicators so that the reader can have a perception of the concepts under analysis. The table includes stocks from the S&P 500.

#### Technical Analysis Table

{{<Investment_Analysis_Part_I_Article/Technical_Analysis_table>}}

The first indicator is the Parabolic SAR (PSAR), which is analyzed by comparing its value to the stock’s price. Its purpose is to emphasize the price movement direction, as well as, providing the resistance or support levels. When PSAR is below the stock price, the stock it is deemed to be in an uptrend (bullish signal); while it is deemed to be in a downtrend (bearish) when PSAR is above the stock price. Also, PSAR indicates the support level when in an uptrend and the resistance level in a downtrend. Finally, if the stock price crosses the PSAR level, it is assumed to be a trend reversal.

The second indicator presented is the “Golden Cross”. The Golden Cross is calculated based on the difference between a short-term Moving Average (50 days) and a long-term one (200 days). Moving Averages crossovers are very popular indicators in TA and the Golden Cross is probably the most well-known. MA crossovers will be positive when the short-term MA is above the long-term one, and negative when the opposite occurs. Moreover, a positive MA crossover is a bullish indicator and represents an upward trend, while a negative oner represents bearish market behavior.
The third and fourth indicators are some of the most popular oscillators: Relative Strength Index (RSI) and Commodity Channel Index (CCI). Both these indicators’ goal is to determine over-bought and over-sold levels which may imply a reversal in their price evolution. Having that said, the RSI values range from 0 to 100 and when its value crosses below 30 a stock is deemed as over-sold, while when above 70 it is considered to be over-bought. On the other hand, CCI is an unbounded indicator, but, typically, values above 100 represent over-bought levels while values below -100 may indicate over-sold activity.

Finally, the fifth and last indicator is the ADX (Average Directional Index), which must be used alongside the Directional Indicator (DI). The ADX is used to determine if a trend is strong, when it’s above 25; or not, when it’s below 20. As for the DI, it indicates the direction of that trend depending on whether it is positive (uptrend) or negative (downtrend). Please note that the DI is the DI+ minus the DI-.

Having this in mind, have you found any candidate for an investment opportunity?

---
### Sources

**Data Source:** [Yahoo Finance](https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Investment%20Analysis)

**Suggested Books**

* *Techncial Analysis*: "Technical Analysis of the Financial Markets", by John J. Murphy;
* *Japansese Candlesticks*: "Japanese Candlestick Charting Techniques", by Steve Nison.

**Cover Image Credits:** © BRENDAN MCDERMID | Reuters | Corbis

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.