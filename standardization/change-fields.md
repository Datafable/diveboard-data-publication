# Fields to change

Done | Diveboard field | DwC field | Old value | New value | Remarks
--- | --- | --- | --- | --- | ---
y | DateLastModified | modified | 2012-12-05 17:29:50 UTC | 2012-12-05T17:29:50Z
y | Institutioncode | institutionCode | DIVEBOARD | Diveboard | `fixed value`
y | RecordURL | references | http://www.diveboard.com/ bruno.lestrade/DPaanH | `idem` | Ideally an occurrence URL
y | RecordID | catalogNumber | 20745099 | `idem` | Should be unique
y | ScientificName | scientificName | Carcharhinus melanopterus (Quoy and Gaimard, 1824) | `idem` | From EOL
y | BasisOfRecord | basisOfRecord | o | HumanObservation | `fixed value`
y | Source | nameAccordingTo | WORMS | EOL, WORMS | How does EOL provide this value?
y | Kingdom | kingdom | | `?` | If provided by EOL
y | Phylum | phylum | | `?` | If provided by EOL
y | Class | class | | `?` | If provided by EOL
y | Order | order | | `?` | If provided by EOL
y | Family | family | | `?` | If provided by EOL
y | Genus | genus | | `?` | If provided by EOL
y | IdentifiedBy | identifiedBy | | Bruno Lestrade | Identical to `recordedBy`
y | Collector | recordedBy | Bruno Lestrade - Diveboard | Bruno Lestrade | 
y | YearCollected | eventDate | 2005 | 2005-07-25 | Merge data into `eventDate`
y | MonthCollected | eventDate | 7 | 2005-07-25 | Merge data into `eventDate`
y | DayCollected | eventDate | 25 | 2005-07-25 | Merge data into `eventDate`
y | StartTimeOfDay | eventTime | 0 | 14:03:02Z | Merge data into `eventTime`
y | EndTimeOfDay | eventTime | 29/60 | 14:03:02Z | Merge data into `eventTime` with `/` if duration is provided
y | Country | country | Egypt | `idem` | 
y | Longitude | decimalLongitude | 34.513 | `idem` |
y | Latitude | decimalLongitude | 28.501 | `idem` |
y | CoordinatePrecision | coordinateUncertaintyInMeters | 100 | `idem` |
y | MinimumDepth | minimumDepthInMeters | 0 | `idem` | `fixed value`
y | MaximumDepth | maximumDepthInMeters | 12.0 | `idem` |
