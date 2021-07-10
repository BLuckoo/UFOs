# Module 11 - Javascript UFOs
![image](https://user-images.githubusercontent.com/82583576/125167989-46c80600-e171-11eb-886d-caede57b4c50.png)

## **1. Overview**
The objective of this analysis is to build a dynamic web page that will allow readers to get information about UFO sightings. 

The web page is built using HTML, Javascript, CSS and the Bootstrap framework. 

Based on the filters used by the readers, data will be imported from a Javascript file containing the data as Javascript objects. The readers will be able to filter the information based on five different elements, such as date, city, state, country and shape of the sightings.

The pertinent information about the sightings will then be presented in the form of a table using Javascript on the web page.

## **2. Results**

The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. (20 pt)
The event listener is modified to detect changes to each filter in the app.js file. (10 pt)
The updateFilters() function saves the element, value, and the id of the filter that was changed. (20 pt)
The filterTable() function loops through all of the filters and keeps any data that matches the filter values. (20 pt)
The webpage filters the table correctly based on user input. (20 pt)

In this module, you'll build a table using data stored in a JavaScript array. You'll also create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.

Once entering the website our client will see the basic opening and title with the picture at the top, as the client scrolls down they will begin to see all the data and filters that we have(which is in the image below). From this image below we have 5 different filters to choose from; the date, city, state, country & shape. You can choose any of these filters enter the search bar, then the HTML page will show all of the sightings for that specific search. Multiple filters can be entered at the same time to further inspect the data in the specific search bar that is entered.

## **3. Summary**

This web page is clean, simple, appealing and informative for the readers. The filters allow the readers to look at the specific information they are searching.

However, the comments in the data set could be more informative with better descriptions as well as some validation of the information, such as number people witnessing the same sightings.

Improvements that can be made to the web page are as follows:
  . Have a date range grouping to indicate how many sightings within a certain geographic area - this can show some seasonality trends for the sightings.
  . Include a count of sightings based on the different filters.
