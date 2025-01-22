## **1. Scalability**

**Definition of Scalability**

- Scalability is the ability of a system to handle increased loads without impacting performance or stability. It ensures the system can grow to meet user, traffic, or data demands efficiently.

**Types of Scalability**

1. **Vertical Scaling (Scaling Up):**
   - Involves upgrading the hardware (e.g., adding more CPU, RAM, or storage).
   - Simpler to implement but has a physical limit and can be expensive.
   - Example: Upgrading a single database server to a more powerful one.
2. **Horizontal Scaling (Scaling Out):**
   - Adds more machines or servers to distribute the load.
   - Offers better fault tolerance and virtually unlimited growth potential.
   - Example: Adding more instances of a web server behind a load balancer.

**Importance of Designing for Scalability**

- Ensures the system can handle sudden traffic spikes without degrading performance.
- Prepares the system for long-term growth in users, data, or workload.
- Reduces downtime and enhances user experience during high-demand periods.

**Techniques for Achieving Scalability**

1. **Load Balancing:**
   - Distributes incoming traffic across multiple servers to prevent overload on a single machine.
   - Types: Round-robin, least connections, IP hash.
2. **Partitioning (Sharding):**
   - Divides a database or dataset into smaller, manageable pieces called shards.
   - Each shard handles a portion of the data, improving performance and scalability.
   - Example: Splitting user data by geographical regions.
3. **Caching:**
   - Stores frequently accessed data in memory (e.g., Redis, Memcached).
   - Reduces database load and improves response times.
   - Example: Caching user session data or product search result**Definition of Scalability in System Design**
