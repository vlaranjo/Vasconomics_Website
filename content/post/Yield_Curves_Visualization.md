---
date: 2020-05-23
description: "The Yield Curves 101"
featured_image: "uploads/Yield_Curves_Visualization/Yield_Curves_Visualization_Cover.jpg"
tags: ["Financial Markets", "Economy"]
title: "Yield Curves: Visualization"
author: "Vasco Laranjo"
---
The Yield Curve Flattening, Yield Curve Inversion, Yield Curve Control, Yield Curve Manipulation…

Reference interest rates are good instruments for monetary policy and give us some insight on the state of an economy. However, the Yield Curve is a much more powerful tool to visualize the current state and future expectations about the economy’s growth direction, at a given time. 

Further to that, during the last years, especially due to the challenge on managing low interest rates by central banks, the Yield Curve has been granted additional importance. In this article, I will present the ground base understandings about Yield Curves and provide different visualizations, as well as, the code source to generate those visualizations in Python.

### Yield Curve 101

First, let’s understand what the Yield Curve is:

> Yield Curve: is a representation of the Yield to Maturities (interest rates) for different maturities of the same issuer or issuers with similar credit quality.

> In other words, the Yield Curve can be seen as the curve uniting the dots representing the interest rates paid at the different maturities by interest bearing products (e.g. bonds) with the same credit rating.

The most followed Yield Curve on the planet is the one for the US. Therefore, below I will present the current US Yield curve. I will be using data from Investing.com as of 22nd of May 2020 for these and the remaining graphs. If you are interested on learning how to generate this and the following figures using Python, please refer to the Code Source section on the bottom of the article. 

{{<Yield_Curves_Visualization_Article/US_Yield_Curve_current>}}

As we can see, the US yield curve is currently upward sloped, meaning that Treasury bonds with longer maturities pay higher interests, which is the most common shape for the curve. Nevertheless, the curve does not always follow this shape as we will see in the section dedicated to the *types of the Yield Curve*.

Moreover, it is important to understand the factors affecting the Yield Curve shape. 

The 3 main factors are:

1. **Reference Interest Rates**: these are the benchmark rates defined by the Central Banks which have a direct impact in each security’s interest rate. The Central Bank defines, typically, the reference short-term rates, which then serve as the base level for the yield curve construction.

2. **Economic Growth Expectations**: serve as an indication of the future levels of interest rates, thus, affecting the yield curve at each maturity. A way of understanding this effect is by taking the example of a very strong economic growth above an economy’s equilibrium, which will lead to an increase in aggregate demand. In turn, this will force the Central Bank to increase its interest rate so that the equilibrium between supply and demand is restored.

3. **Inflation**: has a negative impact on real returns, as we observed in the article [Deposits and Inflation] (https://vasconomics.com/post/deposits_rate_and_inflation/). In that sense, higher inflation levels will make investors to require higher interest rates.

As far as the traditional positive slope is concerned, this is due to the so-called *bond risk premia*, representing the premium to hold a bond (longer maturity) versus the risk-free asset (short maturity).

Keeping these factors in mind, in the next section we will have a look at the *types of the Yield Curve*.


### Types of the Yield Curve

Due to the factors described in the previous section, there are different types of yield curves depending on its shape. 
There are 5 main types of Yield Curves:

1. **Normal**: is positively sloped and concave, that is, at each maturity the yields (interest rates) are higher, but they are increasing at a slower pace.

2. **Steep**: is positively sloped but not as concave as the normal curve, or not concave at all.

3. **Inverted**: is negatively sloped and concave, that is, at each maturity the yields are lower, but they are decreasing at a slower pace.

4. **Flat**: the yields are the same or similar across the maturities.

5. **Humped**: occurs when medium-term interest rates yields are greater/smaller than short-term rates and then invert this direction to turn smaller/greater than long-term rates, respectively. This is a rare shape and indicates that growth expectations at a certain mid-term maturity are different than those for the long-term prospects.

{{<Yield_Curves_Visualization_Article/Yield_Curves_Types>}}

Now that we know that Yield Curves have different shapes, we might be wondering about how they change over time.

### Yield Curve Shifts and Twists

Yield Curves change constantly as their yields are computed based on fixed income securities, which are traded during market hours. Accordingly, it is important to understand that such changes can be both shifts and twists:

* **Shift**: parallel shift occurs when yields across maturities change (+ or -) by the same magnitude.

* **Twist**: non-parallel shifts that occur when changes in yields across maturities are different and, thus, changing the shape/slope of the yield curve.

Let’s have a look at the US Yield Curve over different periods of time, so that we have a visual impression of these effects.

{{<Yield_Curves_Visualization_Article/US_Yield_Curves_Historical>}}

The first impression we take from the graph is the large negative shift from 1 year and 3 months ago to the current levels. This shift is due to decrease in reference rates by the US Federal Reserve, which was a synchronized move made by the major Central Banks as a response to the economic impact of the COVID-19 pandemic. 

Furthermore, it is interesting to note that the US Yield Curve had a hump shape 1 year and 3 months ago. This was due to the expectations of a reduction on economic growth in the mid-term cycle, resulting from the fact that the US economic growth was above the long-term equilibrium, thus, indicating lower yield in the mid-term. 

Finally, as a last point it is interesting to note the twist on the yield curve 1 month ago and the current one. As we can see, the short-term rates are now lower than 1 month ago, but the long-term rates are higher.

#### Yield Curves around the Globe

In the last section of this article, I decided to present a dynamic graph with an historical view of the yield curves for different countries. It is important here to recall the factors influencing yield curves, especially when comparing developed with developing economies. You will find that developing economies, such as Brazil, have higher yields across maturities and that its shape it’s also steeper. On the other hand, developed economies like Germany, for example, currently display negative rates and a flat shape in the short-term ranges of maturities.

{{<Yield_Curves_Visualization_Article/Multiple_Yield_Curves>}}

To conclude with, I find the case of Portugal especially interesting. In the previous section, we discussed that there was a synchronized decrease of reference interest rates by central banks. In the Eurozone, the monetary policy did not rely on changing the reference rates but still it was expansionary. Nevertheless, we see that short and mid-term yields 1 month ago were higher than those of 1 year ago. 

The coronavirus also decreased the economic growth potential, so this is not the reason for such upward shift. In fact, the cause here is due to the perception of credit quality of Portuguese sovereign debt. 

In other words, investors perceived an increase in the risk of Portuguese Treasury defaulting on its interest payment obligations and, thus, requiring a higher yield. A closer look at the debt levels of each country is also a very interesting topic and, who knows one we can discuss in another article.

#### Yield Curve by Country Table (in %)

{{<Yield_Curves_Visualization_Article/Yield_Curves_table>}}

---
### Sources

**Data Source:** [Investing.com] (https://www.investing.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Yield%20Curves%20Visualization)

**Cover Image Credits:**  © Dan Smith / [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Federal_Reserve.jpg#filelinks) / [CC BY-SA 2.5](https://creativecommons.org/licenses/by-sa/2.5/deed.en)