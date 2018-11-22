# Hackathon preliminary agenda

This agenda is **preliminary**, feel free to suggest or make changes!

## Before the Hackathon

The key to the hackathon being an effective use of our time is proper preparation. There are some tasks that everyone needs to do, to be ready to start on the first day. Other individual tasks are also listed below - please volunteer yourself for suitable tasks!

I think that we will need two online meetings before the hackathon, one before Christmas and one about one week before the workshop.

### Tasks for everyone

* Schema finalized
* Do basic tutorials using RDFLib
* Background reading TBD
* Review of EXIOBASE data and metadata
* Choose new data source
* Choice of inventory module
* Read basic overview of relevant resources

### Individual tasks

| Task | Responsible |
| --- | --- |
| Design/find basic tutorials using RDFLib | ? |
| Choose background reading | All (individual contributions) |
| Extract or create lists of JSON-LD UUIDs for common data (units, etc.) | ? |
| Map (or borrow existing mappings of) EXIOBASE elementary flows to ecoinvent | ? |
| Pre-calculate example results for EXIOBASE in Brightway | Chris |
| Generate basic overview of existing BONSAI or other relevant outside resources | Chris |

## Monday

### Morning: Basic foundation

- Review of our data schema
- RDF parsing/construction (possibly with outside consultant)
- DB access and querying
- EXIOBASE structure and metadata

### Afternoon: Getting EXIOBASE into database

- Mapping EXIOBASE categories to our standards (industry and product codes, locations, etc.)
- Write parsers for EXIOBASE format to RDF
- Entering data into Jena DB (possible evening or overnight)
- Keep running list of schema or other potential future changes

## Tuesday: Retrieving data from Jena as usable LCI datasets

- Review JSON-LD format
- Write queries to join relevant data to create datasets as JSON-LD
- Test LCA results against existing implementation in Brightway

## Wednesday

### Morning: Addition of new data sources (TBD)

- Map metadata to our standards
- Write parsers to RDF
- Enter data into Jena DB

### Afternoon

Social event

## Thursday

### Group A: Data reconciliation

- Data reconciliation algorithms: Theory and practice (possible link to pre-workshop reading)
- Data reconciliation of new data source and EXIOBASE
- How to store reconciled data: Best practices and implementation in our database

**Goal**: Implementation of a small test algorithm

### Group B: Inventory modules

By inventory modules, we mean a basic model of a process or industrial sector that can be easily updated, manually or (preferably) automatically, as well as applied to multiple world regions.

- Programming standards and common APIs (or meta-APIs)
- Best practices for testing and documentation
- Implementation of a pre-selected inventory module in Python

**Goal**: Implementation of a small test model

### Late afternoon

- Sharing approaches, challenges, and potential solutions between groups

## Friday

### First part

- Both groups document and publish their work

### Second part

- Each group reviews and tests out the work of the other group

### Third part

- Finishing up any outstanding tasks
- Organization of workshop report paper
- Planning for & assignment of next steps
