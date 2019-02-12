# Project: Feed Reader Testing

#### Project Overview

This is a project to test a RSS Feed Reader application using **Jasmine** a JavaScript testing
framework.

#### Running the app locally

Open up the _index.html_ file in your preferred web browser.

#### About the test

1. RSS Feeds: Test to make sure the allFeeds variable has been defined and it is not empty. The test loops for each feed to ensures each one has an URL, it is not empty and each feed has to have a name, and it is not empty as well.

   - are defined
   - each feed has an URL and is not empty
   - each feed has a name and that name is not empty

2. The menu: Test if the menu is hidden by default on page load. Test ensures when _icon-list_ is clicked the menu is visible and hidden when clicked again.

   - menu hidden by default
   - display menu when clicked and hidden when clicked again

3. Initial Entries: This test ensures when the loadFeed function is called and completes its work. Making sure there is at least one entry within the .feed container.

   - there is at least an entry within the feed container

4. New Feed Selection: Test ensures that there are more than one feed in the allFeeds and the second feed is different that the first one.
   - new feed different that previous feed
