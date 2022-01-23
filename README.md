# Financial Analytics - Arbitrage analysis

## Packages Used
This project leverages python 3.7

## Installation Guide
The application requires the below programs to be installed

*python
*pandas
*pathjlib
*matplotlib

## Project functionality and Examples of Usage:

In this project, I analyze the arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin trades on markets across the globe, this project analyzes and identifies opportunites for capitalizing on simultaneous price dislocations in those markets by using the powers of Pandas. For this project, I sorted through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Then I apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

### The program will consist of 3 phases:

1. Collect the data: Collect the Bitcoins histroical trade data in csv files from two exchanges: Bitstamp and Coinbase, from 1/1/2018 to 3/31/2018. Using the Pandas read_csv function these files are read in dataframe format. 

2. Prepare the data: The data files are prepared for analysis. For this purpose, a. all Nan rows are dropped, duplicate rows are dropped, and the amount columns are coverted into float format. 

3. Analyze the data: The data files are analyzed for possible arbitrage opportunities using various methods.The analysis starts with a high-level analysis using the describe function, graphs and box plots. Based on the analysis, a particular month is identified that provides the maximum opportunity for arbitrage and this periood is analyzed for the beginning, middle and late periods within this month to zoon in on the arbitrage opportunities within this period. Some snippets of the code used for caluclating profits are provided below for ready refrerence.

4. Calculate Arbitrage Profits:  For each of the three dates, measure the arbitrage spread between the two exchanges by subtracting the lower-priced exchange from the higher-priced one. Then, I will go on to identify profitable trade opportunities (opportunities thatg provide more than a 1% return assuming that the costs of the transactions are around 1%) for the identified dates. Finally, I caluclate the profits (after costs) that the investor could have obtained had he bought the bitcoin at the lower priced exchange and sold it at the higher priced exchange.
<img width="776" alt="Screen Shot 2022-01-23 at 2 41 36 PM" src="https://user-images.githubusercontent.com/96159292/150701270-60b6dbbb-4b1d-4054-acc8-d3f8eccfb9ab.png">
<img width="764" alt="Screen Shot 2022-01-23 at 2 43 30 PM" src="https://user-images.githubusercontent.com/96159292/150701272-22cf5583-1f68-4764-8be7-599f334109c7.png">
<img width="761" alt="Screen Shot 2022-01-23 at 2 43 53 PM" src="https://user-images.githubusercontent.com/96159292/150701274-8a912749-e615-4cdf-a181-98e91976cadb.png">
<img width="783" alt="Screen Shot 2022-01-23 at 2 44 09 PM" src="https://user-images.githubusercontent.com/96159292/150701278-74917cf6-d081-42c8-a237-19d793d98c0b.png">
<img width="772" alt="Screen Shot 2022-01-23 at 2 44 25 PM" src="https://user-images.githubusercontent.com/96159292/150701280-85d968c6-dd64-439a-9ff6-00b6873f3838.png">

## Contributors
Brought to you by Ram Atmakuri (ram.atmakuri@outlook.com)
 License
[MIT] (https://choosealicense.com/licenses/mit/)
