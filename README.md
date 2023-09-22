# TV-data-prep-and-EDA
This is a project I worked on to practice my skills around web scraping, data preprocessing, analysis and EDA. I know working on data about TVs is not super exciting but it was slightly outside my comfort zone because I had zero idea about TVs and electronics, in general. So, I decided to scrape this data just to enhance my research skills on how to extract useful features from messy data about something I am not super invested in and enhance my GK in the process. Now that I am done with this project, I can say that this didn't disappoint.

Here's a rough outline:
1. First off, I scraped data about TVs from www.smartprix.com. It is a dynamically loading website so, I used selenium to scrape it.
2. Once I had the html code of the webpage, I extracted the data using BeautifulSoup, pandas and numpy and stored the data as a pandas dataframe.
3. Then, I cleaned the data and segragated it into useful features.
4. As a result, I got a dataset with around 23 features.
5. Then, I performed EDA on the data where I studied the individual features, inter-feature relationship and also the relationship of features with the target feature Price.
