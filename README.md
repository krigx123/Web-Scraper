
# Wikipedia Scraper

This project is a simple Python script that scrapes Wikipedia articles by following random internal links starting from a given URL. It retrieves the title of each article it visits and continues the process recursively.


## Features

- Scrapes Wikipedia article titles.
- Follows random internal links to navigate to the next article.
- Demonstrates recursive web scraping.


## Usage/Examples

- Open the script file and locate the starting URL in the scrapeWikiArticle function call:
```python
scrapeWikiArticle("https://en.wikipedia.org/wiki/Web_scraping")
```
Replace the URL with your desired starting Wikipedia article.

- Run the script:
```bash
python script_name.py
```

- Example Output:
```python
Web scraping
QVC
XHTV-TDT
State of Mexico
Jocotitlán
Tlalmanalco
Chimalhuacán
Help:IPA/Spanish
Close front unrounded vowel
Polish phonology
```

