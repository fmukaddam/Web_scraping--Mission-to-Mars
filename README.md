# Web_scraping-Mission-to-Mars
Built a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page.

# Step 1 - Scraping
Completed the initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter. <br>
Created a Jupyter Notebook file called mission_to_mars.ipynb and used this to complete all of your scraping and analysis tasks. The following information was scraped from the website:
![alt text](https://github.com/fmukaddam/Web_scraping-Mission-to-Mars/blob/main/Missions_to_Mars/Screenshots/Screen%20Shot%202020-12-28%20at%209.58.30%20PM.png)
<h3> a) NASA Mars News </h3>
Scraped the NASA Mars News Site and collected the latest News Title and Paragraph Text. Assigned the text to variables for reference. <br>
 <h3> b) JPL Mars Space Images - Featured Image </h3>
Used splinter to navigate the site and find the image url for the current Featured Mars Image and assigned the url string to a variable called featured_image_url.
![alt text](https://github.com/fmukaddam/Web_scraping-Mission-to-Mars/blob/main/Missions_to_Mars/Screenshots/Screen%20Shot%202020-12-28%20at%209.58.30%20PM.png)
<h3> c) Mars Facts </h3>
From the Mars Facts webpage I used Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.
Used Pandas to convert the data to a HTML table string.
<h3> d) Mars Hemispheres </h3>
Obtained high resolution images for each of Mar's hemispheres from the USGS Astrogeology sie
![alt text](https://github.com/fmukaddam/Web_scraping-Mission-to-Mars/blob/main/Missions_to_Mars/Screenshots/Screen%20Shot%202020-12-28%20at%209.58.44%20PM.png)

# Step 2 - MongoDB and Flask Application
Used MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.
Created a template HTML file called index.html that will take the mars data dictionary and display all of the data in the appropriate HTML elements.
