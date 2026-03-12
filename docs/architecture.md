# LinkedIn Scraper Architecture

This project is an automation tool that collects LinkedIn posts mentioning specific keywords like "Adya AI".

## Workflow

1. Selenium launches Chrome browser
2. Script logs into LinkedIn
3. LinkedIn search is performed
4. Script scrolls through search results
5. Page HTML is captured
6. BeautifulSoup extracts post data
7. Data is cleaned using Pandas
8. Data is saved to:
   - JSON file
   - SQLite database
   - Google Sheets

## Tech Stack

- Python
- Selenium
- BeautifulSoup
- Pandas
- SQLite
- Google Sheets API
- Jupyter Notebook