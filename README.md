# AllSurplus Web Scraper

A Python-based web scraping tool that automates the extraction of auction data from AllSurplus, including lot details, bids, and closing dates. It also fetches average listed and sold prices from eBay for comparison, saving the results to a CSV file for analysis. Built with Selenium, BeautifulSoup, and Pandas.

---

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Support](#support)

---

## Features
- **Automated Login**: Automatically logs into the AllSurplus website using provided credentials.
- **Data Extraction**: Extracts detailed information about auction items, including lot numbers, titles, locations, models, current bids, and closing dates.
- **eBay Price Comparison**: Fetches average listed and sold prices from eBay for the extracted items.
- **CSV Export**: Saves the extracted data along with eBay price comparisons into a CSV file for further analysis.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/AllSurplus-Web-Scraper.git
   cd AllSurplus-Web-Scraper
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.8+ installed. Then, install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up ChromeDriver**:
   - Download the appropriate version of ChromeDriver for your Chrome browser from [here](https://sites.google.com/chromium.org/driver/).
   - Ensure the ChromeDriver executable is in your system's PATH or specify its location in the script.

---

## Usage

1. **Run the Script**:
   ```bash
   python allsurplus.ipynb
   ```

2. **Input Credentials**:
   - The script will prompt you to input your AllSurplus and eBay credentials if not already hardcoded.

3. **Output**:
   - The script will generate a CSV file named `allsurplus.csv` containing the extracted data and eBay price comparisons.

---

## Configuration

- **AllSurplus Credentials**: Update the `email_input` and `password_field` sections in the script with your AllSurplus login credentials.
- **eBay Credentials**: Update the `email_field` and `password_field` sections in the script with your eBay login credentials.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- **Selenium** for browser automation.
- **BeautifulSoup** for HTML parsing.
- **Pandas** for data manipulation and CSV export.

---

## Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.

---



