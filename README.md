Read Me: ikanow.mongodc2013.presentation project
================================================================================

Introduction:

The files and example code in this repository are a part of my presentation 
March 11th, 2013 at  MongoDB Washington DC 2013 titled:
Visualizing MongoDB Objects in Concept and Practice

Please note that this project includes code from the following open source
projects:

- Bootstrap: http://twitter.github.com/bootstrap/
- JQuery: http://jquery.com/
- D3.js: http://d3js.org/

If you'd like to run the code locally you will need to have an instance of
MongoDB and perform the following steps:

1. Start MongoDB using the --rest option (e.g. "mongod --rest");
2. Unzip the MongoDB dump files in the mongodc.zip file;
3. Restore the dump files to your MongoDB server using mongorestore:
	mongorestore --db mongodc <pathtodumpfiles>/mongodc

Note: In order to run the Google Maps JavaScript API examples you will need to
acquire an API Key from Google. Instructions for obtaining a key can be
found at the following URL: 
https://developers.google.com/maps/documentation/javascript/tutorial#api_key
