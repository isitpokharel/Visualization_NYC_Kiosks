# NYC LinkNYC Kiosks Interactive Map

Welcome to the NYC LinkNYC Kiosks Interactive Map project! This project aims to provide a visual representation of LinkNYC kiosks across all boroughs of New York City using cartographical data. Users can explore and locate LinkNYC kiosks conveniently on the map and click on the location to see details about the particular Kisosk. 

## Features

- **Interactive Map:** Navigate through the map to explore the distribution of LinkNYC kiosks in different boroughs.
  
- **Kiosk Details:** Click on individual kiosks to view detailed information, such as location, status, and additional relevant data.


## Data Sources

The project utilizes cartographical data of New York City and LinkNYC kiosks data to create an accurate and up-to-date representation of the kiosks' locations.


Boundaries of Neighborhood Tabulation Areas as created by the NYC Department of City Planning using whole census tracts from the 2010 Census as building blocks. These aggregations of census tracts are subsets of New York City’s 55 Public Use Microdata Areas (PUMAs) available at https://data.cityofnewyork.us/City-Government/NTA-map/d3qk-pfyz.

LinkNYC kiosk location data available at https://data.cityofnewyork.us/Social-Services/LinkNYC-Map/tgrn-h24f


## How to USE

You can compile a html using presentation.Rmd file or download the presentation.html file and view it on browser. 

To compile using the rmd file , you will have to clone the entire repo and change the location specified in this part of the code. 

link_nyc <- read.csv("/Users/ipokharel/Desktop/512_presentation/LinkNYC_Map.csv")
shape_file_folder <- "/Users/ipokharel/Desktop/512_presentation/nynta2020_23b"
setwd(shape_file_folder)
setwd("/Users/ipokharel/Desktop/512_presentation")

