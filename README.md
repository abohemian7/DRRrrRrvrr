`bower install`
`open src/index.html`


Andrew Boyer

building a web app that allows basic maintenance of guest registry.

The main academic components of the project are setting up
gulp, karma, and getting angular to work with the MVC model we've discussed.

Build steps... in a console in the root (DRRrrRrvrrWorking) directory:

1- npm install (patiently)
2- bower install (should be fast)
3- gulp

in separate terminal, in the project root directory...
4- check which version of python you're running
    1a- if 2.X, run : python -m SimpleHTTPServer 8000
    1b- if 3.X, run : python -m http.server 8000

5- go to http://localhost:8000/dist/



• readme up to date
• gulpfile with
    • Karma test
    √ jshint tests
    √ concat JS and CSS
    √ uglify JS and minify CSS
    √ liverelead using gulp connect that watches JS, CSS, and HTML
• tests
    • all controllers and services need tests
        • tests for controllers should mock the DOM elements and services
    • find all the spots where you can make a "should" statement and make a test for each


TESTS:




