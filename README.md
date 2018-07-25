
The objective of the FEND Feed Reader testing project was to implement an outside source testing program called “Jasmine” to test the viability of the application JavaScript functions. Jasmine acts as a quality control analysis mechanism so that websites are effective and function properly. According to Wikipedia, “Jasmine is an open-source  testing framework for JavaScript that will not cause problems in the file or integrated development environment.”

We were required to construct specific viability tests using provided source code from Udacity. Each test was directed by function to look for particular aspects of the website that involved animation, activation or change in data content.

All tests were placed in a $() function to accommodate the possible need of specific DOM elements.
In addition, each individual test consisted of a test suite that provided variable definitions and additional function call.  Two of the final tests were required to involve asynchronous functions.

**Test #1 – RSS Feeds** 
This test utilized the allFeeds variable given in the app.js file to ensure that it is not empty of data in the array and that the allFeeds variable was defined. We were instructed to change the array for demonstration to see what test errors would occur in Jasmine and to return the information back to its original state to ensure all data was present and would pass the test.

**Test #2 - URL data**
Required to write a loop function that would go through each individual feed in the allFeeds array and look for a specific url defined that was provided with the title of each feed.  Test error occurred only if the url data was empty.

**Test #3 – Name data**
Required to write a loop function that would go through each individual feed in the allFeeds array and look for a specific name defined that was provided with the url of each feed.  Test error occurred only if the name data was empty.

**Test #4 – Menu Element**  
Required to write a new test suite using “the menu” element.  It was to determine that the menu was hidden by default and would show and then again hide itself only upon ‘click’.  Involved analysis of the HTML and CSS to figure out how the menu was hidden and showing.

**Test #5 – Completed Work (Initial Entries)**
Required to write a new test suite with an "initial entries" variable.  The test was constructed to make sure that the loadFeed function was completing its work by providing a single entry in the feed container.  The loadFeed function was asynchronous and utilized a beforeEach function with done(); at the end.

**Test #6 New Feed Selection**
Required to write one last test suite with "new feed selection" variable.  This test was to make sure that if the news feed content changed within the array that the loadFeed function would activate the change to show the new data content.

