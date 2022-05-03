# MISSION TO MARS
_Web Scraping to Extract Online Data_


## Overview of the Project

Large organizations employ web scraping to assess and track the competition within their industires via online. 
This project was undertaken to polish an existing web app that uses an automated web browser to visit different websites containing data on Mars Exploration and publish the results on a webpage.

### The main goals for the project include:

- Scarping full-resolution images and titles of Mars Hemisphere.
- Updating the the scraping script and the index.html file, so that the Mars Hemisphere images and tiles can be displayed on the page using Flask app.
- Make the Webpage Mobile-reponsiveand improve the appearance of the page using Bootstrap3 components.

### Resources:
1. MongoDB
2. Jupyter Notebook
3. Visual Studio Code



## Results

* **Scarpe Full-Resolution Images and Titles of Mars Hemisphere**

Using Jupyter Notebook, the Mission_to_Mars script was updated with code to visit and scrape imgaes and tiles of Mars Hemisphere.

_Below is an example of the  Code used to extract and store Hemisphere image_

![hemisphere_images](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Hemisphere%20images.PNG)


* **Updating Web App with Mars Hemisphere Images and Title**

The updated Mission_to_Mars.ipynb was converted to a python file and exported so that it could be read and cleaned using VSCode.
The original scrape script was then updated with the new code from Mission_to_Mars file so the process to extract hemisphere data would be automated.
To do this a new function was created after mars_facts function to hold the hemisphere code and a new dictionary (hemisphere) was also created in the data dictionary of the scrape_all function to hold the mages and tiles of Mars Hemisphere. 

_Example of the final scrape code_

![Scrape_code 1](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/scrape_code%201.PNG)


![Scrape_code 2](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/scrape_code%202.PNG)


The index.html file was also updated to reflect the change in the scraping file and retrieve the images and titles was to be displayed. 

![index.html](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/index.PNG)


* **Improve Responsiveness and Styling of the Webpage using Bootstrap3 Components.*

The responsiveness of the app was imporved with update to the grid system in the html so the page could be displayed on all platforms and devices.
Finally the appearance of the webpage was also improved by incorporating a background image into the header tag, changing the color of the scrape button and changing the shape of the featured_image to thumbnail.

_Example of the code to style page_

![style](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Background.PNG)


_Example of the code to improve responsiveness_

![Responsive](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Responsiveness.PNG)


## Final Webpage Display
![Web View]()

