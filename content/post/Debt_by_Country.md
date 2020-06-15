---
date: 2020-06-15
description: "Government Debt Value, Comparison between Countries and Evolution"
featured_image: "uploads/Debt_by_Country/Debt_by_Country_Cover.jpg"
tags: ["Economy", "Money"]
title: "Sovereign Debt by Country"
author: "Vasco Laranjo"
---
Covid-19 and the urge to lockdown countries had a sudden economic impact never seen before. Some mentioned that the pandemic’s impact was a sort of combined impact of the Spanish Flu and the Great Depression together and at the same time. On the other hand, there was a major difference when it comes to the economic impact, in that Governmental and Central Banks’ response was much faster now than it was during the Great Depression. Moreover, this response was utterly faster than it was in the GFC in 2007-2008. 

Apart from the reference interest rates’ cuts, which had an immediate impact on each country’s Yield Curve, as we saw in the previous article; Governments’ Treasury Departments were “forced” to take action by issuing debt. While it is still early to see the impact of Covid-19 on debt levels (no data still available), I found it worth to explore the topic of Sovereign debt.

In that sense, in this article we will look at: the total issued sovereign debt distribution by country, the debt-to-GDP levels by countries, and the evolution of debt-to-GDP by country over time.

### Sovereign Debt

To begin with, it is important to define what is Sovereign Debt and how is it raised, that is, how do Governments generate debt.

> **Sovereign debt**: is a measurement of how much the government owes to its creditors. In simple terms, the difference between government receipts and spending during one period will determine the change in the level of sovereign debt at the end of that period.

> Governments create debt by issuing Government bonds which are sold to market participants. However, less creditworthy countries or countries facing credit issues, for example due to a credit crunch, may also issue debt by borrowing from a supranational organization, such as the IMF.

Having defined sovereign debt, it is now time to look at the total sovereign debt distribution between countries. In order to do that, I will present below a Treemap with the General Government Gross Debt by country for 2019, with data obtained from the IMF Cross Country Macroeconomic Statistics.  If you are interested in learning how to generate this and the following figures using Python, please refer to the Code Source section at the bottom of the article.

#### General Government Gross Debt (in USD Billions), by country, in 2019

<div style="position: relative; padding-bottom: 70%; height: 0; overflow: hidden;">
  <iframe src="https://vasconomics.com/special_graphs/debt_by_country/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" title="SP500 by sector" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
 </div>

The United States are the biggest economy in the world; therefore, it probably does not come as a big surprise that it is also the country with the largest amount of debt. On the other hand, when looking at the second and third place we already find a catch: China has the second biggest GDP in the world and Japan the third, but Japan has a bigger sovereign debt than China.

Furthermore, it is interesting to note that Italy has a larger amount of outstanding debt than Germany, despite the latter having an economy almost twice bigger.

In that sense, it is very insightful to observe what are the countries with the largest amounts of sovereign debt. Yet, it may not be very consistent to use gross debt levels to compare the sovereign debt levels between countries. Accordingly, the measure that should be used for making such comparison is: the **Debt-to-GDP** ratio.

### Debt-to-GDP ratio

> **Debt-to-GDP**: is the ratio of a country’s public debt to its Gross Domestic Product (GDP).

When evaluating the debt levels of either a company or a government it is important to understand the entity’s ability to pay back its issued debt. Thus, since a country’s production is measured by its GDP, then its Debt-to-GDP level is a reliable indicator of its ability to pay the interests on its outstanding debt.

Oppositely to the General Government Gross Debt, the Debt-to-GDP by being a ratio provides a standard means of comparison between countries. Hence, we can now use the World Map to accurately compare the Debt-to-GDP between countries.

Tip: zoom and other functions available on the right corner, in all the graphs presented.

{{<Debt_by_Country_Article/Debt_to_GDP_Map>}}

There are a couple of particularly interesting things to observe in the World’s Map Debt-to-GDP. The first of them is that the country with the highest Debt-to-GDP ratio is Japan with a whopping 237%. Apart from Japan, the only country with a ratio above 200% is Venezuela. Interesting to note though, how different in terms of economic status the two countries are, but still both are highly reliant on debt issuance. 

Moreover, on the last section we compared Italy to Germany as the former having a large value of Gross Debt. Nevertheless, the largest Debt-to-GDP ratio in the EU belongs to Greece, as we can see from the map. Finally, the Southern European countries have a deep contrast with the Nordic ones when it comes to Debt. This difference came to a climax during the European Debt Crisis, when Portugal (a country not usually spoken about when it comes to its economy) made covers of global financial newspapers. 

Still, one question remains: Was it always like this?

### Debt-to-GDP Evolution over Time

In the final section of this article, I present the Debt-to-GDP evolution over time for each country.

{{<Debt_by_Country_Article/Debt_to_GDP_multiple_countries>}}

Following the European Debt Crisis, the Southern European countries were nicknamed as PIGS (Portugal, Italy, Greece & Spain) due to their mismanagement of public accounts and dependency on debt. 

Nevertheless, we can see from the graph that during the 90’s the Debt-to-GDP of Portugal and Spain were not very distant from the one of Germany. Ultimately, in 2000, when the Euro was established, the Debt-to-GDP of Portugal (50%) and Spain (58%) was actually lower than that of Germany (59%) and France (59%). On the other hand, Italy and Greece had Debt-to-GDP ratios of over 100% in 2000. 

While not aiming to make any conclusion regarding the benefits and drawbacks of entering the Eurozone, I believe it is very important to keep in mind the Debt profile evolution of Portugal and Spain when comparing these countries to Italy and Greece.

What is your take from this analysis? Be welcome to share your thoughts and comments on the discussion below!

---
### Sources

**Data Source:** [IMF Data] (https://www.imf.org/en/Data)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Debt%20by%20Country)

**Cover Image Credits:**  © Mehaniq/ ID: 1727142091/Shutterstock.com