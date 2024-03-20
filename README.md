# Disney Movie Data Scraping Project

This project involves scraping data about Disney movies from Wikipedia using Python libraries such as BeautifulSoup and Requests. The scraped data includes information about various Disney movies, such as their titles, release dates, directors, and more. The scraped data is then cleaned and stored in a CSV file for further analysis.

## Project Structure

- **Data Scraping**: 
  - The `disney_movie_scraper.ipynb` notebook contains the code for scraping data about Disney movies from Wikipedia.
  - It utilizes the BeautifulSoup library to parse HTML content and extract relevant information.
  - The scraped data is cleaned and stored in a JSON format before being converted to a Pandas DataFrame.
  
- **Data Cleaning**: 
  - The cleaned data is then saved as a CSV file named `disney_movie_data_final.csv`.
  
- **Data Analysis**: 
  - The Pandas DataFrame provides insights into various attributes of Disney movies, such as release dates, directors, and more.

## Usage

1. **Data Scraping**: 
   - Open the `disney_movie_scraper.ipynb` notebook in Google Colab or any Python environment.
   - Run the notebook to scrape data about Disney movies from Wikipedia.
   
2. **Data Cleaning**: 
   - Once the scraping is complete, the scraped data will be saved in a JSON file named `disney_data_cleaned.json`.
   - Load the cleaned data into a Pandas DataFrame.
   
3. **Data Analysis**:
   - The `disney_movie_data_final.csv` file contains the cleaned data, which can be further analyzed using Python libraries like Pandas and Matplotlib.

## Requirements

- Python 3.x
- Libraries: BeautifulSoup, Requests, Pandas

## Credits

- Data is scraped from Wikipedia, a free online encyclopedia.
