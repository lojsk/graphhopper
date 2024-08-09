### Merge multiple .osm.pbf
```
// convert smallerst to osm (only one file can be osm.pbf)
$HOME/osmconvert slovenia-latest.osm.pbf -o=slovenia-latest.osm

// merget it to all.osm.pbf
$HOME/osmconvert slovenia-latest.osm alps-latest.osm.pbf -o=all.osm.pbf
 
```
