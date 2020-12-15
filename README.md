# An R Docker image for scraping ESRI endpoints

This Docker image will install the basics necessary for writing a scraper in R for ESRI/ArcGIS API endpoints, since compiling R and all the required packages can easily take 20min. To use this image, just reference in your Dockerfile like so:

```Dockerfile
FROM tomcardoso/docker-r-scrape-esri

# Other stuff goes here…
```
