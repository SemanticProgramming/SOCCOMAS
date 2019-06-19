# SOCCOMAS: A FAIR Web Content Management System based on Semantic Programming using the Semantic Programming Ontology
(version 0.2 beta)

SOCCOMAS (**S**emantic **O**ntology-**C**ontrolled application for web **CO**ntent **MA**ngement **S**ystems) is a semantic web content management system (S-WCMS) that utilizes the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO) and a Java Interpreter (https://github.com/SemanticProgramming/Interpreter) as well as an Interface (https://github.com/SemanticProgramming/Interface). SOCCOMAS is controlled by a source code ontology (SC-Basic), which contains descriptions of features and workflows typically required by an S-WCMS, such as user administration with login and signup forms, user registration and login process, session management and user profiles, but also publication life-cycle processes for data entries (i.e. collections of assertional statements referring to a particular entity of a specific kind, like for instance a specimen) and automatic procedures for tracking user contributions, provenance and logging change-history for each editing step of any given version of a data entry. All data and metadata are recorded in RDF following established (meta)data standards using terms and their corresponding URIs from existing ontologies. The Java Interpreter interprets and dynamically executes the descriptions in SC-Basic by interpreting them as declarative specifications (see Fig. 1). Each S-WCMS based on SOCCOMAS stores data and metadata in a FAIR way as a knowledge graph in a Jena tuplestore framework. 


![alt text](https://github.com/SemanticProgramming/SOCCOMAS/blob/master/images/SOCCOMAS_Workflow.jpg)
Figure 1. OVERALL WORKFLOW OF SOCCOMAS. Left: Jena tuple store framework containing the data of the Semantic Web Content Management System (S-WCMS) run by SOCCOMAS as well as a set of ontologies. The ontologies comprise (i) the Semantic Programming Ontology (SPrO), which defines the commands, subcommands and variables used for describing an S-WCMS, (ii) the SOCCOMAS source code ontology (SC-Basic), which contains the descriptions of general workflows and features that can be used by any S-WCMS, and (iii) a source code ontology (INST-SCO) for a particular S-WCMS, which has been individually customized to contain the descriptions of all features that are special to this particular SWCMS. The data of the S-WCMS are stored in form of instance-based semantic graphs. Middle: The Java-based middleware with associated MongoDB reads the descriptions contained in SC-Basic
and INST-SCO and interprets them as the specification of this particular S-WCMS. Right: The frontend, based on the JavaScript framework AngularJS, with HTML and CSS output for browser requests and access to a SPARQL endpoint for service requests.

The following data schemes, database processes, and entry form and graphical user interface (GUI) specifications have been developed for SOCCOMAS and fully described in the SOCCOMAS source code ontology as well as documented through vue files:
Markup : * data schemes:
              * general data architecture of named graphs and directories and their relations;
              * data entry life cycle model;
              * versions and provenance management model;
              * change-log model for modelling every editing step a user conducts for a specific version of a document;Nested bullet
          * database processes:
              * user sessions management;
              * tracking of user contributions;
              * tracking change-log;
              * tracking provenance;
              * status transitions associated with the data entry life cycle (e.g., save, publish, start revision, delete, etc.);
          * entry form and GUI specifications:
              * general GUI representation of a data document, with navigation of the document's different versions, and specification of each version's copyright-license (with specification of functionality);
              * log-in and sign-up pages (with specification of functionality);
              * user document with user profile (with specification of functionality);
              * admin page for maintenance (with specification of functionality).




Further information on the project is available at http://escience.biowikifarm.net - feel free to contact us at 
dev@morphdbase.de

This repository contains the SOCCOMAS source code ontology (SC-Basic), which contains the specification of basic functions and processes of an S-WCMS. You need the Java Interpreter (https://github.com/SemanticProgramming/Interpreter) to interprete and execute these specifications, together with the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO) which provides the terms used in SC-Basic and the Interface (https://github.com/SemanticProgramming/Interface).

**Please be aware that this project is ongoing research! This code is for demonstration purposes only. Do not use
 in production environment!**

