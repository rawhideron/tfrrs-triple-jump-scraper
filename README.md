# TFRRS Triple Jump Scraper

This project scrapes triple jump data from TFRRS (https://tf.tfrrs.org) and saves it to a CSV file.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/rawhideron/tfrrs-triple-jump-scraper.git
```

2. Install dependencies:
```bash
npm install
```

## Usage

Run the scraper:
```bash
npm start
```

The script will:
1. Navigate to TFRRS
2. Search for Cole Goodman's results
3. Extract triple jump data
4. Save the data to C:\Users\Rawhi\Documents\cole_goodman_tripple_jump.csv

## Dependencies

- Puppeteer for web scraping
- csv-writer for CSV file creation

## Note

Make sure you have proper permissions to write to the specified directory path.