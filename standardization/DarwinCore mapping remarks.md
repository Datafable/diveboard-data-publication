# Darwin Core mapping

## Root

DwC term | Status | remark 
--- | --- | ---
type | OK
modified | OK
language | suggested | `empty`
rights | OK
rightsHolder | OK
accessRights | -
bibliographicCitation | change: I would drop this field. | `keep`
references | OK
institutionID | -
collectionID | -
datasetID | OK
institutionCode | OK
collectionCode | -
datasetName | OK
ownerInstitutionCode | OK | www.diveboard.com
basisOfRecord | OK
informationWithheld | -
dataGeneralizations | -
dynamicProperties | -

## Occurrence

DwC term | Status | remark
--- | --- | ---
occurrenceID | OK
catalogNumber | OK
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
eventDate | OK
eventTime | OK
startDayOfYear | -
endDayOfYear | -
year | -
month | - 
day | -
verbatimEventDate | -
habitat | empty
fieldNumber | -
fieldNotes | `empty` | something for later
eventRemarks | `empty` | something for later

## Location

DwC term | Status | remark
--- | --- | ---
locationID | -
higherGeographyID | -
higherGeography | -
continent | `empty`
waterBody | OK
islandGroup | -
island | -
country | OK
countryCode | change: leave `BLANK` empty |to check
stateProvince | -
county | -
municipality | `removed` 
locality | change: concatenate as `locality, municipality` | I would not do this
verbatimLocality | OK | `municipality, locality` concatenated
verbatimElevation | -
minimumElevationInMeters | OK
maximumElevationInMeters | OK
verbatimDepth | -
minimumDepthInMeters | OK
maximumDepthInMeters | OK | one digit after the `,`
minimumDistanceAboveSurfaceInMeters | -
maximumDistanceAboveSurfaceInMeters | -
locationAccordingTo | -
locationRemarks | `empty`
verbatimCoordinates | -
verbatimLatitude | -
verbatimLongitude | -
verbatimCoordinateSystem | -
verbatimSRS | -
decimalLatitude | OK
decimalLongitude | OK
geodeticDatum | OK
coordinateUncertaintyInMeters | OK
coordinatePrecision | -
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
nameAccordingTo | change: 5 records with blank `scientificName` should be empty here has well.| to check
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
