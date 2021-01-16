# Mapping_Earthquakes
**Challenge Overview**

In this challenge, we added a third map style as an additional tile layer. We ,also, added tectonic plate GeoJSON data  to the map to illustrate the relationship between the location and frequency of seismic activity and tectonic plates.We also added a Major earhquake GeoJSON data with magnitude greater than 4.5 for the last one week. To illustrate the severity of the earthquakes in relation to the tectonic plates, we logged in to GitHub and accessed the tectonic plate data from this GitHub repository. We, also, made an API call to the tectonic plate data using d3.json(), and then added the data as an overlay to the map using the L.geoJSON() layer. In addition to the streets and satelliteStreets maps, we added a third map style also. All map styles were added to the base layer so that they showed up on the map to allow the user to change which layers are visible.

**Objectives**


Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
Style the tectonic plate LineString data to stand out on the map.
Add the tectonic plate data as an overlay with the earthquake data.
Add the major earthquake data as an overlay with the earthquake data
Add a third map style to allow the user to select from three different maps.

**Challenge Summary**


For the challenge, a third map style is added to the logic.js file and has the following:

It is added to the baseMaps.

When selected the map style is present on the map.

The earthquake ,tectonic data  and major earthquake data are present on the map style.

<img width="1202" alt="Screen Shot 2021-01-16 at 3 23 05 PM" src="https://user-images.githubusercontent.com/71113701/104823318-f188e880-580e-11eb-8451-058cc5268720.png">


<img width="1189" alt="Screen Shot 2021-01-16 at 3 22 34 PM" src="https://user-images.githubusercontent.com/71113701/104823348-21d08700-580f-11eb-91a0-a65e95ccc497.png">

<img width="1204" alt="Screen Shot 2021-01-16 at 3 26 59 PM" src="https://user-images.githubusercontent.com/71113701/104823401-62c89b80-580f-11eb-83f6-8f4e4b649024.png">







