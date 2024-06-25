# Nike Shoe Web Scraper Project

## About

This project involves creating a web scraper to monitor the price of Nike shoes from the Nike website. The scraper extracts the shoe title, price, and the date of extraction, and stores this data in a CSV file. This allows for tracking price changes over time.

## Purposes Of The Project

The main aim of this project is to automate the process of monitoring the price of a specific Nike shoe, enabling users to track price changes and potentially make purchasing decisions based on the trends observed.

## About Data

The data collected from the Nike website includes the following columns:

| Column   | Description                          | Data Type      |
| :------- | :----------------------------------- | :------------- |
| Title    | The title of the Nike shoe           | VARCHAR(100)   |
| Price    | The price of the Nike shoe           | DECIMAL(10, 2) |
| Date     | The date when the data was collected | DATE           |

### Analysis List

1. Web Scraping
   > Connect to the Nike website and extract the title and price of a specific shoe.

2. Data Storage
   > Store the extracted data in a CSV file for tracking purposes.

3. Function Implementation
   > Combine the scraping and data storage functionality into a reusable function.

## Approach Used

1. **Web Scraping:**
   - Use the `requests` library to connect to the Nike website and retrieve the HTML content.
   - Use `BeautifulSoup` to parse the HTML content and extract the shoe title and price.

2. **Data Storage:**
   - Use the `csv` library to write the extracted data into a CSV file.
   - Implement functionality to append new data to the CSV file on subsequent runs.

3. **Function Implementation:**
   - Combine the web scraping and data storage code into a function `check_price()` that can be run periodically to update the CSV file with the latest price.

# Conclusion

This project automates the process of monitoring the price of a specific Nike shoe by scraping the data from the Nike website and storing it in a CSV file. This enables users to track price changes over time and make informed purchasing decisions.

For more details, you can view the full Jupyter notebook file [HERE](https://github.com/Dilan-GitHub/NikeShoeWebScrapperPython/blob/main/Nike%20Shoe%20Web%20Scraper%20Project.ipynb).
