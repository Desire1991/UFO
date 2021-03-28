# UFO

Overview:

In this project, I created a table with a main purpose of organizing UFO data stored as a JavaScript array. Then I changed the data to a table using HTML, Bootstrap, and JavaScript D3 library. The table will have the ability to filter data based on specific criteria such as date, city, state, country, and UFO shape, however this filtering process will be case sensitive

Results:

To perform the search, user can enter their desire values on the Filter Search section-left side of the table. After entering a value, the table will automatically be filtered to match with the user's selections. 

![Entire_Table](https://user-images.githubusercontent.com/74233163/112760282-ea731900-8fbb-11eb-83d3-f0e8e03fab22.png)

To go back to the original table, either remove current values in the Filter Search section, click F5 on the keyboard, or click the title UFO Sightings on the top left of the web page.


![Webpage](https://user-images.githubusercontent.com/74233163/112760285-eba44600-8fbb-11eb-9826-293ef478fc46.png)

Summary:


One of the biggest drawbacks of this new design is that the filters are case-sensitive. Even if the users type the correct value that matches the data set but did not enter it as lowercase, the filter feature will not work.

With that been said, I have some suggestions that we can make in the next version of the website:

We can use the Javascript Regular Expression feature in the Filter Search area to make it easier to search for the users.
We can create a Reset Filters button so that users can clear all of the filter values that they entered without having to manually delete individual values or find the navigation bar to refresh the page.

Another suggestion is to aid the filtering process would be to create a “Comments” filter. While it is not possible to filter to a specific comment by user input, the “Comments” filter could instead be used to look for specific phrases within the comments text such as “green” or “projectile”.
