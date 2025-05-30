# amazon_web_scarping
This Jupyter Notebook provides a solution for scraping product information from Amazon. It extracts details such as product title, price, rating, number of reviews, and availability for items listed on Amazon search result pages.

Features
Product Information Extraction: Functions to reliably extract key product details from Amazon product pages, including:
Title
Price
Rating
Number of reviews
Availability status
Dynamic Product Listing Scraping: Iterates through product links found on an Amazon search results page to gather detailed information for each product.
Data Export: Saves the scraped data into a CSV file (amazon_data.csv) for further analysis.
Data Handling: Utilizes Pandas for data manipulation, including handling missing titles and dropping incomplete records.
Technologies Used
Python
BeautifulSoup: For parsing HTML content.
Requests: For making HTTP requests to Amazon.
Pandas: For data structuring and analysis.
NumPy: For numerical operations and NaN handling.
Matplotlib and Seaborn: (Used for potential data visualization, although specific plots are not detailed in the provided code snippet).
How to Use
Install Dependencies: Ensure you have all the necessary libraries installed. You can install them using pip:
Bash

pip install beautifulsoup4 requests pandas numpy matplotlib seaborn
Set User-Agent: Update the HEADERS variable in the notebook with a valid User-Agent string to mimic a web browser and avoid being blocked by Amazon.
Define Target URL: Modify the URL variable to specify the Amazon search results page you wish to scrape. Currently, it is set to search for "play station 5" on Amazon India.
Run the Notebook: Execute all cells in the Jupyter Notebook sequentially.
Output
Upon successful execution, the notebook will generate an amazon_data.csv file in the same directory, containing the scraped product details
