# CRIC-WS

This repository contains the prototype of the CRIC Ontology made with Protégé.

The ontology maps a subset of the  the Computing Resource Information Catalogue (CRIC) of WLCG.

The Datamodel of CRIC is complex and a direct mapping of the dataset to RDF is not advisable.

A Domain Mapping approach based on Mapping Master was used as a prototype implementation.

## Built with

The ontology has been built with [Protégé 5.5.0](https://github.com/protegeproject/protege) with the [Cellfie plugin](https://github.com/protegeproject/cellfie-plugin).

## Repository structure

This repository contains:
- The OWL ontology: [CRIC-WS.owl](CRIC-WS.owl) 
- pdf report for the project: [WS-CRIC.pdf](WS-CRIC.pdf)
- The transformation rules used to import the data from a spreadsheet export of relational data: [TransformationRules.json](TransformationRules.json);
- A few notebooks used to parse non relational json data: [facility-parser.ipynb](facility-parser.ipynb) and [resource-parser.ipynb](resource-parser.ipynb).

