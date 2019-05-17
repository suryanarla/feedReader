# Feed Reader testing
The main goal of this project is to test the project by using various test cases. Here I am using **Jasmine** framework to write all the test cases. Really its a behaviour-driven development framework.

## I worked on following steps to complete this project.
1. Downloaded the skeleton project from rubric which was provided by **Udacity**.
2. Tested the initial project by opening `index.html` in chrome browser by using a server named **web-server for chrome** (`200 OK`).
3. From the requirements given by the udacity, I manipulated all the modules in feedreader.js using test cases.
4. I identified the `describe` function initially given by udacity and manipulated remaining modules based on this.
5. Implemented a test case for `url fields` (defined and notToBeEmpty ) by observing `allFeeds[]` array which was located in `app.js`. I used `toBeTruthy()` function to implement this.
6. Similarly implemented test case for `name` field also by using looping concept in it.
7. Wrote test case for menu. The test case included
    + Check the `.menu-hidden` class is activated initially.
    + Checked that if we click on the menu then the `.menu-hidden` class have to be set to `false`.
    + Checked that if we clicked the menu twice, the `.menu-hidden` class have to be set to `true`.
8. Built a test case for checking the initial entries not to be 0 after loading.
9. Implemented a test case to show the old data is different from newly activated data after page refreshed successfully. Here the `loadFeed(0, function(){})` holds initial entries. Similarly `loadFeed(1, function(){})` holds newly activated entries.
10. Tested entire project in `index.html`. I was exited after observing the output.

## Running this project after implementation
1. Download the zip file or github repository and extract it.
2. Run the project by opening root file (`index.html`) in any web browser.
3. Identify the test cases along with the blue color dots (.), blue dots represents success case and failures are identified by red colored dots.
4. We can observe test case also in that given jasmine test cases window in web browser.

## Conclusion
Really it's a wonderful experience I have got. I know development strategies. But I learnt how to implement testing strategy for a project also. I learnt how to write test cases using **Jasmine** framework.
