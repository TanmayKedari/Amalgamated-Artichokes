# Amalgamated-Artichokes
A problem from ICPC-2015 World Final

Fatima Cynara is an analyst at Amalgamated Artichokes(AA). As with any company, AA has had some very good times as well as 
some bad ones. Fatima does trending analysis of the stock prices for AA, and she wants to determine the largest decline in
stock prices over various timespans. For example, if over a span of time the stock prices were 19, 12, 13, 11, 20 and 14,
then the largest decline would be 8 between the first and fourth price. If the last price had been 10 instead of 14, then the
largest decline would have been 10 between the last two prices. Fatima has done some previous analyses and has found that the
stock price over any period of time can be modelled reasonably accurately with the following equation:
price(k) = p · (sin(a · k + b) + cos(c · k + d) + 2)
where p, a, b, c and d are constants. Fatima would like you to write a program to determine the largest price decline over
a given sequence of prices. Figure A.1 illustrates the price function for Sample Input 1.
You have to consider the prices only for integer values of k.
