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
   -  Translation: 1% of chance that a portfolio will lose $10 million in a year
   -  A 5% 3-month Value At Risk (VaR) of $1 million represents : 
   - Translation: A 5% chance of the asset declining in value by $1 million during the 3-month time frame.
  
### **Stress tests**

- **Method of assessing risks to firms or portfolios through the use of 3 scenarios**

- **Tries to incorporate all potential economic and financial crises, such as recessions, appreciation and depreciation of currency, liquidity crisis, etc.**
- **Tries to incorporate all the interconnections between financial institutions.**
- **Does not look at historical returns, and looks at all the details of the portfolios and their vulnerabilities during all sorts of potential financial crises.**

---------------

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

Normal distribution is not ok because not have outliers ! which represents the markets (not previsible)

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

### **Beta & CAPM**

![Beta](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/10.png?raw=true) 

The beta of a potential investment is a measure of how much risk the investment will add to a portfolio that looks like the market. If a stock is riskier than the market, it will have a beta greater than one. If a stock has a beta of less than one, the formula assumes it will reduce the risk of a portfolio.

> In fact the beta of the i stock is its covariance with the market divided by the variance of the return on the market. It's just a scaled covariance and the average beta has to be one, because I could substitute the average return on the assets. And that's the return of the market, so then the covariance of anything with itself is equal to the variance. It just equals one.

**The measure of systematic risk is captured by the Beta**
-> if beta is low there is no return

### **Capital Asset Pricing Model (CAPM)**
https://www.investopedia.com/terms/c/capm.asp


![Beta](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/11.png?raw=true) 

**Market risk** Is the risk for an asset to experience losses due to factors that affect the entire stock market

**idiosyncratic risk** Is the risk which is endemic to a specific asset and therefore not the market as a whole

## **Week 1 - Lesson 3**

### **Insurance Fundamentals**

> **Policy** **holders** have a **contract** with the insurance company **to** **protect** **them** **against** certain **well defined risks** and for that they **pay** a **premium**, a regular payment which in exchange they protect them to the defined risks.

#### **Fundamental Insurance Principles & Issues**

- **Risk Pooling** (regroupement des risks) is the source of ALL value in insurance
  - Mathematical formula (if not others risks, 
  - war, pandemic..)
  **RISK POOLING : If individual events are independent, risk can be decreased by averaging across all of the events**
  
  - Standard deviation formula for Insurance

    ![Insurance Principles](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/12.png?raw=true) 

    -  if *n* policies, each has independent probability *p* of a claim, then the number of claims follows the binominal distribution. The standard deviation of the fraction of policies that result in a claim is:

    - p = probability of death
    - n = number of policies 
  - The number of death is almost null.
 
 ### The concept of insurance relies on **the law of large numbers**: *as n get large, standard deviation approaches zero*.

### **Risk pooling is the source of all value in insurance**

**2 factors/issues can influence it:**
 
 - **moral hazard** (moral risk) :
    > **dealt with partially by deductions and co-insurance**
    > when people have an insurance and take more risks
    > i have a fire insurance > "I don't care if the house burn"
 - **selection bias** (exams, obligations...) :
   > **dealt with by group policies, by testing and referrals, and by mandatory government insurance**
   > my insurance covered more than what the real value of the house is. "I will burn the house and pretend it's ok".

> Example: **crop insurance for famrmes** 
> 
> Problem: it's manipulable (cheat, lies (resell etc..), don't do the needful)
> 
> Solution: Weather insurance for farmers in under-developed countries, where it's very important to know, and sensors to know when the seeds were planted and what's the ground quality, humidity etc...

![Crop Insurance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/01.jpg?raw=true) 

![Crop Insurance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/02.jpg?raw=true) 

![Types of life insurance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/13.png?raw=true) 

![Types of life insurance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/14.png?raw=true) 

![Types of life insurance](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/15.png?raw=true)

### **Insurance Milestones**

- 1300s - **Burial societies ancient Rome,** true insurance policies appeared in Italy in 14th Century
- Rapid development of **actuarial theory starting** in 1600s with notion of probability. (and the first life tables)
- 1600s - **First life insurance and fire insurance**
- Marketing 1840 - Morris Robinsson Mutual Life of NY - **First door 2 door sales** 
- Marketing 1880 - Henry Hyde Equitable Life Assurance Society : large cash value (pshychological farming) (if you don't pay anymore you loose the pot) - **first apparition of insurance + saving**
- Marketing 1890 - Vivianna Zelizer's study : The sales pitch changed from challenging god to *"if your man die, he will be able to protect you from beyond the grave, i make it possible"*

  > **Life insurance is a relic, of a day when people died young (or bet to..)**

  > *Why were people initially hesitant to adopt life insurance?*
  >**It felt like gambling and  betting on the life of a loved one**

![Life insurance timeline](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/life-insurance-history-timelines.jpg?raw=true)

### **Insurance is a Local Phenomenon**

> How to protect insurance default / bankruptcy?

- USA : Federal Insurance Office (Dodd Frank) : Monitor insurance companies, looking for systemic risk.
- USA : States Insurance Guarantee Funds : 
  - Most US states have guarantee funds protecting insurances against failure of the insurance company
  - 1941 - The first state to set up such a fund was NY
  - Goal : Protect indivudals only.

![Insurance is a Local Phenomenon](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/16.png?raw=true)

- China 
  - CIRC - max 50 000 Yuan (not a lot...)

> Food for thought : I think that governement interventions like for the 2008 GFC will not come again, and anti-cyclic measures will be implemented globally to spread the power of the big insurance firms... where Fintech & DeFi have their role to play...)
> Too big to fail companies (see AIG)are a problem for a viable economical system interdependant and complex. 

**US Governements Regulations of Insurance**

- 1945 McCarran-Ferguson Act - Delegated insurance regulation to the 50 states/states regulators. -> Issue to normalize partially solved by the next point
- NAIC / National Association of Insurance Comissioners creates standardized laws (Lobby?)
- 1993 : NAIC adopted risk based capital requierements (collaterals)
- 1999 : Financial Modernization act allow **banks to affiliate with insurance companies**

**In europe : Insurance Europe's Reinsurance Advisory Board - RAB** - https://www.insuranceeurope.eu/ + Assuralia in belgium

### **Health Insurance**

- 1694 - First health insurance by Hugh the Elder Chamberlen
- 1850 - First US Health Insurance : Franklin Health Insurance company of Massachussetts

**The Health Maintenance Organization Act (HMO) of 1973**

![The Health Maintenance Organization Act (HMO) of 1973](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/17.PNG?raw=true)

*What was the key concern that led to the regulation of health insurance via the Health Maintenance Act of 1973?*
> Doctors received money when people were sick, and thus they were not incentivized to cure people.

**US Emergency Medical Treatment and Active Labor Act (EMTALA) of 1986**

![US Emergency Medical Treatment and Active Labor Act (EMTALA) of 1986](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/18.PNG?raw=true)

> Tax for everybody to cover emergency services
> It's paid by the hospital if you can't pay it.

**US Patient Protection and Affordable Care Act 2010 (Obamacare)**

![ObamaCare](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/19.PNG?raw=true)

Issues:
- 45 millions people are uninsured > risk they will go to hospital if they are dying...implying they don't recieve preventive care
- this system implies that if you leave the company > you have to find an insurer to cover you health > selection bias > medical test > higher monthly bills

### **Disasters**

- Hearthquake Insurance (2010 Haiti)
- Flood Insurance (2010)
- Wind Insurance (2010)
- Terrorism Risk ()
![Casualty Insurance in Haiti](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/20.PNG?raw=true)

![Katrina](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/21.PNG?raw=true)

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/21.PNG?raw=true)

*Before 9/11/2001, insurers:*
Generally did not exclude terrorism risk, which they then saw as inconsequential. 

## **Week 1 - Lesson 4 : Defining the best portfolio **

CAPM (Capital Asset Pricing Model) is based on rational markets and rational investors, it links to behavourial finance.

### **Calculate Beta Stock**

  - See in the template folder how to calculate the beta of a stock.

### **Short Sales**

  - It means to have a negative quantity of a tradable asset
  - 799 stocks in 2008 were abolished of being shorted due to the 1929 stock crisis fear


# Quotes: 

Andrew Carnegie - The business world selects for people with natural talents

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/22.PNG?raw=true)

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/23.PNG?raw=true)

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/24.PNG?raw=true)

Efficient market :
https://www.investopedia.com/terms/m/marketefficiency.asp

Prospect theory : Théorie des perspectives: loss aversion
https://www.youtube.com/watch?v=sM91d5I36Po&feature=emb_title
https://en.wikipedia.org/wiki/Loss_aversion


Heirdbehaviour : https://www.youtube.com/watch?v=L8aRm82r8l8

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/25.PNG?raw=true)


![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/26.PNG?raw=true)

![Terrorism](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/27.PNG?raw=true)

![Wishful thinking](https://github.com/cwrisec/Yale-FinancialMarkets/blob/master/28.PNG?raw=true)

![Terrorism](https://qph.fs.quoracdn.net/main-qimg-0660b89f818ef2ae6a4c4bf64dafbfedG?raw=true)  

Compound interests : https://www.lucbrialy.com/interets-composes.html
