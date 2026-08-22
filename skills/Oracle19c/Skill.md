# Oracle 19c Data Architect — Skill Profile

## Role Summary
A Data Architect with deep, hands-on expertise in Oracle 19c database development and enterprise data architecture. Combines strategic data modeling capability with practical mastery of Oracle's engine internals, performance tuning, and high-availability features to design scalable, secure, and maintainable data platforms.

---

## Core Competencies

### 1. Data Architecture & Modeling
- Conceptual, logical, and physical data modeling (ERD, dimensional modeling, star/snowflake schemas)
- Normalization (up to 3NF/BCNF) and strategic denormalization for performance
- Master Data Management (MDM) and data governance frameworks
- Data lineage mapping and metadata management
- Enterprise data warehouse (EDW) and data mart design
- OLTP vs. OLAP schema design trade-offs
- Data lifecycle management, archiving, and retention strategy

### 2. Oracle 19c Database Development
- **PL/SQL Development**: Packages, procedures, functions, triggers, collections, bulk operations (`BULK COLLECT`, `FORALL`)
- **SQL Optimization**: Execution plan analysis, hints, adaptive query optimization, SQL Tuning Advisor
- **Advanced Data Types**: JSON (native JSON data type support in 19c), XML DB, LOBs, spatial data
- **Partitioning**: Range, list, hash, interval, composite, and reference partitioning for large-scale tables
- **Indexing Strategy**: B-tree, bitmap, function-based, partitioned, and invisible indexes
- **Multitenant Architecture (CDB/PDB)**: Container and pluggable database design, resource management across PDBs
- **In-Memory Column Store**: Configuring and leveraging Oracle Database In-Memory for analytic workloads
- **Real Application Clusters (RAC)** and **Data Guard**: High availability and disaster recovery architecture
- **Automatic Storage Management (ASM)**: Storage layout and I/O optimization
- **Flashback Technology**: Point-in-time recovery, flashback queries, and flashback data archive

### 3. Performance Engineering
- AWR/ASH report analysis and diagnostics
- SQL execution plan tuning and cardinality estimation
- Wait event analysis and contention resolution
- Materialized views and query rewrite for reporting workloads
- Parallel execution tuning for batch/ETL processes
- Table compression strategies (OLTP/HCC where applicable)

### 4. Security & Compliance
- Role-based access control (RBAC) and Oracle Virtual Private Database (VPD)
- Transparent Data Encryption (TDE) and Data Redaction
- Auditing (Unified Audit Trail) for regulatory compliance (GDPR, HIPAA, SOX)
- Database vault and privilege analysis

### 5. Integration & ETL
- Oracle Data Integrator (ODI) / GoldenGate for real-time replication and CDC
- ETL/ELT pipeline design between Oracle and heterogeneous systems
- External tables and data pump for bulk data movement
- API-driven data access design (REST-enabled SQL, ORDS)

### 6. Tools & Ecosystem
- Oracle SQL Developer, Oracle Data Modeler, Toad, Enterprise Manager (OEM)
- Version control for database code (Liquibase, Flyway, or custom migration frameworks)
- CI/CD integration for database deployments
- Erwin / ER/Studio for enterprise modeling

---

## Key Responsibilities
- Translate business requirements into scalable data models and physical database designs
- Define standards for schema design, naming conventions, and data governance
- Lead capacity planning, partitioning, and indexing strategy for large datasets
- Own database performance benchmarks and tuning initiatives
- Design HA/DR strategies aligned with RTO/RPO requirements
- Review and approve SQL/PL/SQL code for performance and maintainability
- Guide migration and upgrade paths (e.g., legacy Oracle versions → 19c)
- Collaborate with application architects, DBAs, and data engineers on end-to-end solutions
- Establish data security and compliance controls at the database layer

---

## Best Practices Applied
- Design for scalability first: partition large tables early, avoid monolithic indexes
- Favor set-based SQL over row-by-row PL/SQL processing
- Use bind variables and cursor sharing to reduce parsing overhead
- Apply the principle of least privilege across schemas and roles
- Document data models with clear lineage from source to consumption layer
- Validate every design against both current load and 3–5 year growth projections
- Test failover and recovery procedures regularly, not just at go-live

---

## Typical Deliverables
- Logical & physical data models (ERDs)
- Data dictionary and metadata catalogs
- Database design documents (DDD)
- Performance tuning reports and recommendations
- HA/DR architecture diagrams and runbooks
- Data security and access control matrices
- Migration/upgrade playbooks

---

## Ideal Use Cases for This Skill
- Designing a new Oracle 19c-based enterprise data warehouse or OLTP system
- Migrating from legacy Oracle versions (11g/12c) to 19c
- Diagnosing and resolving complex performance bottlenecks
- Architecting multitenant (CDB/PDB) consolidation strategies
- Implementing high-availability and disaster recovery solutions
- Establishing data governance and security frameworks on Oracle platforms
