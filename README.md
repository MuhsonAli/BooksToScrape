# BooksToScrape
BooksToScrape is a Python script for extracting data from a bookstoscrape.com. It scrapes details such as titles, prices, and 
image URLs for each book in various categories and saves this data in CSV format. Additionally, it downloads the images of each book.

## Features
- Extracts book details from each category on bookstoscrape.com.
- Downloads book images.
- Saves data in CSV files, one for each category.
- Packages the CSV and images into a ZIP file for each category.

## Installation
To run this script, you need Python installed on your system. Clone this repository to your local machine:
```bash
git clone https://github.com/MuhsonAli/BooksToScrape.git
cd BooksToScrape
```

## Usage
To run the script, navigate to the project directory and execute:
```bash
python mod5.py
```

## Output
After running the script, you will find the following in the project directory:
- A directory for each book category containing the downloaded images.
- A CSV file for each category with book details.
- A ZIP file for each category containing the corresponding CSV file and image files.
