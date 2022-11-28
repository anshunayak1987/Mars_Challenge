RESOURCES:
          we use two sites
          https://redplanetscience.com
          ![image](https://user-images.githubusercontent.com/111711194/204312798-b9c502d3-a244-45f5-9ed6-3855861c5738.png)

          
          
          https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html
         ![image](https://user-images.githubusercontent.com/111711194/204311988-7e55615a-7957-47de-8ef1-6bba9d0ee88c.png)

# Mars_Challenge
The aim of this project is to apply full web-scraping for the mission to Mars by collecting data, organizing and storing data, analyzing data, and then visually communicating our insights.
Analysis of data and Results:
a.Scrape Title and Preview Text from mars News
Using Splinter an automated browsing was used to visit the Mars news site. Then, we have extracted the HTML code with Beautiful Soup. After that, we have scraped and extracted the titles and preview text of the news articles and we have stored them in a dictionary.
To see the full code written in this part check part_1_mars_news.ipynb
b.Scrape and Analyze mars Weather Data
Using Splinter an automated browsing was used to visit the Mars temperature data site. Then, we have extracted the HTML code with Beautiful Soup and we have scraped and extracted the Mars temperature table into a Pandas DataFrame and we have cleaned the table data by editing its data types.
After extracting Mars temperature table, we used this table to analyze and visualize the data by finding answers to the following questions:
 ![image](https://user-images.githubusercontent.com/111711194/204311988-7e55615a-7957-47de-8ef1-6bba9d0ee88c.png)
  
  a.How many months exist on Mars?
  
  b.How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  
  c.What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  
  d.Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  
  e.About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

Finally, the last step was to export our data as mars_table.csv
