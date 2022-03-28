# UFOs

## Overview
Sightings of UFOs have long been reported and speculated about around the world. Here, we have created a webpage that queries data on UFO sightings and locations. Data can be filtered using the date, city, state, country, and UFO shape.

## Results
Below is the initial display of the webpage with the five data filters on the left-hand side:

<img width="1258" alt="Screen Shot 2022-03-27 at 8 08 30 PM" src="https://user-images.githubusercontent.com/92702922/160310181-5d968f4c-16f2-4557-8f6c-7e98b94679ea.png">

To use the filters, one can simply enter one of the fields (for example, the date) and then continue to add more fields. The interactive filters will automatically once we click outside of the filters themselves. In this example, we entered the date for 1/1/2010 and got all results with all date. Then, we entered the "bonita" in the city field and our results are narrowed further. See the image below:

<img width="1018" alt="Screen Shot 2022-03-27 at 8 38 30 PM" src="https://user-images.githubusercontent.com/92702922/160312439-8cec02f1-42c1-420a-b5b2-00d3fc14692b.png">

To repeat a new query with the filters, the webpage must be refreshed.

## Summary

This webpage completes a simple query using data filters to pinpoint UFO sightings by several fields, such as date, city, state, country, and UFO shape. However, some of these filters have limitations regarding how data is entered. For example, dates must be entered in M/D/YYYY format and will not accept MM/DD format. 

As a result, one recommendation would be to allow for varying date formats for input. Another recommendation would be to remove case sensitivity for the remaining fields of city, state, shape, and country. These fields only work when lowercase strings are entered, which are already convenient, but allowing for filters to accept strings regardless of their case would make this webpage even more effective.
