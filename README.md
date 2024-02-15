# Car-Details-Web-Scraping-Project-using-Selenium
Car Details Web Scraping Project using Selenium and BeautifulSoup

    Objective: Developed a web scraping script in Python to extract detailed information about used cars from the Cars24 website, including brand, selling price, kilometers driven, fuel type, and transmission type.
    Technologies Used:
        Selenium: Used for web scraping to navigate through web pages and extract car details.
        BeautifulSoup: Utilized for parsing the HTML content of the web pages and extracting specific information.
        Pandas: Used to organize the extracted data into a tabular format (DataFrame).
    Workflow:
        Created a Selenium WebDriver to open the Cars24 website and retrieve the page source.
        Used BeautifulSoup to parse the HTML content and extract car details from specific sections of the page.
        Extracted brand, selling price, kilometers driven, fuel type, and transmission type for each car listing.
        Stored the extracted data in a Pandas DataFrame and saved it as a CSV file for further analysis.
    Outcome: Successfully scraped data for 777 used car listings from the Mumbai region and saved it in a CSV file ('Mumbai.csv')
