---
title: "Financial Markets"
date: 2022-12-01T20:15:47+05:30
draft: false
---

I recently enrolled in ['Financial Markets' by Yale University](https://www.coursera.org/learn/financial-markets-global) - a coursera program, to start exploring Economics. As a Software Engineer this field is very much uncharted territory for me, so if you have a roadmap to exploring Economics from scratch I'd be happy to hear from you.

## Some useful math

### Regression Line

Regression line formula = $y = mx + c$

y = dependant variable\
x = independant variable\
m = slope or regression coefficient\
c = constant

Technique to find the line of best fit = Least Squares Method\
Minimise the vertical distance from the data points to the regression line - Get the smallest sum of squares of errors or 'variance'

Used to check the relationship between a company's stock price returns vs returns of an index (eg: Reliance vs Nifty50)\
If slope > 1, then the stock tends to overreact to index movements, and if slope < 1 it tends to underreact.

Good article: [Least Squares Method: What It Means, How to Use It, With Examples](https://www.investopedia.com/terms/l/least-squares-method.asp#:~:text=Least%20Squares%20Regression%20Line,points%20to%20the%20regression%20line.)

### Bell curve or Normal probability distribution

y-axis = probability density\
x-axis = value

Normal distribution is uniquely identified by mean and standard deviation(σ)

In normal distribution mean = 0, standard deviation = 1, skew = 0, kurtosis = 3. It is symmetrical\
Empirical Rule = For all normal distributions:\
68.2% of the observations will appear within +/- 1σ of the mean\
95.4% of the observations will fall within +/- 2σ\
99.7% within +/- 3σ

This means that data points lying outside 3σ are outliers, and rare.\
However stock market returns do not conform to an exact normal distribution curve. They have many outliers being volatile and so the normal distribution graph tends to have fat tails - which is measured by kurtosis (>3)\
Fat tail means that there is greater probability of finding outliers.

Good read: [How Normal Distribution Is Used in Finance](https://www.investopedia.com/terms/n/normaldistribution.asp#:~:text=The%20normal%20distribution%20is%20the,the%20standard%20deviation%20is%201.)

### Central Limit Theorem (CLT)

Given a sufficiently large sample size from a population with a finite level of variance, the mean of all sample will be approximately equal to the mean of the whole population and samples approximate a normal distribution.

Useful to study the returns of stock index which may contain 1000s of stocks. You can take sample out of it say 30-50 stocks and study it's returns instead of all 1000, and that can be used to understand the returns of the overall stock index. Eliminate bias by randomly sapping out stocks.

