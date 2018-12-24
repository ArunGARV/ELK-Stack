# Business Intelligence using ELK stack

ELK, which stands for (E)lasticsearch, (L)ogstash, (K)ibana is an open source technology stack that was not necessarily designed for this type of real time analytics use case. Elasticsearch forms the platform for indexing data, in the form of JSON documents. Logstash serves as the data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favourite stash.(In this case, its naturally Elasticsearch). Kibana is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Put it all together, and you have a way to import all of your data sources into a single searchable place.
Follow the documentation at "https://medium.com/@arun_37023/creating-dashboards-with-real-time-interactive-visualisation-using-elk-stack-63f7e3607ca2"

