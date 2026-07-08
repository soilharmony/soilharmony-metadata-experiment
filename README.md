# Soilharmony Metadata Experiment

A repository to test a number of technologies for metadata capture to facilitate data harmonisation and transfer functions.

In order to facilitate the usage of transfer functions, it is important to understand the nature of the source data, the augmented data and the transfer funtions itself. 
For each (augmented) observation result, we need carefull registration of the observed soil property, the unit of measure, the sample preparation, observation procedure and any applied transfer functions.
A number of standardised approaches are available to capture this information.
This repository collects those approaches and tests them on a number of indicators:

- Accuracy & completeness
- Reproducability
- Ease of use

Identified approaches:

- [RO-Crate - ISA profile](https://github.com/nfdi4plants/isa-ro-crate-profile); a [ISA](https://isa-tools.org/index.html) based profile on [RO-Crate](https://www.researchobject.org/ro-crate/)
- [Observations Measurements & Samples](https://www.ogc.org/standards/om/) is a convention for standardising (soil) observation data adopted in [ISO28258:2013](https://www.iso.org/standard/44595.html) and [INSPIRE](https://inspire-mif.github.io/technical-guidelines/data/so/dataspecification_so.pdf)
- [Frictionless Data - Table Schema](https://specs.frictionlessdata.io/table-schema/) is a basic mechanism to capture metadata about the schema of tabular data
- [Schema.org - variableMeasured](https://schema.org/variableMeasured) is a mechanism in the semantic web/search engine domain to annotate datasets with measurement details

---

The project [Towards a harmonised pan-European monitoring of soil health descriptors](https://doi.org/10.3030/101296615), also known as `SOILHARMONY`, receives funding from the European Union’s HORIZON Innovation Actions 2022 under grant agreement No. 101296615.
