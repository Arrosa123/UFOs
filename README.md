# UFOs

## Overview of Project:
The purpose of this project was to learn how to take data stored as a JavaScript array or list and organize it into a table. So Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date,we added table filters for the city, state, country, and shape.

## Results:
Using JavaScript and HTML, we modified the code in our index.html file to create more table filters. In addition to the date filter we created in this module, and added filters for the city, state, country, and shape, as shown in the following image:

![ufo](https://user-images.githubusercontent.com/96403349/159211004-59e07e66-9f0a-4119-8a04-6699483809c7.png)

Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

1. The list element that creates the button is removed, and there are five list elements for filtering in the index.html file.
2. The event listener is modified to detect changes to each filter in the app.js file.
3. The updateFilters() function saves the element, value, and the id of the filter that was changed.
4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
5. The webpage filters the table correctly based on user input.

Here we can show how to select, drop and display information by using filter search section and can filter by one or all of the search criteria.

![2022-03-20 (1)](https://user-images.githubusercontent.com/96403349/159211472-0391e628-6211-49e3-ba6b-cfc9da43e600.png)

## Summary:

The drawback of this webpage is the page not able to retain the results from a search once the page is refreshed because the refresh returns the page to and the table to the default settings.

### recommendations
- Search results should be retained even when the page is refreshed.
- Under the filter elements, there can be a "Download button" , which downloads the filtered data for the users.


