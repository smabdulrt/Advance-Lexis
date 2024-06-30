# Advance Lexis Website Scraping Project

## Overview
This project involves scraping public website from the Lexis Advance platform to extract valuable information for research and analysis. The data gathered will be used for various purposes including legal research, market analysis, and content aggregation.

## Features
- **Data Extraction:** Scrapes specified public pages from Lexis Advance websites.
- **Data Cleaning:** Processes and cleans the scraped data to ensure accuracy and usability.
- **Storage:** Saves the cleaned data into a structured format (CSV, JSON, or a database).
- **Scheduling:** Supports scheduling for periodic scraping to keep the data up-to-date.
- **Logging:** Logs the scraping process and any errors encountered for troubleshooting.

## Requirements
- Python 3.x
- BeautifulSoup4
- Requests
- pandas
- Scrapy 
- Selenium
- webDriver manager
- Openpyxl

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/lexis-scraping.git
    cd lexis-scraping
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. **Run the scraper:**
    ```sh
    scrapy crawl advance_lexis
    ```

## File Structure
```plaintext
advance-lexis/
├── advance_lexis/                   # Directory to spider and spider settings
├── advance_lexis.xlsx               # sample output
├── cookies.pkl                      # cookies stored
├── input_file.xlsx                  # input urls
├── runner.bat                       # to run the spider
└── README.md                        # Project documentation
```

## Contributing
1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The [Scrapy](https://docs.scrapy.org/en/latest/) library for parsing HTML and XML documents.
- The [Selenium](https://www.selenium.dev/documentation/) library for making HTTP requests.
- The [pandas](https://pandas.pydata.org/) library for data manipulation and analysis.

## Contact
For questions or support, please contact [smabdulrt@gmail.com](mailto:smabdulrt@gmail.com).

---

Feel free to modify this README file to suit the specific details of your project. Happy scraping!
