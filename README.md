# 🌐 Web Scraping Internshala Data

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.8-blue?style=flat-square&logo=python) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.9.3-yellow?style=flat-square&logo=python) ![Requests](https://img.shields.io/badge/Requests-2.25.1-red?style=flat-square&logo=python)

## 📑 Project Overview

This project involves scraping job listings data from Internshala using Python libraries `BeautifulSoup` and `requests`. The goal is to collect job data and save it in a CSV format for further analysis. The project includes a Jupyter Notebook that demonstrates the web scraping process and a sample HTML file used for scraping.

## 🗂️ File Structure

- **Webscraping.ipynb**: The main Jupyter Notebook containing the web scraping code and analysis.
- **Internshala.html**: Sample HTML file used for scraping.
- **jobs.csv**: Output file containing the scraped job data in CSV format.
- **README.md**: Project documentation.

## 📚 Libraries Used

- ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.9.3-yellow?style=flat-square&logo=python)
- ![Requests](https://img.shields.io/badge/Requests-2.25.1-red?style=flat-square&logo=python)

## 🔧 Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vaishnaviii03/web-scraping-internshala.git
   cd web-scraping-internshala
2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Launch Jupyter Notebook**:
```bash
jupyter notebook
```
4. **Open `Webscraping.ipynb` to explore the scraping process and results.**

## 🔍 Key Steps in Web Scraping

### Fetching the Web Page:
- Used the `requests` library to send an HTTP request to the Internshala job listings page and retrieve the HTML content.

### Parsing HTML Content:
- Used `BeautifulSoup` to parse the HTML content and extract relevant job data such as job titles, company names, and job descriptions.

### Storing Data:
- Saved the scraped data into a CSV file (`jobs.csv`) for further analysis.

### Analyzing Data:
- Loaded the CSV file into a Pandas DataFrame to analyze the collected job data.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Acknowledgements
- **BeautifulSoup**: For providing a powerful library for parsing HTML and XML documents.
- **Requests**: For simplifying HTTP requests to fetch web pages.


