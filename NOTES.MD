Deployment Areas:
1. Zones - Smallest entity
2. Region - Subdivided into Zones
3. Multi Region - 2 or more Regions

Compute Service Options
1. Iaas - Compute Engine (VMs : Instances)
    a. Choose Regions and Zones to deploy
    b. User decide OS and Software to put on it
    c. Use **public** or **private** image to create instances

    Manage multiple instances with **instance groups**
    Add/Remove capacity using **autoscaling with instance groups**
    Attach/Detach disks as needed
    Can be used with Google Cloud Storage
    Use SSH to connect directly

2. CaaS - Google Kubernetes Engine
    **Container-Orchestration** system for automating deploying, scaling and managing containers
    Flexibility to integrate with on-premise Kubernetes
    Uses **Compute Engine** instances as NODES in a cluster (A group of Nodes)

3. PaaS - App Engine
    Fully managed, serverless platform for developing and hosting web applications as scale
    Provisions servers and scales app instances based on demand

4. FaaS - Cloud Functions
    Serverless execution environment for building and connecting cloud services
    Simple, Single-Purpose Functions that are attached to events
    Triggered on Event Fired
    Use Cases
        1. Data Processing or ETL Operations
        2. Webhooks to respond to HTTP triggers
        3. APIs that compose loosely coupled logic
        4. Mobile backend functions

5. FaaS - Cloud Run
    Fully managed compute platform for deploying and scaling containerized apps quickly
    Abstracts away all infrastructure management
    Serverless for Containers


Storage Classes
1. Standard (Max Uptime, No Limits)
2. Nearline (Low-Cost, Accessed <1 / Month)
3. Coldine (Even Lower Cost, Accessed <1 / QTR)
4. Archive (Lowest Cost, Accessed <1 / Year)

Availabiliy
1. Region (Single)
2. Dual Region
3. Multi-Region

Storage Options
1. Cloud Storage
    Consistent, Scalable, large-capacity, highly durable object storage
    Available in Different Storage Classes and Availability
2. Filestore
    Fully managed NFS file server

3. Persistent Disks
    Durable **block storage** for instances
    Connected to OS
    Standard / SSD (Faster) Options
    Available in Zonal / Regional Options

DataBases
SQL
1. Cloud SQL
    Fully managed DB Service
    PostgreSQL, MySQL, SQL Server
    Highly available across zones
2. Cloud Spanner
    Scalable Relational DB Service
    Support transactions, strong consistency and sync replication
    Highly available across regions and globally

NoSQL
1. Bigtable
2. Datastore (Mobile, Web, IoT)
3. Firestore (Realtime)
4. Memorystore