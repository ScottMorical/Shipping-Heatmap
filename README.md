# [Shipping-Heatmap](https://scottmorical.github.io/Shipping-Heatmap/)
## Output
[Shipping Heatmap](https://scottmorical.github.io/Shipping-Heatmap/)

## Intro
For this project I partnered with a company (specifically the Director of Business Intelligence) that asked me to analyze their 2022 sales data for shipping optimizations. The primary method of optimization they were interested in was hotspots for establishing distributional centers to lower their shipping costs as they utilize an external trucking company. 

A heatmap utilizing straight lines for their current shipping routes was the clients suggestion.

## Data
Total of 509 city/location data was used in the final version. The initial data can be found in src as "StartingData.xlsx" and the output Excel file used to create the map can be found as "LocationOutput.xlsx".


## Deeper Dive
Libraries used - Google Maps API, Folium Library, Openpyxl Library (for excel manipulation)

To create the heatmap I used quartiles for the total amount of gallons shipped to a location to vary the color, and the total shipments to a location to vary the line thickness.
