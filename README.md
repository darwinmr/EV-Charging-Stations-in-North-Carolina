# EV-Charging-Stations-in-North-Carolina

"EV Charging Stations in North Carolina" (A map that displays both a representation the total charging stations per county and the network type for each charging station)

This web map displays the locations and types of EV Charging Stations across North Carolina. The data was obtained from the USDE Alternative Fuels Data Center [[https://www.nea.org/resource-library/teacher-salary-benchmarks](https://afdc.energy.gov/stations/#/analyze?region=US-NC&show_map=true&country=US&fuel=ELEC&lpg_secondary=true&hy_nonretail=true&ev_levels=all 
)] and placed in a CSV file. I used QGIS to coount each number of points per county polygon. Next, using the open source tool geojson.io the CSV file was converted to a geoJSON file which contained the names of the stations, locations, and network types; it was then loaded into VSCode as a javascript file. Using Leaflet JavaScript library, the geoJSON features were displayed as Font Awesome icons. 
