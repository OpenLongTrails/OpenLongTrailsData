Appalachian Trail

Source: OpenStreetMap. The Appalachian Trail ("AT") is relation 156553 and is available at: https://www.openstreetmap.org/relation/156553

Method used to obtain this route data:

1. Load https://overpass-turbo.eu/
2. Enter the following query:
    [out:json][timeout:60];
    rel(156553);
    (._;>>;);
    out;
3. Select "Run"
4. Select "Export"
5. Select "GeoJSON" and "GPX"
