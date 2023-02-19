# Introduction

## About this Workshop

MySQL HeatWave Database Service is a fully-managed Oracle Cloud Infrastructure service, developed, managed, and supported by the MySQL team in Oracle

In this workshop, you will learn practices for working with MySQL HeatWave Database Service.



_Estimated Lab Time:_ 3 hours +

### About Oracle MySQL Database Service

Benefits of MySQL HeatWave Database Service include:

- On-demand scalability: MDS offers unmatched scalability to facilitate the management of deeply integrated applications using a small footprint even in large deployments with many terabytes of data. On-demand flexibility is one of the key features of MDS. This database offering allows complete customization by eCommerce businesses with demanding database server requirements.

- High performance: MDS features a unique storage-engine framework that allows system administrators to configure MDS for optimal performance. Regardless whether it’s to run an eCommerce site that receives a million queries in a day or a high-speed OLTP system, MDS is engineered to meet the requirements of even the most demanding applications while ensuring high speed, full-text indexes and unique memory cache for enhanced performance.

- Data security: MDS is well known for being the most secure and reliable database management system, serving as the database back-end for web applications such as WordPress, Drupal, Joomla, Facebook and Twitter. The data security and support for transactional processing that are included in recent versions of MDS can greatly benefit any business, especially eCommerce businesses that involve frequent orders or other transactions.

- Comprehensive transactional support: MDS ranks highly on the list of transactional database offerings available in the market. With features like complete atomic, consistent, isolated, durable transaction support, multiversion transaction support, and unrestricted row-level locking, it is the go-to solution for full data integrity. It guarantees instant deadlock identification through server-enforced referential integrity.

- Reduced total cost of ownership (TCO): By migrating current database apps to MDS, enterprises are enjoying significant cost savings on new projects. The dependability and ease of management that accompany MDS save you time otherwise wasted troubleshooting downtime issues and performance problems.

### About Deployment Options

Deployment options for Oracle MySQL Database Service include:

- Standalone: With the Standalone option, users get a single-instance MDS back-ended by resilient and secure Oracle Cloud Infrastructure Block Volumes. This option is typically recommended for test and development environments.

- High Availability: The High Availability option is recommended for use cases that require either or both higher uptime and zero data-loss requirements. When you select this option, MDS provides three instances across different availability or fault domains. The data is then replicated across the instances using a Paxos-based consensus protocol implemented by the MySQL Group Replication technology. Applications connect to only one endpoint to read and write data to the database. In case of a failure, MDS will automatically failover to a secondary instance in a matter of minutes, without data loss or application reconfiguration.

- HeatWave: The HeatWave option deploys a preconfigured database system which allows accelerated query processing, suitable for both OLTP and OLAP workloads. With its innovative in-memory analytics engine, HeatWave provides 400x query acceleration for MySQL at a very compelling price.

  **Lab Setup**
  ![INTRO](./images/heatwave-bastion-architecture-compute.png " ")

### Objectives

In this lab, you will be guided through the following steps:

- Create   on-prem MySQL Community  system
- Migrate on-prem MySQL Community to a HeatWave High Availability System
- Access HeatWave with
    - Database Tools
    - Bastion
    - Load Balancer
- Setup Additional HeatWave security
    - Users
    - Data Masking
    - Audit
- Build LAMP Server for HeatWave
- Manage HeatWave System

### Prerequisites

- An Oracle Free Tier, Paid or LiveLabs Cloud Account
- Some Experience with MySQL Shell - [MySQL Site](https://dev.MySQL.com/doc/MySQL-shell/8.0/en/)

  **You may now proceed to the next lab**

## Acknowledgements

- **Author** - Perside Foster, MySQL Solution Engineering,
- **Last Updated By/Date** - Perside Foster, MySQL Solution Engineering, July 2022
