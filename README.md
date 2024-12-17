# Google Play Store Review Scraper

## Introduction

The Google Play Store Review Scraper is a Python-based tool designed to automate the process of extracting user reviews from the Google Play Store. With the increasing importance of user feedback in app development and marketing, this tool provides a convenient way to gather insights from reviews. By allowing users to filter reviews based on star ratings, it helps in analyzing user sentiment and improving app quality.

## Overview

This project is a Python script that utilizes Selenium to scrape reviews from the Google Play Store. It allows users to specify the number of reviews they want to scrape and filter them based on star ratings. The scraped reviews are then saved into a Word document for easy access and readability.

## Features

- **Scrape Reviews**: Extract reviews from the Google Play Store based on user-defined criteria.
- **Filter by Star Rating**: Users can choose to scrape all reviews or filter them by 1 to 5-star ratings.
- **Random Delays**: The script includes random delays to mimic human-like behavior during scraping, reducing the risk of being blocked by the website.
- **Save to Word Document**: The scraped reviews are saved in a `.docx` file, making it easy to read and share.

## Requirements

To run this script, you need the following:

- Python 3.x
- SeleniumBase
- python-docx
- A compatible web driver (e.g., ChromeDriver for Google Chrome)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SafeerAbbas624/Google_Play_Store_Review_Scraper.git
   cd repository-name
   ```

2. Install the required packages:
   ```bash
   pip install seleniumbase python-docx
   ```

3. Ensure you have the appropriate web driver installed and added to your system's PATH.

## Usage

1. Run the script:
   ```bash
   python main.py
   ```

2. Follow the prompts:
   - **Enter the Google Play Store link**: Provide the URL of the app you want to scrape reviews from.
   - **Specify the number of reviews**: Input the number of reviews you wish to scrape (e.g., 10).
   - **Select a star rating**: Choose a rating from the options provided:
     - [1] All reviews
     - [2] 1-star
     - [3] 2-star
     - [4] 3-star
     - [5] 4-star
     - [6] 5-star

3. After the script completes, check the folder for the `reviews.docx` file containing the scraped reviews.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the Mozilla Public License Version 2.0 - see the [LICENSE](https://github.com/SafeerAbbas624/Google_Play_Store_Review_Scraper/blob/main/LICENSE)) file for details.

## Acknowledgments

- [SeleniumBase](https://seleniumbase.io/) for providing a powerful framework for web automation.
- [python-docx](https://python-docx.readthedocs.io/en/latest/) for creating and manipulating Word documents.
