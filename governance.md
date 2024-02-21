# Establishing data governance
Data governance involved the following steps
- Creating Project, a container for enterprise assets and a mechanism for collaboration.
- Creating connection to one or more enterprise data sources.
- Import metadata using the "Metadata Import" process.
- Enrich metadata of enterprise, this includes
  - Data profiling
  - Data quality analysis
  - Business term mapping

## AssetHub task assembly
We will execute the following AssetHub tasks in the below sequence to acheive the first steps in the data governance process.
1) Import Cloud Pak for Data project with connection to data source.
2) Setup "Metadata Import" process.
3) Execute "Metadata Import" process, this brings in metadata about tables in the data source.
4) Setup "Metadata Enrichment" process.
5) Execute "Metadata Enrichment" process, this further enriches the metadata captured about the tables in the data source.

The following animated image provides a quick preview of what you’ll go through to import metadata from an external data source, enrich that data with auto-assigned business terms, view the enriched data, and publish the enriched data to a catalog.

![UI for data governance](https://www.ibm.com/docs/en/SSQNUZ_4.8.x/wsj/getting-started/images/gov-trust-snippet.gif)
