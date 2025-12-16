# AWS Practitioner Concepts

## Cloud Fundamentals

### **Cloud Value**
Understanding the **business benefits** of moving to the cloud: **reduced costs**, **increased agility**, **global scalability**, and **innovation acceleration**. (To be totally honest, reduce costs is mostly marketing)

### **Shared Responsibility Model**
AWS manages **infrastructure security** (physical, network, hypervisor) while customers handle **security in the cloud** (data, applications, OS, network configuration).

### **Well-Architected Framework**
Six pillars for building **reliable**, **secure**, **efficient** systems: **Operational Excellence**, **Security**, **Reliability**, **Performance Efficiency**, **Cost Optimization**, and **Sustainability**.

#### **Operational Excellence**
Ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures.

#### **Security**
Ability to protect data, systems, and assets to take advantage of cloud technologies to improve your security.

#### **Reliability**
Ability of a workload to perform its intended function correctly and consistently when it's expected to.

#### **Performance Efficiency**
Ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.

#### **Cost Optimization**
Ability to run systems to deliver business value at the lowest price point.

#### **Sustainability**
Ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload.


### **Deployment Models**
**Public cloud** (multi-tenant), **private cloud** (dedicated), **hybrid cloud** (combination), and **on-premises** infrastructure options.

### **Cloud Economics**
Understanding **CapEx vs OpEx**, **economies of scale**, **pay-as-you-go** pricing, and **total cost of ownership** (TCO) benefits (which are in part marketing).

## Cloud Migration & Adoption

### **Cloud Migration**
Strategies for moving workloads: **rehost** (lift-and-shift), **replatform**, **refactor**, **retire**, **retain**, and **repurchase**.

### **Cloud Adoption Framework (CAF)**
AWS methodology with six **perspectives** and four **phases** for successful cloud transformation. **Perspectives** represent different organizational capabilities and stakeholder groups, while **phases** represent the progression of cloud adoption maturity. Each perspective must be addressed **across all phases**, with specific focus areas evolving as organizations mature 

#### **CAF Perspectives**
Organizational capabilities that need to be addressed during cloud adoption:

##### **Business Perspective**
Ensures cloud investments accelerate business outcomes. Focuses on **business value**, **ROI measurement**, **risk management**, and **stakeholder alignment**.

##### **People Perspective**
Addresses organizational change management, training, and skills development. Covers **workforce transformation**, **change management**, and **culture evolution**.

##### **Governance Perspective**
Establishes frameworks for managing cloud environments. Includes **portfolio management**, **program management office**, **business metrics**, and **license management**.

##### **Platform Perspective**
Focuses on technical architecture and implementation. Covers **infrastructure architecture**, **application architecture**, **data architecture**, and **provisioning**.

##### **Security Perspective**
Ensures confidentiality, integrity, and availability of data and workloads. Addresses **identity management**, **detective controls**, **infrastructure protection**, and **incident response**.

##### **Operations Perspective**
Manages cloud services to business standards. Includes **observability**, **event management**, **incident management**, and **change management**.

#### **CAF Phases**
Progressive stages of cloud adoption maturity:

##### **Envision Phase**
Demonstrates business value and establishes transformation strategy through **stakeholder alignment** and **business case development**.

##### **Align Phase**
Identifies capability gaps and cross-organizational dependencies to create comprehensive **action plans** and **skills development**.

##### **Launch Phase**
Delivers pilot initiatives in production to demonstrate **incremental business value** and **validate transformation approach**.

##### **Scale Phase**
Expands pilot initiatives to achieve **desired business outcomes** and **organization-wide transformation**.

### **Migration Tools & Methods**
**AWS Migration Hub**, **Database Migration Service**, and various **assessment tools** for planning and executing migrations.

## Security & Compliance

### **Security Best Practices**
Implementing **defense in depth**, **least privilege access**, **data encryption**, and **continuous monitoring** across AWS services.

### **Identity Management**
**AWS IAM** for user and resource access control, **multi-factor authentication** (MFA), **role-based access**, and **federated identity**.

### **Authentication Methods**
**Username/password**, **access keys**, **temporary credentials**, **SAML**, **OpenID Connect**, and **AWS SSO** integration.

### **Credential Storage**
Secure storage using **AWS Secrets Manager**, **Systems Manager Parameter Store**, and **IAM roles** instead of hardcoded credentials.

### **Root User Protection**
Securing the **root account** with **strong passwords**, **MFA**, **limited use**, and **access key deletion**.

### **Encryption Options**
**Encryption at rest** and **in transit** using **AWS KMS**, **CloudHSM**, **SSL/TLS**, and service-specific encryption features.

### **Compliance & Governance**
Meeting **regulatory requirements** through **AWS compliance programs**, **audit trails**, **data residency**, and **governance frameworks**.

### **Logging & Monitoring**
**CloudTrail** for API logging, **CloudWatch** for metrics and monitoring, and **Config** for configuration compliance.

## Architecture & Availability

### **High Availability**
Designing systems across **multiple Availability Zones** with **redundancy**, **failover mechanisms**, and **load balancing**.

### **Disaster Recovery**
**RTO/RPO** planning using **backup strategies**, **cross-region replication**, and **automated recovery** solutions.

### **Business Continuity**
Ensuring **uninterrupted operations** through **fault tolerance**, **backup systems**, and **incident response** planning.

### **Elasticity & Agility**
**Auto-scaling** capabilities to handle **variable demand**, **rapid provisioning**, and **resource optimization**.

### **Load Balancing**
Distributing traffic across **multiple instances** using **Application Load Balancer**, **Network Load Balancer**, and **Classic Load Balancer**.

### **Auto Scaling**
**Horizontal scaling** based on **demand patterns**, **metrics-based scaling**, and **predictive scaling** capabilities.

## Infrastructure & Provisioning

### **Provisioning Methods**
**AWS Console**, **CLI**, **SDKs**, **CloudFormation**, **CDK**, and **third-party tools** for resource deployment.

### **Infrastructure as Code**
**CloudFormation** templates, **AWS CDK**, and **Terraform** for **version-controlled**, **repeatable** infrastructure deployment.

### **Automation Benefits**
**Reduced human error**, **consistent deployments**, **faster provisioning**, and **cost optimization** through automation.

## Networking & Connectivity

### **Network Security**
**VPC** design, **security groups**, **NACLs**, **WAF**, **Shield**, and **network segmentation** best practices.

### **Connectivity Options**
**VPN**, **Direct Connect**, **Transit Gateway**, **VPC Peering**, and **PrivateLink** for secure connectivity.

### **Data Sovereignty**
Understanding **data location**, **regional compliance**, **cross-border data transfer** regulations, and **local data residency** requirements.

## Storage & Backup

### **Storage Classes**
**S3 storage tiers** (Standard, IA, Glacier, Deep Archive), **EBS volume types**, and **EFS** for different **performance** and **cost** requirements.

### **Lifecycle Policies**
Automated **data transition** between storage classes based on **access patterns** and **retention requirements**.

### **Backup Use Cases**
**Point-in-time recovery**, **cross-region backup**, **automated backup schedules**, and **disaster recovery** scenarios.

### **Intelligent Tiering**
**S3 Intelligent Tiering** automatically moves objects between **frequent** and **infrequent access tiers** based on **usage patterns** to optimize costs without performance impact.


## Cost Management

### **Cost Optimization**
**Rightsizing instances**, **reserved instances**, **spot instances**, **storage optimization**, and **resource scheduling**.

### **Fixed vs Variable Costs**
Understanding **on-demand** vs **reserved** pricing, **committed use discounts**, and **variable cost** benefits.

### **Rightsizing**
Matching **instance types** and **sizes** to actual **workload requirements** for optimal **price-performance** ratio.

### **Pricing Models**
**On-demand**, **reserved instances**, **spot instances**, **savings plans**, and **dedicated hosts** pricing options.

### **Storage Tiers & Costs**
Understanding **storage pricing** across different **S3 classes**, **retrieval costs**, and **data transfer charges**.

### **Data Transfer Costs**
**Inbound** (usually free), **outbound pricing**, **inter-region transfer**, and **CDN** cost optimization strategies.

### **Cost Allocation Tags**
**Resource tagging** for **cost tracking**, **department billing**, **project allocation**, and **budget management**.

## Support & Monitoring

### **Billing Support**
**Cost Explorer**, **budgets and alerts**, **billing reports**, and **cost anomaly detection** tools.

### **Support Plans**
**Basic** (free), **Developer**, **Business**, **Enterprise** support with different **response times** and **coverage levels**.

### **AWS Partner Network**
**Consulting partners**, **technology partners**, **solution providers**, and **training partners** for specialized expertise.

### **Trusted Advisor**
**Best practice recommendations** for **cost optimization**, **security**, **fault tolerance**, **performance**, and **service limits**.

### **Health Dashboard**
**Service health monitoring**, **personal health notifications**, and **scheduled maintenance** information.

### **Abuse Reporting**
Process for reporting **security incidents**, **suspicious activity**, and **policy violations** to AWS.

### **Technical Assistance**
**Documentation**, **forums**, **support cases**, **architectural guidance**, and **troubleshooting** resources.

## Services by Function

### **AI/ML Tasks**
**SageMaker** for machine learning, **Rekognition** for image analysis, **Comprehend** for text analysis, and **Lex** for chatbots.

### **Analytics Tasks**
**Redshift** for data warehousing, **EMR** for big data processing, **Kinesis** for real-time streaming, and **QuickSight** for visualization.

### **Application Integration**
**SQS** for messaging, **SNS** for notifications, **Step Functions** for workflows, and **EventBridge** for event routing.

### **Business Applications**
**WorkMail** for email, **Chime** for communications, **WorkDocs** for collaboration, and **Connect** for contact centers.

### **Developer Tools**
**CodeCommit**, **CodeBuild**, **CodeDeploy**, **CodePipeline** for **CI/CD**, and **Cloud9** for development environments.

### **End User Computing**
**WorkSpaces** for virtual desktops, **AppStream** for application streaming, and **WorkLink** for secure mobile access.

### **Frontend Services**
**CloudFront** for content delivery, **Route 53** for DNS, **API Gateway** for APIs, and **Amplify** for web applications.

### **IoT Management**
**IoT Core** for device connectivity, **IoT Device Management**, **IoT Analytics**, and **IoT Greengrass** for edge computing.
