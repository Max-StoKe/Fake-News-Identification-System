# Fake-News-Identification-System
This Python-based system is designed to crawl, store, and analyze fake news reports from the Taiwan FactCheck Center website.  The collected data is able to save into both CSV files and an SQL database, allowing users to browse and review all stored information directly within the system.

This is the current working version (due to HTML structure changes from the Taiwan FactCheckCenter).

The code is currently in Traditional Chinese but English will be added later.

and may have more features.

This is for the reference only :

    ====================== Fake News Checker System =======================
    1. Crawl news data from Taiwan FactCheck Center
    2. Display crawled news data
    3. Save crawled data as CSV
    4. Display News.csv contents
    5. Delete existing database records
    6. Update database with CSV data
    7. Query database records
    8. Exit
    ========================================================================

Explanation of Options

    1. Crawl news data from Taiwan FactCheck Center – Fetch latest news titles, content, and dates.

    2. Display crawled news data – Show the most recent data obtained by the crawler.

    3. Save crawled data as CSV – Export the data into a News.csv file.

    4. Display News.csv contents – View the CSV file in the console.

    5. Delete existing database records – Clear all records from the SQLite database and recreate an empty table.

    6. Update database with CSV data – Import data from the CSV file into the database.

    7. Query database records – Read and display all records from the database.

    8. Exit – Close the program and database connection.
