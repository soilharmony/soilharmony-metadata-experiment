# Soilharmony catalogue prototype based on pycsw

Catalogue is currently available at Wageningen University Kubernetes cluster via <https://soilharmony.containers.wur.nl>.

The [pycsw](https://pycsw.org) software is an easy to set up catalogue component 
rich in catalogue standards support (csw, stac, oaipmh). This folder contains the configuration to 
set up an instance of pycsw tailored with the soilharmony skin.

The initial design has been created with chatGPT, and then furter developed by the team.

## Setup

Some layout templates are injected into the standard container. You can most easily replicate that using  docker compose.

``` 
docker compose up
``` 

Visit the site at http://localhost:8000

In production consider using a postgres database, configurable via pycsw-config.yml

## Loading records

Records are loaded onto the catalogue using [pycsw-admin](https://docs.pycsw.org/en/latest/administration.html) tool.

## Issues & contributions

Specific issues related to the skin or metadata content can be reported here, other cases
can better be reported at https://github.com/geopython/pycsw/issues.
