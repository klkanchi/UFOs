# UFOs

## UFO Sightings with JavaScript

### Purpose

1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.

2. Describe JavaScript syntax and ideal use cases.

3. Build and deploy JavaScript functions, including built-in functions.

4. Convert JavaScript functions to arrow functions.

5. Build and deploy forEach (JavaScript for loop).

6. Create, populate, and dynamically filter a table using JavaScript and HTML

## Overview

The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

## Results:

### Welcome to UFO Sightings!

![UFO_sightings.png](https://github.com/klkanchi/UFOs/blob/main/static/images/UFO_sightings.png)

![data.png](https://github.com/klkanchi/UFOs/blob/main/static/images/data.png)

#### How the filters appear after being used:
By typing in the suggested placeholder elements as the filters, the result returns 2 matches. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website.

![selected_filters.png](https://github.com/klkanchi/UFOs/blob/main/static/images/selected_filters.png)

## Summary:

### Drawback:

The user must know specific dates, cities, or shapes to search. The labels are also case sensitive. Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".Only the cities listed in the data.js in the correct format are printed. 

### Recommendations:

1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.
2. A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.
