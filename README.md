# UFOs

## Overview of Project

Dana is a data journalist who is at a point in her career where she has the freedom to choose the topics she wants to write about. When she's given the opportunity to write about her hometown McMinnville Oregon, she jumps on it for a couple of reasons. First, it's an opportunity to revisit the memories and people back home. And second, the topic UFOs. 

McMinnville is famous for its sightings and even has an annual gathering of UFO enthusiasta. It's a topic that Dana has been interested in since she was a child. When she first heard about farmer Trent's sighting back in 1950. The only thing she has to go on so far is a JavaScript file filled to the brim with sighting information. Countries, cities, states, type of sighting, there is a lot in this file. Thankfully, Dana is aware of JavaScript visual functionality. Her plan is to first use Javascript to display the data as a table. However, because there is so much data, sifting through it without any adjustments would be a challenge. Additionally, Dana wants to put everything together in a tidy HTML page. Her article, the table of data to support her findings, and easy to use filters to fine tune the results.

### Purpose

The purpose of this analysis is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, to add table filters for the city, state, country, and shape.

## Results

### The Webpage

Upon landing on the webpage, visitor will see the following page:

<img width="1360" alt="UFO_webpage" src="https://user-images.githubusercontent.com/95826875/157372458-7fcb0820-fc64-4072-b1e5-35cc9773033f.png">

### The Filters

Using JavaScript and HTML, the code from the module is modified in the index.html file to create more table filters. In addition to the date filter created in this module, filters for the city, state, country, and shape are added further.

<img width="1371" alt="UFO_sightings" src="https://user-images.githubusercontent.com/95826875/157372127-21a7468c-d304-447a-9a35-b3694cf203d8.png">

#### Search Criterias

Visitor will type the placeholder elements as the filters in lower case letter without any spaces at the end of the text and hit enter. This will return the filtered matches. To reset the filters, visitor can click the 'UFO Sightings' at the top left corner of the website.

_Search by City_

<img width="1323" alt="Screen Shot 2022-03-08 at 11 36 10 PM" src="https://user-images.githubusercontent.com/95826875/157373890-4fe7549a-8b67-4cef-8277-82af45d5d082.png">

_Search by State_

<img width="1318" alt="Screen Shot 2022-03-08 at 11 36 36 PM" src="https://user-images.githubusercontent.com/95826875/157373971-1c306b26-09e7-4641-879b-de5381d5e1b9.png">

_Search by City and Country_

<img width="1318" alt="Screen Shot 2022-03-08 at 11 37 11 PM" src="https://user-images.githubusercontent.com/95826875/157373989-d9303dc1-48dd-407c-ae95-d1f852aaa4c3.png">

_Search by City, Country and Shape_

<img width="1314" alt="Screen Shot 2022-03-08 at 11 43 35 PM" src="https://user-images.githubusercontent.com/95826875/157374321-1720e558-6b30-40f5-94bb-76dc62b34911.png">

In this way, user can filter the data with multiple criterias!

## Summary

### Drawbacks of this Webpage

There are few drawbacks with this design:

1. The search elements are 'case-sensitive'. the filters will not work if the input is not given exactly how they are in the data.

2. User must know specific city, state, country, and shape to filter the data.

3. There's no click button, the data will be filtered on hiting enter.

4. The data is not updated.

### Recommendations for further Development

1. Adding functionality to accept 'upper cases' and to trim extra spaces from the entered data.

2. Adding functionality to pull latest data from live sources.

3. Adding features like click button, sorting filters to make page more interactive.

4. Adding functionality to explore a date range instead of sticking to a singular date. 



