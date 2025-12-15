---
title: The CMECS Catalog
layout: default
parent: About_CMECS
nav_order: 3
---
# The CMECS Catalog

The Coastal and Marine Ecological Classification Standard (CMECS) Catalog is the authoritative collection of ecological units (terms + definitions) and unit relationships (the CMECS framework). 

The CMECS Catalog was originally created by [NatureServe](https://www.natureserve.org/products/coastal-and-marine-ecological-classification-standard-cmecs) as a Microsoft Access database, and represents the CMECS units as published in the [FGDC-STD-018-2012 document](https://repository.library.noaa.gov/view/noaa/27552). The contents of this database were exported into tables in Microsoft Excel Worksheets, checked for accuracy against the FGDC-STD-018-2012 document, then encoded in an Extensible Markup Language (XML) Resource Description Framework (RDF) and Web Ontology Language (OWL) file, cmecs.owl, and released as [CMECS v1.0.0](https://github.com/NOAA-OCM/cmecs/releases/tag/v1.0.0). 

The **CMECS Catalog** [cmecs.owl](https://github.com/NOAA-OCM/cmecs/tree/main/src) file the complete representation of the CMECS classification. It contains all units that are or have been members of the CMECS classification throughout its lifecycle, as well as various annotations that provide metadata for each unit that enable Findability, Accessibility, Interoperability, and Reuse (FAIR, https://www.go-fair.org/fair-principles/). The cmecs.owl file is stored and managed in a Git repository; authoritative versions are publicly released via this GitHub site as changes are made. Version releases also include the CMECS Catalog in CSV and XLXS formats. A browsable text output of the CMECS Catalog ecological units and implementation guidance, the [**CMECS Thesaurus**](https://github.com/NOAA-OCM/cmecs/wiki/CMECS-Thesaurus-Quick-Link), is also available in PDF and MD formats. 

See the [Files and Releases](https://github.com/NOAA-OCM/cmecs/wiki/CMECS-Catalog-Files-and-Releases-Links) page of this Wiki for a guide and links to these files.

**_NEW: The most recent version of the CMECS Catalog is available to browse on [EcoPortal](https://ecoportal.lifewatch.eu/ontologies/CMECS)_**
