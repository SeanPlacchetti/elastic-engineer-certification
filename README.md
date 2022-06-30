# Elastic Engineer Certification Study Notes
(based on the breakdown here: https://www.elastic.co/training/elastic-certified-engineer-exam)
Elastic Certified Engineer is based on 7.13 as of June 29, 2022 according to https://www.elastic.co/training/certification/faq
Here is a link to the documentation for that version: https://www.elastic.co/guide/en/elasticsearch/reference/7.13/index.html

## Data Management

- Define an index that satisfies a given set of requirements
  - [Index Modules](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/index-modules.html)
- Use the Data Visualizer to upload a text file into Elasticsearch
  - [Upload Data Kibana](https://www.elastic.co/guide/en/kibana/7.13/connect-to-elasticsearch.html#upload-data-kibana)
- Define and use an index template for a given pattern that satisfies a given set of requirements
  - [Index Templates](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/index-templates.html)
- Define and use a dynamic template that satisfies a given set of requirements
  - [Dynamic Templates](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/dynamic-templates.html)
- Define an Index Lifecycle Management policy for a time-series index
  - [Index Lifecycle Management](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/index-lifecycle-management.html)
- Define an index template that creates a new data stream
  - [Data Stream Index Template Step](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/set-up-a-data-stream.html#create-index-template)

## Searching Data

- Write and execute a search query for terms and/or phrases in one or more fields of an index
  - [Search Your Data](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/search-your-data.html)
- Write and execute a search query that is a Boolean combination of multiple queries and filters
  - [Boolean Compound Query](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/query-dsl-bool-query.html)
- Write an asynchronous search
  - [Async Search](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/async-search.html)
- Write and execute metric and bucket aggregations
  - [Metric Aggregations](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/search-aggregations-metrics.html)
  - [Bucket Aggregations](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/search-aggregations-bucket.html)
- Write and execute aggregations that contain sub-aggregations
  - [Pipeline Aggregations](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/search-aggregations-pipeline.html)
- Write and execute a query that searches across multiple clusters
  - [Cross-cluster Search](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/modules-cross-cluster-search.html)
- Write and execute a search that utilizes a runtime field
  - [Runtime Search Request](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/runtime-search-request.html)

## Developing Search Applications

- Highlight the search terms in the response of a query
  - [Highlighting](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/highlighting.html)
- Sort the results of a query by a given set of requirements
  - [Sort Search Results](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/sort-search-results.html)
- Implement pagination of the results of a search query
  - [Paginate Search Results](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/paginate-search-results.html)
- Define and use index aliases
  - [Add Index Alias](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/indices-add-alias.html)
- Define and use a search template
  - [Search Templates](https://www.elastic.co/guide/en/elasticsearch/reference/7.13/search-template.html)

## Data Processing

- Define a mapping that satisfies a given set of requirements
  - 
- Define and use a custom analyzer that satisfies a given set of requirements
  - 
- Define and use multi-fields with different data types and/or analyzers
  - 
- Use the Reindex API and Update By Query API to reindex and/or update documents
  - 
- Define and use an ingest pipeline that satisfies a given set of requirements, including the use of Painless to modify documents
  - 
- Configure an index so that it properly maintains the relationships of nested arrays of objects
  - 

## Cluster Management

- Diagnose shard issues and repair a cluster's health
  - 
- Backup and restore a cluster and/or specific indices
  - 
- Configure a snapshot to be searchable
  - 
- Configure a cluster for cross-cluster search
  - 
- Implement cross-cluster replication
  - 
- Define role-based access control using Elasticsearch Security
  - 
