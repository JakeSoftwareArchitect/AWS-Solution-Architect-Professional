# Databases

## Redshift

Redshift is a petabite scale data warehouse, designed for reporting and analytics.

- Comsists of a leader node and one or more support nodes.
- Redshift can use S3 to perform snapshot backups.
- Can recieve data from FireHose
    - There are two types of backup:
    - Automated backups: occur every 8 hours or after every 5 GB of data, by default having 1 day retention (max 35). Snapshots are incremental.
    - Manual snapshots performed by a manual trigger.


ETL - Extract, Transform and Load. This is the process of taking data from one system and putting into another. RedShift facilitates zero ETL.

Amazon RedShift Data Sharing:

> Amazon Redshift data sharing allows you to share data within and across organizations, AWS regions, and even 3rd party providers, without moving or copying the data. Read from and write to the same Redshift databases using multiple data warehouses and extend the ease of use, performance, and cost benefits that Amazon Redshift offers to multi-warehouse, data mesh architectures. Enable access to live, up-to-date data within and across the organization instantly, eliminating multiple Extract, Transform, Load (ETL) pipelines, enabling collaboration on data, and reducing time to insights. 

Has Apache spark integration built in.


