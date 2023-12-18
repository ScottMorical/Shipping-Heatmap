# [Shipping-Heatmap](https://scottmorical.github.io/Shipping-Heatmap/)
## Output
[Shipping Heatmap](https://scottmorical.github.io/Shipping-Heatmap/)

## Intro
For this project I partnered with a company that asked me to analyze their 2022 sales data for shipping optimizations. The primary method of optimization they were interested in was hotspots for establishing distributional centers to lower their shipping costs. A heatmap utilizing straight lines for their current shipping routes was the clients suggestion.

## Data
Total of 509 city/location data was used in the final version. This example data is mocked up to retain the confidentiality of the original sales data.
![ExampleSS](https://github.com/ScottMorical/Shipping-Analysis/assets/110702768/98d9d1b2-b35c-4b7b-bad3-8920c4087f8f)

## Deeper Dive
Libraries used - Google Maps API, Folium Library, Openpyxl Library (for excel manipulation)

To create the heatmap I used quartiles for the total amount of gallons shipped to a location to vary the color, and the total shipments to a location to vary the line thickness.