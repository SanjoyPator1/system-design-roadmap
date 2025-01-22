# **3. Data Storage and Databases**

### **Purpose**

Understand the principles of data storage and database design, including the trade-offs between different database types, how to model data effectively, and optimize performance for distributed and large-scale systems.

---

## **Chapter List for Data Storage and Databases**

---

### **3.1 Relational Databases (SQL) and ACID Properties**

1. **Introduction to Relational Databases**:
   - What are relational databases?
   - Common relational database management systems (RDBMS): MySQL, PostgreSQL, SQL Server.
2. **Understanding SQL**:
   - Basics of SQL: SELECT, INSERT, UPDATE, DELETE.
   - Advanced SQL concepts: JOINs, GROUP BY, HAVING, nested queries.
3. **ACID Properties**:
   - Atomicity, Consistency, Isolation, Durability.
   - Real-world examples of ACID transactions.
4. **When to Choose Relational Databases**:
   - Use cases for relational databases.
   - Trade-offs compared to NoSQL databases.
5. **Hands-On Exercises**:
   - Create and query a database using MySQL or PostgreSQL.
   - Design a schema for a basic e-commerce system.

---

### **3.2 NoSQL Databases**

1. **Introduction to NoSQL**:
   - What are NoSQL databases, and why were they created?
   - Differences between SQL and NoSQL.
2. **Types of NoSQL Databases**:
   - **Key-Value Stores**:
     - Examples: Redis, DynamoDB.
     - Use cases: Caching, session storage.
   - **Document Stores**:
     - Examples: MongoDB, CouchDB.
     - Use cases: Content management systems, JSON-like data storage.
   - **Wide Column Stores**:
     - Examples: Cassandra, HBase.
     - Use cases: High write throughput, time-series data.
   - **Graph Databases**:
     - Examples: Neo4j, Amazon Neptune.
     - Use cases: Social networks, fraud detection.
3. **CAP Theorem and NoSQL**:
   - Consistency, Availability, Partition Tolerance.
   - Examples of how different NoSQL databases prioritize these factors.
4. **When to Choose NoSQL Databases**:
   - Advantages and limitations of NoSQL databases.
   - Scenarios where NoSQL databases are a better choice than relational databases.
5. **Hands-On Exercises**:
   - Set up a MongoDB database and perform CRUD operations.
   - Experiment with Redis for caching data.

---

### **3.3 Data Modeling and Schema Design**

1. **Importance of Data Modeling**:
   - What is data modeling, and why is it critical?
   - Logical vs physical data models.
2. **Schema Design for Relational Databases**:
   - Normalization: 1NF, 2NF, 3NF, and beyond.
   - Denormalization and when to use it.
3. **Schema Design for NoSQL Databases**:
   - Designing schemas for document stores, key-value stores, and graph databases.
   - Differences in schema design strategies for SQL and NoSQL.
4. **Data Modeling Tools**:
   - Tools like ERD (Entity-Relationship Diagram) for schema design.
   - Software for data modeling: dbdiagram.io, MySQL Workbench.
5. **Hands-On Exercises**:
   - Design a normalized schema for a relational database.
   - Model data for a NoSQL database using MongoDB or DynamoDB.

---

### **3.4 Database Indexing, Partitioning, and Sharding**

1. **Database Indexing**:
   - What are indexes, and why are they important?
   - Types of indexes: B-Tree, Hash, Full-Text.
   - Trade-offs: Performance benefits vs additional storage.
2. **Database Partitioning**:
   - Horizontal vs vertical partitioning.
   - Benefits and challenges of partitioning.
3. **Sharding in Distributed Databases**:
   - What is sharding, and how does it work?
   - Techniques for sharding: Range-based, hash-based, and directory-based.
4. **When to Use Indexing, Partitioning, and Sharding**:
   - Scenarios for each technique in improving performance and scalability.
5. **Hands-On Exercises**:
   - Create and analyze indexes in MySQL or PostgreSQL.
   - Partition a table and observe query performance improvements.

---

### **3.5 Distributed Databases and Replication**

1. **Introduction to Distributed Databases**:
   - What are distributed databases, and why are they used?
   - Examples: Google Spanner, Amazon Aurora, CockroachDB.
2. **Replication**:
   - Types of replication: Master-slave, master-master, multi-region.
   - Trade-offs between synchronous and asynchronous replication.
3. **Consistency Models**:
   - Strong consistency vs eventual consistency.
   - Examples of databases and their consistency guarantees.
4. **Trade-offs in Distributed Databases**:
   - Balancing consistency, availability, and partition tolerance.
5. **Hands-On Exercises**:
   - Set up replication in MySQL or MongoDB.
   - Experiment with eventual consistency using a NoSQL database.

---

### **3.6 Storage Engines: InnoDB, RocksDB**

1. **What Are Storage Engines?**:
   - Role of storage engines in databases.
   - Differences between storage engines.
2. **InnoDB**:
   - Features of InnoDB (e.g., ACID compliance, row-level locking).
   - Use cases for InnoDB.
3. **RocksDB**:
   - Features of RocksDB (e.g., high write throughput, log-structured storage).
   - Use cases for RocksDB in modern applications.
4. **Choosing a Storage Engine**:
   - Factors to consider when selecting a storage engine.
5. **Hands-On Exercises**:
   - Explore InnoDB settings and optimizations in MySQL.
   - Experiment with RocksDB using a sample project.

---

### **Implementation Tasks for Data Storage and Databases**

- **Relational Databases**:
  - Design and implement a relational schema for an e-commerce system.
  - Write and optimize SQL queries for complex data retrieval.
- **NoSQL Databases**:
  - Model and store hierarchical data using a document store.
  - Implement a caching layer using a key-value store like Redis.
- **Data Modeling**:
  - Create an ERD for a library management system.
  - Develop a schema for time-series data using a wide-column store.
- **Indexing, Partitioning, and Sharding**:
  - Test query performance with and without indexing.
  - Experiment with sharding in a distributed database.
- **Distributed Databases**:
  - Set up a distributed database cluster and test replication.
  - Analyze the impact of consistency models on query performance.
- **Storage Engines**:
  - Compare the performance of InnoDB and RocksDB for a write-heavy workload.

This detailed chapter list covers every essential concept and practical aspect of database design and storage systems.

---
