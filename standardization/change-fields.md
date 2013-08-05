# Fields to change

Done | Diveboard field | DwC field | Old value | New value | Remarks
--- | --- | --- | --- | --- | ---
n | DateLastModified | modified | 2012-12-05 17:29:50 UTC | 2012-12-05T17:29:50Z
n | Institutioncode | institutionCode | DIVEBOARD | Diveboard | `fixed value`
n | RecordURL | references | http://www.diveboard.com/ bruno.lestrade/DPaanH | `?` | Ideally an occurrence URL
n | RecordID | catalogNumber | 20745099 | `idem` | Should be unique
n | ScientificName | scientificName | Carcharhinus melanopterus (Quoy and Gaimard, 1824) | `idem` | From EOL
n | BasisOfRecord | basisOfRecord | o | HumanObservation | `fixed value`
n | Source | nameAccordingTo | WORMS | EOL, WORMS | How does EOL provide this value?
n | Citation | bibliographicCitation | Bruno Lestrade 2005-07-25 through Diveboard : http://www.diveboard.com | `?` | To be discussed
n | Kingdom | kingdom | | `?` | If provided by EOL
n | Phylum | phylum | | `?` | If provided by EOL
n | Class | class | | `?` | If provided by EOL
n | Order | order | | `?` | If provided by EOL
n | Family | family | | `?` | If provided by EOL
n | Genus | genus | | `?` | If provided by EOL
n | Species | specificEpithet | | `?` | If provided by EOL
n | Subspecies | infraspecificEpithet | | `?` | If provided by EOL
n | ScientificNameAuthor | scientificNameAuthorship | | `?` | If provided by EOL
n | IdentifiedBy | identifiedBy | | Bruno Lestrade | Identical to `recordedBy`
n | Collector | recordedBy | Bruno Lestrade - Diveboard | Bruno Lestrade | 
n | YearCollected | eventDate | 2005 | 2005-07-25 | Merge data into `eventDate`
n | MonthCollected | eventDate | 7 | 2005-07-25 | Merge data into `eventDate`
n | DayCollected | eventDate | 25 | 2005-07-25 | Merge data into `eventDate`
n | StartTimeOfDay | eventTime | 0 | 14:03:02Z | Merge data into `eventTime`
n | EndTimeOfDay | eventTime | 29/60 | 14:03:02Z | Merge data into `eventTime` with `/` if duration is provided
n | ContinentOcean | higherGeographyID | #<Region:0x00000006498760> | `idem` | To what does this refer exactly?
n | Country | country | Egypt | `idem` | 
n | Locality | locationID | #<Location:0x000000068d9c98> | `idem` | To what does this refer exactly?
n | Longitude | decimalLongitude | 34.513 | `idem` | Are these numbers rounded?
n | Latitude | decimalLongitude | 28.501 | `idem` | Are these numbers rounded?
n | CoordinatePrecision | coordinateUncertaintyInMeters | 100 | `idem` | Verify these are meters. 100m sees a good estimate for clicking on Google Maps
n | MinimumDepth | minimumDepthInMeters | 0 | `idem` | Verify these are meters
n | MaximumDepth | maximumDepthInMeters | 12.0 | `idem` | Verify these are meters
n | Temperature | - | 28.0 | `idem` | This can be provided in a `MeasurementOrFacts` extension, requires some work (this might be split in surface and bottom temp.)
n | ObservedWeight | - | | 10.2 | Currently not recorded, to be discussed. Can be provided in `MeasurementsOrFacts` extension.
