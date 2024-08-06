# Web Summarizer 📝🌐

This project is a web summarizer tool that extracts and summarizes article content from web pages. It uses CloudScraper to bypass Cloudflare, Selenium for handling dynamically loaded content, BeautifulSoup for web scraping, and HuggingFace Transformers for summarization.

## Overview
The Web Summarizer is a Python-based project designed to fetch and summarize web content. It bypasses Cloudflare protection, extracts article content using BeautifulSoup, and generates concise summaries using HuggingFace's `pipeline` API.

## Features
- **Cloudflare Bypass:** Uses CloudScraper to bypass Cloudflare protection and access the web page content.
- **Dynamic Content Handling:** Utilizes Selenium to load and extract content from pages that require JavaScript rendering.
- **Web Scraping:** Uses BeautifulSoup to extract article content from web pages.
- **Text Summarization:** Leverages HuggingFace Transformers for summarization.
- **Output to Text File:** Saves the summarized text to a local file.

## Getting Started
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tanmayypramanick/web-summarizer.git
   cd web-summarizer
   
2. **Set up the environment:**
Ensure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt

3. **Run the Jupyter Notebook:**
Open the summarizer.ipynb file in Jupyter Notebook or JupyterLab and execute the cells.

## Usage

1. **Set the URL:**
- Open the summarizer.ipynb file.
- Locate the cell where the URL variable is defined.
- Replace the placeholder URL with the URL of the article you want to summarize:
  ```bash
  URL = 'https://medium.com/@natashanewbold/python-automation-project-with-source-code-news-summeriser-37132d89ae16'

2. **Run the Notebook:**
Execute each cell in the notebook sequentially to perform the following steps:
- Bypass Cloudflare protection.
- Use Selenium to load and extract content from the page.
- Use BeautifulSoup to scrape the article content.
- Summarize the extracted content using HuggingFace Transformers.
- Save the summarized text to a file named webpage_summary.txt.

## Technologies Used
- **Python:** The main programming language used.
- **CloudScraper:** For bypassing Cloudflare protection.
- **Selenium:** For handling pages that require interaction with JavaScript and dynamically loaded content.
- **BeautifulSoup:** For parsing HTML content and extracting text.
- **HuggingFace Transformers:** For text summarization.
- **Jupyter Notebook:** For interactive code execution and documentation.
  
## Project Structure
- summarizer.ipynb: The main Jupyter Notebook containing the code.
- requirements.txt: List of required packages.

## Notes
Ensure you have internet connectivity for real-time web scraping and summarization.
Customize the code as needed to handle different web page structures.

## Conclusion
Feel free to explore, modify, and use this project as a starting point for your own web summarization needs! 🚀
