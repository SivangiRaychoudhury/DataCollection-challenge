# DataCollection-challenge

In this challenge, I will be collecting data, organizing and storing data, analyzing data and then visually communicating my insights. This challenge is divided into two parts. 
1. Scrape titles and preview text from the Mars news article.
2. Scrape and analyze Mars weather data, which exists in the table.
To achieve these, Jupyter notebook is used with python libraries like BeautifulSoup and Splinter, pandas and matplotlib.

PART 1:
In this part, I worked on the file named part_1_mars_news.ipynb, to scrape the website.
1. Use automated browsing to visit the Mars news site Links to an external site. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
   - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
   - Store all the dictionaries in a Python list.
   - Print the list in your notebook.

PART 2:
In this part, I worked on the file named part_2_mars_weather.ipynb, to scrape the mars weather data.
1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
   - id: the identification number of a single transmission from the Curiosity rover
   - terrestrial_date: the date on Earth
   - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
   - ls: the solar longitude
   - month: the Martian month
   - min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
   - pressure: The atmospheric pressure at Curiosity's location
4. Examine the data types that are currently associated with each column. I have to convert the data to the appropriate datetime, int, or float data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:
   - How many months exist on Mars?
   - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
   - What are the coldest and the warmest months on Mars (at the location of Curiosity)? Plot the results as bar chart.
   - Which months have the lowest and the highest atmospheric pressure on Mars? Plot the results as bar chart.
   - About how many terrestrial (Earth) days exist in a Martian year? Visually estimate the result by plotting the daily minimum temperature.
6. Export the DataFrame to a CSV file.






