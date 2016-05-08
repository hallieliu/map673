# Lab 04: Tasks 1 + 2

** DATASETS: **
Primary Household Energy Source by County (2009),
County Population (2009)

** Data Source: **
[Kenya's open data portal](https://www.opendata.go.ke/)

** Scenario ** - An NGO called Energy Everywhere aims to improve access to electricity in developing populations. They are investigating how Kenyans currently power their households, and want to know more about what sources are available and which ones are most used, as well as how many households in each county are without power.  EE wants to make a map summarizing the data they've been provided by the Kenyan Government.

** Why make this product? **
* To visually identify the need for electricity (and whether it is needed) and compare the distribution of different power sources in use
* To connect numbers to real places
* To visualize population information

** What do I want to get from this product? **
* A tool for data exploration that works well and is easy to use
* A map that is visually pleasing and understandable

** What do I want to provide to users of this product?**
* A map that works
* An interface that is useable and requires little explanation
* Data presented in ways that invite them to think about it differently than they would numbers in a table
* Ability to add layers and toggle them on/off

** Content Requirements **

* Population density as areal data by county
 * choropleth 
 * households per sq km 
* Energy data as proportional symbols 
 * toggle layers 
 * different color for each layer 
 * each source is a layer   
* Popup for county summarizing 
 * total no. households,
 * no. households per sq km 
 * no. households + % per energy source    
* Popup for energy data 
 * Total # households for that source
 * % of households for that source in that county
 * % of national total for that source from that county    
* Basemap that includes county boundaries
* Legend


** Functional Specifications **

* Bind county location geoJSON to pop density from CSV file

* Load energy data dynamically from CSV file

* Data layer for population density

* Data layer for each energy source

* Data layers will be drawn to map

* Popup information will be attached to each symbol and available on click or hover (energy data popups include bar/graphs??)

* Legend and toggle options will be visually combined to one unit



