---
date: 2020-04-22
description: "Visualizing Companies' Size by Stock Market Value"
featured_image: "uploads/Largest_Companies_by_Marketc_Cap/Largest_Companies_by_Marketc_Cap_Cover.jpg"
tags: []
title: "Largest Stocks by Market Cap"
author: "Vasco Laranjo"
---
In the last century, we observed a high growth in technological innovation which was later boosted by the creation of the Internet. The rise of the Internet was a <abbr title=" Taleb’s Black Swan theory ">Black Swan </abbr>, which would then fuel a notorious bubble in the stock market: the *Dot.com Bubble*. 

Stock valuations for companies with businesses focused around the use of Internet became highly inflated and continued to grow as a sort of speculative mania for companies whose name finished with “.com”. However, poor management and lack of a solid business plan would prove that these valuations were too high and, eventually, the bubble burst in 2000, erasing many companies. One of the most infamous cases discussed is the one of “Pets.com”. On the other hand, some of those companies had strong management, as well as, a solid business plan and finances. A good example here is “Amazon” which is one of the largest American companies, in terms of market cap.

Thereafter, in the last 20 years we have continued to observe this surge in technological companies. Large technological companies became highly mediatic as their products and services are easily consumed. Therefore, this leads to the question: what are the largest companies by market value?

### Measuring a Company's Size

There are different ways to measure the size of a company. We could look at a company’s headcount or at its Balance Sheet. When looking at the Balance Sheet, comparing companies’ sizes can be done by looking at their Book Value.

> **Book Value**: is the net assets' value of a company, that is, the difference between its total assets (not including intangible assets) and liabilities.

Notwithstanding, in a Stock Market's perspective, the largest companies are defined by their Market Value.

> **Market Value**: represents the market capitalization of company and reflects the aggregated value that a company has in accordance to the stock market.

<img src="https://latex.codecogs.com/svg.latex?Market \ Cap\ = Stock\ Price \times Shares\ Outstanding"/>

There is, however, a major limitation of using the Market Value on the analysis of the largest companies: not including companies not listed in the stock market. Some examples are: Mars, IKEA and Lego. Nevertheless, from a retail investor's perspective, it would be fairly hard to get a share of those companies’ equity, so let’s focus on the largest companies by market capitalization.

For some readers who are still entering the stock market's world, it may be interesting to notice that the size of a company is not only dependent on its Stock Price, but also on the number of Shares Outstanding. It is relatively natural to have the perception that the size of a company is very high when its price is high. Nevertheless, this is not always the case because companies can decide to do something known as stock split, which divides the number of existing shares into multiple shares. Stock splits, typically, occur when the price of the stock increases significantly. This is a type of corporate action that will not change the total value of Market Capitalization, but in turn provides a boost in the liquidity of the shares.

Now that we have covered what Market Cap means, it is time to look at the largest companies by this measure. In this sense, I decided to present the companies in the S&P500 and the STOXX600 following a treemap visualization. S&P500 is a stock market index that measures the stock performance of the 500 largest companies listed on stock exchanges in the United States; while STOXX600 is a stock index including the largest 600 European stocks, among 17 European countries. 

The data presented refers to the end of last quarter, that is, 31st March of 2020. If the reader is interested in generating these figures on their own, at the end of the article both the data and source code references are disclosed.

### S&P500 companies by Market Cap

The Treemap below presents the S&P500 companies by Market Cap with a division by sector through clicking:

<div style="position: relative; padding-bottom: 70%; height: 0; overflow: hidden;">
  <iframe src="https://vasconomics.com/special_graphs/sp500_by_sector/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" title="SP500 by sector" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
 </div>

 The reader will now understand the references to the technological sector in the introduction. 
 
 Indeed, Information Technology is the largest sector of the S&P500 amounting to a share of 25% of its total value. When looking at the S&P table in the last section of the article we can see that the two largest companies in this index represent this sector: Microsoft and Apple. On the other hand, it is interesting that Amazon is not considered to be an Information Technology company, but rather Consumer Discretionary. The same goes for Facebook and Alphabet* (Google's parent company), which represent the Communications Services. Nevertheless, all these 5 companies are mostly known for their Internet-based solutions.

 *Please note that Alphabet should be ranked in 4th place since it has two classes of stock (GOOG and GOOGL) and, therefore, its market cap amounts to USD 750bn.

Let’s now have a look at the other side of the North Atlantic to see if we read the same story…


### STOXX600 companies by Market Cap

While the S&P500 comprises stocks from only one country (the US), the STOXX600 includes companies from 17 countries. In that sense, it is interesting to start the analysis of the largest European companies by market cap with the division by country, following their division by sector.

The treemap below presents the STOXX600 companies by Market Cap with a division by country and, then, sector through clicking:

#### STOXX600 companies Market Cap, by Country and Sector

<div style="position: relative; padding-bottom: 70%; height: 0; overflow: hidden;">
  <iframe src="https://vasconomics.com/special_graphs/eurostoxx_by_country/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" title="STOXX by country" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
 </div>

The first surprise here is to note that the biggest square, that is, the country whose stocks have the largest share in the index, is not Germany. Germany is the biggest economy of the European Union and the fourth biggest economy in the world, when looking at the Gross Domestic Product (GDP). This is again a reminder for the reader to realize that the stock market, many times, does not represent what is happening in the economy. A example on this is just to look at the stock market dynamics during the Covid-19 (SARS-CoV-2) pandemic: late reaction and fast optimism despite its economic effects.

Secondly, it is also interesting to see the contrast between the treemap and the STOXX600 table at the end of the article. The two largest companies by market cap are both Swiss: Nestle and Roche, as well as, the fourth company: Novartis. However, Switzerland is only ranked in third place in the treemap graph.

The UK’s largest share of 21% in the STOXX600 is, then, largely represented by tree major companies in the Top 10 picture: Shell, HSBC and AstraZeneca. It is curious that, in the S&P500 ‘s Top 10 we didn’t observe any company from the Banking (HSBC) nor the Energy (Shell) sector like we do in the STOXX600. 

Intrigued by this, let’s use this as a motivation to have a look at the STOXX600 treemap with a division by sector and, then, by country:

#### STOXX600 companies Market Cap, by Sector and Country

<div style="position: relative; padding-bottom: 70%; height: 0; overflow: hidden;">
  <iframe src="https://vasconomics.com/special_graphs/eurostoxx_by_sector/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" title="STOXX by sector" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
 </div>

The last graph offers a large contrast of the STOXX600 and the S&P500. 

The first thing to note is that the dispersion in terms of sectors' sizes appears to be much lower, since the largest sector (Financials) has only 15% share of the total index compared to the 25% of the Information Technology in S&P500. 

Moreover, the percentage of Information Technology in the European stock index is much lower and equal only to 6%, being SAP its largest company (and it is also the largest German company, considering this analysis). 

As a final note, it is hard not to find it intriguing that, despite all the negative impacts of the Global Financial Crisis and the European Debt Crisis on the overall economy and the banking sector, Financials continue to have the largest share in the STOXX600, one of the main European stock markets indices...

### Stock Indices Ranking Tables

#### S&P500

{{<Largest_Stock_by_Market_Cap_Article/SP500_Data_Table>}}

#### STOXX 600

{{<Largest_Stock_by_Market_Cap_Article/Stoxx600_Data_Table>}}

---
### Sources

**Data Source:** [Yahoo Finace] (https://finance.yahoo.com/)

**Code Source:**
[GitHub Page] (https://github.com/vlaranjo/Vasconomics_Materials/tree/master/Articles/Largest%20Stocks%20by%20Market%20Cap)

**Cover Image Credits:**  © No intentions of copyright infringement. Taken from https://thesponge.com.au/brand-name-creation/how-to-name-your-brand-like-the-10-most-valuable-global-brands-do/
