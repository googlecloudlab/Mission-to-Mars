# Mission-to-Mars

## Overview

In this project, I automate a web browser to visit different websites to extract data about the Mission to Mars. I store the data in a MongoDB NoSQL database, and then render the data in a web application created with Flask.

I use BeautifulSoup and Splinter, to scrape tables and images of Mars’s related websites.

I use Python and HTML skills to write code for scraping, update the Mongo database, and modify the index.html file so the webpage contains all the information I collected.

The web app is mobile-responsive.


## Components

- The Mission_to_Mars_Challenge.ipynb file with all the code used for scraping.
- The scraping.py file contains the code for scraping the web sites.
- The app.py file for the flask application.
- The index.html file in the template folder and any CSS stylesheets.
- A README.md that describes the purpose of this repository. 


## Bootstrap 3

The final webpage is mobile-responsive, There are several elements from Bootstrap 3 in the index.html file. Here are a two examples that were added as part of the assignment:

- The paragraph with the text of the latest Mars News has been altered to stand out by using the .lead tag [Lead Body Copy](https://getbootstrap.com/docs/3.3/css/#lead-body-copy).
Here is an example on how the paragraph appears with Lead Body Copy enabled:
![Lead Body Copy Example](images/Bootstrap%203%20Lead%20Body%20Copy%20Example.png)

- The Hemisphere images have been shaped into circles by using the class="img-circle" tag on the image.  Below is a before and after comparison of the Hemisphere images

**Before**
![Hemisphere Before](images/Hemisphere%20Before.png)

**After as Circles**
![Hemisphere Circle](images/Hemisphere%20Circle.png)