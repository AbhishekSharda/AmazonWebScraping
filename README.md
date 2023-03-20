# AmazonWebScraping
Steps i took to scrape data fro Amazon.ca:-
 *  Using Auto Scrapper Library in Python,I tried scraping data from Amazon.ca
 *  Firstly, I searched for Data science Books, and selected a book in search results, i.e."Data Analysis for Social Science: A Friendly and Practical Introduction"
 *  Secondly, I provided the price, title and number of star ratings voted on that book by multiple users, and sent that data to my AutoScraper,along with URL of that 
    webpage.
 *  AutoScraper provided me with those three values, namely, price, title and name of the books present in that page divided into 3 different sets.
 *  Hence AutoScraper retrieved the information I required from the webpage,just by providing it with values of just one book.
 *  Further, to test my Scraper, I provided  a different URL to my model and this time instead of searching for data science books, I searched for physics books.
 *  Since my model was already setup to scrape those 3 values from page, no matter which URL I provided to it from Amazon.ca product search, it will be returning price, '   title and name of the product. 
 *  So,I tried retrieving the price of physics books from search page, and it successfully returned me with list of price for all the search results.
