# amazon-web-scraper

This project is a web scraper designed to extract product information from eBay listings. The scraper specifically targets eBay listings for car shocks and gathers details such as the item title, condition, price, placement, included items, seller name, and seller rating. The collected data is saved into a CSV file for further analysis.

## Features:
  1. Scrapes multiple product listings from eBay based on a search term.
  2. Extracts key details including:
     - Product title
     - Condition
     - Price
     - Placement on the vehicle
     - Items included with the product
     - Seller name and rating
  3. Saves the data into a structured CSV format.

## Technologies Used:

  - Python: Core programming language.
  - BeautifulSoup: Library for parsing HTML and extracting product details.
  - Requests: For making HTTP requests and fetching webpage data.
  - Pandas: For data manipulation and saving the results to a CSV file.
  - NumPy: For data cleaning operations.

## Requirements

Before running the script, make sure to install the following Python libraries:

    pip install requests beautifulsoup4 pandas numpy

## How to Use

  1. Clone this repository:
  
    git clone https://github.com/Rupert-S/ebay-web-scraper
    
    cd ebay-web-scraper

  2. Open the web_scraper_final.ipynb notebook in Jupyter Notebook or Jupyter Lab.

      Run the script. The scraper will fetch product listings for "car shocks" on eBay, extract relevant details, and store them in a CSV file named ebay_car_shocks.csv.

### Customization

  To scrape a different product, change the URL variable in the script to target a different eBay search query.

## Output

The scraper generates a CSV file (ebay_car_shocks.csv) with the following columns:

  - title: Product title.
  - condition: Product condition (e.g., new, used).
  - price: Price of the product.
  - items: Items included in the sale.
  - placement: Placement of the part on the vehicle.
  - seller_name: Name of the seller.
  - seller_rating: Seller’s rating on eBay.
