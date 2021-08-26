# UFOs
An interactive webpage on UFO sightings

## Project Overview
The purpose of this project was to create a dynamic webpage that would hold data from a JS file in a table. The table can be filtered by accepting user input and adjusting the content displayed by inserting JavaScirpt into an HTML page. CSS and Bootstrap components were used to add customization. 

### Resources
   - Data Source:
        - [data.js](https://github.com/samanthajpv/UFOs/blob/8ddc91532e3341772eaf7e1dbd718e89c19b4b27/static/js/data.js)
   - Language: JavaScript, HTML, CSS
        - CSS Framework: Bootstrap
   - Software: VSCode
   - Code:
        - [app.js](https://github.com/samanthajpv/UFOs/blob/8ddc91532e3341772eaf7e1dbd718e89c19b4b27/static/js/app.js)
        - [style.css](https://github.com/samanthajpv/UFOs/blob/8ddc91532e3341772eaf7e1dbd718e89c19b4b27/static/css/style.css)
        - [index.html](https://github.com/samanthajpv/UFOs/blob/8ddc91532e3341772eaf7e1dbd718e89c19b4b27/index.html)

## Results
The webpage is composed of 6 parts as seen in the image below. Using the multiple search criteria is discussed in the Table Filters section.
IMAGE
1. Navigation Bar - The text "UFO Sightings" text will refresh the page when clicked.
2. Page Header - An image was used as background of the header for styling purposes.
3. Article Title - An article was added to give the readers a background of what the page is about and to be able to grab their attention as well. Visiting a page with just a table and no customization would appear dull to visitors.
4. Article Paragraph - The article paragraph was placed in line with the title to give the page an organized look.
5. Table Filters - There are 5 search filters available to the user, namely, Date, City, State, Country, and Shape.
    - When the page is initially loaded, with the *index.html* file, it displays all of the table data. 
    - There is a placeholder text in each search box to give the user a guide on the format of the data available for searching.
    - User can input only one criteria for each filter and the data table on the right will update accordingly if there is a match with the user input. User has to click outside of the search box to see the change. User can input one, or fill in all of the search filters. Table will return data as long as combination of the searches have a match. If no data is returned, it means that user input does not have any match in the UFO sightings data.
    IMAGE
    IMAGE
    - To reset the filters, text in the filter search boxes should be removed or the navigation bar can be clicked to refresh the page.
6. Table of Sightings Data - Table is updated through the JavaScript code of logging the elements that changed (if there was an input), looping through the filters, and matching it up with the data file. Refer to *[app.js](https://github.com/samanthajpv/UFOs/blob/8ddc91532e3341772eaf7e1dbd718e89c19b4b27/static/js/app.js)*.

## Summary
One drawback of this design is that filtering the data is a process of trial and error. The user may have to scroll down to get a glimpse of the information that can be filtered but it is most likely a guessing game for most. In order to make the webpage more user-friendly, below are recommendations for further development:
    - **Add dropdown option** - It will be easier for users if there will be a list of the available terms for searching. For example, a dropdown list of the cities, states, countires, and shapes will be helpful, as well as making the range of the date option limited to what is in the data. In addition, it will also be convenient if the dropdown list will update depending on other filters and show only what is left for filtering.
    - **Add option for multiple criteria in a search box** - A user might want to see data with multiple search criteria such as two cities or three different shapes. Enabling this feature will make the webpage more dynamic and not as restrictive as the current design.

## Reference
(1) Trilogy Education Services. (2021, August). *Module 11 Challenge*. https://courses.bootcampspot.com/courses/626/assignments/13321?module_item_id=213126