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
 > Images:
    - Mars news   
    <img width="300" alt="Screenshot 2023-08-25 at 12 25 50 PM" src="https://github.com/coryselzer/html-challenge/assets/134936973/25e5fe7f-1a41-4f81-acbe-97e00361700c">
    - Mars weather
    <img width="300" alt="Screenshot 2023-08-25 at 12 26 36 PM" src="https://github.com/coryselzer/html-challenge/assets/134936973/b8706f11-4a8d-4c7e-aace-3454db207ee7">

