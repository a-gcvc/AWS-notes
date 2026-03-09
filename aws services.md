## ANALYTICS

- **Amazon Athena** is an interactive query service that makes it easy to analyze data in **Amazon S3 using standard SQL**. Athena is **serverless**, so there is no infrastructure to manage, and you pay only for the queries that you run.

- **Amazon EMR** is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto. Amazon EMR makes it easy to set up, operate, and scale your big data environments by automating time-consuming tasks such as provisioning capacity and tuning clusters.

- **Amazon Kinesis** makes it easy to collect, process, and analyze **real-time, streaming data** so you can get timely insights and react quickly to new information.

- **Amazon Data Firehose** is the easiest way to reliably **load streaming data** into data stores and analytics tools. It can capture, transform, and load streaming data into Amazon S3, Amazon Redshift, Amazon OpenSearch Service, and Splunk, enabling near real-time analytics with existing business intelligence tools and dashboards you’re already using today.

- **Amazon Kinesis Data Streams** is a massively scalable and durable **real-time data streaming service**. Kinesis Data Streams can continuously capture gigabytes of data per second from hundreds of thousands of sources such as website clickstreams, database event streams, financial transactions, social media feeds, IT logs, and location-tracking events.

- **Amazon Kinesis Video Streams** makes it easy to securely stream video from connected devices to AWS for analytics, ML, playback, and other processing. Kinesis Video Streams **automatically provisions and elastically scales** all the infrastructure needed to ingest streaming video data from millions of devices. It also durably stores, encrypts, and indexes video data in your streams, and allows you to access your data through easy-to-use APIs.

- **Amazon Redshift** is the most widely used cloud data warehouse. It makes it fast, simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools. 

- **AWS Data Exchange** makes it easy to find, subscribe to, and use third-party data in the cloud. Once subscribed to a data product, you can use the AWS Data Exchange API to load data directly into Amazon S3 and then analyze it with a wide variety of AWS analytics and ML services.

- **AWS Data Pipeline** is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at speciﬁed intervals. 

- **AWS Glue** is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics.

- **AWS Lake Formation** is a service that makes it easy to **set up a secure data lake in days**. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis. A data lake enables you to break down data silos and combine different types of analytics to gain insights and guide better business decisions.
--------------------------

## APPLICATION INTEGRATION

- **AWS Step Functions** is a fully managed service that makes it easy to coordinate the components of distributed applications and microservices using visual workflows. Step Functions is a reliable way to coordinate components and step through the functions of your application. Step Functions provides a graphical console to arrange and visualize the components of your application as a series of steps.

- **Amazon AppFlow** is a fully managed integration service that enables you to securely transfer data between Software-as-a-Service (SaaS) applications such as Salesforce, Zendesk, Slack, and ServiceNow, and AWS services such as Amazon S3 and Amazon Redshift, in just a few clicks.

- **Amazon EventBridge** is a serverless event bus that makes it easier to build event-driven applications at scale using events generated from your applications, integrated Software-as-a-Service (SaaS) applications, and AWS services.

- **Amazon MQ** is a managed message broker service for **Apache ActiveMQ Classic and RabbitMQ** that makes it easy to set up and operate message brokers in the cloud. Message brokers allow different software systems–often using different programming languages, and on different platforms–to communicate and exchange information.

- **Amazon Simple Notification Service (Amazon SNS)** is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.

- **Amazon Simple Queue Service (Amazon SQS)** is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates the complexity and overhead associated with managing and operating message oriented middleware, and empowers developers to focus on differentiating work.
Amazon SQS offers two types of message queues. Standard queues offer maximum throughput, best-effort ordering, and at-least-once delivery. Amazon SQS FIFO queues are designed to guarantee that messages are processed exactly once, in the exact order that they are sent.
------------------

## BUSINESS APPLICATIONS

- **Amazon Pinpoint** makes it easy to send targeted messages to your customers through multiple engagement channels. You can integrate Amazon Pinpoint into your mobile and web apps to capture usage data to provide you with insight into how customers interact with your apps. Amazon Pinpoint also tracks the ways that your customers respond to the messages you send—for example, by showing you the number of messages that were delivered, opened, or clicked.

- **Amazon WorkDocs** is a fully managed, secure enterprise storage and sharing service with strong administrative controls and feedback capabilities that improve user productivity.
Users can comment on files, send them to others for feedback, and upload new versions without having to resort to emailing multiple versions of their files as attachments.
----------------

## CLOUD FINANCIAL MANAGEMENT

- **AWS Cost Explorer** has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. 

- **AWS Budgets** gives you the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. Budgets can be tracked at the monthly, quarterly, or yearly level, and you can customize the start and end dates.

- **Savings Plans** is a flexible pricing model offering lower prices compared to On-Demand pricing, in exchange for a specific usage commitment (measured in $/hour) **for a one or three-year period**. Compute Savings Plans apply to usage across **Amazon EC2, AWS Lambda, and AWS Fargate**.
----------------

## COMPUTE

- **Amazon Elastic Compute Cloud (Amazon EC2)** is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale computing easier for developers.

    - **On-Demand Instances** — With On-Demand Instances, you pay for compute capacity by the hour or the second depending on which instances you run. No longer-term commitments or upfront payments are needed. You can increase or decrease your compute capacity depending on the demands of your application and only pay the specified per hourly rates for the instance you use. On-Demand Instances are recommended for:

        Users that prefer the low cost and flexibility of Amazon EC2 without any up-front payment or long-term commitment

        Applications with short-term, spiky, or unpredictable workloads that cannot be interrupted

        Applications being developed or tested on Amazon EC2 for the first time

    - **Spot Instances** —Spot Instances are available at up to a 90% discount compared to On-Demand prices and let you take advantage of unused Amazon EC2 capacity in the AWS Cloud. You can significantly reduce the cost of running your applications, grow your application’s compute capacity and throughput for the same budget, and enable new types of cloud computing applications. Spot Instances are recommended for:

        Applications that have flexible start and end times

        Applications that are only feasible at very low compute prices

        Users with urgent computing needs for large amounts of additional capacity

    - **Reserved Instances** — Reserved Instances provide you with a significant discount (up to 72%) compared to On-Demand Instance pricing. You have the flexibility to change families, operating system types, and tenancies while benefiting from Reserved Instance pricing when you use Convertible Reserved Instances.

    - **Savings Plans** — Savings Plans are a flexible pricing model that offer low prices on EC2 and Fargate usage, in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a one or three year term.

    - **Dedicated Hosts** — A Dedicated Host is a physical EC2 server dedicated for your use. Dedicated Hosts can help you reduce costs by allowing you to use your existing server-bound software licenses, including Windows Server, Microsoft SQL Server, and SUSE Linux Enterprise Server (subject to your license terms), and can also help you meet compliance requirements.

- **Amazon EC2 Auto Scaling** helps you maintain application availability and allows you to automatically add or remove EC2 instances according to conditions you define. You can use the fleet management features of Amazon EC2 Auto Scaling to maintain the health and availability of your fleet.

- **Amazon Lightsail** is designed to be the easiest way to launch and manage a virtual private server with AWS. Lightsail plans include everything you need to jumpstart your project – a VM, SSD-based storage, data transfer, DNS management, and a static IP address – for a low, predictable price.

- **AWS Batch** enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (such as CPU or memory-optimized instances) based on the volume and specific resource requirements of the batch jobs submitted.

- **AWS Elastic Beanstalk** is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and Internet Information Services (IIS).

You can simply upload your code, and AWS Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, and auto scaling to application health monitoring.

- **AWS Fargate** is a compute engine for Amazon ECS that allows you to run containers without having to manage servers or clusters. With AWS Fargate, you no longer have to provision, configure, and scale clusters of VMs to run containers. 

- **AWS Lambda** lets you run code without provisioning or managing servers. You pay only for the compute time you consume—there is no charge when your code is not running.

- **AWS Outposts** bring native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility. You can use the same APIs, the same tools, the same hardware, and the same functionality across on-premises and the cloud to deliver a truly consistent hybrid experience. Outposts can be used to support workloads that need to remain on-premises due to low latency or local data processing needs.

- **AWS Wavelength** is an AWS Infrastructure offering optimized for mobile edge computing applications. Wavelength Zones are AWS infrastructure deployments that embed AWS compute and storage services within communications service providers’ (CSP) datacenters at the edge of the 5G network, so application traffic from 5G devices can reach application servers running in Wavelength Zones without leaving the telecommunications network. 
------------------

## CONTAINERS

- **Amazon Elastic Container Registry (Amazon ECR)** is a fully managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images. Amazon ECR is integrated with Amazon Elastic Container Service (Amazon ECS), simplifying your development to production workﬂow.

- **Amazon Elastic Container Service (Amazon ECS)** is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines (VMs), or schedule containers on those VMs.

- **Amazon Elastic Kubernetes Service (Amazon EKS)** makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS. Amazon EKS runs the Kubernetes management infrastructure for you across multiple AWS Availability Zones to eliminate a single point of failure.
----------------

## DATABASES

- **Amazon Aurora** is a **MySQL and PostgreSQL** compatible **relational database** engine that combines the speed and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases.

- **Amazon DynamoDB** is a **key-value** and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-Region database with built-in security, backup and restore, and in-memory caching for internet-scale applications.

- **Amazon ElastiCache** is a web service that makes it easy to deploy, operate, and scale an in-memory cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.

ElastiCache supports two open-source in-memory caching engines:

    Redis — a fast, open-source, in-memory key-value data store for use as a database, cache, message broker, and queue

    Memcached — a widely adopted memory object caching system

Amazon ElastiCache Serverless is a serverless option for Amazon ElastiCache that simplifies cache management and instantly scales to support the most demanding applications.

- **Amazon MemoryDB** is a Redis-compatible, durable, in-memory database service that delivers ultra-fast performance. It is purpose-built for modern applications with microservices architectures.

- **Amazon Neptune** is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

- **Amazon Relational Database Service (Amazon RDS)** makes it easy to set up, operate, and scale a relational database in the cloud. 
Amazon RDS is available on several database instance types—optimized for memory, performance or I/O—and provides you with six familiar database engines to choose from, including **MySQL, MariaDB, PostgreSQL, Oracle Database, Microsoft SQL Server, and Amazon RDS on AWS Outposts**. You can use the AWS Database Migration Service to easily migrate or replicate your existing databases to Amazon RDS.

- **Amazon Timestream** is a fast, scalable, fully managed time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day at 1/10th the cost of relational databases.

- **Amazon DocumentDB (with MongoDB compatibility)** is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads.
-----------------

## DEVELOPER TOOLS

- **AWS CloudShell** is a browser-based shell that makes it easy to securely manage, explore, and interact with your AWS resources. CloudShell is pre-authenticated with your console credentials.

- **AWS CodeArtifact** is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process.

- **AWS CodePipeline** is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. 

- **Amazon Q Developer** (formerly Amazon CodeWhisperer) assists developers and IT professionals with their tasks—from coding, testing, and upgrading applications, to diagnosing errors, performing security scanning and fixes, and optimizing AWS resources.

- **AWS X-Ray** helps developers analyze and debug distributed applications in production or under development, such as those built using a microservices architecture. X-Ray, you can understand how your application and its underlying services are performing so you can identify and troubleshoot the root cause of performance issues and errors.
--------------

## FRONTEND WEB AND MOBILE SERVICES

- **AWS Amplify** makes it easy to create, configure, and implement scalable mobile applications powered by AWS. Amplify seamlessly provisions and manages your mobile backend and provides a simple framework to easily integrate your backend with your iOS, Android, Web, and React Native frontends. Amplify also automates the application release process of both your front-end and back-end allowing you to deliver features faster.

- **AWS AppSync** makes it easy to build data driven mobile and web applications by handling securely all the application data management tasks such as online and offline data access, data synchronization, and data manipulation across multiple data sources. AWS AppSync uses GraphQL, an API query language designed to build client applications by providing an intuitive and flexible syntax for describing their data requirement.
-----------------

## ML and AI

- **Amazon CodeGuru** is a developer tool that provides intelligent recommendations to improve code quality and identify an application’s most expensive lines of code.

- **Amazon Comprehend** uses ML and natural language processing (NLP) to help you uncover the insights and relationships in your unstructured data. The service identifies the language of the text; extracts key phrases, places, people, brands, or events; understands how positive or negative the text is; analyzes text using tokenization and parts of speech; and automatically organizes a collection of text files by topic.

- **Amazon Fraud Detector** is a fully managed service that uses ML and more than 20 years of fraud detection expertise from Amazon, to identify potentially fraudulent activity so customers can catch more online fraud faster.

- **Amazon Comprehend Medical** is a HIPAA-eligible natural language processing (NLP) service that uses machine learning that has been pre-trained to understand and extract health data from medical text, such as prescriptions, procedures, or diagnoses.

- **Amazon Kendra** is an intelligent search service powered by ML. Amazon Kendra reimagines enterprise search for your websites and applications so your employees and customers can easily find the content they are looking for, even when it’s scattered across multiple locations and content repositories within your organization.

- **Amazon Lex** is a fully managed artificial intelligence (AI) service to design, build, test, and deploy conversational interfaces into any application using voice and text. Amazon Lex enables developers to build conversational chatbots quickly. 

- **Amazon Polly** is a service that turns text into lifelike speech. Amazon Polly lets you create applications that talk, enabling you to build entirely new categories of speech-enabled products.

- **Amazon Rekognition** makes it easy to add image and video analysis to your applications using proven, highly scalable, deep learning technology that requires no ML expertise to use. With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content.

- With **Amazon SageMaker AI**, you can build, train, and deploy ML models for any use case with fully managed infrastructure, tools, and workflows. SageMaker AI removes the heavy lifting from each step of the ML process to make it easier to develop high-quality models.

- **Amazon Textract** is a service that automatically extracts text and data from scanned documents. Amazon Textract goes beyond simple optical character recognition (OCR) to also identify the contents of fields in forms and information stored in tables.

- **Amazon Transcribe** is an automatic speech recognition (ASR) service that makes it easy for customers to automatically convert speech to text. The service can transcribe audio files stored in common formats, like WAV and MP3, with time stamps for every word so that you can easily locate the audio in the original source by searching for the text.

- **Amazon Translate** is a neural machine translation service that delivers fast, high-quality, and affordable language translation.
----------------

## MANAGEMENT AND GOVERNANCE

- **AWS Auto Scaling** monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas. 

- **AWS CloudFormation** gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.

- **AWS CloudTrail** is a web service that records AWS API calls for your account and delivers log files to you.

- **Amazon CloudWatch** is a monitoring and management service built for developers, system operators, site reliability engineers (SRE), and IT managers.

- **AWS Compute Optimizer** recommends optimal AWS resources for your workloads to reduce costs and improve performance by using machine learning to analyze historical utilization metrics.

- **AWS Control Tower** automates the set-up of a baseline environment, or landing zone, that is a secure, well-architected multi-account AWS environment. 

- **AWS Config** is a fully managed service that provides you with an AWS resource inventory, configuration history, and configuration change notifications to enable security and governance. The AWS Config Rules feature enables you to create rules that automatically check the configuration of AWS resources recorded by AWS Config.
With AWS Config, you can discover existing and deleted AWS resources, determine your overall compliance against rules, and dive into configuration details of a resource at any point in time. 

- **AWS License Manager** makes it easier to manage licenses in AWS and on-premises servers from software vendors such as Microsoft, SAP, Oracle, and IBM. AWS License Manager lets administrators create customized licensing rules that emulate the terms of their licensing agreements, and then enforces these rules when an instance of Amazon EC2 gets launched. 

- **Amazon Managed Grafana** is a fully managed and secure data visualization service that you can use to instantly query, correlate, and visualize operational metrics, logs, and traces from multiple sources. Amazon Managed Grafana makes it easy to deploy, operate, and scale Grafana, a widely deployed open-source data visualization tool that is popular for its extensible data support.

- **Amazon Managed Service for Prometheus** is a serverless, Prometheus-compatible monitoring service for container metrics that makes it easier to securely monitor container environments at scale. 

- **AWS Organizations** helps you centrally manage and govern your environment as you grow and scale your AWS resources. Using AWS Organizations, you can programmatically create new AWS accounts and allocate resources, group accounts to organize your workflows, apply policies to accounts or groups for governance, and simplify billing by using a single payment method for all of your accounts.

- **AWS Service Catalog** allows organizations to create and manage catalogs of IT services that are approved for use on AWS. Service Catalog allows you to centrally manage commonly deployed IT services and helps you achieve consistent governance and meet your compliance requirements, while enabling users to quickly deploy only the approved IT services they need.

- **AWS Trusted Advisor** is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices.

- The **AWS Well-Architected Tool (AWS WA Tool)** helps you review the state of your workloads and compares them to the latest AWS architectural best practices. A workload is defined as any set of components that deliver business value, which could be an application or website. The tool is based on the AWS Well-Architected Framework, developed to help cloud architects build secure, high-performing, resilient, efficient, and sustainable application infrastructure.
-----------------

## MIGRATION AND TRANSFER

- **AWS Application Discovery Service** helps enterprise customers plan migration projects by gathering information about their on-premises data centers.

- **AWS Application Migration Service (AWS MGN)** allows you to quickly realize the benefits of migrating applications to the cloud without changes and with minimal downtime.

- **AWS Database Migration Service (AWS DMS)** helps you migrate databases to AWS easily and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database.

- **AWS Migration Hub** provides a single location to track the progress of application migrations across multiple AWS and partner solutions. Using Migration Hub allows you to choose the AWS and partner migration tools that best fit your needs, while providing visibility into the status of migrations across your portfolio of applications.

- The **AWS Snow Family** helps customers that need to run operations in austere, non-data center environments, and in locations where there's lack of consistent network connectivity.

- **AWS Snowball** is the smallest member of the AWS Snow Family of edge computing, edge storage, and data transfer devices, weighing in at 4.5 pounds (2.1 kg) with 8 terabytes of usable storage.

- **AWS Snowball Edge** is an edge computing, data migration, and edge storage device. Snowball Edge can do local processing and run edge-computing workloads in addition to transferring data between your local environment and the AWS Cloud. Each Snowball Edge device can transport data at speeds faster than the internet.

- **AWS DataSync** is a data transfer service that makes it easy for you to automate moving data between on-premises storage and Amazon S3 or Amazon Elastic File System (Amazon EFS).

- **AWS Transfer Family** provides fully managed support for file transfers directly into and out of Amazon S3 or Amazon EFS. With support for Secure File Transfer Protocol (SFTP), File Transfer Protocol over SSL (FTPS), and File Transfer Protocol (FTP), the AWS Transfer Family helps you seamlessly migrate your file transfer workflows to AWS by integrating with existing authentication systems, and providing DNS routing with Amazon Route 53 so nothing changes for your customers and partners, or their applications. 

------------------
## NETWORKING AND CONTENT DELIVERY

- **Amazon API Gateway** is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

- **Amazon CloudFront** is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. CloudFront is integrated with AWS – both physical locations that are directly connected to the AWS global infrastructure, as well as other AWS services.

- **AWS Direct Connect** makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your data center, office, or co-location environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.

- **Elastic Load Balancing (ELB)** automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.

    - **Application Load Balancer** is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. Operating at the individual request level (Layer seven), Application Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) based on the content of the request.

    - **Network Load Balancer** is best suited for load balancing of TCP traffic where extreme performance is required. Operating at the connection level (Layer four), Network Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) and is capable of handling millions of requests per second while maintaining ultra-low latencies. Network Load Balancer is also optimized to handle sudden and volatile traffic patterns.

    - **Gateway Load Balancer** makes it easy to deploy, scale, and run third-party virtual networking appliances. Providing load balancing and auto scaling for fleets of third-party appliances, Gateway Load Balancer is transparent to the source and destination of traffic. This capability makes it well suited for working with third-party appliances for security, network analytics, and other use cases.

    - **Classic Load Balancer** provides basic load balancing across multiple Amazon EC2 instances and operates at both the request level and connection level. Classic Load Balancer is intended for applications that were built within the EC2-Classic network. EC2-Classic was retired on August 15, 2022.

- **AWS Global Accelerator** is a networking service that improves the availability and performance of the applications that you offer to your global users.

- **Amazon Route 53** is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route users to internet applications by translating human-readable names.

- **AWS Transit Gateway** is a service that enables customers to connect their Amazon Virtual Private Clouds (VPCs) and their on-premises networks to a single gateway. With AWS Transit Gateway, you only have to create and manage a single connection from the central gateway in to each Amazon VPC, on-premises data center, or remote office across your network.

- **Amazon Virtual Private Cloud (Amazon VPC)** lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. You can use both IPv4 and IPv6 in your VPC for secure and easy access to resources and applications.

- **AWS Virtual Private Network (AWS VPN)** solutions establish secure connections between your on-premises networks, remote offices, client devices, and the AWS global network. AWS VPN is comprised of two services: AWS Site-to-Site VPN and AWS Client VPN. 
------------

## SECURITY, IDENTITY AND COMPLIANCE

- **Amazon Cognito** lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. Amazon Cognito enables you to save data locally on users’ devices, allowing your applications to work even when the devices are offline. You can then synchronize data across users’ devices so that their app experience remains consistent regardless of the device they use.

- **Amazon Detective** makes it easy to analyze, investigate, and quickly identify the root cause of potential security issues or suspicious activities. Amazon Detective automatically collects log data from your AWS resources and uses machine learning, statistical analysis, and graph theory to build a linked set of data that enables you to easily conduct faster and more efficient security investigations.

- **Amazon GuardDuty** is a threat detection service that continuously monitors for malicious activity and anomalous behavior to protect your AWS accounts, workloads, Kubernetes clusters, and data stored in Amazon Simple Storage Service (Amazon S3). The GuardDuty service monitors for activity such as unusual API calls, unauthorized deployments, and exfiltrated credentials that indicate a possible account reconnaissance or compromise.

- **Amazon Inspector** is a new automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure. 

- **Amazon Macie** is a fully managed data security and data privacy service that uses inventory evaluations, machine learning, and pattern matching to discover sensitive data and accessibility in your Amazon S3 environment. Using Macie, you can detect a large and growing list of sensitive data types for many countries and Regions, including multiple types of financial data, personal health information (PHI), and personally identifiable information (PII), as well as custom types.

- **AWS Artifact** is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS security and compliance reports and select online agreements. Reports available in AWS Artifact include our Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls. Agreements available in AWS Artifact include the Business Associate Addendum (BAA) and the Nondisclosure Agreement (NDA).

- **AWS Certificate Manager** is a service that lets you easily provision, manage, and deploy Secure Sockets Layer/Transport Layer Security (SSL/TLS) certiﬁcates for use with AWS services and your internal connected resources. 

- The **AWS CloudHSM** is a cloud-based hardware security module (HSM) that enables you to easily generate and use your own encryption keys on the AWS Cloud. With AWS CloudHSM, you can manage your own encryption keys using dedicated FIPS 140-2 Level 3 validated HSMs. 

- **AWS Firewall Manager** is a security management service which allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. 

- **AWS Identity and Access Management (IAM)** enables you to securely control access to AWS services and resources for your AWS users, groups, and roles.

- **AWS Network Firewall** is a managed service that makes it easy to deploy essential network protections for all of your Amazon Virtual Private Clouds (VPCs). The service can be setup with just a few clicks and scales automatically with your network traffic, so you don't have to worry about deploying and managing any infrastructure. 

- **AWS Resource Access Manager (AWS RAM)** helps you securely share your resources across AWS accounts, within your organization or organizational units (OUs) in AWS Organizations, and with IAM roles and IAM users for supported resource types. You can use AWS RAM to share transit gateways, subnets, AWS License Manager license configurations, Amazon Route 53 Resolver rules, and more resource types.

- **AWS Secrets Manager** helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. 

- **AWS Security Hub** is a cloud security posture management service that performs automated, continuous security best practice checks against your AWS resources.

- **AWS Shield** is a managed Distributed Denial of Service (DDoS) protection service that safeguards web applications running on AWS. AWS Shield provides you with always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage Support to benefit from DDoS protection.

- **AWS IAM Identity Center (SSO)** is a cloud SSO service that makes it easy to centrally manage SSO access to multiple AWS accounts and business applications. With just a few clicks, you can enable a highly available SSO service without the upfront investment and on-going maintenance costs of operating your own SSO infrastructure. 

- **AWS WAF** is a web application ﬁrewall that helps protect your web applications or APIs against common web exploits and bots that may affect availability, compromise security, or consume excessive resources. AWS WAF gives you control over how traffic reaches your applications by enabling you to create security rules that control bot traffic and block common attack patterns, such as SQL injection or cross-site scripting. You can also customize rules that filter out specific traffic patterns.
------------------

## STORAGE

- **AWS Backup** enables you to centralize and automate data protection across AWS services.

- **Amazon Elastic Block Store (Amazon EBS)** provides persistent block storage volumes for use with Amazon EC2 instances in the AWS Cloud. Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure, offering high availability and durability.

- **Amazon Elastic File System (Amazon EFS)** provides a simple, scalable, elastic file system for Linux-based workloads for use with AWS Cloud services and on-premises resources. It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, so your applications have the storage they need – when they need it.

- **Amazon File Cache** is a fully managed high-speed cache on AWS that makes it easier to process file data, regardless of where the data is stored. Amazon File Cache serves as temporary, high-performance storage for data in on-premises file systems, or in file systems or object stores on AWS.

- **Amazon FSx for Lustre** is a fully managed file system that is optimized for compute-intensive workloads, such as high performance computing, machine learning, and media data processing workflows. Amazon FSx for Lustre is seamlessly integrated with Amazon S3. 

- **Amazon FSx for NetApp ONTAP** offers the first complete, fully managed NetApp file system available in the cloud making it easy for you to migrate or extend existing applications to AWS without changing code or how you manage your data. Amazon FSx for NetApp ONTAP offers high-performance file storage that is broadly accessible from Linux, Windows, and macOS compute instances via the industry-standard NFS, SMB, and iSCSI protocols. With Amazon FSx for NetApp ONTAP, you get low-cost, fully elastic storage capacity with support for compression and deduplication to help you further reduce storage costs.

- **Amazon FSx for OpenZFS** is a fully managed file storage service that lets you launch, run, and scale fully managed file systems built on the open-source OpenZFS file system. Amazon FSx for OpenZFS makes it easy to migrate your on-premises file servers—without changing your applications or how you manage data—and build new high-performance, data-driven applications in the cloud.

- **Amazon Simple Storage Service (Amazon S3)** is an object storage service that offers industry-leading scalability, data availability, security, and performance. 
**Amazon S3 storage classes** are a range of storage classes that you can choose from based on the data access, resiliency, and cost requirements of your workloads.

The S3 storage classes include:

    - S3 Intelligent-Tiering for automatic cost savings for data with unknown or changing access patterns

    - S3 Standard for frequently accessed data

    - S3 Express One Zone for your most frequently accessed data

    - S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for less frequently accessed data

    - S3 Glacier Instant Retrieval for archive data that needs immediate access

    - S3 Glacier Flexible Retrieval (formerly Amazon Glacier) for rarely accessed long-term data that does not require immediate access

    - Amazon Glacier Deep Archive (Amazon Glacier Deep Archive) for long-term archive and digital preservation with retrieval in hours at the lowest cost storage in the cloud

If you have data residency requirements that can’t be met by an existing AWS Region, you can use the **S3 Outposts** storage class to store your S3 data on premises. 

You can use **S3 Object Lock** to help prevent S3 objects from being deleted or overwritten for a fixed amount of time, or indefinitely. Object Lock can help you to meet regulatory requirements that require WORM (write-once-read-many) storage, or to simply add another layer of protection against object changes or deletion.

- The **AWS Storage Gateway** is a hybrid storage service that allows your on-premises applications to seamlessly use AWS cloud storage. You can use the service for backup and archiving, disaster recovery, cloud data processing, storage tiering, and migration.