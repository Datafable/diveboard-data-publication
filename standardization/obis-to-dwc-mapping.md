# OBIS to Darwin Core mapping

OBIS term (obsolete) | DwC term | example value | status | remarks | example value DwC
--- | --- | --- | --- | --- | ---
CollectorNumber | recordNumber | - | n/a
Field Number | fieldNumber | - | n/a
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
