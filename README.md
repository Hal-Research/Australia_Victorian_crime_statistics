# Victorian crime statistics by postcode
## Static map

![alt text](Static map/VIC_Crimes_2012_2016_by_postcode.jpg "Average no. of Crimes (2012-2016)")

This is a static map showing the average number of crimes by each postcode using a colorscale. 
The code can be found in the folder Static map.

This inspired me to try an Interactive version.

## Interactive map for Victorian Crime Statistics in Australia (2012-2016)

![Alt](/Vic_Crimes_2012_2016_by_postcode.gif "Average no. of Crimes (2012-2016)")

You can view the interactive map by downloading the html file. It is made using folium. 

Downloaded the shape file for the postcode boundaries of the state of Victoria from the [Australian DataVic website](https://www.data.vic.gov.au/data/dataset/postcode-boundaries-polygon-vicmap-admin)

Converted it into json format using pyshp and also [this website](https://mygeodata.cloud/converter/shp-to-json)


View the [Jupyter notebook here](http://nbviewer.jupyter.org/github/pr4deepr/Australia_Victorian_crime_statistics/blob/master/Vic_Crimes.ipynb)
