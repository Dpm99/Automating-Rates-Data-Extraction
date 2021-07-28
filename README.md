# Automating-currency-rates-data-mining
In the current age of data, there are vast amounts of data that can be accessed for free. This is the case of the European Central Bank - Statistical Data Warehouse which holds data regarding the daily or monthly rates of some currencies. In this small project I create a python script that allows for automatic rates data extraction for the dollar, pound and real currencies. By running this code everyday you can extract the required data from the website and it will automatically detect if your current file (if it exists, if it doesn't then the program creates one) is already up to date, if not, it uploads the new data. 


### Dollar: https://sdw.ecb.europa.eu/quickview.do?SERIES_KEY=120.EXR.D.USD.EUR.SP00.A&
### Pound: https://sdw.ecb.europa.eu/quickview.do?SERIES_KEY=EXR.D.GBP.EUR.SP00.A
### Real: https://sdw.ecb.europa.eu/quickview.do?SERIES_KEY=120.EXR.D.BRL.EUR.SP00.A
