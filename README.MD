# Yale - Fincancial markets

 It's a course on how you can make your mark on society, but it's not a course on how to get rich.

## **Week 1 - Lesson 1**

### **Objectives**

- Discuss the relevance of this course in everyday life and the importance of ethical judgements in finance.
- Understand the main sources of risk a security is subject to, and the main methods used to evaluate risk of an entire portfolio.
- Describe why an investment may be considered high risk, and the sources of the so called 'disaster risk.'
- List the key events in the history of insurance, and how insurance differs between the state and national level in the U.S.
- Identify the qualitative differences between the normal and fat tail distributions, and give examples of risk pooling, moral hazard and selection bias.
- Understand the principle of risk diversification.
- Explain the Capital Asset Pricing Model (CAPM), and the role of short-selling within the model.
- Recall how to compute optimal risk-return portfolios.
- Understand the concept of efficient frontier in portfolio management.

### **Welcome**

Finance is:

- About making things happen 
- Important because Every human activity that's useful needs financing. T

### **Introduction**

Financial Institutions are a pillar of civilized society:
- directing ressources across spaces and time to their best uses
- supporting and incentivizing people in their productive ventures
- managing the economic risks they take on.
The workings of these institutions are important to comprehend if we are to predict their actions today and their evolution inthe coming information age.

This course will help to understand how institutions works and our place in society.

### **Topics covered in this course**

- Risk
- Insurance
- Diversification
- History of finance
- Innovation|
- Efficient Markets
- Behavorial finance - Application of sociology, psychology, and others social sciences to understand financial events, it's a *revolution in finance*
- Debt
- Stocks
- Real estate
- Regulation - Markets needs to be regulated, because of humans nature which is manipulative and tricky.
- Banking
- Futures
- Monetary policy
- Endowment management
- Options
- Investment banking
- Money Managers
- Exchanges
- Public Finances
- Non profits
- Purpose

### **Finance is a Technology, for Good or Evil**

- All technologies can be used or misused.
- Developping world is more interrested in our finance technology than in our paitry foreign aid or empty sympathies.
- This is not a course on how to make money yourself rich to lead a self indugent life.
- The most successful people in finance end their live as philantropists.

## **Week 1 - Lesson 2**

### **VaR / Value at Risk**

  - VAR in finance means two things:
    - Variance
    - Value at Risk (VaR)
 - Invented after stock markets crash of 1987
 - **VaR or Value at Risk is a measure used by some finance people to quantify risk of an investment/portfolio and it's quoted in units of dollars for a given probability and time horizon**
 - **VaR or Value at Risk is usually quoted in units of $ for a given probability and time horizon**
 - Example :
   -  1% one-year VaR/Value at Risk of $10 million
   -  Translation : 1% of chance that a portfolio will lose $10 million in a year
  
### **Stress tests**

- **Method of assessing risks to firms or portfolios through the use of 3 scenarios**
  
  The idea of a stress test is that, let's look at a portfolio not just by its historical returns and how variable they are, but let's look at the details of the portfolio and **ask what vulnerabilities there are** for various kinds of financial crisis because what actually stresses firms the most are crisis, 

- Originally, term reffered to a medical procedure to test for cardiovascular fitness.
- OFHEO started testing firms' ability to withstand economic crisis before the 2008 crisis, failed.
- **Dodd Frank Act 2010** requires the Federal Reserve to do annual stress tests for nonbank financial institutions it supervisesfor at least 3 economic scenarios.
- European Banking Authority (EBA), 2011
- Ordered by governements - China, USA
- Critic of stress tests such as Anat Admatti find them inadequate

### **S&P 500**

- Standard & Poor's 500 stock price index 
- Used as a benchmark for returns

**Comparaison S&P 500 vs Apple** - Can be used witin tradingview
![](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/01.PNG?raw=true)

**Monthly returns S&P 500 vs Apple** - Monthly returns, note the volatility and the pattern // to the s&p

![](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/02.png?raw=true)

## Variance of Apple vs Variance of S&P 500

- Standard deviation (ecart-type) of Apple capital gain in a decade shown is 12.8% a month. -> we won money
- Standard deviation (ecart-type) of S&P500 capital gain in a decade shown is 4.7% a year. -> we lost money

**Standard deviation definition:**  It's a way to measure price volatility by relating a price range to its moving average

**Tradinview Script** : https://www.tradingview.com/scripts/standarddeviation/

![Scatter diagram](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/03.png?raw=true)

### **Joe McNay**

The class of 1954 in 1979 gave $370 000 and asked Joe McNay to invest for 25 years, he choose walmart, homedepot and some internet stocks now it's worth 90 million because they didn't want to look at the volatility

### **Distribution and Outliers (= abbérations)**

**The distribution or Normal Law or Normal Distribution** 

2 parameters:
- means (µ) (ou moyenne en français)
- deviation (o) (ou ecart-type en français)

**Normal distribution have 2 tails(queues), finance doesn't tends to follow this distribution, that we tend to have outliers or fat tails**

![The distribution or Normal Law](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/04.png?raw=true)

- µ = 0
- o = 1 & 3
- the high means the probability to get to those value.
  
![The distribution or Normal Law](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/05.png?raw=true)

Explaination = https://www.youtube.com/watch?v=E4EdnaP-iCg

- µ = 10 mm
- o = 0.5 mm

**The Cauchy distribution** 

- **Fat tail distribution**
- Famous mathematician
- 100 draws (tirages) from normal distribution in blue
  - have a pattern
- 100 draws from Cauchy distribution in red
  - we are not living in a fairly stable world whose risk I understand, but the problem is, there are these big events that occur from time to time.


![The Cauchy distribution](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/06.png?raw=true)

**Central limit theorem** 

- Averages of a large number of  independent identically distributed shocks (whose variance is finite) BUT it means:
  - Can fail if the underlying shocks are fat tailed
  - Can fail if the underlying shocks lose their independence 

Note the fat tails :

![Normal vs Cauchy distribution](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/07.png?raw=true) 

- Example we can note the returns is between +/- 6%
- We can also see the outliers for the 19 oct 87 and the 30 oct 1928

![Normal vs Cauchy distribution](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/08.png?raw=true) 

**Outliers**

- Normal distribution with same mean (µ) and standard deviation(o) as the historigram shown has a probability of a drop greater than 20% equal to 3*10^71 (means almost 0) but it's false read again black swans and others books from nassim taleb ;-)

### **Covariance - COV**
https://www.tradingview.com/scripts/covariance/
https://www.abcbourse.com/apprendre/19_variance_covariance.html
https://www.youtube.com/watch?v=0mDgPDO8l5s

- Risk is determined by Covariance COV
- Is useful in order to understand if there is a link / liaison between 2 assets (x & y), if near 0 = independant variables (linked)
- it's a probability rate average (moyenne de % d'une probabilité) to compare investiments
- It's Very important for **capital asset pricing model**

![Covariance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/09.png?raw=true) 

**Beta**

![Beta](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/10.png?raw=true) 

> In fact the beta of the i stock is its covariance with the market divided by the variance of the return on the market. It's just a scaled covariance and the average beta has to be one, because I could substitute the average return on the assets. And that's the return of the market, so then the covariance of anything with itself is equal to the variance. It just equals one.
