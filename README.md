# Data at scale

## Golden source
 - A defnitive source of information
## Golden dataset
 - It denotes the original data that is created
## Domain Data Sore (DDS)
 - They consume, integrate and change the context of data from other systems. If DDS creates golden dataset then it becomes Golden source.
## Data Integration
 - Combining data from different sources
## Application types in the context of data
 - Data provider
 - Data consumer
## Ubiquitous Language 
 - An evolving common, rigorous language between developers and users.The term is used by Eric Evans in Domain Driven Design

## Data Architectures
 + Read-only datastore architecture
   - Reads are eventualy consistant due to delay in updation of query side datastore.
 + API architecture
 + Streaming architecture
 + Command and Query Responsibility Segregation (CQRS) 
   - An application design pattern
   - Why? 
      * Reading large volumens of data from a busy application can be risky.
   - Solves the problem of large reads by creating a copy of data exclusively for reads
   - Reads are eventualy consistant due to delay in updation of query side datastore.
## Agreements used in Data applications
 - Data delivery contracts 
 - Data sharing agreements  
 These are stored centrally for the functioning of autonomous teams.

## Information Architecture
 A discipline focused on making information findable and understandable.
 - Richard Saul Wurman had coined the expression 'information architect' in 1975

## Data Modelling Architectures
 + RDBMS
 + Key-value pairs
 + Graph oriented
 + Column oriented
 + NOSQL
### Data complexity contributers
 + Velocity
 + Volume
 + Varsity
 + Variety
 + Transformation
### Data management strategies
 + Data locality
   - Affected nonfunctional requirement is throughput
 + Replication
   - Affected nonfunctional requirement is reliability
 + Sharding 
   - Distributing data across multiple different nodes, can improve performance
 + Partition
   * Distributing data across multiple different nodes, can improve performance
   * Partition criteria
     - Range partitioning
     - List partitioning
     - Composite partitioning
     - Round-Robin partitioning
     - Hash partitioning
 + Caching
   - Affected nonfunctional requirement is throughput
 + Normalization and Denormalization

### Data architecture approaches based on properties
 + Datawarehouse
 + Hadoop for structured and unstructured data
 + Data lake to keep data in original form

## Data Modelling Methodologies
 + Bottom-up methodologies
   - Identify attributes and then move up
 + Top-down methodologies
   - Identify entities, relations and then the attributes


