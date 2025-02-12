java c
Empirical Finance: Course Work 1 Your   team   has   been   recently   hired   by Imperial Global Asset Management,   and   your   task   is   to   run   a   few   exercises.    Below,   you   find   the   guidelines   about   your   assignments,   but you can amend the specifications if you have plausible economic arguments.   Finally,   write a brief investment report of about 3,000 words (this is just indicative) as a financial   economist.   Describe what you have   done   and present the   key   results.    There   is   no   need   to   write   any   formulas.    You   can   also be   creative   and   report   whatever   may   convince   an   investor to bet on your strategy. Whether a strategy works or not, try to come up with an   economic story that explains why this   is   the   case.    Last but not   least,   make   any   assump-   tions you need, but please mention them.   You do not need to submit codes and/or excel   files.
Data 
You have collected the following long-span data from Global Financial Data: 
• Stock   market   index   for   both   the   US   and   Japan,
• Short-term   Treasury   yield   for   both   the   US   and   Japan,
• Long-term   Treasury   yield   for   both   the   US   and   Japan,
• GBPUSD   exchange   rate.
Exercise 1 [30%] 
Take   data   for   the   US   (i.e., stock   market   index, short-term   yield, and   long-term   yield)   and answer the following questions.
Questions 
1.   Present   and   comment   their   summary   statistics.
2.   Present   and   comment   the   ACF   and   PACF.
3.   Identify the appropriate time-series specification, and estimate the key   parameters.   Present   and   discuss   your   results.
Exercise 2 [30%] 
Consider the following models:
1.   Benchmark   model
yt      = α +   εt
2.   Competing model
yt      = α +   βxt−1   +   εt
where
•   yt   is   the   monthly   stock   return   between   t   − 1 and   t,
•   xt−1    is   the   term   spread   (long-term   yield   minu代 写Empirical Finance: Course Work 1
代做程序编程语言s   short-term   yield)   observed   at   time   t   −   1.
3.   Use   an   expanding   window   (start   with   10 years   of   data)   as   well   as   a   10-year   rolling window   to   generate   out-of-sample   (OOS) forecasts   for   both   models   using   US   data
Questions 
1.   Compute   the OOS R-squared or   Ro(2)os,
2.   Test   the null hypothesis of equal predictive ability using   the   Clark   and   West   test.
3.   Present   and   discuss   your   results.
Exercise 3 [40%] 
Consider the following models:
1.   Benchmark   model   for   stock   returns
yt      = α +   εt
2.   Competing model for stock returns
yt      = α +   βxt−1   +   εt
3.   For   exchange   rate   returns, always   use   this   model
et      = α +   βzt−1   +   εt
where
•   yt   is   the   monthly   stock   return   between   t   − 1 and   t,
•      et   is   the   monthly   exchange   rate   return   between   t   − 1 and   t,
•   xt−1    is   the   term   spread   (long-term   yield   minus   short-term   yield)   observed   at   time   t   −   1.
•   zt−1   is the interest rate differential (US short-term yield minus   Japan short-term   yield) observed   at   time   t   − 1.
4.   Use   an   expanding   window   (start   with   10 years   of   data)   as   well   as   a   10-year   rolling window   to   generate   out-of-sample   (OOS) forecasts   using   all   data.
Questions 
Consider   a portfolio   consisting   of the US   stock market,   Japan   stock   market,   and   the   US   short-term bond (a proxy for the riskless rate).
•   Set   σ   *       =    10%   per   annum   as   target   volatility,   and   rebalance   your   portfolio   every month using your OOS forecasts.
• Report portfolio mean and volatility in % per annum, SR and SO per annum,
•   Report   the performance fee P   in   basis   points   per   annum,
•   Plot the cumulative returns, portfolio weights, and the one-year rolling SR.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
