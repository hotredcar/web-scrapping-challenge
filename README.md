# web-scrapping-challenge-

In this assiggnment, we extracted information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. 

There were 2 elements to this assignment: 

Part 1: Titles and preview texts were scraped from Mars news articles <https://static.bc-edx.com/data/web/mars_news/index.html>. The code was saved as <part_1_mars_news.ipynb>.

Part 2: Mars weather data, which existed in a table <https://static.bc-edx.com/data/web/mars_facts/temperature.html> was scraped and analysed. The code was saved as <part_2_mars_weather>. 

A quick summary of the parameters:
id:         the identification number of a single transmission from the Curiosity rover terrestrial_date: the date on Earth
sol:        the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls:         the solar longitude
month:      the Martian month
min_temp:   the minimum temperature, in Celsius, of a single Martian day (sol)
pressure:   The atmospheric pressure at Curiosity's location

The data collected was organised, analysed and finally imported as <mars_data.csv>