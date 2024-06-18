# Overview

This is a simple map of the top 20 locations to visit in the state of Idaho, USA. The purpose of this code was for me to learn ArcGIS and how it can be used with JavaScript and HTML to create a custom map with locations marked with view filters.

To be able to create a layer in ArcGIS, I first needed to create a .csv file with the requisite details of the locations I wanted to display. This involved creating columns to hold details such as the location's name, coordinates, and description. To save on unecessary effort, I simply had ChatGPT generate the top  20 locations to visit in Idaho. I then fact-checked each of the locations to ensure that they were real and their details were correct, (which was necessary, as three of the provided locations were in different states). Then, when I passed it into ArcGIS, it was converted to a geojson file, which is simply a JSON formatted file that contains the locations and their details. This file was downloaded and placed into the same directory as my index.html, which contains JavaScript to show the locations in the geojson file and apply filters to only show classes of locations. The index.html file is also linked to a item.html file that references links and modules within the ArcGIS website to properly display the basemap for the locations to be shown on.

ChatGPT was used to generate a list of locations and led me through the process of using ArcGIS.

I chose and created this project because I previosly had little experience in integrating high-level programming languages with webpages. Any webpages that I've created previously lacked backend code. Thanks to my experience in this project, I now have a deeper understanding of this integration.

[Software Demo Video](https://www.youtube.com/watch?v=JYVdp7r96wA)

# Development Environment

Visual Studio Code

HTML - Used to create the Webpage that the map is on.

GeoJSON - Filetype used to store ArcGIS locations and location details.

JavaScript - The backend logic for displaying the information on the webpage, interacting with locations, etc.
# Useful Websites

* [ChatGPT](http://chat.openai.com)
* [ArcGIS](http://arcgis.com/home/index.html)

# Future Work

* Include more locations.
* Include more location types, such as Historical.
* Choose a more visually appealing basemap, and possibly add driving directions.
