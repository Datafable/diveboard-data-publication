# Darwin Core mapping

## Root

DwC term | Status | remark 
--- | ---
type | OK
modified | OK
language | suggested | Suggest to drop
rights | OK
rightsHolder | OK
accessRights | -
bibliographicCitation | change: I would drop this field. | keep: no harm done
references | OK
institutionID | -
collectionID | -
datasetID | OK
institutionCode | OK
collectionCode | -
datasetName | change: I propose: `Diveboard - Scuba diving citizen science` | agreed &proposed
ownerInstitutionCode | OK | www.diveboard.com
basisOfRecord | OK
informationWithheld | -
dataGeneralizations | -
dynamicProperties | -

## Occurrence

DwC term | Status | remark
--- | ---
occurrenceID | change: is `diveboard: 7_0_33102` an internal ID? | yes, shoudl be a GUID, OK for me
catalogNumber | 'not ok' | nameAccordingTOID
occurrenceRemarks | -
recordNumber | -
recordedBy | OK
individualID | -
individualCount | -
sex | -
lifeStage | -
reproductiveCondition | -
behavior | -
establishmentMeans | -
occurrenceStatus | -
preparations | -
disposition | -
otherCatalogNumbers | -
previousIdentifications | -
associatedMedia | empty
associatedReferences | -
associatedOccurrences | - 
associatedSequences | -
associatedTaxa | -

## Event

DwC term | Status | remark
--- | --- | ---
eventID | empty
samplingProtocol | -
samplingEffort | -
eventDate | change: format as `modified`, including time | agreed and proposed
eventTime | remove |agreed and proposed
startDayOfYear | -
endDayOfYear | -
year | -
month | - 
day | -
verbatimEventDate | -
habitat | empty
fieldNumber | -
fieldNotes | empty | something for later
eventRemarks | empty | something for later

## Location

DwC term | Status | remark
--- | --- | ---
locationID | suggested | This is not a good term, i would drop it
higherGeographyID | suggested | This is not a good term, i would drop it
higherGeography | -
continent | empty
waterBody | OK
islandGroup | -
island | -
country | OK
countryCode | change: leave `BLANK` empty | shoudl be ok
stateProvince | -
county | -
municipality | remove | not agreed
locality | change: concatenate as `locality, municipality` | I would not do this
verbatimLocality | -
verbatimElevation | -
minimumElevationInMeters | OK
maximumElevationInMeters | OK
verbatimDepth | -
minimumDepthInMeters | OK
maximumDepthInMeters | change: why are number of decimals so varied? | divecomputers?
minimumDistanceAboveSurfaceInMeters | -
maximumDistanceAboveSurfaceInMeters | -
locationAccordingTo | suggested | no
locationRemarks | empty
verbatimCoordinates | -
verbatimLatitude | -
verbatimLongitude | -
verbatimCoordinateSystem | -
verbatimSRS | -
decimalLatitude | OK
decimalLongitude | OK
geodeticDatum | OK
coordinateUncertaintyInMeters | change: add values from `coordinatePrecision` here | was OK
coordinatePrecision | remove | ok
pointRadiusSpatialFit | -
footprintWKT | -
footprintSRS | -
footprintSpatialFit | -
georeferencedBy | -
georeferencedDate | - 
georeferenceProtocol | - 
georeferenceSources | OK
georeferenceVerificationStatus | -
georeferenceRemarks | -

## Identification

DwC term | Status
--- | ---
identificationID | -
identifiedBy | OK
dateIdentified | OK
identificationReferences | -
identificationVerificationStatus | -
identificationRemarks | -
identificationQualifier | -
typeStatus | -

## Geological context

n/a

## Taxon

DwC term | Status | remarks
--- | --- | ---
taxonID | empty
scientificNameID | -
acceptedNameUsageID | - 
parentNameUsageID | -
originalNameUsageID | -
nameAccordingToID | empty | EOL ID | proposed
namePublishedInID | -
taxonConceptID | -
scientificName | OK
acceptedNameUsage | -
parentNameUsage | -
originalNameUsage | -
nameAccordingTo | change: 5 records with blank `scientificName` should be empty here has well.| ??
namePublishedIn | -
namePublishedInYear | -
higherClassification | -
kingdom | OK | EOL
phylum | OK | EOL
class | OK | EOL
order | OK | EOL
family | OK | EOL
genus | OK | EOL
subgenus | - | EOL
specificEpithet | empty | EOL
infraspecificEpithet | empty | EOL
taxonRank | OK | EOL
verbatimTaxonRank | -
scientificNameAuthorship | empty | EOL
vernacularName | empty | EOL
nomenclaturalCode | -
taxonomicStatus | -
nomenclaturalStatus | -
taxonRemarks | -

## Resource relationship

n/a

## Measurement or fact

DwC term | Status
--- | ---
occurrenceID | 
measurementID | 
measurementType | 
measurementValue | 
measurementAccuracy | 
measurementUnit | 
measurementDeterminedDate | 
measurementDeterminedBy | 
measurementMethod | 
measurementRemarks | 