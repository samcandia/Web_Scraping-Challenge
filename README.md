# Background 

In this challenge I collected data, organized and stored data, analyzed data, and then visually communicated my insights.

## Part 1: Scraped titles and previewed text from Mars news articles.

1. Used automated browsing to visit the Mars news site and inspected the page to identify which elements to scrape.

2. Created a Beautiful Soup object and used it to extract text elements from the website.

3. Extracted the titles and previewed text of the news articles that were scraped and stored the scraped results in a Python data structure as follows:

    {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
     'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
 
## Part 2: Scraped and Analyzed Mars Weather Data

1. Used automated browsing to visit the Mars Temperature Data Site and Inspected the page to identify which elements to scrape.

2. Created a Beautiful Soup object and used it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, I used Beautiful Soup here to continue sharpening my web scraping skills.

3. Assembled the scraped data into a Pandas DataFrame

4. Examined the data types that are currently associated with each column. If necessary, casted (or converted) the data to the appropriate datetime, int, or float data types.

5. Analyzed the dataset by using Pandas functions to answer the following questions:

-How many months exist on Mars?

-How many Martian (and not Earth) days worth of data exist in the scraped dataset?

-What are the coldest and the warmest months on Mars (at the location of Curiosity)?
     Plotted the results as a bar chart.
     
-Which months have the lowest and the highest atmospheric pressure on Mars?

    Plotted the results as a bar chart.
-About how many terrestrial (Earth) days exist in a Martian year? 

    Considered how many days elapse on Earth in the time that Mars circles the Sun once.

6. Export the DataFrame to a CSV file.
