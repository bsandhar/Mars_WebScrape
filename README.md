## Step 1 - Scraping

Used BeautifulSoup, Pandas, and Requests/Splinter to webscrape data about Mars from NASA.gov, Twitter among other sites

### NASA Mars News

* Scraped and collected latest title and body text [NASA Mars News Site](https://mars.nasa.gov/news/)

### JPL Mars Space Images - Featured Image

* Visit the url for JPL Featured Space Image [here](https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars).

* Navigated site to find image URL of current featured Mars Image (using Splinter)

### Mars Weather

* Scraped latest Mars weather tweets (https://twitter.com/marswxreport?lang=en)

### Mars Facts

* Visited the Mars Facts webpage [here](http://space-facts.com/mars/) and used Pandas to scrape the table containing facts about the planet.

### Mars Hemispheres

* Visited the USGS Astrogeology site [here](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) to obtain high resolution images for each of Mar's hemispheres.

- - -

## Step 2 - MongoDB and Flask Application

Used MongoDB with Flask templating to create a new HTML page that displays all of the information collected
