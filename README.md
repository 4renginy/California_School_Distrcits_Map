# California_School_Distrcits_Map

The purpose of this project is to create CA map with all the school districts with distinct information on it.

1- Data;
The data has been pulled out from ;
https://gis.data.ca.gov/datasets/e9476c422f0842a7a38652aaf4c7597c_0/geoservice?geometry=-129.601%2C36.267%2C-111.331%2C39.305 



The data has very detailed information about the distrcits with 138 colums and 944 rows. For this project I have used
handfull of them but upon request the information on poppup windows could be extended.

2-Tools used;
To accomodate this project I have used HTML, JavaScript and CSS,

    HTML; setup the page with necessary libraries for leaflett, javaScript connections and css files.
    CSS; the only setup for the project was height for the map
    javaScript; 
        1- Created a config file for API key
        2- Created backgound layer and any other layer wanted to add to project in our case I added
            street view and 
            satellite view
        3-Created a base layer to hold both maps
        4-Created map object with center and zoom level set for default layer
        5-Created a schooldata layer
        6-Pulled the school data from source
        7-Created popups 
        8-Added all the info to geojason layer
    Combine all the data and show off.

Originally I wanted to have markers for popups but then I decided it would be too crowded and busy so
I have decided to leave it just the way leaflet set up. I wish I could change the border colors.
