**Forbes Companies Sustainability Metrics**

![image](https://user-images.githubusercontent.com/86231288/131556861-0d0ba55a-4427-487a-a5ee-0a57cac98f66.png)

This repository is created to build a dataset of Forbes 2021 2000 companies' financial metrics and ESG and CSR metrics. The ESG information has been collected from 5 different publically available data analytics firm. The websites used for ESG metrics are: S&P Global, MSCI, Yahoo Finance, CSR Hub, SustainAnalytics. The website used to collect financial information is Yahoo Finance.

**Project Motivation**
The motivation behind this webscraping project is to gather the publically available data on ESG and financial metrics, and decipher if there is a relation between company's financial status with its performance in Sustainability.

The dataset generated contains 2000 rows with all the Forbes 2000 companies with 28 columns containing company info, its financial info and its ESG ratings

**Package details**


![image](https://user-images.githubusercontent.com/86231288/131556680-107d95f1-2bbc-4721-ad49-1077b9efe8af.png)

Selenium is used to scrape all the websites. forbes2000.py is the first file to be run. All other files can be run in any preference. Below is the information of each of the .py files:

**scraper.py** This Python file serves as an input for all the other .py files. It has a Class that includes all the methods that are used commonly in all the .py files.

**forbes2000.py** This file scrapes the companies name listed on Forbes 2000 website. Along with that information such as Country, Sales, Profit, Asset, and Market value of the companies is also collected. The output of this code is used as an input for all of the below files.

**scraper.py** This Python file serves as an input for all the other .py files. It has a Class that includes all
       the methods that are used commonly in all the .py files.

**snp_global.py** : This file collects ESG score and supporting information such as Industry, Ticker, Country,
        Company Name from the S&P Global website. https://www.spglobal.com/esg/scores/

**msci.py** : This file collects ESG rating and Company name from the MSCI website. 
       https://www.msci.com/our-solutions/esg-investing/esg-ratings/

**csrhub.py** : This file collects CSR rating and Company name from the CSR Hub website.
        https://www.csrhub.com/search/name/

**sustainanalytics.py** : This file collects ESG risk rating, Company and Industry name
        from the SustainAnalytics website. https://www.sustainalytics.com/esg-ratings

**yahoo.py** : This file collects the below information from the Yahoo Finance website
        (https://finance.yahoo.com/lookup):
        ESG rating, company name and financial metrics such as Market Cap, Trailing P/E, return on asset, 
        Total Debt/Equity (mrq), Operating Cash Flow and Stock Price, Price/Book (mrq), Most Recent Quarter (mrq),
        Profit Margin, Op_Margin, return on equity, Diluted EPS, PayoutRatio

License:
MIT © Shweta Yadav

Support:
For any questions and suggestions, connect with me on LinkedIn:  http://www.linkedin.com/in/shweta-yadav1
