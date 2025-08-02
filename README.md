# Court_Case_Tracker

This project is an AI-powered legal case analysis tool that retrieves and displays detailed information about court cases, including case number, court name, case type, and filing year. It supports multiple courts like the Supreme Court, Bombay High Court, and Delhi High Court. Users can search for civil or criminal cases and get predictions on outcomes, estimated disposal time, and relevant legal insights. The system uses web scraping and legal databases to deliver accurate and real-time results for legal professionals and researchers.

# Tech Stack

* HTML5, CSS3
* JavaScript 
* Python 
* RESTful API
* Selenium
* BeautifulSoup
* SQLite 
* Flask

# Features

* User can input Case Type, Case Number, and Filing Year via a web form.
* Supports court selection like Supreme Court, Delhi High Court, and Bombay High Court.
* Backend fetches and parses case metadata: parties, filing date, next hearing, judge, and status.
* Displays latest judgment/order PDF links with download option.
* Logs each user query and response in a SQLite database.
* Provides AI-based prediction on case outcome, disposal time, and confidence score.
* Renders visual analytics using Chart.js.
* Implements error handling for invalid input or court site issues.

# Output
<img width="1196" height="613" alt="Screenshot 2025-08-02 164208" src="https://github.com/user-attachments/assets/a00e60c8-367a-4cdd-9f1c-8214c01097e9" />

# Installation

* git clone https://github.com/yourusername/court-case-analyzer.git
* cd court-case-analyzer
* pip install -r requirements.txt
* python app.py

