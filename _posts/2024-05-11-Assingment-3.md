---
title: "Assingment 3"
date: 2024-05-11T15:34:30-04:00
categories:
  - Blog
tags:
  - assignment
---

Assignment 3: 

Spatial Data

## **Introduction**
For this assignment on Spatial Data, I have chosen the source of [The Brooklyn City and Business Directory 1879-80](https://archive.org/details/1880BPL/page/n21/mode/2up). This source is a directory to businesses, government agencies and public services in Brooklyn in the year 1880. The source includes the name of the business or business owner, the occupation, and the address of the business. 

## **Data Collection**
I chose 2 random pages 221-222 and I copied the words of the entire page, and created a csv file of the data using chatgpt. I was able to manually copy and paste from the page onto chatGPT because there was an ocr layer already applied on to the source. The prompt I provided chatGPT with was: “Make a CSV file with and only using  the above data  with 50 rows.” I attempted to tell chatGPT to create more rows of data, but when I tried that, chatGPT began to make up data or repeat data. With the CSV file created, I uploaded it to google sheets. The columns include the name of the business owner, their occupation, the location of their business. Using Geocode by Awesome Table, I was able to produce longitude and latitude data from the given addresses. As all the addresses were located in Brooklyn, I added Brooklyn in front of all the addresses in order to improve accuracy. The Geocode was able to provide 35 out of 50 longitudinal and latitudinal data. I’m unsure whether the remaining 15 were a result of Geocode not being able to produce the data or an error with the data from the OCR. 











##Data Visualization

Using [kepler.gl](https://kepler.gl), a powerful web- based app that helps with visualizing geolocation data, we were able to provide a map from the CSV. Due to the nature of the data, there were no repeats and meaningful grouping of the data. Most of the occupations were different and grouping by name doesn’t really provide much insight. 

