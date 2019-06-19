# SOCCOMAS: A FAIR Web Content Management System based on Semantic Programming using the Semantic Programming Ontology
(version 0.2 beta)

SOCCOMAS (**S**emantic **O**ntology-**C**ontrolled application for web **CO**ntent **MA**ngement **S**ystems) is a semantic web content management system (S-WCMS) that utilizes the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO) and a Java Interpreter (https://github.com/SemanticProgramming/Interpreter) as well as an Interface (https://github.com/SemanticProgramming/Interface). SOCCOMAS is controlled by a source code ontology (SC-Basic), which contains descriptions of features and workflows typically required by an S-WCMS, such as user administration with login and signup forms, user registration and login process, session management and user profiles, but also publication life-cycle processes for data entries (i.e. collections of assertional statements referring to a particular entity of a specific kind, like for instance a specimen) and automatic procedures for tracking user contributions, provenance and logging change-history for each editing step of any given version of a data entry. All data and metadata are recorded in RDF following established (meta)data standards using terms and their corresponding URIs from existing ontologies. The Java Interpreter interprets and dynamically executes the descriptions in SC-Basic by interpreting them as declarative specifications. Each S-WCMS based on SOCCOMAS stores data and metadata in a FAIR way as a knowledge graph in a Jena tuplestore framework. 




Further information on the project is available at http://escience.biowikifarm.net - feel free to contact us at 
dev@morphdbase.de

This repository contains the SOCCOMAS source code ontology (SC-Basic), which contains the specification of basic functions and processes of an S-WCMS. You need the Java Interpreter (https://github.com/SemanticProgramming/Interpreter) to interprete and execute these specifications, together with the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO) which provides the terms used in SC-Basic and the Interface (https://github.com/SemanticProgramming/Interface).

**Please be aware that this project is ongoing research! This code is for demonstration purposes only. Do not use
 in production environment!**

