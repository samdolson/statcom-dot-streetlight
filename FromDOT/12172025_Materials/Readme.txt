##./DATA/CONFLATED/*
RAMS AADT conflated to OSM segments provided by Streetlight
Contains Streetlight volumes, and RAMS AADT

Interstate segments all have a Zone_Name that starts with the interstate route; so something like 'I 80 / 5190691'
Ramps all have a Zone_Name that starts with 'motorway_link'. Should look something like 'motorway_link / 19706740'


##./DATA/RAMS_EXPORT/*
Shapefile exports of spatial tables. 
Contains Iowa DOT AADT.
Created by LRS overlays
##./DATA/STL_EXTRACT/
Contains Streetlight exports; 2022 and 2024, Motorways (OSM designation for roads that carry highest volume, highest speed ) and ramps (OSM calls these motorway_links)


We are most interested in the correlation between AADT_IADOT and VOLUME_STL on the interstates, ramps, and both together. Possibly segmented by AADT/Volume.