**link**: (https://d1.awsstatic.com/whitepapers/aws-overview.pdf)

# Six Advantages of Cloud Computing

- Trade capitcal expense for variable expense
- Benefit from massive economies of scale
- Stop guessing capacity
- Increase speed and agility
- Stop spending money running and maintaining data centers
- Go global in minutes

# Types of Cloud Computing

Important to understand the difference between Infrastructure as a Service, Platform as a Service, and Software as a Service and which strategy is best for your business needs.

## Cloud Computing Models

### Infrastructure as a Service (IaaS)

- Provides the basic building blocks for cloud IT
  - Networking features, computers (virtual or dedicated hardware), data storage

### Platform as a Service (PaaS)

- Removes the need for managing the underling infrastructure (hardware, os)
  - Dont need to worry about resource procurement, capacity planning, software maintenance, patching, etc

### Software as a Service (SaaS)

- Provides a completed product that is run and managed by the service provider. 
  - Typically end-user applications
  - E.g. web-based email, you don't need to consider how the software is built or runs, just how to use it

## Cloud Computing Deployment Models

### Cloud
Fully deployed in the cloud, all parts run in the cloud.

### Hybrid
Connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud. 

### On-premise
Using virtualization and resource management tools, this is sometimes called a "private cloud". On-premise deployment typically don't provide many ebenfits of cloud computing.

# Global Infrastructure

AWS Cloud infrastructure is built around AWS Regions and Availability Zones.

AWS Region is a physical geographical region with multiple AZ zones. Each AZ has multiple data centers.

Allows higher availability, fault tolerance and scalability. 

Each Amazon Region is designed to be completely isolated from the other Amazon Regions. AZ are also isolated, by AZs in the same Region are connected by low latency links. 

# Security and Compliance

## Security

AWS Centers are built securely, business' don't need to pay for this. Security is available at a lower cost in comparison to on-premise alternatives.

AWS Cloud uses a **shared responsibility model**, AWS is responsible for security of the cloud, you are responsible for security in the cloud. 

### Benfits of AWS Security

- Keep your data safe
- Meet Compliance Requirements
- Save Money
- Scale Quickly

## Compliance

**AWS Cloud Compliance** enables you to understand the robust controls in place at AWS to maintain security and data protection in the cloud. 

# AWS Web Services Cloud Platform

## AWS Management Console

access and manage AWS through the AWS Management COnsole, a simple and intuitive UI. 

## AWS Command Line Interface

CLI is a unified tool to manage your AWS services. 

## Software Development Kit

SDK simplifies using AWS services in your application with a API tailored to different programming languages or platform. 

## Analytcs

### Amazon Athena

Interactive query services that makes it easy to analyse data in Amazon S3 using standard SQL. Athena is serverless. 

### Amazon EMR

A managed Hadoop framework that makes it easy, fast, and cost-effective to process vast amounts of data across dynamically scalable Amazon EC2 instances. 
- Can also run Apache Spark, HBase, Presto, and Flink. 
- Interact with S3, DynamoDB
- EMR notebooks, based on Jupyter Notebooks

### Amazon CloudSearchh

Managed service to make it simple and cost effective to setup, manage and scale a search solution for your website or application. 

### Amazon Elasticsearch Service

Elasticsearch to search, analyze and visualize data in real-time. 
- Use cases such as log analytics, full-text search, application monitoring, clickstream analytics. 
- Integrates with Kibana and Logstash. 

### Amazon Kinesis

Collect, process, and analyze real-time streaming data for timely insights. 

Four services currently offered: Kinesis Data Firehose, Kinesis Data Analytics, Kinesis Data Streams, and Kinesis Video Streams. 

### Amazon Kinesis Data Firehose

Easiest way to reliably load streaming data into data stores and analytics tools. Capture, transform, and load streaming data into Amazon S3, Amazon Redshift, Amazon Elasticsearch Service, and Splunk. 

Fully managed service that automatically scales to match throughput of data. 

It can batch, compress, transform, and encrypt. 

Configure delivery stream to automatically convert the incoming data to columnar formats like Apache Parquet and Apache ORC, before the data is delivered to Amazon S3, for cost-effective storage and anlytics. 

### Amazon Kinesis Data Analytics

Analyze streaming data. SQL users can easily query streaming data, Java users can use open source java libraries and AWS integrations to transform and analyze data in real-time. 

### Amazon Kinesis Data Streams

KDS can continuously capture gigabytes of data per second from hundreds of throusands of sources such as website clickstreams, database event streams, financial transactions, social media feeds, IT lods, and location-tracking events. 

### Amazon Kinesis Video Streams

Securely stream video from connected devices to AWS.

### Amazon Redshift

Fast and scalable data warehouse that makes it simple and cost-effective to analyze your data across your data warehouse and data lake. 

10 times faster than other solutions.

### Amazon QuickSight

Business intelligence (BI) services that makes it easy for your to deliver isnights to everyone in your organization. 

### AWS Data Pipeline

Werb service to reliable process and move data between different AWS compute and storage services, as well as on-premises data sources at specified intervals. 

Create complex data processing workloads that are fault tolerant, repeatable and highly available. 

### AWS Glue

Managed ETL serice for customers to prepare and load their data for analytics. 

Simply point AWS Glue to your data stored in AWS, and AWS discovers your data and stores the associated metadata in the AWS Glue Data Catalog. Once cataloged, it is immediately searchable, queryable, and available for ETL.

### AWS Lake Formation

Service to set up a secure data lake in days.

A data lake is a centralized, curated and secured repository that stores all your data, both in its original form and prepared for analysis. 

Data lake enables your to break down data silos and combine differentt ypes of analytics to gain insights and guide better business decisions. 

Creating a data lake involes a lot of manual, complicated and time-consuming takes. Such as loading data from diverse sources, monitoring those data flows, setting up partitions, turing on envryption and managing keys, defining transformation jobs and monitoring their operation, re-organizing data into a columnar format, configuring access control settings, deduplicating redundant data, matching linked records, granting access to data sets, and auditng access over time.

With Lake Formation it is a simple as defining where your data residers, and what access and security policies your want to apply. Then your data collected and catalog into databased and object storages, and move into your new Amazon S3 data lake, cleans and classifies data using ml algorithms, and secures access to your sensitive data. 

### Amazon Managed Streaming for Apache Kafka (Amazon MSK)

Serivce to build and run application that use Apache Kafka to process streaming data. 

Use Apache Kafka APIs to populate data lakes, stream changes to and from databased, asnd power ML and analytics applications. 

## Application Integration

### AWS Step Functions

Lets you coordinate multiple AWS services into serverless workflows so you can build and update apps quickly. Design and run workflows that stitch together services such as AWS Lambda and Amazon ECS into a feature-rich applications. 

### Amazon MQ

Managed message broke service for Apache ActiveMQ that makes it easy to set up and operate message brokers in the cloud. 

### Amazon SQS

Amazon Simple Queue Service is a fully managed messaging queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. 

Two different types of message queues offered, standard queues offer maximum throughput, best-effort ordering, and at least once delivery. SQS FIFO queues are designed to guarentee that messages are processed exactly once, in the exact order they are sent. 

### Amazon SNS

Amazon Simple Notification Service, high available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications. 

Amazon SNS provides topics for high-throughput, push-based, many-to-many messaging. 

SNS can fan out notifications to end users using mobile push, SMS, and email.

### Amazon SWF

Amazon Simple Workflow helps developers build, run, and scale background jobs that have parallel or sequential jobs. SWF is a fully-managed state tracker and task coordinator in the cloud. 

If your application's steps take more than 500 miliseconds to complete, you need to track the state of processing. 

## AWS Cost Management

### AWS Cost Explorer

Easy-to-use interface to visualize, understand, and manage AWS costs and usage over time. 

### AWS Budgets

Set custom budgets that alert you when your costs or usage exceed (or are forcasted to exceed) your budgeted amount. 

Can be tracked at the monthly quarterly, or yearly level, you can customize the start and end dataes.

### AWS Cost and Usage Report

A single location for accessing comprehensive information about your AWS costs and usage. 

### Reserved Instance (RI) reporting.

AWS provides a number of RI-specific cost management solutions out-of-the-box to help you better understand and manager your RIs. Using the RI utilization and coverage reports available in AWS Cost Explorer, you can visualize your RI data at an aggregte level or inspect a particular RI subscription. 

## Blockchain

### Amazon Managed Blockchain

A fully managed service that makes it easy to create and manager scalable blockchain network using the popular open source frameworks Hyperledger Fabric and Ethereum, 

Build applications where multiple parties can execute transactions without the need for a trusted, central authority. 

Removes need for individual network memebers to manually provision hardware, install software, create and amange certificates for access control. 

Managed Blockchain can replicate an immutable copy of your blockchain network activity into Amazon Quantum Ledger Database (QLDB). 

## Business Applications

### Alexa for Business

Use Alex to get more done, as an intelligent assistant to be more productive in meeting rooms, at their desks, and even with the Alexa devices they already have at home. 

### Amazon WorkDocs

Secure enterprise storage and sharing service with strong administrative controls and feedback capabilities that improve user productivity. 

### Amazon WorkMail

Secure and managed business email and calendar service. 

### Amazon Chime

Communications service that transforms online meetings with a secure, easy-to-use application that you can trust. `