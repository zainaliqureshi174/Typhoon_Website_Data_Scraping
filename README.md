# Web Scraping Project for Extracting Structured HTML Content
## Project Description
This project involves web scraping specific content from webpages. The task was to extract HTML elements like h1, h2, h3, p, and ul from a list of URLs stored in a CSV file and save the extracted structured content into a new CSV file. The scraped data is formatted to preserve the hierarchical structure of headers and lists from the source web pages.

## Technologies Used:
Python: Used as the main programming language for scripting.
Selenium: A web automation tool for navigating and scraping web pages.
Pandas: For handling CSV files and data storage.
Numpy: (if required for data manipulation during analysis or saving processes).
Chrome WebDriver: Automates interactions with the Chrome browser using Selenium.

## Key Features:
Extracts and formats HTML content from specific tags (h1, h2, h3, p, ul).
Supports traversing and parsing li elements within ul tags to retain list formatting.
Handles multiple URLs by reading from a CSV file.
Saves extracted data in a new CSV file for easy access and reuse.

## Files:
Typhoon.csv: Contains the URLs to scrape.
extracted_webpage_content.csv: Output file with structured HTML content from each webpage.
main_script.py: The main script containing the logic for scraping and saving data.

## Instructions to Run:
Install necessary dependencies by running:

pip install pandas selenium webdriver-manager

Ensure that Chrome is installed, as this script uses Chrome WebDriver.

Place the URLs in a CSV file (e.g., Typhoon.csv). The URLs should be in the third column (index 2).

Run the main script to extract and save the content:

Typhoon_Website_Data_Scraping.ipynb
The output file (extracted_webpage_content.csv) will contain two columns: the URL and the corresponding structured HTML content.

Libraries Required:
selenium
pandas
webdriver-manager
Future Improvements:
Implementing error handling for failed page loads or missing elements.
Adding support for scraping additional HTML elements or attributes based on future client requirements.
Introducing multithreading to speed up the extraction process for a large number of URLs.

## Project Completion: Successfully completed via Upwork.
## Developer: Muhammad Zain Ali

