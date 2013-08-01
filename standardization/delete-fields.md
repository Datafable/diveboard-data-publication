# Fields to delete

Done | OBIS field | DwC field | Old value | Remarks
--- | --- | --- | --- | ---
n | CollectionCode | collectionCode | | Applies to specimens only
n | CatalogNumber | catalogNumber | | Applies to specimens only
n | YearIdentified | ~ dateIdentified | | Provided in other field
n | MonthIdentified | ~ dateIdentified | | Provided in other field
n | DayIdentified | ~ dateIdentified | | Provided in other field
n | TypeStatus | typeStatus | | Applies to specimens only
n | StartYearCollected | ~ eventDate | | Provided in other field
n | StartMonthCollected | ~ eventDate | | Provided in other field
n | StartDayCollected | ~ eventDate | | Provided in other field
n | EndYearCollected | ~ eventDate | | Provided in other field
n | EndMonthCollected | ~ eventDate | | Provided in other field
n | EndDayCollected | ~ eventDate | | Provided in other field
n | YearCollected | ~ eventDate | 2005 | Provided in other field
n | MonthCollected | ~ eventDate | 7 | Provided in other field
n | DayCollected | ~ eventDate | 25 | Provided in other field
n | JulianDay | - | | Can be derived from `eventDate`
n | StartJulianDay | startDateOfYear | | Can be derived from `eventDate`
n | EndJulianDay | endDateOfYear | | Can be derived from `eventDate`
