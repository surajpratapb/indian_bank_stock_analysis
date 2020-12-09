## INDIAN BANK STOCK ANALYSIS FROM 2006 TO 2020
### Overview
- Collected stock data of big Indian banks from Yahoo Finance
- Plotted Returns ,Closing and Selling prices of various banks
- Created interactive plots using cufflinks
- Visualised various socio-politcal events related stock market changes

### Code and Resources Used
- Python Version: 3.7
- Packages: pandas, numpy,matplotlib, seaborn, cufflinks, datareader,plotly
- ![Yahoo Finance](https://in.finance.yahoo.com/)
- ![Udemy.com](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)

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
<p align="center">
  <img src="assets/original_table.JPG">
 </p> 

### Exploratory Data Analysis
I created another dataframe named returns which used the returns formula to calucate and store the returns of all the bank stocks.
 <p align="center">
  <img src="assets/Returns_formula.JPG">
 </p>   
 
 Where Pt = Price of Stock at time 't' 
 <p align="center">
  <img src="assets/return_table.JPG">
 </p>       

I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from my EDA.

- The Min And Max stock returns: 
<img src="assets/min_max.JPG">
- Intrestlingly AXIS bank's best and worst returns in over a decade were between 2008-10-10 & 2008-10-13
   
- I also plotted the distribution of the returns of SBI & HDFC banks. Both banks have similar devations from average and considered the most stable banks in India.
  <img src="assets/SBI_HDFC_returns.JPG"> 
  
- Also plotted the Simple Moving Average plot for Punjab National Banks in 2018 . A huge drop is noted relating to the controversial 2018 PNB scam.
  <img src="assets/PNB2018.JPG"> 
  
 - A Correlation heatmap is plotted to show all the diffrent relationships between stock close prices
  <img src="assets/corr_heatmap.JPG"> 
  
  ### Conclusion
  - SBI & HDFC banks have stayed the most reliable banks of the said time period
  - SBI is the best majority Govt. share bank & HDFC is the best private share bank
  
 #### Check out the attached ipynb file for more detailed analysis.
 
 ### How to Use
  - Refer to the ipynb file.
  
  ### Credits 
  -  ![Yahoo Finance](https://in.finance.yahoo.com/)
  -  ![Jose Portilla](https://www.udemy.com/user/joseportilla/)
  -  ![Wikipedia](https://en.wikipedia.org/wiki/Global_financial_crisis_in_2009#:~:text=In%20March%202009%2C%20Blackstone%20Group,by%20the%20global%20financial%20crisis.&text=On%20June%2022%20the%20World,since%20the%20second%20world%20war.)
  
