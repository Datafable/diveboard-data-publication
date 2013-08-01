# Fields to change

Done | OBIS field | DwC field | Old value | New value | Remarks
--- | --- | --- | --- | --- | ---
n | DateLastModified | modified | 2012-12-05 17:29:50 UTC | 2012-12-05T17:29:50Z
n | Institutioncode | institutionCode | DIVEBOARD | Diveboard | `fixed value`
n | RecordURL | references | http://www.diveboard.com/ bruno.lestrade/DPaanH | `?` | Ideally an occurrence URL
n | RecordID | occurrenceID | 20745099 | `idem` | 
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
n | Subgenus | subgenus | | `?` | If provided by EOL
n | Species | specificEpithet | | `?` | If provided by EOL
n | Subspecies | infraspecificEpithet | | `?` | If provided by EOL
n | ScientificNameAuthor | scientificNameAuthorship | | `?` | If provided by EOL
n | IdentifiedBy | identifiedBy | | Bruno Lestrade | Identical to `recordedBy`
n | Collector | recordedBy | Bruno Lestrade - Diveboard | Bruno Lestrade | 
n | YearCollected | eventDate | 2005 | 2005-07-25 | Merge data into `eventDate`
n | MonthCollected | eventDate | 7 | 2005-07-25 | Merge data into `eventDate`
n | DayCollected | eventDate | 25 | 2005-07-25 | Merge data into `eventDate`
