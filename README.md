## INDIAN BANK STOCK ANALYSIS FROM 2006 TO 2020
### Overview
- Collected stock data of big Indian banks from Yahoo Finance
- Plotted Returns ,Closing and Selling prices of various banks
- Created interactive plots using cufflinks
- Visualised various socio-politcal events related stock market changes

### Code and Resources Used
- Python Version: 3.7
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, cufflinks, datareader,plotly
- Yahoo Finance : https://in.finance.yahoo.com/
- Udemy.com : https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/

### Data Collection
Used python's datareader package to read stock data directly from Yahoo Finance's Website. All stocks data is from National Stock Exchange(NSE). 
The following bank data were collected.
 + AXIS Bank
 + Bank Of Baroda
 + HDFC  Bank Limited 
 + ICICI BANK
 + IndusInd Bank
 + Kotak Mahindra Bank
 +  Punjab National Bank
 + STATE BANK OF INDIA
 
With each stock I pulled the following details:
+ High
+ Low
+ Open
+ Close
+ Volume
+ Adj Close

Then I combined all the pulled data into a single dataframe and named it bank_stocks. 

### EDA
I created another dataframe named returns which used the returns formula to calucate and store the returns of all the bank stocks.
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables.
