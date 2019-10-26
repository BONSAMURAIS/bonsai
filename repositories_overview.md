# Introduction to BONSAI repositories
This document provides a brief overview of the 26 repositories in BONSAMURAIS and will be updated if more repositories 
are added or current repositories are modified. 

## Graphical scheme
Figure of how (some of) the repositories described below are linked (editable version [here](https://github.com/BONSAMURAIS/bonsai/blob/master/Bonsai_git_scheme_v2.drawio)).
![](https://github.com/BONSAMURAIS/bonsai/blob/master/Bonsai_git_scheme_v2.png)

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
1. [BONSAI- ontology-RDF-framework](https://github.com/BONSAMURAIS/BONSAI-ontology-RDF-framework) - Discussions on how ontology was developed. Includes examples in .ttl and xml format for what the data should look like
   links to published ontology [ontology.bonsai.uno/core#](ontology.bonsai.uno/core#) as well as URIs to be used for time intervals, activity type...etc
2. [ontology](https://github.com/BONSAMURAIS/ontology)- Code to publish the core ontology for BONSAI to the web [ontology.bonsai.uno/core#](ontology.bonsai.uno/core#).

## RDF conversion, data, storage
1. [rdf](https://github.com/BONSAMURAIS/rdf) - Contains .ttl files of concepts defined in the ontology. e.g. ActivityType, FlowObject... (Insufficient documentation)
2. [arborist](https://github.com/BONSAMURAIS/arborist) -  Generate the URIs needed for the BONSAI knowledge graph. Designed to work with core BONSAI ontology. 
3. [importer](https://github.com/BONSAMURAIS/importer)- imports RDF into the triplestore . BONSAI seeder is a cmd line interface utility that parses .ttl files and updates their content to the Jena instance 
4. [triple-store](https://github.com/BONSAMURAIS/triple-store) - Competency queries and information related to the Bonsai RDF triple-store backend: Apache Jena (Multiple issues on development of SPARQL endpoint)

## Correspondence tables
1. [Correspondence-tables](https://github.com/BONSAMURAIS/Correspondence-tables) - Work space for the correspondence tables working group for BONSAI hackathon 2019
2. [LCIA_Module](https://github.com/BONSAMURAIS/LCIA_Module) - collect and prepare LCIA methods (charactherization factors) to convert in RDF format for entry into the database
3. [grafter](https://github.com/BONSAMURAIS/grafter) - transform correspondance tables into in expressions of the form subject–predicate–objec

## Exiobase conversion
1. [Exiobase-conversion-software](https://github.com/BONSAMURAIS/Exiobase-conversion-software) - Exiobase conversion to RDF (scripts not updated)
2. [mojo](https://github.com/BONSAMURAIS/mojo) - The system model frame work. Turning the raw data into into a computational structure .

## Web Application
1. [bonsai_web_api](https://github.com/BONSAMURAIS/bonsai_web_api) - This repository hosts the code, issues and tasks related to the deployment of web-based applications to receive and serve user requests for LCA calculations. [https://app.bonsai.uno](https://app.bonsai.uno)
2. [bonsai_api](https://github.com/BONSAMURAIS/bonsai_api) - REST API to serve LCA results and queries to the BONSAI database. 

## Auxillary repositories
1. [bentso](https://github.com/BONSAMURAIS/bentso) - BONSAI living model for European electricity via ENTSO-E API
2. [beebee](https://github.com/BONSAMURAIS/beebee) - Conversion utility to parse BONSAI resolved database dumps for Brightway2
