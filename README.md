# snowflake
Snowflake, architecture, products, features, use case, and learning.

## Snowflake is a software-as-a-service tool for data warehousing and is sometimes called Data warehouse as a service tool.

It has 3 layers



## Snowflake follows hybrid architecture
** Decouples compute and storage so that both can be scaled independently in multi-cluster shared data architecture.**
. Cloud-native hence elastic
. 

1. Data Storage Layer
  > Cloud storage with compressed secure and encrypted data. Using underlying cloud platforms storage facility to storage large amount data data and can be scaled.
> Cloud Data redundancy. Pay only for storage used.
3. Compute and processing Layer
  > Virtual warehouse, running machines like Azure VM or EC2, different size to serve different workload.
4. Cloud service Layer (Brain of the system)
  > Authentication and Authorization
> Session and User management
> Query compilation, optimization and Data caching
> Virtual Warehouse management, Coordinate data Updates and Transaction management
> Metadata management, support zero copy cloning, Time travel and Data sharing.
> Manage virtual warehouses.
