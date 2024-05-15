# Naturalia Web Scraping
![store-6140c4a457aa04 78867185](https://github.com/jeanbaptistejacq/Naturalia-Web-Scraping/assets/80902643/036d6043-4d6b-487d-acc3-06a0effba66a)
<br/>
<br/>
We are using Python to scrap a Naturalia product page. The aim is to track the daily price of that product in a csv file. We are indeed creating a function to append the daily prices into a csv file.

## Content

[1. Getting Started](#getting-started)  
&emsp;[1.1 Requirements](#requirements)  
[2. Download and Installation](#download-and-installation)  
[3. Data Source](#data-source)  
[4. Data Exploration Process](#data-exploration-process)  
[5. License](#license)  

## Getting Started

Web scraping is a technique to automatically access and extract large amounts of information from a website.

In this project we are going to use Naturalia product (Bottle of water) search result link as the source of our raw data [link](https://bio.naturalia.fr/products/MPX_2138023/details).
### Requirements

1. Python 3.6+
2. install BeautifulSoup **```pip install beautifulsoup4```**
3. install Requests **```pip install requests```**
4. install Pandas **```pip install pandas```**
5. the user-agent of your browser. To get the user-agent, just search for "my user agent" on Google and copy the user-agent string.
6. product search url from Naturalia

## Download and Installation

1. You can clone this repository or simply download the .zip file by clicking on 'Code' -> 'Download ZIP' at <https://github.com/jeanbaptistejacq/COVID-19-SQL-Data-Exploration>.

2. Once you have all the files of this project, you can find the dataset in different tables in excel files in the 'tables' folder. They need to be imported into a new database or an existing one so the queries can be executed against them.

3. Open your SQL DB Manager, create a new database or use an existing one to import the excel files into tables. The steps may vary depending on the DB manager you are using. Here is a general approach: In your DB manager, locate the option to import data from a file or external source ->
Select the Excel files one by one and follow the prompts to specify the target table and mapping of columns ->
Verify that the data has been imported successfully by checking the table contents.

4. The queries I wrote for this project can be found in the 'queries' folder. You can open the file directly to run them or create new query windows to copy/paste them into the editor.  

5. Execute the query you want to retrieve the desired results.  

**Note:** Please ensure you have a valid database connection established in your DB manager before executing the queries. Adjust the queries if needed based on the structure of the imported tables.

## Data Source



## Data Exploration Process




## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
