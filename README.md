# Feed Reader Testing

**Auther:** Asmaa Hassan.

**Date:** Feb 2, 2017.

##Description:
This project is part of Udacity FrontEnd nanodegre, The required tests for the project (RSS Feed testing, RSS Feed properties, menu default state, and menu hiding/showing) are all provided and are comprehensive enough to adequately test the functionality


##Project Instruction:
###Data Collection
- You can read the project requirements at the following url:
https://review.udacity.com/#!/rubrics/18/view

- To get started please download the original code from the following repository:
https://github.com/udacity/frontend-nanodegree-feedreader


### steps:
1- I edit the allFeeds variable in ./js/app.js to make the provided test fail and to see how Jasmine visualizes this failure in my application. then i return the allFeeds variable to a passing state.

2- write the flowing tests:
- Test and confirm each feed in the allFeeds object has a URL defined and the URL is not empty.
- Test and confirm each feed in the allFeeds object has a Name defined and the Name is not empty.
- Test and confirm the menu element is hidden by default and the menu changes visibility when the menu icon is clicked.
- Test and confirm the loadFeed function is called and completes its work, and there is at least a single .entry element within the .feed container.
- Test and confirm the content actually changes when a new feed is loaded by the loadFeed function.