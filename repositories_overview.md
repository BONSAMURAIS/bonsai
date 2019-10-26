# Introduction to BONSAI repositories
This document provides a brief overview of the 26 repositories in BONSAMURAIS and will be updated if more repositories 
are added or current repositories are modified. 

## Repositories for management, guidelines and documentation
1. [.github](https://github.com/BONSAMURAIS/.github) - Community health -  BONSAI Code of Conduct. Links for accessing community support
2. [bonsai](https://github.com/BONSAMURAIS/bonsai) - Management and Documentation for BONSAI . Also hosts the Wiki
3. [enhancements](https://github.com/BONSAMURAIS/enhancements) - BEP formal decision-making system used for software development. Decisions, debates, voting...etc
4. [python-skeleton](https://github.com/BONSAMURAIS/python-skeleton)- Guidelines for developing projects and packages for BONSAI using python.
5. [reproducibility](https://github.com/BONSAMURAIS/reproducibility) - Guidelines to provide transparency and reproducibility of the work products of BONSAI/ Hackathon
6. [infrastructure-private](https://github.com/BONSAMURAIS/infrastructure-private)- Passwords, config and other non public data for BONSAI infrastructure (contains password for access to ODA jena)
7. [hackathon-2019](https://github.com/BONSAMURAIS/hackathon-2019) - Planning and info for BONSAI hackathon
8. [bonsai.uno](https://github.com/BONSAMURAIS/bonsai.uno) - Development of the static webpage for bonsai using python library staticjinja
9. [board](https://github.com/BONSAMURAIS/board) - Private repository for BONSAI board meeting minutes

## Repositories for BONSAI ontology
1. [BONSAI- ontology-RDF-framework](https://github.com/BONSAMURAIS/BONSAI-ontology-RDF-framework) - Discussions on how ontology was developed. Includes examples in .ttl and xml format for what the data should look like. Links to published ontology [ontology.bonsai.uno/core#](ontology.bonsai.uno/core#) as well as URIs to be used for time intervals, activity type...etc. The figure below shows the graphical representation of the BONSAI ontology. All data in BONSAI is transformed to RDF using the concepts defined in the BONSAI ontology. 
2. [ontology](https://github.com/BONSAMURAIS/ontology)- Code to publish the core ontology for BONSAI to the web [ontology.bonsai.uno/core#](ontology.bonsai.uno/core#).

## RDF conversion, data, storage
1. [arborist](https://github.com/BONSAMURAIS/arborist) - Creates .ttl files of the meta data in Exiobase and other data sources based on an ontology. Designed to work with BONSAI ontology. 
2. [rdf](https://github.com/BONSAMURAIS/rdf) - Contains .ttl files of metadata in. e.g. ActivityType, FlowObject... (Insufficient documentation)
3. [importer](https://github.com/BONSAMURAIS/importer)- imports RDF into the triplestore . BONSAI seeder is a cmd line interface utility that parses .ttl files and updates their content to the Jena instance 
4. [triple-store](https://github.com/BONSAMURAIS/triple-store) - Competency queries and information related to the Bonsai RDF triple-store backend: Apache Jena (Multiple issues on development of SPARQL endpoint)

## Correspondence tables
1. [Correspondence-tables](https://github.com/BONSAMURAIS/Correspondence-tables) - Work space for the correspondence tables working group for BONSAI hackathon 2019.
2. [LCIA_Module](https://github.com/BONSAMURAIS/LCIA_Module) - collect and prepare LCIA methods (charactherization factors) to convert in RDF format for entry into the database.

## Exiobase conversion
1. [Exiobase-conversion-software](https://github.com/BONSAMURAIS/Exiobase-conversion-software) - Exiobase conversion to RDF (scripts not updated)
2. [mojo](https://github.com/BONSAMURAIS/mojo) - The system model frame work. Turning the raw data into into a computational structure .

## Web Application
1. [bonsai_api](https://github.com/BONSAMURAIS/bonsai_api) - REST API endpoints to query the BONSAI database using POST and GET methods.

## Graphical scheme
Figure of how (some of) the repositories described here are linked to support data conversion from tabular form to  (editable version [here](https://github.com/BONSAMURAIS/bonsai/blob/master/Bonsai_git_scheme.drawio)).
![](https://github.com/BONSAMURAIS/bonsai/blob/master/Bonsai_git_scheme.png)

## Auxillary repositories
1. [bentso](https://github.com/BONSAMURAIS/bentso) - BONSAI living model for European electricity via ENTSO-E API
2. [beebee](https://github.com/BONSAMURAIS/beebee) - Conversion utility to parse BONSAI resolved database dumps for Brightway2

## Deprecated repositories
1.[bontofrom](https://github.com/BONSAMURAIS/bontofrom)
2.[correspondentia](https://github.com/BONSAMURAIS/correspondentia)
3.[grafter](https://github.com/BONSAMURAIS/grafter)
4.[bonsai_web_api](https://github.com/BONSAMURAIS/bonsai_web_api)

