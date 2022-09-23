# UFOs

## Overview of Project

This exercise is about UFO sightings. 
We develop a table using data stored in a JavaScript array and create filters across multiple dimensions to have a detailed analysis of the UFO sightings. 

## Objective

The purpose of this analysis is to provide filters for the date, city, state, country, and shape that allow viewing information of the data through user input.

## Results

* Javascript array storing the data:
[data.js](https://github.com/gopivasanth/UFOs/blob/c03d7ab5aeee9ffbf927c16738485d61fb8d17e1/static/js/data.js)
* Javascript file housing the analysis; where we built the table and filters:
[app.js](https://github.com/gopivasanth/UFOs/blob/c03d7ab5aeee9ffbf927c16738485d61fb8d17e1/static/js/app.js)
* HTMLfile for the visualization
[index.html](https://github.com/gopivasanth/UFOs/blob/c03d7ab5aeee9ffbf927c16738485d61fb8d17e1/index.html)

## Analysis Using the Filters:
While the data is stored in the dataframes in Java Script, the users could filter on 

1. Date
2. City
3. State
4. Country
5. Shape

The users could filter by one or all of the above fields to check on the analyis of the relevant UFO sightings.

![WebPage Filter.PNG](https://github.com/gopivasanth/UFOs/blob/2d06cb3a6b2e3ec084f99be497552a916f49cef2/static/images/UFO-Finder.png)

## Summary

A drawback of this design is that the user has to have idea of the avaliable data i.e, respective values in each of the filter fields. 

A recommendation for further development is to have the fields in filters displayed as drop down values

A second recommendation for this analysis would be to make the filtering with hierarchical paths, only relevant options showing up when one of the filter is selected.
