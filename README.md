# Books-Data-Scraping-using-Selenium
# 📚 Flipkart Data Science Books Scraper

This project uses Python and Selenium to scrape detailed information about **Data Science books** listed on [Flipkart](https://www.flipkart.com). It automates the browsing process, collects book information across multiple pages, and saves the data for further analysis.

---

## 🔍 Objective

To extract relevant book data such as:
- **Title**
- **Author**
- **Selling Price**
- **MRP**
- **Discount**
- **Rating**
- **Language**
- **Publisher**
- **Edition**
- **Number of Pages**

The collected data is stored in a structured format using a pandas DataFrame, useful for data analysis and insights.

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Selenium WebDriver**
- **pandas**
- **ChromeDriver**

---

## 🚀 How It Works

1. Launches a Chrome browser and logs into Flipkart using a mobile number (manual OTP entry required).
2. Searches for “Data Science Books”.
3. Iterates through multiple result pages.
4. Visits each book link and scrapes the desired details.
5. Saves the results into a pandas DataFrame.

---

## 📦 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/flipkart-books-scraper.git
   cd flipkart-books-scraper
