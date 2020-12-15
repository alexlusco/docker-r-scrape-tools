# An R Docker image for web scraping in R

This Docker image will install the basics necessary for writing a scraper in R, since compiling R and all the required packages can easily take 20min. To use this image, just reference in your Dockerfile like so:

```Dockerfile
FROM alexlusco/docker-r-scrape-tools

# Other stuff goes here…
```
