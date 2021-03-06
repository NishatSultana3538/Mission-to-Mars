# Mission_to_Mars


## Overview of the Mission_to_Mars: 
The script we're building is designed to scrape the most recent data—that means that each time we run the script, we'll pull the newest data available. As long as the website continues to be updated with new articles, which is likely, we'll have a constant influx of new information at our fingertips.
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Results: 
### Scrape Full-Resolution Mars Hemisphere Images and Titles

At first I wrote code to use my  browser to visit the Mars Hemispheres website to view the hemisphere images 
![website_visit](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/images/hemisphere%20images_Mars_website.png)

when I print the list of dictionary items I got the following url

![hemisphere_image_url](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/images/hemisphere_image_url.png)



Using the [Mission_to_Mars_Challenge.ipynb](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb), [app.py](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/app.py), [sraping.py](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/scraping.py) and [index.html](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/templates/index.html)  I got the following webpage that has the full-resolution images and the titles of the four hemisphere images as below image:

![hemisphere_image](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/images/Mars_hemisphere.png)

After updating the html file I got following image:

![webpage_image](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/images/Mission_to_Mars.png)

I change html file to make the website is mobile-responsive. I use the DevTools to test the responsiveness of my website and got the following image:

![mobile_responsive](https://github.com/NishatSultana3538/Mission-to-Mars/blob/main/images/mobile_responsive.png)












