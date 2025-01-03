# Flipkart-Product-Scraper
This project is a web application built using Flask and Selenium that scrapes product details from Flipkart for specified search queries. It collects product names, prices, and image URLs for a list of search terms and displays the results on a webpage.
# Flipkart Product Scraper with Flask

This project demonstrates a Python web application that scrapes product details from Flipkart using Selenium and displays them in a web interface built with Flask.

## Features
- Scrapes product names, prices, and images for predefined search terms.
- Uses Selenium for web scraping.
- Displays the scraped data on a webpage.

## Requirements
To run this project, you need to have the following installed:
- Python 3.6+
- Google Chrome browser
- ChromeDriver (compatible with your Chrome version)
- Required Python packages:
  - Flask
  - Selenium

## Installation
1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Install the required Python packages:
    ```bash
    pip install flask selenium
    ```
4. Download and set up ChromeDriver:
    - Download ChromeDriver from [ChromeDriver Downloads](https://chromedriver.chromium.org/downloads).
    - Place the `chromedriver` executable in your system's PATH or the project directory.
## Clone the repository
```bash
git clone https://github.com/Pooja389/Flipkart-Product-Scraper.git
```
## Usage
1. Define the search terms in the `intersested_searches` list in the Python script.
2. Run the application:
    ```bash
    python webscraper.py
    ```
3. Access the web application at `http://127.0.0.1:5000` in your browser.

### Flask Web Application
- **`Flask`**: Used to create a simple web server.
- **`render_template`**: Renders an HTML template to display the scraped data.

### Selenium Web Scraper
- **Search Terms**: The `intersested_searches` list contains the predefined search terms.
- **Scraping**: Uses Selenium to scrape product names, prices, and image URLs from Flipkart.
- **Data Collection**: Combines scraped data into a list of tuples and passes it to the Flask application.

### Output
Each search displays:
- Product Name
- Price
- Product Image

## Notes
- Make sure Flipkart allows scraping for personal or educational purposes.
- Be mindful of Flipkart's terms of service.
- This script is intended for educational purposes only.

## License
This project is licensed under the MIT License.
