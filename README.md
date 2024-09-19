## Part 2: Data Protection, Governance, and Monitoring

### 1. Data Protection
Ensuring the security of the data was a top priority. The following AWS services were used to protect the data:
- **S3 Bucket Policies**: Strict access control measures were enforced to limit access to the data stored in the S3 buckets.
- **S3 Encryption**: AWS Key Management Service (KMS)-based encryption was enabled for all data stored in the S3 buckets, ensuring data security both at rest and in transit.
- **Data Replication**: Data replication across different AWS regions was implemented to provide redundancy and disaster recovery, ensuring high availability of the data in case of regional failures.
![DataBrew Data Preparation](DataProtection.jpg)


### 2. Data Governance
AWS CloudTrail was leveraged to manage data governance by logging all API requests and tracking changes in the AWS environment. CloudTrail's multi-region support ensured that governance was applied comprehensively across all regions, providing full visibility into system activity and ensuring compliance with the data protection policies.
![Data Governance](DataGovernance.png)

### 3. Data Monitoring
To monitor the health and performance of the system, AWS CloudWatch was employed. Several key metrics were tracked through custom CloudWatch dashboards:
- **Estimated Charges**: Monitored cost variations associated with S3 storage and other AWS services used in the project.
- **Bucket Size (in Bytes)**: Tracked the growth of data storage over time to ensure optimal resource management and forecasting future storage needs.
- **Data Transfer and Query Metrics**: Tracked data transfer rates and query performance to identify potential bottlenecks in the system.
  ![Data Monitoring](DataMonitoring.png)
  
   ![Data Monitoring1](datamonitoring1.png)
  
   ![Data Monitoring](datamonitoring2.png)
