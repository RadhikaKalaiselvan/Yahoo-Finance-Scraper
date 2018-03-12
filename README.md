# Yahoo-Finance-Scraper
Jupyter Notebook to scrape Yahoo finance website

2 ways to fetch stock value:

1. Change the name of the company for which you want the stock data and then run Stock_Data_Main.ipynb and enter 'Yes' in the console to get values from Yahoo API

2. Fetch stock data by scraping Yahoo finance page, run Stock_Data_Main.ipynb and enter 'No' in the console 

Graph Generation:
X-axis – Date
Y-axis- Stock value

•	For each data we find the open value, close value of the stock, find the mid value of these values. The mid value is y coordinate and date is the x coordinates of a point. 

•	Status is a new column in the data set which stores the trend of the stock on that day based on the open and close values. (Possible values for status are increasing, decreasing, equal)

•	The increasing stock is shown in green and decreasing stock is shown in red.

•	The height of the bar is absolute value of the difference between close and open value.

•	Once the bar graph is generated, we place a line graph over the bar graph.

Python Version: 3.6.1

Install Libraries:   pip3 install PyQt5


![alt text](https://github.com/RadhikaKalaiselvan/Yahoo-Finance-Scraper/blob/master/Sample%20Output.png)
