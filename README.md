# Real Time Bus Tracker
This real time bus tracker collects live GPS location data on Boston's public bus system using an API from the MBTA. The script asks for the bus locations on the first bus route every 15 seconds and maps the coordinates accordingly using mapbox. After 14 seconds of the markers being displayed on the map, a 1 second removal of the markers shows new data is about to come in. If the operator desires, a popup at each location is created and displayed by clicking on the bus' marker for each bus. This program demonstrates the use of asynchronous and recurring functions to properly collect, analyze, and display data.

## How to Run?
First, download all the files as a .zip file. Then extract the files onto a folder of your choice and load index.html into a browser. 
Open the console window in developer tools to see the location array being updated every 15 s, as well as a 1 second removal of all markers. Select a marker to see which bus it is!

## Roadmap of Future Improvements
As someone who grew up in Massachusetts and loved how cheap and accessible Boston's public transportation was relative to Vegas, it would be great if an MBTA employee used a more refined version of this to monitor and supplement their daily routes. Some features that would really flesh this out are: additional bus routes, alerts when a bus has been idle, and alerts when a bus is removed from a route. The more information that is included the more useful it would be for the apporpriate audience.

## License Information
This project was created as part of the MIT xPRO Full Stack Development program. Mapbox and MBTA APIs were incorporated in this project, as well as a baseline for this project from Dr. Sanchez of MIT. 

