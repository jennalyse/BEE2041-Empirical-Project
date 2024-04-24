# BEE2041-Empirical-Project

This project was all about using data from Kaggle.com on plane crashes since 1908. The weblink to this data is 'https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908'. I chose this data set as it is highly comprehensive and on a topic of interest to me. To replicate this project, it is essential to download the csv file attached to the website.

The original dataset is the 'Airplane_Crashes_and_Fatalities_Since_1908.csv' file.

My project is split into two parts - the preprocessing of my data, and the report. 
The preprocessing includes converting string to 'datetime' format, extracting the year from the 'Date' column, handling missing values, and standardising data. I defined a dictory to replace aircraft operators to all contain a standard format. 
Finally I have created a new column for each country associated with each crash based on the dictionary replacements, to enable me to web scrape to extract ISO country codes. I used data from 'https://unstats.un.org/unsd/methodology/m49/' to extract ISO country coces using 'BeautifulSoup'.
Now it is not essential to follow all these steps or in the same way to produce a report on plane crashes, this is just what I thought to implement. In the instructions given, I was tasked to use some form of webscraping, but it is likely more convenient for replication of my results to directly import this csv file using this GitHub page 'https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv'. I have previously used this and upon reflection of using both would use the latter. 

This preprocessing is in the 'DataPreprocessing.ipynb' file.

My final dataset that I use in my report is in the 'cleaned_crashes.csv' file.

Then my report is in the 'BlogPost.ipynb' file. 

