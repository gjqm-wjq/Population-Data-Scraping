# Population Data Scraping

This repository contains Python scripts for scraping population milestone data from Wikipedia pages and exporting it to Excel files.

## Table of Contents
- [Description](#description)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Scripts](#scripts)
- [License](#license)

## Description
The scripts in this repository scrape population milestone data from the Wikipedia page [World Population Milestones](https://en.wikipedia.org/wiki/World_population_milestones). Three different scripts are provided, each targeting specific tables on the page:

- `main1.ipynb`: Scrapes population data from a specific table containing columns 'Country/nationality', 'Population', 'Born (date)', 'Name', and 'Notes'.
- `main2.ipynb`: Extracts population milestone data from a table titled 'World population milestones in billions (UN estimates)'.
- `main3.ipynb`: Scrapes data from a table with USCB estimates.

## Dependencies
- Python 3.x
- Requests library
- BeautifulSoup library
- Pandas library

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the desired script(s) to scrape the population data.
4. Check the generated Excel files for the extracted data.

## Scripts
- `main1.ipynb`: Scrapes population data from a specific table on the Wikipedia page.
- `main2.ipynb`: Extracts population milestone data from a specific table on the Wikipedia page.
- `main3.ipynb`: Scrapes data from a table with USCB estimates on the Wikipedia page.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
