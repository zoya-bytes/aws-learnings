# Auto Scaling or AWS Auto Scaling

Auto Scaling group service intigrates with Cloudwatch and it will monitor the resources on  a metric that you have given or set. eg:CPU utilization, if CPU utilization crossed the threshold it can adjust the capacity by adding the more instances on your autoscaling group. which is based on Cloudwatch alarms, so while creating Auto Scaling we need to create alarms too(to add or remove the capacity). Adding the capacity to maintain the performance or removing the capacity to maintain the cost.

## How this Works?

AWS AUTO SCALING (Unified scaling for your cloud applications) > EXPLORE YOUR APPLICATIONS > DISCOVER WHAT YOU CAN SCALE > CHOOSE WHAT TO OPTIMIZE > TRACK SCALING AS IT HAPPENS.

## Simple Storage Service (S3)

S3 is the one of the oldest and used service of Amazon.This service enables the internet storage. You can use amazon Simple Storage Service to store and retrive any amount of data at any time, from anyplaces on the web. It is object-Based Storage eg; dropbox, google drive where you upload your documents, files etc and access from anywhere through internet.

## Relational Database Service (RDS)

Relational Database Service  solves relational database administration problem.
"A relational database is a collection of data items with pre-defined relationships between them. These items are organized as a set of tables with columns and rows. Tables are used to hold information about the objects to be represented in the database. Each column in a table holds a certain kind of data and a field stores the actual value of an attribute. The rows in the table represent a collection of related values of one object or entity. Each row in a table could be marked with a unique identifier called a primary key, and rows among multiple tables can be made related using foreign keys. This data can be accessed in many different ways without reorganizing the database tables themselves."

Shared Responsibility  Model

The Shared Responsibility Model is a security and compliance framework that outlines the responsibilities of cloud service providers (CSPs) and customers for securing every aspect of the cloud environment, including hardware, infrastructure, endpoints, data, configurations, settings, operating system (OS), network controls and access rights.

Customer Responsibility for the Security In the Cloud

1. Customer Data
2. Platform, Applications, Identity and Access Management (IAM)
3. Operating System, Network and Firewall Configuration
4. Client-side data Encryption, Data Integrity Authentication
5. Server-side Encryption (File System and/ or Data)
6. Networking Traffic protection (Encryption, integrition, Identity)

AWS Responsibility The security Of the Cloud

1. Software
2. Compute, Storage, Database, Networking
3. Hardware/ AWS Global Infrastructure
4. Regions, Availability Zones, Edge locations.