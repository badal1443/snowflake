# How storage layer works.

### Snowflake stores all data in databases and the database is a logical grouping of objects within a snowflake instance.

  > Objects are tables (Permanent, transient and temporary) and vies (standard and materialised).
> These objects are part of 1 or more schemas.
> Can store structured (relational) data or semistructured non-relational data like, JSON, XML, Parquet, Avro etc) in a secure cloud storage space.
> 

### When data is loaded in tables:
> Snowflake converts the data in optimized columnar compressed format (CCF).
> These AES 256 encrypted data through CCF causes lot of data efficiency by making faster workload, low compute and storagecosts.
> Overhead of storing the data securily into s3 buckets,/azure blob storage  or GCP buckets is taken care by Snowflake.
> Data can only be accessed using SQL in UI or through connectors.
> Cost is calculated based on vaerage life of data in bytes in short (transient) or long (Permanent) lived tables.

