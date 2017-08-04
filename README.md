# Feedreader Project

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Utilizes the - [Jasmine](https://github.com/jasmine/jasmine) Framework

## To run the application

- Clone or Download the ZIP file
- Open the folder on your computer
- Open `index.html` in your browser
- Scroll to the end to see the tests

## What was implemented

Review the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)

1. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
2. Return the `allFeeds` variable to a passing state.
3. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
4. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
5. Write a new test suite named `"The menu"`.
6. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
7. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
8. Write a test suite named `"Initial Entries"`.
9. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
10. Write a test suite named `"New Feed Selection"`.
11. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

## License

The project is licensed under the [MIT license](license.txt).
