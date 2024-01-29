Module 11 Challenge
Background:
You are now equipped to undertake a comprehensive web-scraping and data analysis project. You have acquired the skills to identify HTML elements on a webpage, extract information using both automated browsing with Splinter and HTML parsing with Beautiful Soup, and scrape various types of data such as HTML tables and recurring elements like news articles.

As you tackle this challenge, keep in mind that you are reinforcing essential skills in data collection, organization, storage, analysis, and visualization.

What You're Creating:
This assignment involves two technical products. You will deliver the following:

Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data, available in a table.

Files:
Download the necessary files to begin your project.

Instructions:
Part 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook named part_1_mars_news.ipynb in the provided starter code folder.
Follow the steps outlined in the notebook to scrape the Mars News website.
Utilize automated browsing to navigate to the Mars news site and inspect the page to identify elements for scraping.
Extract titles and preview text from the news articles, storing the results in Python data structures:
Each title-and-preview pair should be stored in a Python dictionary with two keys: 'title' and 'preview'.
Example: {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
Store all dictionaries in a Python list and print the list in the notebook.
Optionally, export the scraped data to a JSON file.
Part 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook named part_2_mars_weather.ipynb in the provided starter code folder.
Follow the steps outlined in the notebook to scrape and analyze Mars weather data.
Utilize automated browsing to navigate to the Mars Temperature Data Site and identify elements for scraping.
Assemble the scraped data into a Pandas DataFrame with appropriate column headings.
Analyze the dataset using Pandas functions to answer specific questions about Mars weather data, such as:
How many months exist on Mars?
How many Martian days of data are available?
Identify the coldest and warmest months on Mars.
Determine which months have the lowest and highest atmospheric pressure.
Estimate the number of Earth days in a Martian year.
Export the DataFrame to a CSV file.
These instructions will guide you through the process of completing the assigned tasks effectively. Adjust as necessary based on your specific requirements and findings.
