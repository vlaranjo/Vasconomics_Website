---
date: 2019-11-14
description: "Are the richest countries always colder than poor countries?"
featured_image: "Economic_Wealth_and_Climate/Golden-Beach.jpg"
tags: ["Economy", "Climate"]
title: "Economic Wealth and Climate"
author: "Vasco Laranjo"
---
When in university in the early 2010's in Portugal, me and my colleagues would discuss whether all the richest countries had to be the ones with the worse weather. The worse weather for us represented cold temperatures and this vision made sense for us based on a Southern European country and glancing at Northern counterparts, such as Germany or Norwar.

However, we always kept one country in our mind: Australia!

As the reader will see later on, Australia was definitely not the country with the highest relation richest-hottest. 

Now, let's define what we mean by "rich country". Here, we as individuals are interested on our well-being, thus, let's focus on the countries were individuals are considered to be *Wealthy*.

### How to measure a Country's Wealth on the optic of an Individual?
Let's start with a very well-known concept: Gross Domestic Product.

> **Gross Domestic Product (GDP)** is the total monetary or market value of all the finished goods and services produced within a country's borders in a specific time period (year, quarter, month, etc.). 
As a broad measure of overall domestic production, it functions as a comprehensive scorecard of the country’s economic health. *Investopedia*

All in all, GDP gives us a picture of the size of an economy; and when looking at it's growth from one period to another it gives us the health of the economy, that is, whether it's improving or not. 

However, for someone looking for the wealthiest countries we cannot solely look at the GDP itself. Otherwise, it would be obvious that bigger countries (territory) would get a huge advantage over small ones. 

How is Luxemburg supposed to have a bigger economy than Brazil? Still, are the individuals in Luxembourg, in general, poorer than the ones in Brazil? 

This leads us to the concept of GDP per capita:

> **GDP per capita** is a metric that breaks down a country’s GDP by the number of its inhabitants.

Using the GDP per capita allows us to get a smoother picture of wealth, but still there is one thing missing: the Cost of Living. 

To understand this concept, the reader just needs to picture 2 countries that have relatively the same economy size and population. After this, we only need to compare how much individuals earn (salaries, etc.) and how much they spend on their daily lives (rent, food, etc.). Following this, we arrive to the concept of Purchasing Power Parity.

> **Purchasing Power Parity (PPP)** is an economic popular macroeconomic analysis metric to compare economic productivity and standards of living between countries through a "basket of goods" approach.

> *Investopedia*

Finally, let's compare Wealth by using the metric **GDP per Capita PPP** among countries and compare their temperatures.

### GDP per Capita PPP and Temperature by Country

Below you will see a scatter plot where each circle represents a country and is placed according to its GDP per Capita PPP (in Thousands of $) and the Temperature (average annual in Celsius).
Also, for the reader's convenience, the different colours represent the different continent where a country belongs.

Note that, the data presented is an average between 2010-2016 values, when available. It was decided to take the average, to avoid overstating the figures on speficially warm years for some countries.

Tip: zoom available in the left-bottom corner.

{{<Economic_Wealth_and_Climate_Article/Temp_vs_GDP>}}

Main conclusions from the figure:

* There seems to be a negative relationship between Wealth and Temperature, from the black trendline;
* The European countries are the milder, with most of the EU countries above the trendline;
* The Middle East countries, known for their Oil & Gas exports, are the outliers as the hottest and wealthiest;

Australia:

* Has a good relationship Wealth-Temperature being well-above the trendline!

Portugal:

* Is above the trendline. But we can still complain that it has one of the lowest GDP per Capita PPP when comparing to its EU peers.

Since climate is not only about warm temperatures, I decided to repeat this exercise for Rainfall (average annual mm of rain) instead of Temperature.

### GDP per Capita PPP and Rainfall by Country

{{<Economic_Wealth_and_Climate_Article/Rainfall_vs_GDP>}}

In this plot we picture some similarities but also some differences to the pervious one:

* Again, there seems to be a negative relationship between Wealth and Rainfall, though to a lesser extent;
* The European countries seem to occupy again a center place in the plot;
* The Middle East wealthy countries, passed from the right top side to the left top side, since it rarely rains in the desert;
* The African countries now seem to be more widespread along the horizontal axis, although they are generally close to the floor.

Australia:

* Occupies a desirable position within the area of the wealthies EU nations with a similar profile to Sweden.

Portugal:

* Is sharing part of its "circle area" with the Bahamas - who would say?

Don't be shy and share your findings below on the comments area.

#### GDP per Capita PPP and Climate by Country Table

{{<Economic_Wealth_and_Climate_Article/Climate_and_Economy>}}

---
### Sources

**Data Source:** The World Bank, with few exceptions:

[Climate Data] (https://climateknowledgeportal.worldbank.org/download-data)

[GDP per Capita PPP Data] (https://databank.worldbank.org/reports.aspx?source=2&series=NY.GDP.PCAP.PP.CD&country=)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Economic%20Wealth%20and%20Climate)
