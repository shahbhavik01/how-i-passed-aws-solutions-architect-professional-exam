# how-i-passed-aws-solutions-architect-professional-exam
How I studied for and passed the AWS Solutions Architect Professional Exam

I'm just starting this and it's a work in progress. Should have a much cleaner repository in a few days. 


## Here's all the material you came for. Read information in sections 3 onwards for more nuanced tips.

# Section 1. Re:Invent Videos Watched:

https://www.youtube.com/watch?v=SUWqDOnXeDw (S3 and Glacier Deep Dive)

https://www.youtube.com/watch?v=TJxC-B9Q9tQ (RDS Deep Dive)

https://www.youtube.com/watch?v=_YYBdsuUq2M (Elasticache)

https://www.youtube.com/watch?v=9wgaV70FeaM (Storage Gateway)

https://www.youtube.com/watch?v=KGKrVO9xlqI (Networking VPCs together)

https://www.youtube.com/watch?v=8gc2DgBqo9U (Data flow through AWS)

https://www.youtube.com/watch?v=z0FBGIT1Ub4 (Network Load Balancer)

https://www.youtube.com/watch?v=uj7Ting6Ckk (Amazon Global Network)

https://www.youtube.com/watch?v=tzJmE_Jlas0 (Security Anti-patterns: Mistakes to avoid)

https://www.youtube.com/watch?v=9TwkMMogojY (ELB deep dive) 2

https://www.youtube.com/watch?v=71fD8Oenwxc (Security across multi-account) 

https://www.youtube.com/watch?v=id-PY0GBHXA (Assessing Readiness to migrate at scale) 4

https://www.youtube.com/watch?v=Y33TviLMBFY (Migrating databases and data warehouses to cloud) 5

https://www.youtube.com/watch?v=w95murBkYmU (Scale to 10 mil users) 3

https://www.youtube.com/watch?v=xc_PZ5OPXcc (Models of availability) 6

https://www.youtube.com/watch?v=RMrfzR4zyM4 (Multi-region active-active architecture) REALLY IMP I THINK 1

https://www.youtube.com/watch?v=a7EMou07hRc (Disaster recovery)

https://www.youtube.com/watch?v=01hy48R9Kr8 (Cloudformation deep dive) 2

https://www.youtube.com/watch?v=Qik9LBktjgs (Docker and ECS)

https://www.youtube.com/watch?v=GEPJ7Lo346A (CI best practices)

https://www.youtube.com/watch?v=CcspJkc7zqg (Building a business case)

https://www.youtube.com/watch?v=XQFweGjK_-o (Cost Optimization)


# Section 2. Links to all the whitepapers I read, took notes of and reviewed close to the exam

https://d1.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf - 

https://d1.awsstatic.com/whitepapers/Multi_Tenant_SaaS_Storage_Strategies.pdf -

https://d0.awsstatic.com/whitepapers/performance-at-scale-with-amazon-elasticache.pdf -

http://d0.awsstatic.com/whitepapers/AWS_Securing_Data_at_Rest_with_Encryption.pdf -

http://d0.awsstatic.com/whitepapers/aws-migrate-resources-to-new-region.pdf?refid=70138000001adyu -

https://d0.awsstatic.com/whitepapers/aws-amazon-vpc-connectivity-options.pdf -

https://d1.awsstatic.com/whitepapers/Networking/integrating-aws-with-multiprotocol-label-switching.pdf - 

https://d1.awsstatic.com/whitepapers/Security/Networking_Security_Whitepaper.pdf -

https://d1.awsstatic.com/aws-answers/AWS_Multi_Account_Security_Strategy.pdf

https://d1.awsstatic.com/whitepapers/Migration/aws-migration-whitepaper.pdf 

https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf 

https://d1.awsstatic.com/whitepapers/Migration/migrating-applications-to-aws.pdf 

https://d1.awsstatic.com/whitepapers/AWS-Cloud-Transformation-Maturity-Model.pdf 

https://d1.awsstatic.com/whitepapers/aws-web-hosting-best-practices.pdf 

https://d0.awsstatic.com/whitepapers/aws-scalable-gaming-patterns.pdf - 65 pages

https://d1.awsstatic.com/whitepapers/cost-optimization-automating-elasticity.pdf - 10 pages

https://d0.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf - 85 pages

https://d1.awsstatic.com/whitepapers/microservices-on-aws.pdf - 

https://d1.awsstatic.com/whitepapers/Storage/Backup_and_Recovery_Approaches_Using_AWS.pdf

https://d1.awsstatic.com/whitepapers/getting-started-with-amazon-aurora.pdf - 25 pages

https://d1.awsstatic.com/whitepapers/architecture/AWS-Reliability-Pillar.pdf - 62 pages. 

https://d1.awsstatic.com/whitepapers/DevOps/infrastructure-as-code.pdf - 39 pages

https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf - 36 pages

https://d1.awsstatic.com/whitepapers/overview-of-deployment-options-on-aws.pdf - 23 pages

https://d1.awsstatic.com/whitepapers/architecture/AWS-Cost-Optimization-Pillar.pdf - 25 pages

https://d1.awsstatic.com/whitepapers/total-cost-of-operation-benefits-using-aws.pdf -

https://d1.awsstatic.com/whitepapers/introduction-to-aws-cloud-economics-final.pdf - Only 15 pages


# Section 3. I went through this amazing, short, FREEEEE course by AWS:

https://www.aws.training/Details/eLearning?id=34737

The videos are more scenario based and walks you through sample questions. One main thing I LOVED about this course is that it talks you through the thought process of someone arriving to the correct answer. This thought process is CRUCIAL during the exam. 

# Section 4. I took the AWS Solution Architect - Professional course through ACloudguru. These guys are amazing and cost effective. I highly recommend them. Truly worth it. 

https://acloud.guru/

# Section 5. Do you know what the following terms mean? All these are not just AWS terminology. Knowing what they mean should help you towards the exam and becoming more knowledgable about AWS and surrounding technologies. (These is not an exhaustive list and these are in no particular order)


Row-locking
Contention 
Vault Lock APIs on Glacier
Large Binary Objects (BLOBs)
Different DynamoDB Indices (Global secondary index and Local secondary index)
Views in RDS
OLAP vs OLTP. 
Ephemeral ports
Memcached vs Redis 
EFS Shares
EFS Mount targets
EFS lifecycle policies and storage classes
Different types of storage gateways
• FILE
• Volume Gateway
	• Cached
	• Stored
• Tape Gateway
Pub/Sub
Lazy writes
Cloudfront SNI
Partition Placement Group
Perpetual Consistency vs Eventual Consistency
DynamoDB Accelerator? (DAX?)
What are jumbo frames?
NFS vs SMB
iSCSI
AWS Service Catalog
FQDN
Types Route 53 health checks
Personal health dashboard
Delete markers on s3 
Canonical data models
"Brown Field" situation
IDS/IPS
Eventbridge
Fargate
Hard Cost vs Soft Cost
IOPS vs Mb/S 
Scalable EBS
Amazon AppStream 2.0 stacks and fleets
Consistent hashing
JDBC/ODBC 
Cloudformation Stackset
AD Connector
AWS SSO
Properties of ELB
Properties of Auto Scaling and it's terminology
AWS Elastic Beanstalk
Properties of Cloudfront
AWS Step Functions
Redshift Spectrum
Cloudfront with dynamic content
Session Data
Cost Optimization Monitor
AWS Cost Explorer
AWS Instance Scheduler
AWS data pipeline
Kinesis Firehose
Kinesis Streams
AWS CodePipeline
AWS CodeStar
Direct Connect Gateway
SOAP vs REST APIs
Route Propagation
