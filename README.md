# SoilHarmony Metadata Experiment

A repository to test a number of technologies for metadata capture to facilitate data harmonization and transfer functions.

In order to facilitate the usage of transfer functions, it is important to understand the nature of the source data, the augmented data and the transfer functions itself. 
For each (augmented) observation result, we need careful registration of the observed soil property, the unit of measure, the sample preparation, observation procedure and any applied transfer functions.
A number of standardized approaches are available to capture this information.

This repository collects those approaches and tests them on a number of indicators:

- Accuracy & completeness
- Reproducibility
- Ease of use

## Catalogue interface

As part of the experiment a catalogue interface is made available, to test user experiences.
The pycsw based catalogue is currently made available via <https://soilharmony.containers.wur.nl/>. 

## Identified metadata approaches

- [RO-Crate - ISA profile](https://github.com/nfdi4plants/isa-ro-crate-profile); a [ISA](https://isa-tools.org/index.html) based profile on [RO-Crate](https://www.researchobject.org/ro-crate/)
- [Observations Measurements & Samples](https://www.ogc.org/standards/om/) is a convention for standardizing (soil) observation data adopted in [ISO28258:2013](https://www.iso.org/standard/44595.html) and [INSPIRE](https://inspire-mif.github.io/technical-guidelines/data/so/dataspecification_so.pdf)
- [Frictionless Data - Table Schema](https://specs.frictionlessdata.io/table-schema/) is a basic mechanism to capture metadata about the schema of tabular data
- [Schema.org - variableMeasured](https://schema.org/variableMeasured) is a mechanism in the semantic web/search engine domain to annotate datasets with measurement details

This work builds on work of the [SoilWise project](https://doi.org/10.3030/101112838) in their [soil observation data encodings repository](https://github.com/soilwise-he/soil-observation-data-encodings).

## Issues and contributions

We welcome you to contribute to this effort, by trying out the approaches on your data, suggest alternative solutions, etc. by submitting an issue in the issue tracker.

---

The project [Towards a harmonised pan-European monitoring of soil health descriptors](https://doi.org/10.3030/101296615), also known as `SOILHARMONY`, receives funding from the European Union’s HORIZON Innovation Actions 2022 under grant agreement No. 101296615.
