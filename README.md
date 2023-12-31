# DistributedDesignPatterns

## Design patterns(Single Application)
In Software Design, there are problems that everyone faces and find solutions to it over time. But since these as said are common, we don't want to re-invent the wheel.
Common language oriented design patterns are classified as Creational, Structural and Behavioural patterns.

Similarly, when it comes to distributed systems, we have its own set of problems. To solve these, experts have already came up with patterns that could solve these challenges

### Most commonly used Distributed Design Patterns

1. **Client-Server Pattern**

(Start with the fundamental client-server architecture as the basis for distributed systems.)
* Client's responsibility - request the server, handle UI, presentation
* Server's responsibility - serve the client, processing etc(Centralized)

![ClientServer.png](Images/ClientServer.png)

Opposite :  P2P Pattern(Decentralized) - Example : BitTorrent - but this is distributed as well
![img.png](Images/P2P.png)


2. **Load Balancing Pattern**

Understand load balancing to ensure even distribution of traffic and scalability.

3. **Replication Pattern**

Learn how replication enhances fault tolerance and data availability.

4. **Partitioning/Sharding Pattern**

Explore data partitioning for distributing data and traffic efficiently.

5. **Messaging Patterns**

Understand how publish-subscribe and message queue patterns enable communication.

6. **Service Discovery Pattern**

Learn how services discover and communicate with each other in dynamic environments.

7. **Database Replication Patterns**

Explore master-slave and master-master replication for database scaling.

8. **Consistency and Replication Patterns**

Understand concepts like eventual consistency and quorum consensus.

9. **Caching Pattern**

Explore distributed caching to improve performance.

10. **Bulkhead Pattern**

Learn about isolating components to enhance system resilience.

11. **Circuit Breaker Pattern**

(Understand how to prevent repeated failures from affecting the system.)

1. Configure a failure threshold - say 'T'
2. Track requests and their state - failure/success
3. If failures cross T within a time period, open the circuit (redirect/failure message) - open
4. After a cooldown time, allow partial requests and see if system is back - half open
5. Depending on success rate in the half-open state, close/open the circuit

Pros:
1. Failure tolerance
2. Load Management
3. Graceful degradation
4. Monitoring and insights
5. Automatic recovery

![img.png](Images/CircuitBreaker.png)

12. **Saga Pattern**

Explore transaction management in long-running processes.

13. **Eventual Consistency**

Delve deeper into the concept of eventual consistency.

14. **Quorum Consensus**

Understand consensus algorithms for data consistency.

15. **Idempotent Pattern**

Learn about designing operations that can be retried safely.

16. **Versioning and Compatibility Patterns**

Understand how to manage backward and forward compatibility.

17. **Microservices Patterns**

Explore architectural patterns related to microservices.

18. **Distributed Tracing and Logging Patterns**

Learn about tracking and logging events in distributed systems.

19. **Security Patterns**

Familiarize yourself with security patterns like authentication and encryption.

20. **Chaos Engineering Patterns**

Understand strategies for testing system resilience.

21. **Streaming Patterns**

Explore patterns related to real-time data processing.