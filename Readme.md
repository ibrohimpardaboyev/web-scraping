# this my Web-Scraping Project 

##### tools I used:
- **Python**
- **requests and bs4** 
- **Pandas**
- **Matplotlib for Visualization**

<a href="https://www.linkedin.com/feed/update/urn:li:activity:7316867782854250496/">you can find images in here</a>

**firstly** we need to find data to scrape <a href="https://www.boxofficemojo.com/chart/top_lifetime_gross/?area=XWW">here</a> is the web page for parsing movies Top liftime Gross Income.
firstly we need to get html code of this page and get elemnt of it using BeautifulSoup Library for scraping web data. After we get All the Data from a web , we need to save it as table using pandas dataframe which helps us to do some operations.Next we need to correct the Lifetime Gross	column to int because it contains $ sign and comma which will cause some misleadings when calculating and next stage is visualize our data. Before visualizing it we need to gategorize the creation date. After this steps Done it is turn to visualize our clean data. you can see visuals in <a href="https://www.linkedin.com/feed/update/urn:li:activity:7316867782854250496/">in here</a>
