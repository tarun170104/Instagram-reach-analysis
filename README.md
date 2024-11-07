
# Instagram Data Analysis & Web Scraping Project

## Overview

This repository contains two Jupyter notebooks:
1. **dataset code.ipynb** - A notebook for analyzing an Instagram dataset.
2. **project.ipynb** - A notebook that installs libraries like Selenium and BeautifulSoup, likely for scraping and web data extraction.

---

## Files

### 1. dataset code.ipynb

#### Description:
This notebook loads an Instagram dataset (`insta_dataset (1).csv`) and performs basic data analysis, including:
- Reading the dataset using `pandas`.
- Displaying the first few rows of the dataset.
- Checking for missing values in the dataset columns.

#### Columns in the dataset:
- `username`: The Instagram username associated with each post.
- `post_number`: The unique identifier for each post.
- `post_url`: The URL of each post.
- `likes`: The number of likes for each post.
- `hashtags`: The hashtags associated with the post.
- `comments`: The comments on the post.

---

### 2. project.ipynb

#### Description:
This notebook installs and sets up libraries commonly used for web scraping:
- **Selenium**: A tool for automating web browsers.
- **BeautifulSoup**: A library for parsing HTML and XML documents.
- **Requests**: A library for making HTTP requests to download web content.

It is assumed that the code in this notebook is used to scrape Instagram or similar social media data, likely for further analysis.

---

## How to Use

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Install the necessary libraries**:
   Before running the notebooks, ensure that you have installed the required libraries by running the following command:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebooks**:
   You can run the Jupyter notebooks using the following command:
   ```bash
   jupyter notebook
   ```

   - **dataset code.ipynb**: For loading and analyzing the Instagram dataset.
   - **project.ipynb**: For setting up the scraping environment.

## License

This project is licensed under the MIT License.
