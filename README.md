# intrordbms
Introductory data engineering project demonstrating skills acquired:

A New York-based coffee shop chain is preparing to expand its operations across the country through a network of new franchise locations. To support this growth, the company is working to improve its data infrastructure and streamline internal operations.

At present, business-critical data is spread across multiple systems, including accounting software, supplier databases, point-of-sale systems, and a collection of spreadsheets. This fragmented setup has made it difficult to generate consistent reports and has limited the company’s ability to make timely, data-driven decisions.

As part of the effort to modernize, a centralized relational database has been designed to integrate key areas such as staff management, store locations, product offerings, and inventory. This project includes identifying core business entities, normalizing and modeling relationships, generating database objects, importing source data, and creating views to support executive reporting needs.

The output, via the following technical aspects, should provide a scalable and maintainable data foundation that supports operational efficiency and provides better access to insights as the company grows nationally:

- Entity and Attribute Identification:
  Analyzed operational data sources to identify core entities such as staff, store locations, and product inventory, along with relevant attributes.

- Database Modeling and Normalization
  Created an entity-relationship diagram (ERD) and normalized all tables to Third Normal Form (3NF) to reduce redundancy and improve data integrity.

- Schema Implementation
  Used SQL to define and deploy all database objects including tables, constraints, relationships, and keys within PostgreSQL using pgAdmin.

- View and Materialized View Creation
  Developed standard and materialized views to support business reporting and improve query performance. Views were exported and staged for use in downstream systems.

- Data Integration Across Platforms
  Imported and staged source datasets into both PostgreSQL and MySQL environments to simulate real-world data loading scenarios from legacy systems.

- Documentation and Export
  Output data from views was exported as CSV files and archived in a structured format for reporting and presentation purposes.

This work demonstrates key data engineering competencies in relational modeling, SQL development, cross-platform data handling, and data lifecycle management.

The datasets used are:


![image](https://github.com/user-attachments/assets/b5d8306d-26a4-4682-af45-e9779785e769)

