# System-Design-Notes
System design topics and concepts and thieir study links

Concepts:

1. Consistent Hashing


2. Distributed Transactions


3. Distributed Locks


4. Cluster management



5. Resiliency


6. CAP theorem


7. Bloom Filters
   Are probabilistic data structure which can tell for sure that item do not belong to a set (No false negatives) and tell item belong to the given set with some certainity, if item is present in the set(false positives are present but can be minimized). It is extremelly useful as it saves a lot of memory. For introduction to subject follow following link: https://www.youtube.com/watch?v=bEmBh1HtYrw .  The basic idea is to use k hash functions to generate a position to set a bit in an array of size n. where n is always > k. 


8. Rate Limiting (Leaky Bucket and Token Bucket algorithms), Load Shedders, 


9. Data Replication

10. Types of data and their mapping to different kinds of databases/stores

11. Caching: Types, places where data can be cached and cache selection

12. Map-Reduce 

