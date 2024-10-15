# Web Scraping Practice Project

Utilizing https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue to practice building a csv file from web scraping. I used and requests.get to access the webpage and BeautifulSoup to parse the information. Next, find_all and indexing were used to access the first table on the site. I also used find and the class tag to show another way to access the same information. The I found all 'th' tags to find the column headings and created a loop to strip everything but the title. The list was then added to a dataframe as the column titles. I then got the row data by accessing all tr tags and added each row to the dataframe. Lastly the dataframe was saved to a CSV to allow for further analysis in the future. 
  
