# OBIS to Darwin Core mapping

OBIS term (obsolete) | DwC term | example value | status | remarks | example value DwC
--- | --- | --- | --- | --- | ---
DateLastModified | modified | 2012-12-05 17:29:50 UTC | keep
Institutioncode | institutionCode | ~~DIVEBOARD~~ | keep |**fixed term** | Diveboard
CollectionCode | collectionCode | - | n/a | no specimens collected
CatalogNumber | catalogNumber | - | n/a | no specimens collected
RecordURL | references | <http://www.diveboard.com/bruno.lestrade/DPaanH> | keep | is divelog url, gives extra info
RecordID | occurrenceID | 20745099 | keep |
ScientificName | scientificName | Pterois | keep| 
BasisOfRecord | basisOfRecord | ~~o~~ | keep | **fixed term** | HumanObservation
Source | | WORMS | n/a | 
Citation | bibliographicCitation | Bruno Lestrade 2005-07-25 through Diveboard : http://www.diveboard.com |  | **discussion** 
Kingdom | kingdom | - | if available | **source EOL**
Phylum | phylum | - | if available | **source EOL**
Class | class | - | if available | **source EOL**
Order | order | - | if available | **source EOL**
Family | family | - | if available | **source EOL**
Genus | genus | - | if available | **source EOL**
Subgenus | subgenus | - | if available | **source EOL** 
Species | specificEpithet | - | keep | **source EOL**
Subspecies | infraspecificEpithet | - | if available | **source EOL**
ScientificNameAuthor | scientificNameAuthorship | - | if available | **source EOL**
IdentifiedBy | identifiedBy | - | use | = `recordedBy` | Bruno Lestrade
YearIdentified | dateIdentified | - | use | = `eventdate` | 2005-07-25
MonthIdentified | dateIdentified | - | move
DayIdentified | dateIdentified | - | move
TypeStatus | typeStatus | - | n/a
CollectorNumber | recordNumber | - | n/a
Field Number | fieldNumber | - | n/a
Collector | recordedBy | ~~Bruno Lestrade - Diveboard~~ | keep | | Bruno Lestrade
StartYearCollected | - | - | unnecessary
StartMonthCollected | - | - | unnecessary
StartDayCollected | - | - | unnecessary
EndYearCollected | - | - | unnecessary
EndMonthCollected | - | - | unnecessary
EndDayCollected | - | - | unnecessary
YearCollected | eventDate | ~~2005~~  | keep | | 2005-07-25
MonthCollected | eventDate | 7 | move
DayCollected | eventDate | 25 | move
JulianDay | - | - | unnecessary
StartJulianDay | startDateOfYear | - | unnecessary 
EndJulianDay | endDateOfYear | - | unnecessary
TimeOfDay | eventTime | - | unnecessary
StartTimeOfDay | - | 0 | unnecessary
EndTimeOfDay | - | 29/60 | unnecessary
TimeZone | - | | unnecessary
ContinentOcean | waterBody | #<Region:0x00000006498760> | keep |should be human readable |Pacific Ocean
Country | country | Egypt | keep
StateProvince | stateProvince | ~~StateProvince~~ | unnecessary
County | county | ~~County~~ | unnecessary
Locality | locality | #<Location:0x000000068d9c98> | keep | name divespot | Elphinstone reef
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
Sex | sex | - | n/a | discussion/you want divers to record the sex of a fish? (if campaigns are organised)
LifeStage | lifeStage | - | keep | discussion/you want divers to record the lifestage (if campaigns are organised)
PreparationType | preparations | - | n/a
IndividualCount | individualCount | - | unnecessary | discussion/you want divers to count the number of fish? (only if campaigns)
ObservedIndividualCount | - | - | unnecessary
ObservedWeight | - | - | n/a 
PreviousCatalogNumber | - | - | n/a
RelationshipType | - | - | n/a
RelatedCatalogItem | - | - | n/a
Notes | occurrenceRemarks | - | keep
