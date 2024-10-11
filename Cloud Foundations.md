![alt text](image-20.png)
# AWS Cloud Foundations Part 1 Fact-Finding Exercise 🌐☁️

Recall what you have learned, and answer the following questions:

---

### 1. **What are IaaS, PaaS, and SaaS?** 
- **IaaS (Infrastructure as a Service)**: 🖥️ Provides virtualized computing resources like servers, storage, and networking. Users manage the operating system, applications, and data. AWS EC2 is an example of IaaS.
  
- **PaaS (Platform as a Service)**: 💻 Offers a platform that allows users to develop, run, and manage applications without dealing with infrastructure complexities. AWS Elastic Beanstalk is an example of PaaS.
  
- **SaaS (Software as a Service)**: 📲 Delivers fully functional software applications over the internet, with the provider managing the infrastructure. Users just use the software. Examples include services like Google Workspace or AWS WorkMail.

---

### 2. **What are the advantages of cloud computing?** ☁️✨
- **Scalability**: 📈 Resources can be scaled up or down based on demand.
- **Cost Efficiency**: 💰 Pay only for what you use, reducing costs.
- **Reliability**: 🔄 Cloud providers offer high availability with redundancy across multiple data centers.
- **Global Reach**: 🌍 Cloud providers have a global network of data centers, allowing for low-latency services.
- **Security**: 🔐 Advanced security features such as encryption, firewalls, and compliance certifications.
- **Automatic Updates**: 🔄 Infrastructure and software updates are managed by the provider.

---

### 3. **What is an AWS Region?** 🌍
An **AWS Region** is a geographical area where AWS has multiple data centers or Availability Zones. Each region is isolated from other regions to provide greater fault tolerance and reduce latency. AWS customers can choose regions based on proximity, legal requirements, and compliance needs.

---

### 4. **What is an Availability Zone?** 🏢
An **Availability Zone (AZ)** is a discrete data center within an AWS Region, with independent power, cooling, and networking. Regions usually have multiple Availability Zones, which are connected by low-latency links. This allows users to run fault-tolerant applications with high availability by distributing resources across AZs.

---

### 5. **What are all the AWS Regions?** 🗺️

As of 2024, AWS has 31 launched regions with plans for additional ones. Some key AWS regions include:

#### **North America:**
- 🇺🇸 US East (N. Virginia, Ohio)  
- 🇺🇸 US West (Oregon, N. California)  
- 🇨🇦 Canada (Central)

#### **Europe:**
- 🇮🇪 Ireland  
- 🇬🇧 London  
- 🇩🇪 Frankfurt  
- 🇫🇷 Paris  
- 🇸🇪 Stockholm  
- 🇮🇹 Milan

#### **Asia Pacific:**
- 🇯🇵 Tokyo  
- 🇰🇷 Seoul  
- 🇸🇬 Singapore  
- 🇮🇳 Mumbai  
- 🇦🇺 Sydney

#### **South America:**
- 🇧🇷 South America (São Paulo)

#### **Middle East & Africa:**
- 🇧🇭 Middle East (Bahrain, UAE)  
- 🇿🇦 Africa (Cape Town)

---

### 6. **What are the categories in which the AWS services are grouped?** 🛠️
AWS services are grouped into several categories, including:
- **Compute**: 🖥️ EC2, Lambda  
- **Storage**: 📦 S3, EBS  
- **Databases**: 📊 RDS, DynamoDB  
- **Networking & Content Delivery**: 🌐 VPC, CloudFront  
- **Security, Identity, & Compliance**: 🔐 IAM, Shield  
- **Analytics**: 📈 Redshift, Athena  
- **Machine Learning**: 🤖 SageMaker, Lex  
- **Developer Tools**: 💻 CodeBuild, CodeDeploy  
- **Management & Governance**: 📋 CloudWatch, CloudTrail

---

### 7. **What is the difference between object storage and block storage?** 🗄️
- **Object Storage**: 📂 Stores data as objects (files) with metadata. Ideal for storing large amounts of unstructured data, like photos, videos, and backups. AWS S3 is an example of object storage.

- **Block Storage**: 🗃️ Divides data into fixed-sized blocks and stores them individually. It is used for databases or applications where low-latency access is needed. AWS EBS is an example of block storage.

---

### 8. **What are two AWS compute services, and what do these services do?** ⚙️
- **EC2 (Elastic Compute Cloud)**: 🖥️ Provides resizable virtual machines (instances) for running applications in the cloud.
  
- **Lambda**: ⚡ A serverless compute service that lets users run code in response to events without provisioning or managing servers.

---

### 9. **What are two AWS storage services, and what do these services do?** 📦
- **S3 (Simple Storage Service)**: 🗄️ A scalable object storage service for storing and retrieving any amount of data. Commonly used for data backup, media storage, and static website hosting.
  
- **EBS (Elastic Block Store)**: 📂 Provides persistent block storage for use with EC2 instances. Ideal for databases and applications that require high-performance storage.

--- 

🌐☁️ **AWS Cloud computing offers a flexible, scalable, and efficient environment for modern applications!**


**Presented by: Osita, Benjamin, Obi, Henry, Arvin, Ola and Jude**