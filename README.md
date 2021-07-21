# High School Sports Profile and Rankings 
This project is a website that shows top 100 player profiles and rankings of high school basketball, baseball and football players across the US. The website and the data gathering was developed using Angular 11, .NET Core APIs, Python, MongoDB and Microsoft Azure.


## Data Sources:
Provided below is a list of data sources that I'm using to gather High School player rankings for Baseball, Football and Basketball.
https://247sports.com/
http://www.espn.com/
https://www.maxpreps.com/

## Tech Stack
Provided below is how each piece of the stack is being used:

![alt text](http://url/to/img.png) - Provides the user interface to show player rankings, player profiles, perform player searches, charts to break of down players by year, state and high school and a map to see players physical locations in the US.

![alt text](http://url/to/img.png) - a .NET Core API that provides data to the UI and retrieves data from the medium( MongDB)

![alt text](http://url/to/img.png) - a dataase that will host the player rankings and profile data.

![alt text](http://url/to/img.png) - a web scraper to scrape data from the data sources the app uses. Data is saved to our MongoDB instance.

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fseeklogo.com%2Fvector-logo%2F352823%2Fmicrosoft-azure&psig=AOvVaw2LFZVpOTvlyWB-7X3PQWHe&ust=1626914272993000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCNDcvZH28vECFQAAAAAdAAAAABAD) - host our web scraper program within a serverless function, host our web api and UI within a web app instance and host our MongoDB.