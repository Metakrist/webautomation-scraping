# webautomation-scraping
Daily Report Scraper
This project automates the login, navigation, data extraction, and Excel update process platform's back office. It uses Selenium and BeautifulSoup to scrape daily win/loss data and updates a predefined Excel report.

🚀 Features
✅ Automated login via Selenium

✅ Dynamic date picker interaction

✅ Data scraping using BeautifulSoup

✅ Excel file manipulation using openpyxl

✅ Simple total calculation (Bet Amount & Payout)

✅ Clean output formatting for Jupyter Notebooks

✅ Uses dynamic file naming and row targeting

🧰 Technologies Used
Python 3.9+ – Core programming language
Selenium – Browser automation and web interaction
BeautifulSoup (bs4) – HTML parsing and table data extraction
pandas – Date handling and basic data transformation
openpyxl – Excel file reading and writing
IPython – Enhanced notebook display (Markdown rendering)
SOCKS5 Proxy Support (Optional) – Route browser traffic through a local proxy using:
Jupyter Notebook or any Python runtime

🔒 Sensitive Data & Config
This project intentionally excludes:
Usernames
Passwords
API links
Proxy addresses
Local Excel paths

To keep this project secure and reusable, all sensitive data is expected to be loaded from a separate config or .env file, or handled inside an ignored notebook

📝 Usage
Modify start_date, end_date, and filenamedt as needed.

Run the script in Jupyter or any Python environment.

The output Excel will be saved to the defined path with updated bet and payout values.

 Security Best Practices
Do not commit real credentials or internal URLs.

Add all personal notebooks and .env files to .gitignore.

Use placeholder values when sharing public examples.
