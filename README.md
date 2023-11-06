# Web Scraping and Analysis Tool

## Overview

InsightSpider automates the process of scraping website data and analyzing it to extract key insights. This tool could be invaluable for businesses looking to understand their competitive landscape or market trends.

## Installation

Before installing the required packages, ensure you have Python 3.6 or later installed. Then, follow these steps to set up the Web Scraping and Analysis Tool:

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/AkashKarnatak/InsightSpider.git
   cd InsightSpider
   ```

2. Install the required Python dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Rename `config-example.yaml` file to `config.yaml` and replace `'YOUR_OPENAI_API_KEY'` with your actual OpenAI API key, and add the URLs you wish to scrape to the `scrape_urls` list.

## Usage

To run the scraper and analysis:

```sh
python3 scraper.py
```

This will:
- Scrape data from the configured URLs.
- Save the scraped content in markdown format in the `scraper_db` directory as `.json` files.
- Analyze the scraped data using OpenAI's GPT model.
- Save the analysis in both raw text and CSV format for easy viewing and processing.

## License

This project is licensed under the AGPL3 License. For details, see the [LICENSE](LICENSE) file.
