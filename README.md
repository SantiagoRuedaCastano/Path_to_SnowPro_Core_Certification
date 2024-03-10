# Path_to_SnowPro_Core_Certification
COF-C02 - SnowPro™ Core Certification


[SnowPro™ Core Certification](https://learn.snowflake.com/courses/course-v1:snowflake+CERT-SPC-GUIDE+B/about)

# Exam Domain Breakdown
| Domain | Domain Weightings on Exams |
| :- | :- |
| Snowflake Data Cloud Features & Architecture | 25% |
| Account Access and Security | 20% |
| Data Transformations | 20% |
| Performance Concepts | 15% |
| Data Loading and Unloading | 10% |
| Data Protection and Data Sharing | 10% |




## Snowflake Data Cloud Features & Architecture (25%)

* Outline key features of the Snowflake Data Cloud
    * [Key Concepts & Architecture](https://docs.snowflake.com/en/user-guide/intro-key-concepts)

    * [Snowflake Editions](https://docs.snowflake.com/en/user-guide/intro-editions)

* Outline key Snowflake tools and user interfaces
    * Snowsight (The Snowflake web interface)
    * SnowSQL (CLI client)
    * [Snowflake Connectors](https://other-docs.snowflake.com/en/connectors)
    * [Snowflake Drivers](https://docs.snowflake.com/en/developer-guide/drivers)
    * [SnowCD(Connectivity Diagnostic Tool)](https://docs.snowflake.com/en/user-guide/snowcd)


* Outline Snowflake’s catalog and objects.
    *	 [Databases](https://docs.snowflake.com/en/guides-overview-db)
    *	 [Stages](https://docs.snowflake.com/en/user-guide/data-load-considerations-stage)
    *	 [Schema types](https://docs.snowflake.com/en/sql-reference/sql/create-schema)
    * Tables
        * [table types](https://docs.snowflake.com/en/user-guide/tables-temp-transient)
        * [Design](https://docs.snowflake.com/en/user-guide/table-considerations)
    *	 [View types](https://docs.snowflake.com/en/user-guide/views-introduction)
    *	 [Data types](https://docs.snowflake.com/en/data-types)
    *	 User-Defined Functions (UDFs)
    *	 User Defined Table Functions (UDTFs)
    *	 Stored procedures
    *	 Streams
    *	 Tasks
    *	 Pipes
    *	 Shares
    *	 Sequences


* Outline Snowflake storage concepts.
    * [Micro-partitions](https://docs.snowflake.com/en/user-guide/tables-clustering-micropartitions)
    * Data clustering
    * Data storage monitoring


## Account Access and Security (20%)


* Outline security principles.
    *	Network security and policies
    *	Multi-Factor Authentication (MFA)
    *	Federated authentication
    *	Key pair authentication
    *	Single Sign-On (SSO)


* Define the entities and roles that are used in Snowflake.
    *	Overview of access control
        * Access control frameworks
        * Access control privileges
    *	Outline how privileges can be granted and revoked
    *	Explain role hierarchy and privilege inheritance


* Data governance capabilities in Snowflake.
    *	Accounts
    *	Organizations
    *	Secure views
    *	Secure functions
    *	Information schemas
    *	Access history
        *   Tracking read/write operations
    *	Overview of row/column-level security
    *	Object tags

## Data Transformations (20%)

* Explain how to work with standard data.
    *	Estimation functions
    *	Sampling
        *	SAMPLE command
        *	/TABLESAMPLE command
        *	Sampling methods
            * Fraction-based
            * Fixed-size
    *	Supported function types
        *	System functions
        *	Table functions
        *	External functions
        *	User-Defined Functions (UDFs)
    *	Stored procedures
    *	Streams
    *	Tasks

* Explain how to work with semi-structured data.
    *	Supported data formats, data types, and sizes
    *	VARIANT column
    *	Flattening the nested structure
        *	FLATTEN command
        *	LATERAL FLATTEN command
    *	Semi-structured data functions
        *	ARRAY/OBJECT creation and manipulation
        *	Extracting values
        *	Type predicates

* Explain how to work with unstructured data.
    * Define and use directory tables
    * SQL file functions
        * Types of URLs available to access files
    * Outline the purpose of User-Defined Functions (UDFs) for data analysis


## Performance Concepts (15%)

* Explain the use of the Query Profile.
    *	Explain plans
    *	Data spilling
    *	Use of the data cache
    *	Micro-partition pruning
    *	Query history

* Explain virtual warehouse configurations.
    *	Types of warehouses
    *	Multi-clustering warehouses
        * Scaling policies
        * Scaling modes
    *	Warehouse sizing
    *	Warehouse settings and access

* Outline virtual warehouse performance tools.
    *	Monitoring warehouse loads
    *	Scaling up compared to scaling out
    *	Resource monitors
    *	Query acceleration service

* Optimize query performance.
    *	Describe the use of materialized views
    *	Use of specific SELECT commands
    *	Clustering
    *	Search optimization service
    *	Persisted query results
    *	Understanding the impact of different types of caching
        * Metadata cache
        * Result cache
        * Warehouse cache


## Data Loading and Unloading (10%)

* Define concepts and best practices that should be considered when loading data.
    *	Stages and stage types
    *	File size and formats
    *	Folder structures
    *	Ad hoc/bulk loading
    *	Snowpipe

* Outline different commands used to load data and when they should be used.
    *	CREATE STAGE
    *	CREATE FILE FORMAT
    *	CREATE PIPE
    *	CREATE EXTERNAL TABLE
    *	COPY INTO
    *	INSERT/INSERT OVERWRITE
    *	PUT
    *	VALIDATE

* Define concepts and best practices that should be considered when unloading data.
    *	File size and formats
        * Overview of compression methods
    *	Empty strings and NULL values
    *	Unloading to a single file
    *	Unloading relational tables

* Outline the different commands used to unload data and when they should be used.
    *	GET
    *	LIST
    *	COPY INTO
    *	CREATE STAGE
    *	CREATE FILE FORMAT


## Data Protection and Data Sharing (10%)

* Outline Continuous Data Protection with Snowflake.
    *	Time Travel
    *	Fail-safe
    *	Data encryption
    *	Cloning
    *	Replication

* Outline Snowflake data sharing capabilities.
    *	Account types
    *	Snowflake Marketplace
    *	Data Exchange
    *	Access control options
        * DDL commands to create and manage shares
        * Privileges required for working with shares
    *	Secure Data Sharing (for example, Direct Share, Listing)


### Virtual Warehouses
[warehouses](https://docs.snowflake.com/user-guide/warehouses)

[Considerations](https://docs.snowflake.com/user-guide/warehouses-considerations)

### Tables
[Snowflake Table](https://docs.snowflake.com/en/user-guide/tables-micro-partitions)

[Comparison of Table Types](https://docs.snowflake.com/en/user-guide/tables-temp-transient#comparison-of-table-types)


### Data Loading
[Considerations](https://docs.snowflake.com/user-guide/data-load-considerations)

