# 🛒 Price Comparison Tool
## Overview
The Price Comparison Tool is a web application that allows users to compare product prices across different e-commerce platforms and helps them find the best deals. The application scrapes product data from multiple online stores, processes the information, and displays the product with the lowest price to the user.
## Key Features
Web Scraping: Scrapes product data like names, prices, and URLs from various e-commerce websites.
Price Comparison: Compares prices of the same product across different websites and highlights the best deal.
User Interface: A clean, intuitive interface for users to search for products and view price comparisons.
Secure Access: The app securely interacts with websites, respecting the robots.txt policies where applicable.
Currency Conversion: (Optional) Convert prices if multiple currencies are involved.
API Support: Integrates with e-commerce platforms that provide official APIs (optional).
## Tech Stack
Backend:
Python: The core logic of the application and web scraping functionality is built using Python.
Flask/Django: A web framework to handle backend logic and serve the data to the frontend.
BeautifulSoup / Scrapy: Python libraries used to scrape the product data from websites.
Frontend:
HTML/CSS/JavaScript: For building the user interface.
React.js (optional): For a more dynamic and interactive user experience.
Database:
SQLite/PostgreSQL/MySQL: Used to store the scraped product information.
## How It Works
User Input: The user inputs the name or URL of the product they want to search.
Web Scraping: The application scrapes multiple e-commerce websites to gather the prices of the specified product.
Comparison: Once the data is collected, the app compares prices, taking into account any additional shipping costs or discounts.
Result Display: The user is presented with the product and the e-commerce site offering it at the lowest price.
## Installation and Setup
To run the project locally, follow the steps below:

1. Clone the Repository
2. Install the Dependencies
```
pip install django-jazzmin
pip install bs4
pip install selenium
pip install requests
```
4. Set Up the Database:
Configure your database (e.g., SQLite, PostgreSQL).
5. Run the migration commands (for Django).
```
python manage.py migrate
python manage.py runserver
```
6. Access the App:
Open your browser and navigate to http://localhost:8000 (for Django).
## Usage
Enter the product name or link.
Click "Search" to begin price comparison.
The application will display the lowest-priced product across the e-commerce websites.
## Contact
For any queries or suggestions, feel free to reach out at:
```
Vishnu Vijayan
Email: vishnuvijayan@example.com
GitHub: Kizhakkekkara-Vishnu-Vijayan
```
## Documentation
For detailed understanding of the project go throught the documentation part of the price comparison website.
