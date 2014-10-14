Stocks
======

Stock Screener

These scripts scrape yahoo's pages for today and tomorrow's companies which are posting quarterly results.

If the EPS estimates are positive and everything looks good, the stock symbol is added to the list.

printstocks.py simply prints the list to stdout, giving something that looks like sample.txt

emailstocks.py emails the list in a pretty html table, and includes links to each stock's page on yahoo.


The basic idea came from a stock trading game where I wanted to bet on high-risk stocks every day.
This screener lets you know what you should bet on for the day - just a warning though, a lot of these stocks dip 10% on bad earnings, so consider yourself warned and don't come looking for me if you made any actual monetary decisions based on my tools.
(although if by some miracle I helped you make a lot of money, a generous donation would be appreciated)
