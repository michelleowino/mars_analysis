## MARS NEWS AND WEATHER PROJECT

![image](https://user-images.githubusercontent.com/119654958/224206354-fd547813-8088-4cc6-90bc-678108309a48.png)

This assignment consists of two technical products. 

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table

## Part 1: Scrape Titles and Preview Text from Mars News 
- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). 

- The titles and preview text of the news articles were scraped and extracted. 

- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. 

## Part 2: Scrape and Analyze Mars Weather Data 

The HTML table was extracted into a Pandas DataFrame. Pandas/Splinter and Beautiful Soup were used to scrape the data. 

The data was analyzed to answer the following questions: 

- How many months exist on Mars? 

- How many Martian days' worth of data are there? 

- Which month, on average, has the lowest temperature? The highest? 

- Which month, on average, has the lowest atmospheric pressure? The highest? 

- How many terrestrial days exist in a Martian year? A visual estimate within was made. 

The DataFrame was exported into a CSV file. 


## References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
