1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   - I would fit automated tests withing a GitHub Actions that runs whever code is pushed. This makes testing consisten and automatic for everyone who is working on the project. If the tests are only run locally, someone could forget to run tests and push the code which might have errors. If tests are done after all development is completed, then the errors could pile up over time and then it will be much harder to find and trace errors. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
    - I would not use E2E testing to check if a function is returning the correct output. E2E testing will most likely check the full user interactions with the program. I would instead just run a unit test for that function to see if it returns the correct output.

3) The difference between navigation and snapshot mode is that navigation mode analyzes the page right after it loads make it useful to measure page-load performance, like how fast a site appears. Snapshot mode analyzes the page in it current state checking things like accessibility and optimization. 

4) Three things we could do to improve is
    - Add proper `alt` text to product images so site is more accessible
    - Improve solor contrast and/or text readability if Lighthouse flags contrast issues
    - Optimize images and other assets to make the page load faster