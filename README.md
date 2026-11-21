Engineering Document Manager (EDM)

An Offline Engineering Document Management System

1. Project Overview

Engineering Document Manager (EDM) is a document management solution designed to centralize the inventory, identification, classification, organization and retrieval of engineering technical documentation.

The system aims to transform scattered technical documentation into a structured and searchable document repository, improving information accessibility, traceability and document organization within engineering environments.

EDM is designed for local infrastructure deployment, operating without internet access or external cloud services.

2. Problem Statement

Engineering departments often manage large volumes of technical documentation distributed across multiple computers, folders and storage locations.

This fragmentation creates challenges such as:

* Difficulty locating technical documents.
* Lack of centralized document inventories.
* Inconsistent document classification.
* Limited document traceability.
* Time-consuming information retrieval.
* Difficulty identifying relationships between technical documents.

EDM addresses these challenges through a centralized document inventory and classification approach.

3. Project Objectives

* Centralize engineering document inventory.
* Automatically identify and classify technical documents.
* Extract relevant metadata and keywords.
* Organize documentation using structured classification criteria.
* Facilitate document retrieval through searchable metadata.
* Identify relationships between associated technical documents.
* Maintain document traceability and repository references.

4. Core Capabilities

The project is designed around the following functional areas:

Document Inventory

* Repository scanning and document registration.
* Duplicate identification.
* File integrity identification through SHA-256 hashing.

Document Classification

* Document type identification.
* Manufacturer and aircraft model classification.
* Extraction of relevant technical identifiers.
* Unclassified document identification for subsequent review.

Document Search

* Full-text search capabilities.
* Metadata-based document retrieval.
* Centralized document indexing.

Document Traceability

* Repository location references.
* Document relationship identification.
* Structured document records.

5. Technical Architecture

EDM is designed as a local application with a centralized database and document repository.

The architecture separates the application, database and document storage layers.

6. Technology Stack

Category	Technology
Programming Language	Python 3.12
Application Interface	Streamlit
Database	SQLite
Search Engine	SQLite FTS5
Data Processing	Pandas
PDF Processing	PyMuPDF
Word Processing	python-docx
Excel Processing	OpenPyXL
Development Environment	Visual Studio Code
AI Development Assistant	OpenAI Codex
Version Control	Git / GitHub

7. Deployment Philosophy

EDM is designed for secure on-premises deployment.

Key principles:

* Offline operation.
* No dependency on external cloud services.
* Local document storage.
* Centralized database management.
* Controlled access within the organization’s infrastructure.
* Preservation of original documents during inventory and classification.

8. Project Scope

The initial development phase focuses on document inventory, identification, classification and metadata management.

Future development areas include advanced document relationships, OCR integration and expanded document retrieval capabilities.

9. Project Status

Development Stage: Initial development and functional validation.

The project is being developed incrementally, prioritizing data integrity, document traceability and a reliable foundation for future expansion.

10. Professional Focus

This project demonstrates the application of software development, engineering information management, process automation and systems architecture to real-world engineering challenges.

⸻

Project: Engineering Document Manager (EDM)

Category: Engineering / Software Development / Process Automation

Architecture: Offline / On-premises