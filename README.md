## Credit means many things.  In the context of money, it means whether someone who has borrowed money will pay back as promised and on time.  

Global debt, as of 3Q2018, is close to *$244 trillion*.  Yes, you read it right.

Our national debt, as of January, 2019, is $22 trillion, a 10% increase comparing with two years ago.  Please see our blog post [debt | 债务](https://www.magicmathmandarin.org/debt-债务/), and [Math of our national debt|国债数学](https://www.magicmathmandarin.org/math-for-our-national-debt/)

The credit market is extremely important to the global economy.

We will use Python and a series of Jupyter Notebooks to explore various public data including [Department of Treasury](https://home.treasury.gov/), [various Federal Reserve Banks](https://www.federalreserve.gov/aboutthefed.htm), and Lending Club loan data. 

The reason why we choose these data sources:

## [Department of Treasury:](https://home.treasury.gov/) 

<img src="https://www.treasury.gov/about/budget-performance/strategic-plan/PublishingImages/Treasury-seal.jpg" alt="Department of Treasury-seal"  width="300" style="float: center;"/>

Nearly all data from the Department of Treasury has some connection to credit.  For example,rates from Treasury bill and notes are the interest rates that the goverment is paying for borrowing the money (from people like you and me, instituions and foreign countries, such as China).

###  [Interest Rates](https://www.treasury.gov/resource-center/data-chart-center/interest-rates/Pages/default.aspx)

- Daily Treasury Yield Curve Rates
- Daily Treasury Real Yield Curve Rates
- Daily Treasury Bill Rates
- Daily Treasury Long-Term Rates
- Historical Treasury Rates
### [Treasury Coupon-Issue and Corporate Bond Yield Curve](https://home.treasury.gov/data/treasury-coupon-issues-and-corporate-bond-yield-curves)

- Treasury Coupon Issues
- Corporate Bond Yield Curve

###  Receipts & Outlays
- [Monthly Treasury Statement](https://www.fiscal.treasury.gov/reports-statements/mts/) 
- Daily Treasury Statement
### How Your Money Is Spent
- [USAspending.gov](https://www.usaspending.gov/#/)
### National Debt
- National Debt to the Penny
### Monitoring the Economy
- Economic Data Tables

<img src="https://www.federalreserve.gov/photogallery/files/ec_05.jpg"  width="300" style="float: center;"/>

## [Federal Reserve Banks](https://www.federalreserve.gov/aboutthefed/structure-federal-reserve-system.htm)

Like Department of Treasury, FRB is also a gold mine for high quality macroeconomic and microeconomic credit data.  Because FRB overseas banks, you can access aggregated data on banks too.  

### What exactly is the Federal Reserve Bank?
The Federal Reserve System is the central bank of the United States. It performs five general functions to promote the effective operation of the U.S. economy.

1. conducts the nation’s monetary policy to promote maximum *employment*, stable prices, and moderate long-term interest rates in the U.S. economy;

2. promotes the stability of the *financial system* and seeks to minimize and contain systemic risks through active monitoring and engagement in the U.S. and abroad;

3. promotes the *safety and soundness of individual financial institutions* and monitors their impact on the financial system as a whole;

4. fosters *payment and settlement system* safety and efficiency through services to the banking industry and the U.S. government that facilitate U.S.-dollar transactions and payments; and

5. promotes consumer protection and community development through consumer-focused supervision and examination, research and analysis of emerging consumer issues and trends, community economic development activities, and the administration of consumer laws and regulations.

### [Payment systems](https://www.federalreserve.gov/paymentsystems.htm)
Payment systems are critical to credit transaction.  The Federal Reserve and payment stakeholders are collaborating to improve the speed, safety, and efficiency of the U.S. payment system.

### [Charge-Off and Delinquency Rates on Loans and Leases at Commercial Banks](https://www.federalreserve.gov/releases/chargeoff/)
When charge-off and delinquency rates go up, commercial banks suffer big losses.  
Charge-offs are the value of loans and leases removed from the books and charged against loss reserves. Charge-off rates are annualized, net of recoveries.
Delinquent loans and leases are those past due thirty days or more and still accruing interest as well as those in nonaccrual status.

### [Assets and Liabilities of Commercial Banks](https://www.federalreserve.gov/releases/h8/current/default.htm)

### [Household Finance](https://www.federalreserve.gov/datadownload/Chart.aspx?rel=G19&series=fdb7cc92045744504cc4c688dc11884b&lastobs=&from=&to=&filetype=csv&label=include&layout=seriescolumn&type=package&pp=Format)

Each of the twelve Federal Reserve Banks have their own specialized data sources, which are quite remarkable.  

## Besides current monetary data and credit scoring, we going to learn history of money.  Remember, those who don't know history are fools. 
![title](images/Jiao_zi.jpg)

## Did you know that paper money 纸币 was first used in ancient China around the 11th century 北宋朝?  
Paper money was used broadly during those days due to shortage of copper and the convenience of paper money.   However, the convenience combined with the unlimited power of the government to print money lead to inflation, subsequently the loss of credibility of the government, and its evenual downfall. So, even though the Northern Song dynasty had an advance monetary system, its credit failed due to long and costly wars. 

## Did you know that the Chinese Southern Song 南宋 dynasty government printed money in no less than six ink colors to prevent counterfeiting?
They printed notes with intricate designs and sometimes even with mixture of unique fiber in the paper to avoid counterfeiting.   That was in 1107!

## Backed by gold or silver too? 
Isn't it amazing that their nationwide standard currency of paper money was backed by gold or silver?!  That was in between 1265 and 1274.  

## In the 13th century, Chinese paper money of Mongol Yuan 元 became known in Europe through the accounts of travelers, such as Marco Polo

"All these pieces of paper are, issued with as much solemnity and authority as if they were of pure gold or silver... with these pieces of paper, made as I have described, Kublai Khan causes all payments on his own account to be made; and he makes them to pass current universally over all his kingdoms and provinces and territories, and whithersoever his power and sovereignty extends... and indeed everybody takes them readily, for wheresoever a person may go throughout the Great Kaan's dominions he shall find these pieces of paper current, and shall be able to transact all sales and purchases of goods by means of them just as well as if they were coins of pure gold"
— Marco Polo, The Travels of Marco Polo
