# Standardization of Diveboard data to DwC-A

## Introduction

Diveboard data are currently provided in the [OBIS schema](http://www.iobis.org/node/304). The [Darwin Core standard](http://rs.tdwg.org/dwc/terms/index.htm) however is a more uniformal and widely adopted way to share biodiversity data. It also also allows to share the data as a standardized data package: the [Darwin Core archive](http://www.gbif.org/informatics/standards-and-tools/publishing-data/data-standards/darwin-core-archives/).

In this directory, we provide instructions how to reformat the Diveboard data from its current OBIS view to Darwin Core.

## Changes to be made

* [Add fields](add-fields.md): Fields that are currently not provided, but which are preferably added. Many are fixed terms (= same value for all fields).
* [Change fields](change-fields.md): Fields that are currently provided, but which require a new header or some slight changes.
* [Delete fields](delete-fields.md): Fields that are currently provided, but which should be deleted, as these are empty or superfluous.

### Overview of DwC fields

* [DwC mapping](dwc-mapping.md): An overview of all Darwin Core terms and their relevance to the Diveboard data.
