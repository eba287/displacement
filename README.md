# Displaced: Exploring the racialized impacts of gentrification

While the disparate impacts of gentrification are widely documented, understanding the extent to which communities of color are being displaced from gentrifying areas remains relatively unclear.

1. Objectives:
    - To map demographic trends in Lexington, KY 1990-2018
    - To explore the extent to which gentrification is displacing black communities and populations of color
    - To complement personal stories and anecdotes (qualitative data) of displacement
    - To facilitate greater access to historic and contemporary census data  

2. Data sources:
    - US Census Bureau: https://data.census.gov/cedsci/ (2013 - 2018, ACS 5 year estimates)
    - NHGIS: https://www.nhgis.org (1990 - 2010, decennial census)
    - Note on methodology: NHGIS provide time series data that are standardized to 2010 geographic boundaries. This means that the block group boundaries on the map remain constant, allowing for easier comparisons through time.

3. User Interface:

    - slider widget: allows the user to change the data through time
    - pop-ups with trend lines: while hovering over areas of the map, a pop-up shows the user detailed data breakdowns for each block group, with a trend line for the data (1990-2018)
    - zoom controls: allows the user to change the scale of the map from the county down to the block groups
    - legend: the dynamic legend shows the data classifications for the choropleth maps

4. Technology stack:
    - Attribute data stored as CSV files; block group boundaries stored as a GeoJSON file
    - JS libraries: omnivore, leaflet
    - Web technologies: HTML and CSS code
    - Hosting platform: GitHub pages
