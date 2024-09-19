## Part 2: Data Protection, Governance, and Monitoring

### 1. Data Protection
Ensuring the security of the data was a top priority. The following AWS services were used to protect the data:
- **S3 Bucket Policies**: Strict access control measures were enforced to limit access to the data stored in the S3 buckets.
- **S3 Encryption**: AWS Key Management Service (KMS)-based encryption was enabled for all data stored in the S3 buckets, ensuring data security both at rest and in transit.
- **Data Replication**: Data replication across different AWS regions was implemented to provide redundancy and disaster recovery, ensuring high availability of the data in case of regional failures.
<img width="360" alt="image" src="https://github.com/user-attachments/assets/a5ed56fd-4683-4910-a804-4a91b4c7840f">



### 2. Data Governance
AWS CloudTrail was leveraged to manage data governance by logging all API requests and tracking changes in the AWS environment. CloudTrail's multi-region support ensured that governance was applied comprehensively across all regions, providing full visibility into system activity and ensuring compliance with the data protection policies.
<img width="360" alt="image" src="https://github.com/user-attachments/assets/65c5db57-a1a2-451a-8613-d2e8b5f9dcb5">



### 3. Data Monitoring
To monitor the health and performance of the system, AWS CloudWatch was employed. Several key metrics were tracked through custom CloudWatch dashboards:
- **Estimated Charges**: Monitored cost variations associated with S3 storage and other AWS services used in the project.
- **Bucket Size (in Bytes)**: Tracked the growth of data storage over time to ensure optimal resource management and forecasting future storage needs.
- **Data Transfer and Query Metrics**: Tracked data transfer rates and query performance to identify potential bottlenecks in the system.
<img width="360" alt="image" src="https://github.com/user-attachments/assets/09399f31-f4fe-4b31-a072-885a0eb48776">
<img width="360" alt="image" src="https://github.com/user-attachments/assets/9b8d5e03-1542-4504-ac21-8812cd1cf483">


