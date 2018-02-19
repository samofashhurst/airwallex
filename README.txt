README.txt

Airwallex QA Home Assessment
============================

Prerequisites
-------------

1. Install Newman. I followed the instructions at http://measureandreport.blogspot.co.uk/2016/09/running-newman-tests-on-osx.html for macOS

Running the Tests
-----------------

1. Open the folder in the command line

2. To run using the preview environment: newman run airwallex.postman_collection.json -d data.csv -e preview.postman_environment.json

3. To run using the demo environment: newman run airwallex.postman_collection.json -d data.csv -e demo.postman_environment.json

Notes
-----

I decided to use this assignment as an opportunity to learn something, and have a go with Postman Collections and Newman.

The test cases are all contained within the data.csv file; the columns ‘status’ and ‘response’ represent the expected values.

Please see bugs.doc for a list of all the issues I found.

At the moment I don’t think it’s very obvious how to match assertion errors in the command line output to the equivalent test cases in the data file, so would definitely want to improve on that (sorry).

Hopefully you don’t have any trouble running the tests, but just in case I’ve included a quick video, airwallex.gif (can open in a browser).


Sam Alexander
19/02/2018
