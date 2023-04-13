# French Notaries Directory Scraper

This Python script uses the `requests`, `BeautifulSoup`, and `csv` libraries to scrape data from the French notaries' directory page (https://www.notaires.fr/fr/directory/notaries), and stores it in a CSV file.

## How to Use

To use this program, you will need to have Python 3.x and the following libraries installed:

- requests
- BeautifulSoup
- csv

You can install these libraries using pip:
```
pip install requests
pip install beautifulsoup4
pip install csv
```


To run the script, navigate to the directory containing the script and run:
```
python notaires_scraper.py
```

The script will loop through all pages of the directory and extract the name, phone number, email, and website of each notary. The extracted information will be stored in a list of lists and saved in a CSV file called `notaires.csv`.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute this code as you see fit.
