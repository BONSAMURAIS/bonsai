# BONSAI

Welcome to the **management and documentation repository** for the Bonsai organisation (named _Bonsamurais_ on GitHub).

This repository hosts **[the Wiki](https://github.com/BONSAMURAIS/bonsai/wiki)** which describes all components of the BONSAI modular software architecture (work-in-progress!). This prominent README document describes how to get started with Bonsai.

If you're a potential Bonsai **developer/contributor**: you're in the right place. There are many ways to contribute. This page will try to effectively direct your energies. Not sure if you want to contribute? [See here!](https://github.com/BONSAMURAIS/bonsai#why-contribute).

For potential Bonsai **user**, open data on BONSAI can be accessed from [the Open Virtuoso triplestore](http://odas.aau.dk/). Accessing data from the triplestore requires [SPARQL](https://www.w3.org/TR/rdf-sparql-query/) know-how. Development of easy to use tools is currently ongoing. Meanwhile some example queries have been developed to help users extract data.

## Overviews and priorities
If you wish to contribute, a starting point could be to look at [the BONSAI repositories overview](https://github.com/BONSAMURAIS/bonsai/blob/master/repositories_overview.md) page.
The figure below explains how (some of) the project repositories described in the BONSAI repositories overview are linked. 
 

![](https://github.com/BONSAMURAIS/bonsai/blob/master/Bonsai_git_scheme.png) 

## What is the current development status?
The Bonsai project is currently undergoing development, since the March 2019 [hackathon](https://github.com/BONSAMURAIS/hackathon-2019). The topics discussed during the hackathon are available on the dedicated [bonsai.groups.io](https://bonsai.groups.io/g/hackathon2019/topics?p=RecentPostDate%2FSticky,,,20,1,0,0) page. BONSAI is currently in alpha stage. Preliminary softwares to convert open datasets on sustainibility assessment using the BONSAI ontology. 
The development status is also visible in the [project board](https://github.com/orgs/BONSAMURAIS/projects/2). This intends to support the prioritisation of tasks. 

## How to communicate with other developers?
BONSAI has a [mailing list](https://bonsai.groups.io/g/main) used for communication to the broader community.
The [Bonsai Slack Workspace](https://bonsai-open.slack.com) is in active usage during planned hackathons and workshops. 

The BONSAI enhancement proposal [BEP0004](https://github.com/BONSAMURAIS/enhancements/blob/bep4-communications/beps/0004-bonsai-communication-strategy.md) describes the knowledge management and internal communication strategy of the organisation.

## What do we mean when we say 'Bonsai'?
The term _Bonsai_ (**b**ig **o**pen **n**etwork **o**f **s**ustainability **a**ssessment **i**nformation) is used within the community for various related concepts. The BONSAI association is a non-profit headquartered in Denmark. The _big open network_ extends well-beyond this organisation, to include the volunteers, digital artefacts, concepts and processes which constitute the full Bonsai project. Core software modules may also be referred to collectively as _Bonsai_, although the boundaries of correct usage here are not yet final or formalised.

## Where is BONSAI described?
High-level descriptions of goals and objective of BONSAI is available at the [Bonsai website](https://bonsamurais.github.io/bonsai.uno/).
This Wiki provides an up-to-date consensus description of the Bonsai project. An overview of the different BONSAI repositories and their content can be found [here](https://github.com/BONSAMURAIS/bonsai/blob/master/repositories_overview.md)
#### Note
###### The tasks and planning on the Wiki supercede the static [work plan](https://bonsai.uno/strategy-work-plan/) hosted on the website.

## Code-of-conduct and decision-making process
Participation is subject to the [BONSAI code of conduct](https://github.com/BONSAMURAIS/.github/blob/master/CODE_OF_CONDUCT.md).

A proposal for using Python-style Bonsai enhancement proposals (BEPs) [has been formulated](https://github.com/BONSAMURAIS/enhancements/blob/master/beps/0002-bonsai-project-community-governance-structure.md) and is [under discussion.](https://bonsai.groups.io/g/main/topic/bep0002_proposal_open_for/30399914?p=,,,20,0,0,0::recentpostdate%2Fsticky,,,20,1,0,30399914). The organisation Chair Chris Mutel has blogged about his thoughts on this topic [here](https://chris.mutel.org/bonsai-governance.html)

## Expected/useful knowledge for contributors
There are many ways to conribute, which require different knowledge and skills, mostly relating to software development. Some general knowledge areas that are useful for all contribution forms are suggested here.

### GitHub
As a distributed collaborative open-source project, we have chosen GitHub for our version control management and project management (decision pending). To contribute source code, you will need to understand the [standard GitHub workflow](https://guides.github.com/introduction/flow/). To help with task management and organisation, familiarity with the usage of [Issues](https://guides.github.com/features/issues/) will help.

### Sustainability Assessments 
The _sai_ in _Bonsai_ stands for _sustainability assessment information_. Most contributors have a background connected to [Lifecycle Assessment](https://en.wikipedia.org/wiki/Life-cycle_assessment) (LCA) and/or [environmentally extended input-output analysis](https://en.wikipedia.org/wiki/Environmentally_extended_input-output_analysis) (EIOA). High-level decision making requires knowledge of this context. However vital low-level contributions do not require this background knowledge.

### Resource Description Framework
The W3C standard [RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework) is used for modelling knowledge and brings numerous benefits (such as allowing to link different data sources consistently). This is related to Linked Data, and the Semantic Web. Understanding RDF will help you to understand what makes Bonsai unique and potentially very powerful. The final two sets of presentation slides of [this Web Fundamentals course](https://rubenverborgh.github.io/WebFundamentals/semantic-web/) are a good starting point and contain links to many other resources. 

Additional background information on open issues at the interface between LCA and Open Data are available [here](https://chris.mutel.org/next-steps.html#id2) and [here](https://lca-net.com/blog/next-step-open-lca-data/).

### Why contribute?
We assume that you recognise the importance of sustainability assessments: to create a world which is more sustainable - society must have a scientifically-grounded understanding of environmental and social impacts of products and processes. But why should you put your efforts into the Bonsai project specifically? 
Sustainability assessment, and life cycle assessment (LCA) in particular, is to a large extent built on cathedrals - large background databases, erected by the efforts of many people over a long period of time, but which are now both expensive and exclusive, and whose gatekeepers limit access to both the data and decisions on its management. [BONSAI](https://bonsai.uno/) believes in another model, a [bazaar](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar) where the entire community can contribute to data generation, validation, and management decisions. We strongly feel that an open database is more transparent and more reproducible, and therefore the only option for the science of life cycle assessment. Such databases are also a prerequisite for LCA studies being used to support democratic decision making.
