# Mars-Analysis-Challenge

# Background 

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

# Part 1: Scrape Titles and Preview Text from Mars News

1. **Automated Browsing:**
   - Visit the [Mars news site](https://www.example-mars-news-site.com).
   - Inspect the page to identify elements for scraping.

2. **Web Scraping:**
   - Create a Beautiful Soup object to extract text elements from the website.
   - Extract titles and preview text of news articles.

3. **Data Storage:**
   - Store results in Python data structures:
     - Each title-and-preview pair in a Python dictionary.
     - Dictionaries with keys: 'title' and 'preview'.
     - Store all dictionaries in a Python list.

4. **Display the Scraped Data:**
   - Print the list of dictionaries in the Jupyter Notebook.

5. **Optional: Export to JSON:**
   - Optionally, store the scraped data in a file.
   - Export the scraped data to a JSON file.

---

# Part 2: Scrape and Analyze Mars Weather Data

1. **Automated Browsing:**
   - Visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
   - Inspect the page to identify elements for scraping.

2. **Web Scraping:**
   - Create a Beautiful Soup object to scrape data in the HTML table.
   - Assemble the scraped data into a Pandas DataFrame.

3. **Data Cleaning:**
   - Examine and convert data types if necessary (datetime, int, float).

4. **Data Analysis:**
   - Answer questions using Pandas functions:
     - How many months exist on Mars?
     - How many Martian days worth of data exist in the dataset?
     - Coldest and warmest months on Mars (average minimum daily temperature).
     - Months with the lowest and highest atmospheric pressure on Mars (average daily pressure).
     - Estimate terrestrial days in a Martian year by plotting daily minimum temperature.

5. **Export to CSV:**
   - Export the DataFrame to a CSV file.
