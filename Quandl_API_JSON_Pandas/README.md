# Qunadl API:

![quandi](https://user-images.githubusercontent.com/67468718/103331359-748dfe80-4a1a-11eb-9594-83abb053e810.JPG)

  * For this exercise, it's required to pull some data from the Qunadl API. 
  * Qaundl is currently the most widely used aggregator of financial market data.
  * Qaundl has a large number of data sources, but, unfortunately, most of them require a Premium subscription. Still, there are also a good number of free datasets.
  * For this project, we will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.
  * While there is a dedicated Python package for connecting to the Quandl API, we would prefer that using the requests package.
  
  
  ## These are your tasks for this project:

  * Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).
  * Convert the returned JSON object into a Python dictionary.
  * Calculate what the highest and lowest opening prices were for the stock in this period.
  * What was the largest change in any one day (based on High and Low price)?
  * What was the largest change between any two days (based on Closing Price)?
  * What was the average daily trading volume during this year?
  * (Optional) What was the median trading volume during this year. (Note: you may need to implement your own function for calculating the median.)
  