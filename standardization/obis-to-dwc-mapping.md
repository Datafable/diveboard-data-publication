# OBIS to Darwin Core mapping

OBIS term (obsolete) | DwC term | example value | status | remarks |
--- | --- | --- | --- | --- |
DateLastModified | modified | 2012-12-05 17:29:50 UTC | keep
Institutioncode | institutionCode | ~~DIVEBOARD~~ Diveboard | keep |**fixed term**
CollectionCode | collectionCode | - | n/a | no specimens collected
CatalogNumber | catalogNumber | - | n/a | no specimens collected
RecordURL | references | <http://www.diveboard.com/bruno.lestrade/DPaanH> | keep | is divelog url,gives extra info
RecordID | occurrenceID | 20745099 | keep
ScientificName | scientificName | Pterois | keep 
BasisOfRecord | basisOfRecord | ~~o~~ HumanObservation | keep | **fixed term**
Source | | WORMS | deprecate | 
Citation | bibliographicCitation | Bruno Lestrade 2005-07-25 through Diveboard : http://www.diveboard.com |  | **discussion** 
Kingdom | kingdom | - | if available | **source EOL**
Phylum | phylum | - | if available | **source EOL**
Class | class | - | if available | **source EOL**
Order | order | - | if available | **source EOL**
Family | family | - | if available | **source EOL**
Genus | genus | - | if available | **source EOL**
Subgenus | subgenus | - | deprecate | 
Species | specificEpithet | - | keep | **source EOL**
Subspecies | infraspecificEpithet | - | if available | **source EOL**
ScientificNameAuthor | scientificNameAuthorship | - | if available | **source EOL**
IdentifiedBy | identifiedBy | Bruno Lestrade - Diveboard | move | =collector
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