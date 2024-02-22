# Goal
To quickly setup and show the outcome/possibilities around Data Governance with our Data & AI platform. One would benefit from using the very intiutive User Interface we have that serves the different personas using the platform.

# Establishing data governance
Data Governance is a much talked about topic in every enterprise, yet there is some level of confusion of what governance means and more importantly where/how to get started. Data governance involves the following steps
- Creating Project, a container for enterprise assets and a mechanism for collaboration.
- Creating connection to one or more enterprise data sources.
- Importing metadata using the "Metadata Import" process.
- Enrich metadata of enterprise, this includes
  - Data profiling
  - Data quality analysis
  - Business term mapping

## AssetHub task assembly
We will execute the following AssetHub tasks in the below sequence to acheive the first steps in the data governance process.
1) Import Cloud Pak for Data project with connection to data source.
2) Setup "Metadata Import" and execute "Metadata Import" process, this brings in metadata about tables in the data source.
4) Setup "Metadata Enrichment" and execute "Metadata Enrichment" process, this further enriches the metadata captured about the tables in the data source.

## What you need to execute this use case
One would need the following input parameter values to execute the use case
1) Github repository with a shell project, this contains only a connection to the data source no other assets.
2) Github token for my repository.
3) Cloud Pak for Data 4.8 URL
4) Cloud Pak for Data 4.8 User name
5) Cloud Pak for Data 4.8 Password

### Actual execution of the Data Governance Use Case
The use case can be invoked from the "Use Case" tab in AssetHub.
<img width="1721" alt="DataGovernaneUseCaseExecution" src="https://github.com/drangar/usecases/assets/16958324/fad6bf9f-b747-46d6-8bbb-06577b7c7afb">

### Total elapsed time = 4 mins !

[![Download and Watch the video]](https://ibm.box.com/shared/static/cawvciqh5bfqr7eqykynu8vl1yyzuut4.mp4)([https://youtu.be/vt5fpE0bzSY](https://ibm.box.com/shared/static/cawvciqh5bfqr7eqykynu8vl1yyzuut4.mp4))

The following animated image provides a quick preview of what you’ll go through to import metadata from an external data source, enrich that data with auto-assigned business terms, view the enriched data, and publish the enriched data to a catalog.

![UI for data governance](https://www.ibm.com/docs/en/SSQNUZ_4.8.x/wsj/getting-started/images/gov-trust-snippet.gif)
