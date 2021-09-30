# The Objective
The goal of this application is to provide a web service (API) for searching a number of closest airports for every pair of cities in a list.

The project uses the following endpoint https://homework.appulate.dev/api/Airport/search to get information about city airports.
More information is available at https://homework.appulate.dev/swagger/index.html.

The application accepts a list of cities' names. Every city could have zero or more airports.
The result is the list of all possible cities pairs. Every city pair has cities names, airport names and distance.
