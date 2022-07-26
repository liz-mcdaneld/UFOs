# UFO Finder

## Overview of the Project

The purpose of this project is to display data in a JavaScript array in an organized dynamic table on the client’s webpage. The data also needs to be able to be filtered by multiple search criteria at the same time. JavaScript is used to create the table and HTML/CSS and Bootstrap are used to customize the appearance of the website.

## Results

The user is greeted by an image of Earth from space behind a jumbotron header “The Truth is Out There”. There is also a navigation bar, “UFO sightings”, that will reset the page after a filter has been applied when clicked. Under this we have two columns, a header column “UFO Sightings: Fact or Fancy?”, and Dana’s article paragraph. 

![UFO_sightings_png](https://user-images.githubusercontent.com/103263248/181077292-83a51892-9042-4d47-ace5-3c8c1d459f7c.png)

The filter bar is set to have placeholder elements as the filters for examples of the information to filter by. A user will type in the desired search criteria, in all lowercase. Then click outside the filter box, or press enter, and the filtered data will populate in the table. For example, to see all the sightings reported in California, type “ca” into the “Enter State” filter, and all results for California will display in the table. To reset the table, click the navigation bar “UFO Sightings” at the top of the website.

•	Unfiltered data displayed in table with placeholders in Filter Search

![initial_visualization_of_webpage_png](https://user-images.githubusercontent.com/103263248/181077405-749bc5cc-0224-4988-84aa-e80dd6371c0f.png)

•	Filtered by State “ca”, California.

![ca_search_example_png](https://user-images.githubusercontent.com/103263248/181077427-da51c728-2d20-456c-bb47-e236dd4d0527.png)

## Summary

### Drawbacks of the Current Design

Based off the search criteria, a user needs to know the exact dates, cities, states, or shapes they are searching for. This isn’t always the best way to filter, as users may not know this exact information. Search criteria must also be entered in all lower-case, with correct spelling, which could confuse useres why lower-case “ca” must be used, instead of the commonly upper-case use of “CA”. Cities with spaces in the name must also be typed as they appear in the dataset. For example, the city Glen Spey, NY must be typed as “glen spey” in lower-case to return the data; “glenspey”, “Glen Spey”, “Glen spey” or other typed variations of the city will not return information.

### Recommendations for Further Development

1.	Additions to the filters to be able to catch misplaced spaces, spaces at the end of words, and upper- and/or lower-case words.

2.	Changing the date search criteria to be a range instead of an exact date. Allowing searches to be entered as a specific month or year, instead of an exact day. Users may want to find all the sigtings for a more generalized period of time, instead of a specfic data.
