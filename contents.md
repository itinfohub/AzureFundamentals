# Azure Cloud Fundamentals

This doc presents fundamentals of Azure cloud which includes the following:


> ####   - Concepts of cloud computing and its features and advantages
> ####   - Core Azure services
> ####   - Azure management tools and core solutions
> ####   - Azure security: general and network
> ####   - Identity, privacy, governance and compliance
> ####   - Cost management and SLA





# Cloud Computing

> ## What is cloud computing?

<details><summary> cloud computing </summary><p>
<pre>
- Using the Internet to deliver from remote computing services: computing; networking; 
  storage; analytics; and intelligence etc.
- Virtual rather than physical
- pay as you go
- rental rather ownership
</pre>
</p></details>

> ## Advantages of cloud computing


| Advantage  | Details |
|---|---|
|Cost-effective | No upfront cost of buying hardware or running data centers. CapEx vs OpEx |
|Agility | Can deploy virtual machines, virtual network etc in minutes, without the <br>need to wait for the ordered hardware to be shipped, mounted, and installed |
|High Availability | Run with high uptime. HA=(uptime/life time)|
|Scalability | Easy to scale horizontally and vertically |
|Elasticity | The ability to automatically scale up/down or in/out based on real time demands |
|Fault Tolerance | The ability to remain up with hardware/data center failures|
|Disater Recovery | The ability to recover from natural or human induced disasters with geo-redundancy|

# Main Azure Services

<pre>
- Compute               - Storage              - Database          - Big Data     - AI
- Network               - Mobile               - Web               - IoT          - DevOps
</pre>


### Compute
 
 | Compute Resource | Comments |
 | :--- |:---|
 | Azure VM | a virtual machine hosted by Azure cloud |
 | Azure VM scale set | identical VMs in the same scale set, automatically create or destroy based on demand |
 | Azure Kubernates Services | cluster management of many container instances |
 | Azure container instance | Azure containerized applications|
 | Azure Functions | event-driven, serverless computing resources. No need to provision VM to run it |
 | Azure Service Fabric | Distributed systems platform facilitating the package, deployment,and management of microservices <br> ; on-premisese, Azure cloud or other clouds |
 | Azure batch | high performance parallel computing |



### Storage
 | Storage Service | Comments |
 |:---|:---|
 |Azure Blob Storage| Globally distributed, highly available, secure object storage |
 |Azure File Storage | Shared file systems, access with SMB or mounting |
 |Azure Queue Storage | Asynchronous access |
 |Azure Table Storage | key-value, semi-structured, schemaless, NoSQL |
 |Azure Disk Storage | virtual hard disk attached to individual VM |



### Database

| Database Service | Comments |
|:---|:---|
|Azure CosmosDB |fully managed; low latency: single digital of millisecond; SLA: 99.999; NoSQL; No-ETL Analystics with Azure Synapse Link |
|Azure SQL database | PaaS;|
|Azure database MySQL ||
|Azure database Postgresql ||
|Azure SQL database on VM | IaaS|
