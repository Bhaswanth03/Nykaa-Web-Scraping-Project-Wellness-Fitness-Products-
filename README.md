# Nykaa-Web-Scraping-Project-Wellness-Fitness-Products-

This project focuses on scraping product data from Nykaa’s wellness, fitness, and recovery category using Selenium and BeautifulSoup.  The goal is to extract structured product-level data for further analysis and insights.

# Features

Extracts product URLs dynamically using Selenium
Scrapes detailed product information:
Product Name
Category & Sub-category
Price & Discount
Seller Information
Return Policy
Ratings & Reviews
Pilot batch testing for validation
Handles partial extraction and saves progress

# Tech Stack

Python
Selenium
BeautifulSoup
Pandas
NumPy
WebDriver Manager

# Workflow

Step 1: Extract Product Links
Scrape all product URLs from Nykaa category page
Step 2: Pilot Run
Test extraction logic on a small subset of links
Step 3: Full Scraping
Iterate through all product URLs
Extract required attributes
Step 4: Data Storage
Save extracted data into CSV files
Step 5: Data Preparation
Clean and structure data for further EDA

# Challenges Faced

Dynamic content loading (handled using Selenium)
Network interruptions during scraping
Partial data extraction

# Future Improvements

Add exception handling for robust scraping
Implement retry mechanism for failed URLs
Use headless browser for faster execution

# Use Cases

Price analysis
Product comparison
Market research
Recommendation systems

# Author

Bhaswanth Kalluru
