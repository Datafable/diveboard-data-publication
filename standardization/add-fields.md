# Fields to add

Done | DwC field | New value | Remarks
--- | --- | --- | ---
y | dateIdentified | 2005-07-25 | Similar to `eventDate`, but just date part
n | continent | Europe | 
y | waterBody | North Sea | 
n | locality | Cavall Bernat, Estartit & Medes Islands | Name of divespot, location
n | eventRemarks | Visibility poor | Remarks about the dive
n | fieldNotes | `description of dive trip` | To be discussed: privacy issues
n | locationRemarks | Has ship wreckage since 2009 | Remarks about the dive site
y | type | Event | `fixed value`
n | language | en | `fixed value`
y | rights | http://creativecommons.org/publicdomain/zero/1.0/ | `fixed value`
y | rightsHolder | Diveboard | `fixed value`
y | datasetID | http://ipt.diveboard.com/resource.do?r=diveboard-occurrences | `fixed value`
n | datasetName | `title of published dataset`| To be discussed
n | ownerInstitutionCode | Diveboard | 
n | countryCode | ES | Depends on how country data are stored
n | locationAccordingTo | Wikipedia | Depends on how location data are stored
y | geodeticDatum | EPSG:3857 | `fixed value` if Google Maps only
y | georeferenceSources | Google Maps | `fixed value` if Google Maps only
n | minimumElevationInMeters | 313 | 
n | maximumElevationInMeters | 313 | Identical to `minimumElevationInMeters`
n | taxonID | `?` | If provided by EOL
n | nameAccordingToID | www.marinespecies.org | Identifier for the source, if provided by EOL
n | taxonRank | If provided by EOL
n | vernacularName | If provided by EOL
n | occurrenceID | Diveboard:20745099 | 
n | associatedMedia | `image-url; image-url` | To be discussed: should refer to the occurrence, not event
n | eventID | `?` | Dive trip ID
n | habitat | Coral reef | Controlled vocabulary for the habitat of the dive
