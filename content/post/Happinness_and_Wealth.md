---
date: 2020-03-18
description: "Can Money Buy Happiness?"
featured_image: "uploads/Happinness_and_Wealth/Happinness_and_Wealth_Cover.jpg"
tags: ["Economy", "Happiness"]
title: "Happiness and Wealth"
author: "Vasco Laranjo, CFA"
---

### Can Money Buy Happiness?

Everybody is searching for happiness! Many people say that money doesn't buy happiness, but perhaps what money can do is to allow a path for happiness. Anyway, this blog as the reader knows is not about Philosophy. Here we are discussing economics and looking at interesting data. So let’s see how Money and Happiness can be unfold in this world of *Vasconomics*.

### Wealth

In a previous [article]( https://vasconomics.com/post/economic_wealth_and_climate/) when referring to Wealth, I presented the metric GDP per Capita PPP. However, in this one I will use Gross National Income (GNI) per capita PPP since it is the metric used in the calculation of the Human Development Index (HDI) and it looks reasonable to me.

> **Gross National Income (GNI)**: is a measure of a country's income, including all the income earned by a country's residents and businesses, which comprises income earned abroad. Oppositely to GDP, it does not account for income earned by foreigners located in the country.

In that sense, the contrast between GNI and GDP is that the former includes income earned by a country’s resident earned abroad and doesn’t include income earned by foreigners within the country’s territory. Hence, it shows a better view of a country’s overall economic condition, especially, on those economy’s with substantial foreign investments.

> **GNI per capita** breaks down the total GNI by the number of a country’s inhabitants.

> **GNI per capita PPP** adjusts the GNI per capita by considering the standards of living between countries through a “basket of goods” approach. Thus, it presents a more consistent metric to make a comparison between different countries.

Now that the definitions are clear and that the metric presented is consistent for a comparison between countries, let’s have a look at the world map. The values for the GNI presented are the latest available corresponding to 2018 and are shown in thousands of dollars.

Tip: zoom and other functions available on the right corner, in all the graphs presented.

{{<Happinness_and_Wealth_Article/GNI_Map>}}

One of the things that astonished me after generating this map was to find that almost all of the world was in yellow and red, while there should be some blue as shown in the scale, right? Well, if the reader zooms in the Middle East region, those blue and strong green colours will be found. It is indeed overwhelming to perceive such differences in wealth around the world and, especially, how wealth tends to be concentrated in small countries/regions.

### Happiness

Wealth was relatively easy to define as it is a quantitative metric, but how can we define happiness?
In order to get a ranking of Happiness by country, I decided to use the **World Happiness Report**, which is an annual publication of the United Nations Sustainable Development Solutions Network. This report is based on a survey presented to each country’s population and in the end the result will be presented in a scale from 0 to 10. 

The variables considered in the calculations of the Happiness Score are: i) real GDP per capita, social support, ii) Healthy Life Expectancy, iii) Freedom to make life choices, iv) Generosity, and v) Perceptions of Corruption.

As we can see, in the report there is one variable representing wealth, the real GDP per capita, which may create some collinearity in the relationship we are trying to find. Still, since there are four other more variables let’s assume the impact to be fairly limited.

As we did for the GNI per capita PPP, let’s have a look at the Happiness score in the world map so that there’s a broad perception of the symmetries and contrasts regionally. Please note that the data presented is for the 2019 report, which used data ranging from 2016 to 2019, according to the publication.

{{<Happinness_and_Wealth_Article/Happiness_Map>}}

Despite large red and yellow areas, the last map presented a “happier” view (pun intended) of the world. Indeed, there is a greater dispersion of happiness vs sadness, in comparison to the spread of wealth. The Western world characterized by Europe, North America and Australia shows larger green areas, whereas Africa the more reddish ones, which unfortunately may not be a surprise for the reader.

We came to the point where both Wealth and Happiness were seen, so it is now time to observe the relation between these two.

### Can Money Buy Happiness?

In this section, I present a scatter plot displaying the relation between our metric of Wealth (Money) and our measure of Happiness to, finally, conclude whether money can bring (buy) happiness or not.

{{<Happinness_and_Wealth_Article/Happiness_vs_Wealth>}}

When looking at the graph it is possible to see a clear positive trendline indicating that more money brings more happiness. Also, we see the incredible outliers in terms of GNI per capita PPP from the Middle East: Qatar, Kuwait and UAE. Notwithstanding, there is a clear outlier on the happiness side: Costa Rica (Pura Vida!). Finally, it is interesting to consider the contrasts on a continent level: despite being very low positioned in terms of Wealth, the poorest countries in North and South America are much happier than the poor African countries.

Therefore, we can also take a different approach to the above question, which is “Money isn´t everything in Life".

And never forget…

{{< youtube gUhRKVIjJtw >}}

#### Full Data by Country Table

{{<Happinness_and_Wealth_Article/Data_Table>}}

---
### Sources

**Data Source:**

- World Happiness Report from [Wikipedia]( https://en.wikipedia.org/wiki/World_Happiness_Report#2019_World_Happiness_Report)

- GNI from [UN-HDR]( https://en.wikipedia.org/wiki/World_Happiness_Report#2019_World_Happiness_Report)

**Code Source:** 
[GitHub Page](https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Happiness%20and%20Wealth)

**Cover Image Credits:**: © No intentions of copyright infringement. Taken from https://thriveglobal.com/stories/money-and-happiness-an-enriching-relationship/