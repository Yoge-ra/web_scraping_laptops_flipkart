
# Web Scraping Flipkart Laptops

This repository contains a Python script for web scraping laptop data from the Flipkart website. The script extracts information such as product names, prices, ratings, AND SPECIFICATION. You can use this script to collect data for your own analysis or project.

## Requirements

Before running the script, ensure you have the following installed:

- **Python 3.12**
- **BeautifulSoup library**
- **Pandas library**
- **Requests library**

You can install the required libraries using the following command:

```bash
pip install beautifulsoup4 pandas requests
```

## Usage

1. Clone this repository or download the script `flipkart_web_scraping.ipynb`.
2. Open the script in a text editor.
3. Update the `url` variable with the desired Flipkart search URL (e.g., the URL for Gaming laptops).
4. Run the script using the following command:

The script will scrape the data from Flipkart and save it to a CSV file named `gaming_laptops.csv`.

## Output

The generated CSV file contains the following columns:

- **Name**: The name of the laptop product.
- **Price**: The regular price of the laptop
- **Ratings**: Customer ratings.
- **Specification**: Describes the laptops features.

Feel free to customize this README to include any additional information specific to your project. Happy scraping! 🚀

---
