# geocoding
This model will geocode any street address using OSM Nominatim service.

Currently this code leverages OpenStreetMap (OSM) Nominatim service only. And thus if the address is not present in the OSM gazetteer then no lat., lon will be returned. That said, as the coverage in OSM is not consistent across the globe, other publicly available gazetteers are being explored to call in this code for geocoding purpose. However, for most of the coarse grained address (city level, state level, country level) the code works fine.
The code is flexible enough and can adapt/accommodate to other premium geocoding service, for example, Google geocoder or HERE geocoder. 

The positive side of OSM is its freely available and has a good coverage in Europe and most part in the USA. A crowdsourcing approach through volunteered geographic information (VGI) is required to enrich the gazetteer. 

