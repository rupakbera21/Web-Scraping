# Web Scraping Project

This project involves web scraping book information from a website using Python, Requests, and BeautifulSoup.

## Overview

The goal of this project is to extract details about books from multiple pages of a website, organize the data, and store it for further analysis.

## Code Overview

### Prerequisites

- Python 3.x
- Required Python libraries: `requests`, `beautifulsoup4`, `pandas`

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/rupakbera21/Web-Scraping
   cd your-repository
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python web_scraping_(solved).py
   ```

   Replace `web_scraping_(solved).py` with the actual name of your script.

   OR

   Click on "Click Here" to redirect to the Colab notebook: 
   [Click Here](https://colab.research.google.com/drive/1HSjfM0Lo0R4uvyzobPKft4AmSFG2XdM3?usp=sharing)

## Code Explanation

- **base_url**: Contains the base URL for the pages to be scraped.

- **Scraping Loop**: Iterates through the specified number of pages, sends HTTP requests, and extracts book details.

- **Data Extraction**: Details like title, rating, price, and link are extracted from each book on the page.

- **Data Storage**: Extracted data is stored in a list of lists (`data_list`), which can be further used for analysis or saved in a file.

- **Dependencies**: The project relies on Python, Requests, BeautifulSoup, and Pandas. Make sure to install them before running the script.
- 

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to my mentor [Rushikesh](https://github.com/rishikonapure) for providing guidance and valuable insights throughout the development of this project. Additionally, I express my gratitude to [PrepInsta](https://prepinstaprime.com/) for offering this valuable opportunity to enhance my skills in web scraping.

Happy Scraping!
