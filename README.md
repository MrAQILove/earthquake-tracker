# Earthquake Tracker
Responsive Earthquake Tracker

Uses:
- Google Map API
- USGS real-time earthquake data (JSON)

This project is to is to display the locations as pins of earthquakes around the world on a map. This project uses real-time earthquake data from the United States Geological Survey (USGS). The USGS website provides their data in a number of formats, which you can copy to your domain for local access by your application. This project requests JSON directly from the USGS servers using the jQuery.getJSON() method. The API returns all the earthquakes in the past 24 hours and can be found here: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_day.geojson

The project is mobile responsive and displays annotations of the earthquake and the time and date it occured. There us also a separate panel on the right hand side that gives you futher information about the earthquake.
