---
date: 2020-01-06
description: "Now that I know what is Technical Analysis, what's Fundamental Analysis? "
featured_image: "uploads/Investment_Analysis_Part_II/Fundamental_Analysis_cover.jpg"
tags: ["Money", "Financial Markets"]
title: "Investment Analysis, Part 2: Fundamental Analysis"
author: "Vasco Laranjo, CFA"
---

This article on Investment Analysis is the second part of a series comprising two articles. In the first [article](https://vasconomics.com/post/investment_analysis_part_i/) I focused on *Technical Analysis* providing firstly a comparison with Fundamental Analysis, later an introduction to its foundations and concluding with an overview of the application of some of its indicators. Now, on this second part, I will focus on *Fundamental Analysis*. The structure of the article is divided into 4 parts: an immersion on Fundamental Analysis framework, a summary of the Multiples Approach application and the link with the topic of Analysts’ Recommendations.

### Intro to Fundamental Analysis (FA)

In the previous article, **Fundamental Analysis** was characterized as a technique used to evaluate the value of a security by attempting to measure its intrinsic value. Furthermore, it was seen that feasible inputs of this methodology are: i) Financial Statements' data, ii) discussions with companies’ Management Boards and iii) economy prospects and industry trends.

Fundamental analysis is usually done following a *top-down approach*, that is, it starts with the assessment of the macro picture of the economy as a whole; and then advances to the smaller components, the so-called the micro factors. More practically what this means is that one starts examining the strength of the economy so to decide in which industry to invest, later analyzes the companies making part of this industry and, finally, calculates the fair market value of a company. The top-down approach contrasts with the *bottom-up approach* which starts from the micro perspective and finishing with the macro analysis.

Having this in mind and keeping things simple, Fundamental Analysis can be split into two dimensions: the **Multiples Approach** and the **Discounted Cash Flow (DCF) analysis**. A DCF analysis is a thorough process, which includes the need for drawing several assumptions, and therefore is usually only undertaken by financial professionals who have a broad access to company financial data and to the Management Board of the companies under analysis. On the other hand, despite being less detailed, the Multiples Approach requires data which is typically easily accessible and the need for assumptions is relatively limited. Note also that these are not concurrent approaches, but instead they complement each other to better perceive the so much aimed *intrinsic value* of the security under analysis.

Finally, after undergoing the examination using FA and arriving to the intrinsic value of the company, the investor will compare it with its current stock price. In that sense, if the intrinsic value is higher than the stock’s market price it is deemed to be *under-valued* and receives a buy recommendation. On the other hand, if the intrinsic value is lower than the current market price of the stock, it is considered *over-valued* which will lead to a sell recommendation.

In the next sub-section, I will explain the concepts behind the Multiples Approach valuation method. Despite not explaining the DCF analysis’ methodology, on the last part of the article I will introduce the concept of **Analysts’ Recommendations**.

#### Multiples Approach

The **Multiples Approach** is based on the belief that that similar assets should be traded at similar prices. Accordingly, it makes use of Financial Multiples to compare the valuation between different companies.

“Multiples” is a term used to define a class of indicators used to evaluate a stock or industry. A Multiple will be simply the ratio between the company’s Price (or Value) and a Financial Metric, such as Earnings. As a final note, it is very important that the reader understands that if the goal is to compare *something*, it is assumed that what is being compared can indeed be comparable. Otherwise, the differences in value will most likely come from differences arising from the “lack of comparability”.

Moving forward in the world of Multiples, it is divided into two categories: i) Equity Multiples and ii) Enterprise Value (EV) Multiples: 

* **Equity Multiples**: as the name says, will be based on <abbr title="The value of a company (Assets) is divided into Liabilities and Equity, where Liabilities are basically the company’s debt. Therefore, the Equity value is the company’s value after the payment of its Debt.">Equity</abbr>, that is, the part of the company that is addressed to investors/shareholders. 
* **Enterprise Value (EV) Multiples**: are based on the Enterprise Value, which is entire value of a firm. 

In that sense, in Equity Multiples the <abbr title="upper part of the ratio">numerator</abbr> will be the company’s market stock Price, while in EV multiples the numerator will be the Enterprise Value of the company.

For this article, I decided to focus on three Equity Multiples: PE, PEG and PB; and two EV Multiples: EV/EBITDA and EV/Sales. Below you will find a description of each of these Multiples:

* **Price to Earnings (PE) ratio**: indicates the dollar amount requested to invest in a company so to receive one dollar of that company’s earnings. It is the most used Equity multiple;
* **Price Earnings to Growth (PEG) ratio**: is the stock’s PE ratio divided by its earnings growth rate. Typically, fast-growth companies have high PE values. Therefore, by factoring in the company's expected earnings growth, investors can make a clearer comparison between fast and slow growth companies;
* **Price to Book value (PB) ratio**: used to compare a company's current market price to its book value (of Equity);

* **Enterprise Value to EBITDA (EV/EBITDA)**: measures the value of a company based on its capacity to generate earnings. It is the most used Enterprise Value multiple;
* **Enterprise Value to Sales (EV/Sales)**: compares the company’s value with its annual sales to determine the capacity of the company to generate revenues.

As mentioned in the beginning, Fundamental Analysis starts with the analysis of the entire economy and the choice of industry. In the case of Industries’ analysis, Multiples can be compared on an historical basis by analysing the Multiples’ evolution over time. Hence, when the value of a specific multiple is above its historical average, it *may* indicate that the industry is over-valued; whereas when the industry’s multiple is below its historical average, it *may* indicate that it is under-valued. When finishing this analysis, the investor must try to identify the reasons behind the indications of under or over valuation. It can be that these perceptions are indicating incorrect market pricing of the industry’s intrinsic value or that there were changes in its dynamics or growth prospects that forced valuation’s changes.

After deciding in which industry to invest, the analysis will be focused on specific stocks. In this stage, the Multiples analysis will not be based on historically values, but instead on the comparison between the current values of a given Multiple across the different companies in an industry. Typically, a higher multiple indicates that the company is over-valued. However, it may also indicate a competitive advantage over its peers or expectations of higher future growth prospects.

Finally, a definitive **Price** or **Enterprise Value** number for a stock, based on a given Multiple, can be obtained by: i) taking the stock’s Industry Average Multiple value and ii) multiplying it by the financial metric value in the <abbr title="lower part of the ratio">denominator</abbr> of the Multiple for this particular stock. 

For example, calculating *Apple Inc.* (AAPL) price based on the PE ratio: i) Apple belongs to “Technology Hardware” industry, so find the Industry Average PE for this industry; and ii) multiply this value for Apple’s current Earnings (denominator), to obtain the Apple’s intrinsic stock price (nominator).

I believe that by now the reader must be eager to see some numbers, so it is about time to show them.

### Applying Fundamental Analysis (FA)

*Disclosure: at the moment of writing this article, I have no connection whatsoever with the people or institutions responsible for the developing of the mentioned resources. All the data shown is as of 02/01/2019.*

Similarly to what I described in Technical Analysis article, I obtain Financial Statements data via Yahoo Finance. It is possible to view this data in the website; however, I am currently using a Python package to obtain it in a faster/more convenient way. Please note that in the end of this article I include the Python’s Code Source where you will find the code used to obtain the table presented.

I decided to include a table with the previously described Multiples including stocks from the S&P 500. Please notice that for each multiple presented, the value of the Industry’s Average is provided so that a comparison between the stock’s multiple and industry can be done.

#### Fundamental Analysis Table

{{<Investment_Analysis_Part_II_Article/Fundamental_Analysis_table>}}

I would like to recommend an example for a first analysis: *Visa* (V). Visa works in the payment services industry but was lately classified within “Information Technology” sector and “Data Processing and Outsourced Services” industry. A short list of the most comparable companies to Visa in the table are MasterCard and PayPal. 

I found it quite interesting that PayPal has a higher PE ratio than Visa, but then it has a lower PEG ratio. This represents the idea that there are higher growth expectations regarding PayPal which may be motivating its higher PE multiple. On the EV multiples side, Visa has a lower EV/EBITDA and a higher EV/Sales than PayPal. This *would mean* it is under-value when looking at EBITDA and over-valued in terms of Sales. Therefore, Visa’s expenses are lower than PayPal’s, when looking at as a proportion of the sales; so it shows Visa’s stronger capacity of turning revenues into profit, enhancing its Enterprise Value.

What about you? Have you found any candidate for an investment opportunity from the table above?

### Analysts’ Recommendations

In the first section of this article, I mentioned that one of the inputs of Fundamental Analysis are discussions with companies’ Management Boards. Also, I cited more complicated methodologies such as the DCF analysis. Well, small investors don’t have access to the companies’ Management Boards and hardly have the time and resources to undertake a DCF analysis. However, big financial institutions typically employ a research department aiming at increasing their brokerage revenue with the release of their analysts’ recommendations. 

For an investor, the most important objective outputs from the research analysts’ report are: i) “Recommendation” and ii) “Price Target”. With their recommendation, research analysts provide input on whether “buy”, “hold” or “sell” a stock; while a “Price Target” indicates the analysts’ vision on the intrinsic future value of the stock, given the current available information.

Again, Yahoo Finance compiles information on Analysts’ Recommendations, which can be viewed on its website.  Personally, I am currently using Python to obtain it in a faster/more convenient way, and the link to the code can be seen in Python’s Code Source at the page’s bottom.

To conclude with, below I present a table with analyst recommendations including stocks from the S&P 500. It is important that the reader realizes that this does not indicate financial advice from my side and my intent is solely to publish educational content. Furthermore, analyst recommendations can be outdated, and as financial markets are constantly changing: what was true 1 minute ago may have changed already.

#### Analysts' Recommendations Table

{{<Investment_Analysis_Part_II_Article/Analysts_Recommendation_table>}}

---
### Sources

**Data Source:** [Yahoo Finance](https://finance.yahoo.com/)

**Code Source:** 
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Investment%20Analysis)

**Cover Image Credits:** © Monty Rakusen | Getty Images

---
### Disclosure: 

The information provided on Vasconomics.com is for general informational purposes only and should not be construed as financial advice. The content on this blog is based on the author's personal opinions and research, and it may not be applicable to your individual financial situation. It is always recommended to consult with a qualified financial professional or advisor before making any financial decisions. The author and Vasconomics.com disclaim any liability for any losses or damages incurred as a result of the information provided on this blog.