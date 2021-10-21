#European HDI Values, 2017 Authored by Abe Krell
---
##Purposes:
This interactive map is based on information sourced from a table by Max Roser from the website "Our World In Data." (ourworldindata.org/human-development-index)

Some features of this webmap include a representation of 43 seperate European Countries, and their respective HDI values, ranging from 0.7 (Moldova) to 0.953 (Norway).  Each country has a graduated circle marker based on their HDI value, where smaller values have smaller circles, while higher HDI values have larger circle representations on the map.

HDI values were compiled and organized throught the following Python Script:
list = [(all hdi values)]
largest = max(list)
smallest = min(list)

This webmap also features centerpoints of each country, sourced from Google Public data (developers.google.com/public-data/docs/canonical/countries_csv.)
