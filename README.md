# Yodel Tracking Status Scraper
## The Aim

The Yodel API was not available to us, we needed another way to gather consignment tracking details, refresh them regularly and monitor the number of days in transit.
We also needed to a way to spot potential shipping issues.

## The solution

I chose to use python for its rapid development style. The plan was to import a list of consignments into a database and call the yodel API, however, it was not cost effective for us. 
Instead I decided to opt for a scraper. Selenium was my first choice but I had issues with the XPaths and found it to be quite brittle. BeautifulSoup4 was the right choice in this use case.


### TO DO: 
~~Try using BeautifulSoup4 instead of selenium.~~

~~Keep list of undelivered items and count days since posted~~

~~Import from FTP, using Linnwork order managment to export the previous days processed orders to ftp~~
