# webscraping
details of process of wrbscraping

Step 1 – Requests The Contents Of A Webpage
        The first step any web scraping program (called a “scraper”) makes is to request the target website for the contents of a specific URL.
        For example, my hypothetical scraper might send a “GET” request to IMDb for the web page that contains “IMDb’s Top 250” movies.
        This information is usually returned to the scraper in HTML format. Which is the file type used to display all the textual information of a website.

Step 2 – Extracts The Desired Data
         Once IMDb’s server returns the HTML file for the Top 250 movies web page, the scraper extracts the data we want from the HTML file.
         In this case, we might want the scraper to extract the: rank, title, IMDb rating, and image thumbnail for all 250 movies in the list.
         This is accomplished through a process called "parsing". Which is just programming speak for splitting up a block of data (string, etc) and converting the desired data            into the format the script needs. Example: this script will "parse" the data string that contains the movie title "The Shawshank Redemption" and converts this data into a          data structure that can be used within your program.
         When a developer is writing a web scraping program, he specifically tells it what types of data it should parse and which data it should ignore.
         
Step 3 – Stores The Scraped Data
         The final step is for the program to store this data in a CSV, JSON or in a database so it can be used manually or in another program.
         Granted that is a very simplified example, and there are many other parts that can be added to this process to make it more powerful – like web crawling, proxymanagement. 
        
