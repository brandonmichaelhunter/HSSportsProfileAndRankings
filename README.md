# High School Sports Profile and Rankings 
This project is a website that shows top 100 player profiles and rankings of high school basketball, baseball and football players across the US. The website and the data gathering was developed using Angular 11, .NET Core APIs, Python, MongoDB\Docker and Microsoft Azure.


## Data Sources:
Provided below is a list of data sources that I'm using to gather High School player rankings for Baseball, Football and Basketball.
https://247sports.com/
http://www.espn.com/
https://www.maxpreps.com/

## Tech Stack
Provided below is how each piece of the stack is being used:

Angular 11 - Provides the user interface to show player rankings, player profiles, perform player searches, charts to break of down players by year, state and high school and a map to see players physical locations in the US.

.NET Core API - provides data to the UI and retrieves data from the medium( MongDB)

Mongo DB - a dataase that will host the player rankings and profile data.

Docker - used to host and run the Mongo DB.

Python - a web scraper to scrape data from the data sources the app uses. Data is saved to our MongoDB instance.

Microsoft Azure - host our web scraper program within a serverless function, host our web api and UI within a web app instance and host our MongoDB.