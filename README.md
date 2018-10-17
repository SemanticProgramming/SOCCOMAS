# SOCCOMAS: A Web Content Management System based on Semantic Programming using the Semantic Programming Ontology
(version 0.2 beta)

SOCCOMAS (**S**emantic **O**ntology-**C**ontrolled application for web **CO**ntent **MA**ngement **S**ystems) is a semantic web content management system (S-WCMS) that utilizes the Semantic Programming Ontology (SPrO) and its associated Java-based middleware. SOCCOMAS is controlled by a source code ontology (SC-Basic), which contains descriptions of features and workflows typically required by a S-WCMS, such as user administration with login and signup forms, user registration and login process, session management and user profiles, but also publication life-cycle processes for data entries (i.e. collections of assertional statements referring to a particular entity of a specific kind, like for instance a specimen) and automatic procedures for tracking user contributions, provenance and logging change-history for each editing step of any given version of a data entry. All data and metadata are recorded in RDF following established (meta)data standards using terms and their corresponding URIs from existing ontologies. The middleware functions as a compiler that dynamically executes the descriptions in SC-Basic by interpreting them as declarative specifications. Each S-WCMS based on SOCCOMAS stores data as a knowledge base in a Jena tuplestore. 


Further information on the project is available at http://escience.biowikifarm.net - feel free to contact us at 
dev@morphdbase.de

This repository contains the SOCCOMAS source code ontology (SC-Basic)

**Please be aware that this project is ongoing research! This code is for demonstration purposes only. Do not use
 in production environment!**
  
 **Code will be made available in the next months**
