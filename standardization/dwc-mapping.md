# Darwin Core mapping

## Root

DwC term | Status
--- | ---
type | OK
modified | OK
language | empty
rights | OK
rightsHolder | OK
accessRights | -
bibliographicCitation | change: I would drop this field. 
references | OK
institutionID | -
collectionID | -
datasetID | OK
institutionCode | OK
collectionCode | -
ownerInstitutionCode | suggested
datasetName | OK
basisOfRecord | OK
informationWithheld | -
dataGeneralizations | -
dynamicProperties | -

## Occurrence

DwC term | Status
--- | ---
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

DwC term | Status
--- | ---
eventID | empty
samplingProtocol | -
samplingEffort | -
eventDate | change: format as `modified`, including time
eventTime | -
startDayOfYear | -
endDayOfYear | -
year | -
month | - 
day | -
verbatimEventDate | -
habitat | empty
fieldNumber | -
fieldNotes | empty
eventRemarks | empty

## Location

DwC term | Status
--- | ---
locationID | suggested
higherGeographyID | suggested
higherGeography | -
continent | empty
waterBody | OK
islandGroup | -
island | -
country | OK
countryCode | change: leave `BLANK` empty
stateProvince | -
county | -
municipality | remove
locality | change: concatenate as `locality, municipality`
verbatimLocality | -
verbatimElevation | -
minimumElevationInMeters | OK
maximumElevationInMeters | OK
verbatimDepth | -
minimumDepthInMeters | OK
maximumDepthInMeters | OK
minimumDistanceAboveSurfaceInMeters | -
maximumDistanceAboveSurfaceInMeters | -
locationAccordingTo | suggested
locationRemarks | empty
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

DwC term | Status
--- | ---
taxonID | empty
scientificNameID | -
acceptedNameUsageID | - 
parentNameUsageID | -
originalNameUsageID | -
nameAccordingToID | empty
namePublishedInID | -
taxonConceptID | -
scientificName | OK
acceptedNameUsage | -
parentNameUsage | -
originalNameUsage | -
nameAccordingTo | change: 5 records with blank `scientificName` should be empty here has well.
namePublishedIn | -
namePublishedInYear | -
higherClassification | -
kingdom | empty
phylum | empty
class | empty
order | empty
family | empty
genus | empty
subgenus | -
specificEpithet | empty
infraspecificEpithet | empty
taxonRank | empty
verbatimTaxonRank | -
scientificNameAuthorship | empty
vernacularName | empty
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
