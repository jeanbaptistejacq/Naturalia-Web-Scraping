# Naturalia Web Scraping
![store-6140c4a457aa04 78867185](https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/036d6043-4d6b-487d-acc3-06a0effba66a)
<br/>
<br/>
We are using Python to scrap a Naturalia product page. The aim is to track the daily price of that product in a csv file. We are indeed creating a function to append the daily prices into this csv file.

## Content

[1. Getting Started](#getting-started)  
&emsp;[1.1 Requirements](#requirements)  
[2. Process of Web Scraping](#process-of-web-scraping)  
[3. Repository Content](#repository-content)  
[4. Function](#function)  
[5. License](#license)  

## Getting Started


We are going to use Naturalia product (5L Bottle of water) search result link as the source of our raw data [link](https://bio.naturalia.fr/products/MPX_2138023/details).
<br/>
<br/>
<img width="941" alt="Capturescrappp" src="https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/deb52697-4f98-4e10-a45e-cfdbd3ea1866">
### Requirements

1. Python 3.6+
2. install BeautifulSoup **```pip install beautifulsoup4```**
3. install Requests **```pip install requests```**
4. install Pandas **```pip install pandas```**
5. the user-agent of your browser. To get the user-agent, just search for "my user agent" on Google and copy the user-agent string.
6. product search url from Naturalia

## Process of Web Scraping

1. Importing the required libraries
2. Specifying the URL containing the dataset and passing it to **`requests.get()`** to get the HTML content of the page.
3. Using BeautifulSoup to parse the HTML content
4. Extracting the required information from the data
5. Saving the pandas dataframe as a CSV file called **`NaturaliaScraperDataset.csv`**

## Repository Content

1. It contains a jupyter notebook file **`Naturalia-scraper.ipynb`** which contains the final codes to be used in the project.
    * function to Extract Product Title, Product Price and Timestamp
    * function to Send yourself an email when the price hits below a certain level

2. It contains a csv file **`NaturaliaScraperDataset.csv`** which contains the final data extracted from the website.


## Function

Function to append daily prices into the CSV file :

<img width="800" alt="Capturescrapp2" src="https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/ddc2be5c-eb63-4fda-9bfe-5b087766ef2b">


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
