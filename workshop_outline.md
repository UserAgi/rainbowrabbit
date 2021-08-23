# WTT Workshop 

Proposal 1: 


## Workshop Plan 

1. Slides: Present geodata, use example of flooding data (Data - Kanton Bern)
    - beginner questions: 
        - what are different data formats (WMS? GeoJSON? ...)
        - what is GIS
        - 4 basic geodata types 
            - map: just pictures, they are performant, but not very useful to analyse, to go deep  
            - point: e.g. a train station
            - ... 
        - what do I need to have on my computer to work with geodata
        - ... 
    - examples of data relevant to flooding: contours of lakes, location of bus stops, locations of water level meters, buildings on affected areas, population density 
    - should it be slides-only, or slides+practical? 

1. Slides: present 3-4 geo-services (Geodienste)
    - what are the geo-services, how are they different from locally stored geo-data 
    - Z.B. Swisstopo, Geodienste.ch, SBB Transport-Data
    - Swisstopo: https://www.geo.admin.ch/de/geo-dienstleistungen/geodienste/darstellungsdienste-webmapping-webgis-anwendungen/web-map-services-wms.html 
    - have an example for geoservice, but also an example of a local data 

1. Slides/Demo: how to integrate geoservices on maps 

1. Practical: 
    - participants pick a dataset that interests them  
    - integrate the dataset/geoservice data on a map
    - spatial analysis: cross-section point and polygon 

1. Output: discussion round 
    - participants present which data they used, what they have achieved  



Snippets: example - take a code snippet and change something to change the layer 

Analytics: prepare data in a small extent, snippets analysis (e.g. how many bus stops in a flooding area), they can then add more layers, they can do a small analysis, add another layer from this region 

ML: extra, as a homework 


## Flooding in Kanton Bern - Data sources 

### Gefarenkarte 
Am Beispiel Kanton Bern Gefahrenkarte mit Ereigniskataster an ausgewählten Standorten vergleichen.

Gefahrenkarte (Gefahren von Flüssen ausgehend) siehe "Naturgefahrenkarten 1:5 000" / "Gefahrengebiete: Wassergefahren" und Ereigniskataster siehe "Naturgefahren Ereigniskataster" / "Ereigniskataster Wasser / Murgang"

Quellen (spezifische URL für jeden Layer muss noch recherchiert werden):

- https://www.geoservice.apps.be.ch/geoservice2/services/a42geo/a42geo_geologiewms_d_fk/MapServer/WMSServer?

- https://www.geo.apps.be.ch/de/geodienste/geodienstangebot/sheet/de-DE/7271c124-1f9a-a674-7515-b14e3864b1c8/geoservice/complete/search_list.html

 
Nebenbei: Geo7 hat eine "Gefährdungskarte Oberflächenabluss" (Gefährdungskarte bei Starkregen) erstellt (verfügbar via map.geo.admin.ch) - es gibt jedoch kein Ereigniskataster dazu

