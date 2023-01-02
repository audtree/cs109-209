# Analyzing Top IMDB Stars

We began by scraping the HTML from the IMDB's webpage of the [Top 100 Stars for 2021](https://www.imdb.com/list/ls577894422/) using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/).

For analysis, we derived a variable for the approximate age of each star at the time of their first credit. This allowed us to identify child stars (first credit before age 11) and late bloomers (first credit after 26).  
