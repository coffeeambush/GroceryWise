# GroceryWise
An app that helps find the best grocery deals in your local area

GroceryWise 🛒
GroceryWise is a data-driven project designed to help users save money by identifying personalized grocery deals. It scrapes weekly grocery flyers from multiple sources, stores the data in a local Microsoft SQL Server, and lays the groundwork for machine learning models to recommend deals based on user preferences.

🧠 Project Overview
Data Collection: Uses Python to scrape grocery flyers from local store websites.

Data Storage: Structured data is stored in a local Microsoft SQL Server database.

Future Plans: Build a machine learning model using Python or R to:

Recommend deals based on user purchase history or preferences

Track price trends

Predict future sales

🚀 Features
Scrapes flyer data (store name, item, price, etc.)

Cleans and standardizes product and price information

Inserts data into MS SQL Server for long-term storage

Ready for integration with a web dashboard or API

🔧 Tech Stack
Python: Web scraping (BeautifulSoup, Requests, etc.)

Microsoft SQL Server: Data storage

pymssql / pyodbc: For database connections

Planned:

R / Python (scikit-learn or caret): Machine learning for deal recommendation

Flask / Shiny / Streamlit: Web app interface (future)

