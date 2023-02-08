# Twitter-Scraping-using-snscrape-and-Pandas
This code scrapes tweets containing the keyword "syria" using the snscrape library. The tweets are stored in a Pandas DataFrame .
This code uses the snscrape library to scrape tweets containing the keyword "syria" from Twitter and store the scraped data in a Pandas DataFrame. The information for each tweet includes the date, content, username, display name, description, reply count, retweet count, like count, quote count, language, and source. The code limits the number of tweets to 1000. After scraping the data, it is saved as a CSV file with the name "NEELESH.csv".

Prerequisites
To run this code, you need to have the following libraries installed:

snscrape
pandas
os
Usage
Run the code by executing it in your Python environment.
The scraped tweets will be stored in the Pandas DataFrame named df.
The resulting data is saved as a CSV file named "NEELESH.csv" in the current working directory.
The saved file can be used for further processing or analysis as needed.
Note
Keep in mind that Twitter may enforce rate limits on the number of requests you can make. Use this code responsibly and in compliance with Twitter's terms of service.
