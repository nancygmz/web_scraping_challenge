# Mars Webscraping Challenge
Scrape and Analyze Mars Weather Data 

## Extracted News Articles 
Created a Beautiful Soup object to extract text elements from https://static.bc-edx.com/data/web/mars_news/index.html.

Extracted titles and preview text of news articles and stored the scraping results in Python data structures.

Stored each title-and-preview pair in a Python dicitonary and gave each dictionary two keys: title and preview.

Stored all the dictionaries n a Python list.

Exported scraped data to a JSON file.

## Extracted Weather Data
Created a Beautiful Soup object to scrape temperature data for Mars from the html table at https://static.bc-edx.com/data/web/mars_facts/temperature.html.

The scraped table data was assembled into a Pandas DataFrame using the heading names for column headings.

Data types were evaluated and convereted where appropriate to dateime, int, or float data types.

Data file was exported as csv file.

## Analysis of Data
Analyzed the dataset by using Pandas functions to answer the following questions about Mars.

How many months exists on Mars? 
12

How many Sols (Martian Days) worth of data exist in the scraped dataset? 
1867

What are the coldest and warmest months on Mars (at the location of Curiosity)? 
Plotting the average low temperature on mars we can determine on average the coldest month is the 3rd month. On average the warmest month is the 8th month.

![avg_low-tempertuare on Mars](https://github.com/nancygmz/web_scraping_challenge/blob/main/graphs/avg_temp.png)

Which month, on average, has the lowest atmospheric pressure? The highest?
Plotting the average atmospheric pressure by month, we can determine that atmospheric pressure on average is lowest in the sixth month and highest in the ninth.

![avg_pressure on Mars](https://github.com/nancygmz/web_scraping_challenge/blob/main/graphs/avg_pressure.png)
