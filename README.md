# GoldSpy Investments
GoldSpy Investments, An up and coming investment fund management took on a small client recently, who wanted to invest a small amount of capital with them. As a beginner to the financial markets he wanted to see if BTC or the S&P500 would be more of a sound investment for the future.

Client recently endowed with a small fortune($200,000),Looking to invest, would like to see whether SPY or BTC is more profitable in the long term, therefore they may choose which to invest in for the long term, or both?

Client would also like to see whether SPY or BTC is more volatile, which will help choose which option to choose long term.


## Technologies
The project leverages Jupyter Notebook packaged with Anaconda, with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entry-point.

* [pathlib](https://github.com/nemec/pathlib) - Path manipulation library for .Net

* [csv](https://github.com/thephpleague/csv) - Csv is a library to ease parsing, writing and filtering CSV in PHP.

* [json](https://github.com/topics/json?l=python) - JSON (JavaScript Object Notation) is a standard file format that uses text to communicate data objects to array data types. This notation makes it easy for applications to parse and generate files. JSON grew out of the need to have a real-time server-to-web browser communication.

* [MCsimulation](https://www.investopedia.com/terms/m/montecarlosimulation.asp) - Monte Carlo simulations are used to model the probability of different outcomes in a process that cannot easily be predicted due to the intervention of random variables. It is a technique used to understand the impact of risk and uncertainty in prediction and forecasting models.

* [seaborn](https://seaborn.pydata.org/) - Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

# Installation Guide

Clone GitHub Respoitories to yoour local machine

```sh
   git clone https://github.com/jpqt/Financial-Application.git
 ```
 
# Usage
Created a `read_csv` Dataframe from London Bullion Market Association csv File on https://data.nasdaq.com/ and dropped the excess btc valuations and kept the daily closing price of btc. Create a dataframe to split the csv to view the btc prices from 2015 till present day. create a print function with the shape to view how many data sets are in the split dataframe. post heads and tail to view if the split dataframe was valid. Finally use `sns.set` and `sns.lineplot` to plot the data from the btc from 2015 till present day.

![Seaborn LBMA](https://github.com/jpqt/Financial-Application/blob/main/Photo/lbma-history.png)




# Rough Breakdown of Tasks

JP: Complete user story?

Taesung: 
SPY vs btc
https://finance.yahoo.com/quote/SPY
https://finance.yahoo.com/quote/GC=F?p=GC=F&.tsrc=fin-srch

## Contributers

Name:Joshua Pak 

Name:Andrew Niles

Name:Daniel Byun

## License
DU 2022
