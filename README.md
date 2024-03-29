# html-challenge
In this challenge, we have scraped data from a Mars news article as well as a table of Mars weather data to learn more about the planet.
> Checklist:
   - Mars news:
       - Used automated browsing to visit the given url and created a BeautifulSoup object to scrape text elements from the site.
       - Created a For Loop to loop through the elements we have found.
       - Created dictionaries to store each element we are looking for and then created a list of dictionaries.
   - Mars weather:
       - Used automated browsing to visit the given url and created a BeautifulSoup object to scrape HTML table data.
       - Created a For Loop to look through the elements we extracted.
             - Appended each row to a list.
       - Used the newly created list to create a Pandas DataFrame with a list of column headers included.
       - Converted column data types for analysis purposes.
       - Used Pandas functions such as .groupby, .count, .mean to analyze data.
       - Created charts via (Pandas .plot) as well as Matplotlib to format/label the charts properly.
       - Wrote the DataFrame out to a CSV file.
