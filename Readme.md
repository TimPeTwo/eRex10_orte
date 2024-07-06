Eine Karte fuer eTrex10
Städtename, Ortsnamen und Stadteile

Benötigte Software
* mkmap
* zip

Benötigte Daten
export-osm von https://overpass-turbo.eu/
''''
node
   [place~"(city|town|village|suburb|hamlet)"]   ({{bbox}});
out;
''''

Reihenfolge der Aufrufe
* ./MyZipStyle.sh
* ./MyConvert.sh
* ./MyRename.sh
* 
