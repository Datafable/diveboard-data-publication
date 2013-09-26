# Fields to delete

Done | OBIS field | DwC field | Old value | Remarks
--- | --- | --- | --- | ---
y | CollectionCode | collectionCode | | Applies to specimens only
y | Subgenus | subgenus | | Not necessary
y | YearIdentified | ~ dateIdentified | | Provided in other field
y | MonthIdentified | ~ dateIdentified | | Provided in other field
y | DayIdentified | ~ dateIdentified | | Provided in other field
y | TypeStatus | typeStatus | | Applies to specimens only
y | CollectorNumber | recordNumber | | If generated ID, better to use `occurrenceID`
y | Field Number | fieldNumber | | If generated ID, better to use `eventID`
y | StartYearCollected | ~ eventDate | | Provided in other field
y | StartMonthCollected | ~ eventDate | | Provided in other field
y | StartDayCollected | ~ eventDate | | Provided in other field
y | EndYearCollected | ~ eventDate | | Provided in other field
y | EndMonthCollected | ~ eventDate | | Provided in other field
y | EndDayCollected | ~ eventDate | | Provided in other field
y | YearCollected | ~ eventDate | 2005 | Provided in other field
y | MonthCollected | ~ eventDate | 7 | Provided in other field
y | DayCollected | ~ eventDate | 25 | Provided in other field
y | JulianDay | - | | Can be derived from `eventDate`
y | StartJulianDay | startDateOfYear | | Can be derived from `eventDate`
y | EndJulianDay | endDateOfYear | | Can be derived from `eventDate`
y | TimeOfDay | eventTime | | Provided in other field
y | StartTimeOfDay | ~ eventTime | 0 | Provided in other field
y | EndTimeOfDay | ~ eventTime | 29/60 | Provided in other field
y | TimeZone | ~ eventTime | | Provided in other field
y | StateProvince | stateProvince | StateProvince | Not really applicable to marine records
y | County | county | County | Not really applicable to marine records
y | StartLongitude | ~ footprintWKT | | Won't support polygons
y | EndLongitude | ~ footprintWKT | | Won't support polygons
y | StartLatitude | ~ footprintWKT | | Won't support polygons
y | EndLatitude | ~ footprintWKT | | Won't support polygons
y | DepthRange | - | DepthRange | Can be derived from `depthInMeters`
y | Sex | sex | | Users cannot add occurrence information
y | LifeStage | lifeStage | | Users cannot add occurrence information
y | PreparationType | preparations | | Applies to specimens only
y | IndividualCount | individualCount | | Users cannot add occurrence information
y | ObservedIndividualCount | ~ individualCount | | Provided in other field
y | PreviousCatalogNumber | - | | Not in DarwinCore
y | RelationshipType | - | | Won't support relations (via `ResourceRelationship` extension)
y | RelatedCatalogItem | - | | Not in DarwinCore
y | Notes | - | | This can be mapped to several fields, see [other file](add-fields.md)
