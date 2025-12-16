# AWS Services In Scope

## Analytics Services

**Amazon Athena** - (Serverless) Interactive query service that analyzes data in S3 using SQL. On the exam, remember it's serverless, pay-per-query, and perfect for ad-hoc analysis of data lakes without setting up infrastructure.

**Amazon EMR** - Managed big data platform for processing vast amounts of data using frameworks like Apache Spark and Hadoop. Exam tip: Think of EMR when you see scenarios involving big data processing, log analysis, or machine learning at scale.

**AWS Glue** - (Serverless) Fully managed ETL (extract, transform, load) service for data preparation and integration. Key for exam: It automatically discovers and catalogs data, making it easy to prepare data for analytics.

**Amazon Kinesis** - (Serverless) Real-time data streaming service for collecting, processing, and analyzing data streams. Exam focus: Kinesis is for real-time data processing, while S3 is for batch processing.

**Amazon OpenSearch** - Managed search and analytics engine for log analytics, real-time monitoring, and search applications. Previously called Elasticsearch. Know it for search functionality and log analysis scenarios.

**Amazon QuickSight** - (Serverless) Business intelligence service for creating interactive dashboards and visualizations. Exam context: When questions mention business analytics, reporting, or data visualization for non-technical users.

**Amazon Redshift** - Managed data warehouse for analytics workloads. Key distinction for exam: Redshift for data warehousing and complex analytics, RDS for transactional databases.

## Application Integration

**Amazon EventBridge** - (Serverless) Event bus service for connecting applications using events from AWS services, SaaS applications, and custom applications. Exam tip: Think event-driven architecture and loose coupling.

**Amazon SNS** - (Serverless) Pub/sub messaging service for sending notifications to multiple subscribers. Remember for exam: SNS is for fan-out messaging (one-to-many), while SQS is for queuing (one-to-one).

**Amazon SQS** - (Serverless) Message queuing service for decoupling application components. Exam essential: SQS prevents message loss and enables asynchronous communication between services.

**AWS Step Functions** - (Serverless) Workflow orchestration service for coordinating multiple AWS services into business workflows. Know for exam: It's for building complex, multi-step applications with visual workflows.

## Business Applications

**Amazon Connect** - Cloud-based contact center service for customer service operations. Exam context: When scenarios mention call centers, customer support, or telephony integration.

**Amazon SES** - (Serverless) Email sending service for transactional and marketing emails. Exam tip: SES for sending emails programmatically, not for email hosting (that would be WorkMail).

## Cost Management

**AWS Budgets** - Service for setting custom cost and usage budgets with alerts. Exam focus: Proactive cost management and getting notified before you exceed spending limits.

**Cost and Usage Reports** - Detailed billing reports with comprehensive cost and usage data. Know for exam: Most detailed billing information available, often used for cost allocation and analysis.

**AWS Cost Explorer** - Tool for visualizing and managing AWS costs over time with recommendations. Exam tip: It provides cost optimization recommendations and helps identify spending patterns.

**AWS Marketplace** - Digital catalog of software solutions that run on AWS. Exam context: Third-party software procurement and simplified billing for software licenses. It is a collection of Amazon Machine Images (AMIs) with an associated cost for the license.

## Compute Services

**AWS Batch** - Managed service for running batch computing workloads. Know for exam: Automatically provisions compute resources for batch jobs, ideal for data processing and analysis tasks.

**Amazon EC2** - Virtual servers in the cloud, the foundation of AWS compute. Exam essential: Understand instance types, purchasing options (On-Demand, Reserved, Spot), and use cases for different scenarios.

**AWS Elastic Beanstalk** - Platform-as-a-Service for deploying web applications without managing infrastructure. Exam tip: Developer-friendly, handles capacity provisioning and load balancing automatically.

**Amazon Lightsail** - Simplified virtual private servers with predictable pricing. Know for exam: Entry-level service for simple workloads, includes compute, storage, and networking at a low cost.

**AWS Outposts** - Brings AWS infrastructure to on-premises locations. Exam context: Hybrid cloud scenarios where you need AWS services in your own data center (on-premises).

**Amazon ECR** - Managed Docker container registry for storing and managing container images. Exam tip: Think container image storage and integration with ECS/EKS.

**Amazon ECS** - Managed container orchestration service for Docker containers. Know for exam: Fully managed container service, integrates well with other AWS services.

**Amazon EKS** - Managed Kubernetes service for container orchestration. Exam focus: When scenarios require Kubernetes expertise or compatibility with existing Kubernetes applications.

**AWS Fargate** - (Serverless) Compute engine for containers without managing servers. Key for exam: Serverless containers - you don't manage the underlying infrastructure, you just launch containers.

**AWS Lambda** - (Serverless) Run code without provisioning servers, event-driven compute. Exam essential: Pay only for compute time, scales automatically, perfect for event-driven architectures.

## Database Services

**Amazon Aurora** - High-performance managed relational database compatible with MySQL and PostgreSQL. Exam tip: Aurora Serverless is available for variable workloads, standard Aurora for consistent high performance.

**Amazon DocumentDB** - Managed document database compatible with MongoDB. Know for exam: When scenarios mention document storage, JSON data, or MongoDB compatibility.

**Amazon DynamoDB** - (Serverless) Fast, flexible NoSQL database with single-digit millisecond latency. Exam essential: Fully managed, scales automatically, perfect for mobile and web applications.

**Amazon ElastiCache** - Managed in-memory caching service supporting Redis and Memcached. Exam context: Improving application performance by caching frequently accessed data.

**Amazon Neptune** - Managed graph database for building applications with highly connected datasets. Know for exam: Social networks, fraud detection, recommendation engines using graph relationships.

**Amazon RDS** - Managed relational database service supporting multiple engines (MySQL, PostgreSQL, Oracle, SQL Server, MariaDB). Exam focus: Automated backups, patching, and Multi-AZ for high availability.

## Developer Tools

**AWS CLI** - Command-line interface for interacting with AWS services programmatically. Exam tip: Alternative to the console for automation and scripting AWS operations.

**AWS CodeBuild** - (Serverless) Managed build service for compiling source code and running tests. Know for exam: Part of CI/CD pipeline, scales automatically, pay only for build time.

**AWS CodePipeline** - Managed CI/CD service for automating release pipelines. Exam context: Automated software delivery from source code to production deployment.

**AWS X-Ray** - Distributed tracing service for debugging and analyzing microservices applications. Exam tip: Helps identify performance bottlenecks and understand request flows in distributed systems.

## End User Computing

**Amazon AppStream 2.0** - Managed application streaming service for delivering desktop applications to users. Exam context: When scenarios mention accessing applications from any device without installation.

**Amazon WorkSpaces** - Managed desktop-as-a-service solution providing virtual desktops. Know for exam: Virtual desktop infrastructure (VDI) in the cloud for remote work scenarios.

**Amazon WorkSpaces Secure Browser** - Managed service providing secure web browser access. Exam tip: For scenarios requiring isolated web browsing for security compliance.

## Frontend Web and Mobile

**AWS Amplify** - Platform for building full-stack web and mobile applications with built-in CI/CD. Exam focus: Developer-friendly platform for front-end developers to build complete applications.

**AWS AppSync** - (Serverless) Managed GraphQL API service for real-time data synchronization. Know for exam: Real-time APIs, offline data sync, and GraphQL use cases.

## Internet of Things

**AWS IoT Core** - Managed service for connecting IoT devices to AWS services. Exam context: When scenarios involve sensors, smart devices, or large-scale IoT deployments.

## Machine Learning

**Amazon Comprehend** - (Serverless) Natural language processing service for text analysis. Exam tip: Extracting insights from text, sentiment analysis, and entity recognition without ML expertise.

**Amazon Kendra** - Intelligent search service powered by machine learning. Know for exam: Enterprise search across documents and data sources using natural language.

**Amazon Lex** - (Serverless) Service for building chatbots and voice applications. Exam context: When scenarios mention conversational AI, chatbots, or voice interfaces.

**Amazon Polly** - (Serverless) Text-to-speech service for converting text into lifelike speech. Exam tip: Think audio content creation, accessibility features, or voice applications.

**Amazon Q** - AI-powered assistant for AWS that helps with coding, troubleshooting, and best practices. Know for exam: AWS's intelligent assistant for productivity and guidance.

**Amazon Rekognition** - (Serverless) Computer vision service for image and video analysis. Exam focus: Facial recognition, object detection, content moderation without deep learning expertise.

**Amazon SageMaker** - Fully managed machine learning platform for building, training, and deploying ML models. Exam context: When scenarios require custom ML model development and deployment.

**Amazon Textract** - (Serverless) Service for extracting text and data from documents using OCR and ML. Know for exam: Converting scanned documents into machine-readable text and structured data.

**Amazon Transcribe** - (Serverless) Speech-to-text service for converting audio to text. Exam tip: Think meeting transcription, voice analytics, or creating subtitles.

**Amazon Translate** - (Serverless) Language translation service for real-time text translation. Exam context: Multi-language applications or content localization scenarios.

## Management & Governance

**AWS Auto Scaling** - Service that automatically adjusts compute capacity based on demand. Exam essential: Helps maintain application availability and optimize costs by scaling resources up or down.

**AWS CloudFormation** - Infrastructure as Code service for provisioning AWS resources using templates. Exam tip: Declarative way to manage infrastructure, enables repeatable deployments.

**AWS CloudTrail** - Service that logs API calls and account activity for audit and compliance. Know for exam: Essential for security monitoring, compliance, and understanding "who did what when."

**Amazon CloudWatch** - Monitoring and observability service for AWS resources and applications. Exam essential: Collects metrics, logs, and events; sets up alarms and automated responses.

**AWS Compute Optimizer** - Service that recommends optimal AWS compute resources based on utilization data. Exam focus: Cost optimization through right-sizing recommendations.

**AWS Config** - Service that tracks resource configurations and compliance with organizational standards. Know for exam: Configuration management, compliance monitoring, and change tracking.

**AWS Control Tower** - Service for setting up and managing secure, compliant multi-account AWS environments. Exam context: Enterprise governance and automated account setup with best practices.

**AWS Health Dashboard** - Provides alerts and guidance when AWS events might affect your resources. Exam tip: Proactive notification about AWS service issues affecting your account.

**AWS License Manager** - Service for managing software licenses across AWS and on-premises environments. Know for exam: License compliance and optimization for commercial software.

**AWS Management Console** - Web-based interface for accessing and managing AWS services. Exam basic: The primary way most users interact with AWS services through a graphical interface.

**AWS Organizations** - Service for centrally managing multiple AWS accounts with consolidated billing. Exam essential: Multi-account management, organizational units (OUs), and service control policies (SCPs).

**AWS Service Catalog** - Service for creating and managing catalogs of approved AWS services and resources. Exam context: Standardizing deployments and maintaining governance in enterprise environments.

**AWS Service Quotas** - Service for viewing and managing your service limits and quotas. Know for exam: Understanding and requesting increases to default service limits.

**AWS Systems Manager** - Unified interface for managing AWS resources with automation capabilities. Exam tip: Patch management, configuration management, and operational insights across resources.

**AWS Trusted Advisor** - Service that provides real-time guidance to help optimize AWS infrastructure. Exam essential: Five categories of recommendations - cost optimization, security, fault tolerance, performance, and service limits.

**AWS Well-Architected Tool** - Service for reviewing workloads against AWS architecture best practices. Know for exam: Helps implement the Well-Architected Framework pillars in your applications.

## Migration & Transfer

**AWS Application Discovery Service** - Service that helps plan migration by discovering on-premises applications and dependencies. Exam context: First step in migration planning to understand current infrastructure.

**AWS Application Migration Service** - Service for migrating applications to AWS with minimal downtime. Know for exam: Lift-and-shift migrations from on-premises or other clouds to AWS.

**AWS Database Migration Service** - Managed service for migrating databases to AWS with minimal downtime. Exam tip: Supports homogeneous and heterogeneous database migrations, including ongoing replication.

**Migration Evaluator** - Service that creates business cases for cloud migration based on current infrastructure. Exam context: Cost analysis and planning tool for migration decision-making.

**AWS Migration Hub** - Central location to track progress of application migrations across multiple AWS tools. Know for exam: Single pane of glass for monitoring migration projects.

**AWS Schema Conversion Tool** - Tool for converting database schemas from one engine to another. Exam focus: Part of database migration process when changing database engines.

**AWS Snow Family** - Physical devices for transferring large amounts of data to and from AWS. Exam essential: Snowcone (8TB), Snowball Edge (up to 80TB), Snowmobile (up to 100PB) for different data transfer volumes.

## Networking & Content Delivery

**Amazon API Gateway** - (Serverless) Managed service for creating, deploying, and managing APIs. Exam tip: Acts as front door for applications, handles authentication, throttling, and monitoring.

**Amazon CloudFront** - (Serverless) Global content delivery network (CDN) for fast content delivery. Exam essential: Caches content at edge locations worldwide for improved performance and reduced latency.

**AWS Direct Connect** - Dedicated network connection between your premises and AWS. Know for exam: Consistent network performance, reduced bandwidth costs, and enhanced security.

**AWS Global Accelerator** - (Serverless) Service that improves global application performance using AWS global network. Exam context: Better than CloudFront for non-HTTP traffic and real-time applications.

**AWS PrivateLink** - Service for accessing AWS services privately without internet gateway. Exam tip: Secure, private connectivity between VPCs and AWS services or third-party services.

**Amazon Route 53** - (Serverless) Scalable DNS web service for domain registration and routing. Exam essential: DNS service with health checks and various routing policies for high availability.

**AWS Transit Gateway** - Service that connects VPCs and on-premises networks through a central hub. Know for exam: Simplifies network architecture by avoiding complex VPC peering relationships.

**Amazon VPC** - Virtual private cloud for launching AWS resources in an isolated network. Exam fundamental: Foundation of AWS networking, includes subnets, security groups, and NACLs.

**AWS VPN** - Secure connection between your network and AWS VPCs. Exam context: Two types - Site-to-Site VPN for office connections and Client VPN for individual user access.

## Security, Identity, & Compliance

**AWS Artifact** - (Serverless) Portal for accessing AWS compliance documentation and agreements. Exam tip: Download SOC reports, PCI documents, and other compliance certifications.

**AWS Audit Manager** - Service for automating audit preparation and compliance monitoring. Know for exam: Simplifies compliance audits by collecting evidence automatically.

**AWS Certificate Manager** - (Serverless) Service for provisioning and managing SSL/TLS certificates. Exam context: Free certificates for AWS services, automatic renewal, and simplified certificate management.

**AWS CloudHSM** - Cloud-based hardware security modules for key management. Exam focus: Dedicated hardware for cryptographic operations when regulatory compliance requires it.

**Amazon Cognito** - (Serverless) Service for user authentication and authorization in web and mobile apps. Exam tip: User pools for authentication, identity pools for authorization, supports social identity providers.

**Amazon Detective** - Service that analyzes and visualizes security data to investigate potential issues. Know for exam: Uses machine learning to identify root causes of security findings.

**AWS Directory Service** - Managed Microsoft Active Directory service in the AWS cloud. Exam context: When scenarios involve existing on-premises Active Directory integration.

**AWS Firewall Manager** - Service for centrally configuring and managing firewall rules across accounts. Exam tip: Simplifies security management across multiple accounts and applications.

**Amazon GuardDuty** - (Serverless) Intelligent threat detection service using machine learning. Exam essential: Continuous security monitoring, detects malicious activity and unauthorized behavior.

**AWS IAM** - Identity and Access Management for controlling access to AWS services and resources. Exam fundamental: Users, groups, roles, policies - the foundation of AWS security.

**AWS IAM Identity Center** - Centralized access management for multiple AWS accounts and applications. Know for exam: Single sign-on (SSO) and centralized permission management across AWS Organizations.

**Amazon Inspector** - Automated security assessment service for applications and infrastructure. Exam context: Vulnerability assessments, security testing, and compliance checking.

**AWS KMS** - (Serverless) Key Management Service for creating and managing encryption keys. Exam essential: Customer-managed keys (CMK), envelope encryption, and integration with other AWS services.

**Amazon Macie** - (Serverless) Data security service that uses machine learning to discover and protect sensitive data. Exam tip: Automatically classifies and protects sensitive data like PII (personal information) in S3.

**AWS RAM** - Resource Access Manager for sharing AWS resources across accounts. Know for exam: Simplifies resource sharing in multi-account environments.

**AWS Secrets Manager** - (Serverless) Service for storing and managing sensitive information like passwords and API keys. Exam context: Automatic rotation of secrets and secure storage of credentials.

**AWS Security Hub** - Centralized security findings management across AWS security services. Exam tip: Single dashboard for security posture, integrates with various AWS and third-party security tools.

**AWS Shield** - (Serverless) DDoS protection service for AWS applications. Exam essential: Shield Standard (free, basic protection) vs Shield Advanced (paid, enhanced protection with 24/7 support).

**AWS WAF** - (Serverless) Web Application Firewall for protecting web applications from common attacks. Know for exam: Protects against SQL injection, XSS, and other web-based attacks.

## Storage Services

**AWS Backup** - (Serverless) Centralized backup service for AWS resources with automated backup policies. Exam tip: Cross-region backup, compliance, and centralized backup management across services.

**Amazon EBS** - Hard drives. Elastic Block Store provides persistent block storage for EC2 instances. Exam essential: Different volume types (gp3, io2, etc.), snapshots, and encryption options.

**Amazon EFS** - (Serverless) Fully managed NFS (shared directories) file system for EC2 instances with automatic scaling. Know for exam: Shared storage across multiple EC2 instances, scales automatically. Focused on Linux.

**AWS Elastic Disaster Recovery** - Service for quickly recovering physical, virtual, and cloud servers. Exam context: Disaster recovery solution with continuous data protection and fast recovery.

**Amazon FSx** - Fully managed file systems optimized for specific use cases (Windows, Lustre, NetApp, OpenZFS). Exam tip: High-performance file systems for specialized workloads and applications. Popular on Windows.

**Amazon S3** - (Serverless) Object storage service for storing and retrieving any amount of data. Exam fundamental: Understand storage classes, lifecycle policies, versioning, and use cases.

**S3 Glacier** - (Serverless) Long-term archival storage with retrieval options ranging from minutes to hours. Know for exam: Different retrieval speeds and costs - Instant, Flexible, and Deep Archive.

**AWS Storage Gateway** - Hybrid cloud storage service connecting on-premises to AWS storage. Exam context: Three types - File, Volume, and Tape Gateway for different hybrid storage needs.

## Support

**AWS Support** - Technical support service with different plans (Basic, Developer, Business, Enterprise). Exam essential: Understand what's included in each support plan, response times, and when to recommend each tier.

