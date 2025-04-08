# 🌍 World Holidays 2025 Scraper

This project is a Python-based web scraper that collects public holiday data for different countries in the year 2025.

## 🚀 Features

- Scrapes world holiday data for the year 2025
- Supports command-line interface (CLI) for ease of use
- Saves data in a structured format (e.g., CSV or Excel)
- Easy to extend for other years or additional countries
- Clean and well-commented codebase

## 🛠️ Technologies Used

- Python 3
- BeautifulSoup (for HTML parsing)
- Requests (for making HTTP requests)
- argparse (for CLI support)
- pandas (for data handling)
- openpyxl (for Excel file export)

## 🌐 Data Source

Holiday data is scraped from [calendarific.com](https://calendarific.com)

## 🔧 Setup Instructions

1. Clone the repository:
```bash
    git clone git@github.com:sumitgit1912/world-holidays-2025-scraper.git
    cd world-holidays-2025-scraper
```

2. Install the required packages:
```bash
    pip install -r requirements.txt
```

## 🧰 CLI Usage
```bash
    python world_holiday_scraper.py --format excel
```

## 📁 Project Structure
```plaintext
world-holidays-2025-scraper/
├── world_holiday_scraper.py
├── holidays.xlsx  # or holidays.csv
├── requirements.txt
└── README.md

