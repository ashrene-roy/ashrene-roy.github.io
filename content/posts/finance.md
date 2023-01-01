---
title: "Financial Markets"
date: 2022-12-01T20:15:47+05:30
draft: false
math: true
---

I recently enrolled in ['Financial Markets' by Yale University](https://www.coursera.org/learn/financial-markets-global) - a coursera program, to start exploring Economics. As a Software Engineer this field is very much uncharted territory for me, so if you have a roadmap to exploring Economics from scratch I'd be happy to hear from you.

## Some useful math

### Regression Line

Regression line formula $y = mx + c$

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

Useful to study the returns of stock index which may contain 1000s of stocks. You can take sample out of it say 30-50 stocks and study it's returns instead of all 1000, and that can be used to understand the returns of the overall stock index. Eliminate bias by randomly swapping out stocks.

## Insurance

The policyholders have a contract with the insurance company to protect them against certain well-defined risks and for that they pay a premium, a regular payment to the insurance company for its standing ready to manage those risks. 

### Fundamental Insurance Principles and Issues

* Risk Pooling

What maybe a risk for one person is not a risk for society at large if they are independent. Because by the Law of Large Numbers, the number of bad outcomes are fairly predictable. The insurance company pools all these risks, and by the Law of Large Numbers is not really risky in itself.

Standard deviation of the fraction of policies that result in a claim is $$ \sqrt{ p(1-p)/n } $$ where p is the probability of the risk to occur such as a calamity, and n is the population size. So for large n the S.D. tends to 0. But this is not the case irl as there could be wars, natural disasters, moral hazards, selection bias increasing the probability of risk.

* Moral hazard

Moral hazard occurs when people knowing they are insured take more risks. So for example, if a house is insured against fire one may say, "I'll be careless with fire because it's insured." So then the risk goes up. Or even worse, if the insurance company insures the house for more than resale value, then "I'll just burn it down and pretend it was an accident. And then I'll get more money than I would have for selling the house."

* Selection bias

The insurance company may not be able to see all of the risk parameters that define risk and sometimes their customers may see them more. For example, health insurance tends to attract sick people. So health insurance companies ask for a medical exam, traditionally, to screen out people who know they're already going to be sick. If they're not successful in doing that, then the selection bias can harm their business and it can destroy an insurance business because, if people know that they're going to be ill, then only sick people sign up. The insurance has to be expensive. Healthy people won't sign up because they don't want to pay the expense and so the whole thing collapses and doesn't work. The government can make it mandatory that insurance companies do not look at the selection.