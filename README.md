
# tunisiaGeoMap
project for Tunisia Map Resources 

- **tunisian.json** have Stats and thiere Delegations and localite and Postal Codes.
- **tunisiaMap.json** to use with Geographies as mapSource Note that to be able to see the map clearly you have to use some projection and scale it around (4300) and center it with [11,34.7].
- **Tunisian_municipality.geojson** this file is used to same as tunisiaMap.json but with more detailed ( compatible with [The GeoJSON Specification](https://geojson.org/) )

you can test Tunisian_municipality.geojson file in [Geojson tool](https://geojson.tools/)
![alt text](assets/geojson-tools.png "Geo Json in Action")

using tunisiaMap.json with [react-simple-map](https://www.react-simple-maps.io/) will give a result like this
![alt text](assets/simple-map.png "Simple Tunisia Map in Action")
