# OBIS to Darwin Core mapping

OBIS term (obsolete) | DwC term | example value | status
--- | --- | --- | ---
DateLastModified | modified | 2012-12-05 17:29:50 UTC | keep
Institutioncode | institutionCode | ~~DIVEBOARD~~ Diveboard | keep
CollectionCode | collectionCode | - | n/a
CatalogNumber | catalogNumber | - | 
RecordURL | references | <http://www.diveboard.com/bruno.lestrade/DPaanH> | keep, if occurrence url
RecordID | occurrenceID | 20745099 | keep
ScientificName | scientificName | Pterois | keep 
BasisOfRecord | basisOfRecord | ~~o~~ HumanObservation | keep 
Source | | WORMS | 
Citation | bibliographicCitation | Bruno Lestrade 2005-07-25 through Diveboard : http://www.diveboard.com | 
Kingdom | kingdom | - | keep
Phylum | phylum | - | 
Class | class | - | 
Order | order | - | 
Family | family | - | 
Genus | genus | - | keep
Subgenus | subgenus | - | unnecessary?
Species | specificEpithet | - | keep
Subspecies | infraspecificEpithet | - | keep
ScientificNameAuthor | scientificNameAuthorship | - | keep
IdentifiedBy | identifiedBy | - | 
YearIdentified | dateIdentified | - | 
MonthIdentified | dateIdentified | - | 
DayIdentified | dateIdentified | - | 
TypeStatus | typeStatus | - | n/a
CollectorNumber | recordNumber | - | unnecessary?
Field Number | fieldNumber | - | unnecessary?
Collector | recordedBy | Bruno Lestrade ~~- Diveboard~~ | keep
StartYearCollected | - | - | n/a
StartMonthCollected | - | - | n/a
StartDayCollected | - | - | n/a
EndYearCollected | - | - | n/a
EndMonthCollected | - | - | n/a
EndDayCollected | - | - | n/a
YearCollected | eventDate | ~~2005~~ 2005-07-25 | keep
MonthCollected | eventDate | 7 | move
DayCollected | eventDate | 25 | move
JulianDay | - | - | unnecessary
StartJulianDay | startDateOfYear | - | unnecessary 
EndJulianDay | endDateOfYear | - | unnecessary
TimeOfDay | eventTime | - | 
StartTimeOfDay | - | 0 | 
EndTimeOfDay | - | 29/60 | 
TimeZone | - | | 
ContinentOcean | continent | #<Region:0x00000006498760> | keep, or use `waterBody`
Country | country | Egypt | keep
StateProvince | stateProvince | ~~StateProvince~~ | unnecessary?
County | county | ~~County~~ | unnecessary
Locality | locality | #<Location:0x000000068d9c98> | keep
Longitude | decimalLongitude | 34.513 | keep
StartLongitude | - | - | unnecessary
EndLongitude | - | - | unnecessary
Latitude | decimalLongitude | 28.501 | keep
StartLatitude | - | - | unnecessary
EndLatitude | - | - | unnecessary
CoordinatePrecision | coordinateUncertaintyInMeters | 100 | keep
MinimumDepth | minimumDepthInMeters | 0 | keep
MaximumDepth | maximumDepthInMeters | 12.0 | keep
DepthRange | - | ~~DepthRange~~ | unnecessary
Temperature | - | 28.0 | 
Sex | sex | - | keep
LifeStage | lifeStage | - | keep
PreparationType | preparations | - | n/a
IndividualCount | individualCount | - | keep
ObservedIndividualCount | - | - | unnecessary
ObservedWeight | - | - | 
PreviousCatalogNumber | - | - | n/a
RelationshipType | - | - | n/a
RelatedCatalogItem | - | - | n/a?
Notes | occurrenceRemarks | - | keep?
