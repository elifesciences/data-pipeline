# eLife Data Pipeline
A consolidated data platform for eLife data sources (Libero, xPub, eJP etc.)

Uses a Python scripts to transform data from XML, JSON, Postgres and HTTP requests into read-optimised data stores in Google BigQuery. Orchestration is handled by Apache NiFi and data transformation can involed a Postgres intermediate data store.

This project is current in early development with the current priority shown with a solid border, and future priorities with a dashed border, in this high level overview below:

![alt text](./Data%20Consolidation%20Pipeline%20Overview.svg "Data Pipeline High Level Overview")
