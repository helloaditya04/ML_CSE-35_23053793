# Web Scraping
Web scraping is the automated process of extracting data from websites. Instead of manually copying information from a webpage, you write a program that visits the website, reads its HTML content, and pulls out the specific data you need — saving it into a structured format like a CSV, Excel file, or database.
Think of it like a bot that reads a webpage the way your browser does, but instead of displaying it visually, it extracts specific information programmatically.

---

# How a Webpage Works (Quick Background)
When you visit any website, your browser receives HTML code from the server. This HTML contains all the text, links, tables, and structure of the page. Web scraping works by reading this HTML and picking out the parts you want.

- [X] Website Server  →  HTML Code  →  Your Scraper extracts data  →  Structured Output (CSV/DB)

---

# Static vs Dynamic Websites
| Type        | Description                                          | Tool to Use                  |
| ----------- | ---------------------------------------------------- | ---------------------------- |
| **Static**  | HTML is directly available in the page source        | `requests` + `BeautifulSoup` |
| **Dynamic** | Content is loaded by JavaScript after the page loads | `Selenium` or `Playwright`   |

---

## Common Use Cases

- Scraping product prices from e-commerce sites (Amazon, Flipkart)
- Collecting news headlines from news websites
- Extracting job listings from job portals (Naukri, LinkedIn)
- Gathering real estate data from property sites
- Pulling sports statistics or stock prices
- Research and academic data collection

---

# Complete Web Scraping Workflow
1. Identify the target website and data you need
        
2. Inspect the page HTML (Right click → Inspect in browser)
        
3. Fetch the HTML using requests
        
4. Parse the HTML using BeautifulSoup
        
5. Locate and extract the required elements
        
6. Store the data in CSV / Database
        
7. Analyze the data using Pandas

---

Web scraping is a powerful technique for automatically collecting large amounts of data from the internet that would be impossible to gather manually. It is widely used in data science, market research, journalism, and competitive intelligence. Combined with pandas, the scraped data can be immediately analyzed, visualized, and used to build machine learning models.
