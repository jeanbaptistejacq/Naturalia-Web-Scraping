# Naturalia Web Scraping
![store-6140c4a457aa04 78867185](https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/036d6043-4d6b-487d-acc3-06a0effba66a)
<br/>
<br/>
We are using Python to scrape a product page from Naturalia. The goal is to track the product's daily price and store this information in a CSV file. To achieve this, we are creating a function that appends the daily prices to the CSV file.

## Content

[1. Getting Started](#getting-started)  
&emsp;[1.1 Requirements](#requirements)  
[2. Process of Web Scraping](#process-of-web-scraping)  
[3. Repository Content](#repository-content)  
[4. Function](#function)  
[5. License](#license)  

## Getting Started


We are going to use Naturalia product (5L bottle of water) search result link as the source of our raw data [link](https://bio.naturalia.fr/products/MPX_2138023/details).
<br/>
<br/>
<img width="941" alt="Capturescrappp" src="https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/deb52697-4f98-4e10-a45e-cfdbd3ea1866">
### Requirements

1. Python 3.6+
2. Install BeautifulSoup **```pip install beautifulsoup4```**
3. Install Requests **```pip install requests```**
4. Install Pandas **```pip install pandas```**
5. The user-agent of your browser. To get the user-agent, just search for "my user agent" on Google and copy the user-agent string.
6. Product search url from Naturalia

## Process of Web Scraping

1. Import the required libraries
2. Specify the URL containing the dataset and pass it to **`requests.get()`** to get the HTML content of the page.
3. Use BeautifulSoup to parse the HTML content
4. Extract the required information from the data
5. Save the Pandas dataframe as a CSV file called **`NaturaliaScraperDataset.csv`**

## Repository Content

1. It contains a Jupyter notebook file **`Naturalia-scraper.ipynb`** with inside the final codes to be used in the project :
    * function to extract Product Title, Product Price and Timestamp
    * function to send yourself an email when the price hits below a certain level

2. It contains a CSV file **`NaturaliaScraperDataset.csv`** with inside the final data extracted from the website.


## Function

Function to append daily prices into the CSV file :

<img width="800" alt="Capturescrapp2" src="https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/ddc2be5c-eb63-4fda-9bfe-5b087766ef2b">


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
