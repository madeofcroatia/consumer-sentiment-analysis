# Consumer Sentiment Analysis

This was inspired by a [twitter thread](https://twitter.com/quantian1/status/1688397994821873664?s=20) by @quantian1. In here, I am attempting to reproduce their regression analysis of the [Index of Consumer Sentiment](http://www.sca.isr.umich.edu/) provided by the University of Michigan's Surveys of Consumers.

# Explanatory Variables / Features

I am attempting to use 9 features for the prediction of the sentiment. :
<ul>
  <li>Inflation rate - annual change of the CPI provided by U. S. Bureau of Labor Statistics</li>
  <li>Inflation rate change</li>
  <li>Unemployment - seasonally adjusted unemployment rate information provided by U. S. Bureau of Labor Statistics, series id: LNS14000000</li>
  <li>Unemployment change - change of the unemployment over a 4 month window</li>
  <li>Housing prices - U.S. Census Bureau and U.S. Department of Housing and Urban Development, Average Sales Price of Houses Sold for the United States [ASPUS], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/ASPUS</li>
  <li>Real wages - U. S. Bureau of Labor Statistics, seasonally adjusted constant (1982-84) dollar adjusted to CPI-U- Median usual weekly earnings, Employed full time, Wage and salary workers, series id: LES1252881600</li>
  <li>Dollar strength - DX-Y.NYB historical data</li>
  <li>Interest rates - Board of Governors of the Federal Reserve System (US), Federal Funds Effective Rate [FEDFUNDS], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/FEDFUNDS</li>
  <li>Stock prices - S&P 500 historical data</li>
</ul>
