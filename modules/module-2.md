# 💡 Module 2

## Azure Fundamentals

Azure is a public cloud provider, but it also offers private, hybrid, and multi-cloud solutions to users. Cloud services in Azure are designed to help users build innovative cloud solutions that help solve our challenges.

It allows us to build, develop, manage, and run resources like servers, databases, storage, or applications in multiple cloud environments. You can use it for different use cases in the cloud using the tools, programming languages, and frameworks that you prefer to use.

Azure offers over 200 services (as of time of writing) in various categories, including computing, networking, storage, databases, analytics, machine learning and AI, the Internet of Things (IoT), cloud-native, containers, and security. However, Microsoft continues to introduce new features and services to Azure regularly, so the number of services may increase over time.

## Benefits of a Cloud Provider



| Benefits              | Descriptions                                                                                                                                                                              |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| High availability     | Microsoft Azure provides high availability and redundancy across all of its worldwide data canters offering a service-level agreement that ensures 99.99% availability.                   |
| Geo-distribution      | Azure helps global enterprises by providing geo-distribution features. Geography-specific endpoints enables international enterprises to comply with regional compliance and regulations. |
| Scalability on-demand | When demand for complexity, traffic, and data expands, there is a flexible and quick way to handle such needs                                                                             |
| Reliability           | The system or application hosted functions correctly even in the face of adversity (hardware or software faults, and even human error)                                                    |
| Elasticity            | A capability to automatically scale cloud resources based on configuration or demand.                                                                                                     |
| Disaster recovery     | When your applications, data, and systems are hosted in Azure, you can be assured of secured end-to-end backup and disaster recovery solutions.                                           |
| Cost management tools | Tools available for cost management in Azure allow users to set budget alerts for their resource groups and resources.                                                                    |
| OpEx vs. CapEx        | Hosting to cloud means an organization can save money from capital expenditures (CapEx) and only pay for operational expenditures (OpEx).                                                 |

## Azure Portal&#x20;

The self-managed portal of Microsoft’s cloud platform is called the _Azure Portal_; it can be accessed by Azure users on their web browsers or via the _Azure mobile app_. It is a web-based administration website for all types of Azure users, where you can manage the Azure cloud services for your organization. It is a powerful portal of cloud administration tools and resources.

[Link: ](https://portal.azure.com)

Features of Azure Portal

* Create, build, manage, and monitor Azure services and cloud resources all in one place anytime and anywhere at your own convenience
* Use command-line tools and the cloud shell for quick creation and deployments
* Manage and organize Azure subscriptions and create management groups that helps in structuring and governing Azure resources
* Use Microsoft Entra ID to manage identity, access, and permissions to resources in Azure
* Configure and manage privacy, data, security, policies, and compliance vital to the organization’s governance
* Customize the portal’s dashboards to get a quick overview of the status of resources right after you log in
* Take control of monthly costs by monitoring resources through spending limits and budget alerts using Azure Cost Management in the Azure Portal

## Microsoft Azure Services

| Category                                             | Function                                                                                   | Azure Services                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Artificial Intelligence (AI) + Machine Learning (ML) | Build modern cloud apps with ML and cognitive integration                                  | Azure Boot Service, Azure Cognitive Services, Azure Machine Learning, Azure AI Anomaly Detector, Azure DataBricks, Azure Open Datasets, Computer Vision, Face API, Azure AI Immersive Reader, Azure AI Document Intelligence, Kinect DK, Microsoft Genomics, Azure Health Boot, Azure Applied AI Services, Azure Percept, Speech Services, etc.                                                                            |
| Analytics                                            | Gather and visualize any type of data regardless of its volume or velocity                 | Azure Analysis Services, Azure Data Explorer, Azure Data Lake Storage, Azure Data Share, Azure Databricks, Azure Stream Analytics, HDInsight, PowerBI Embedded, Azure Synapse Analytics, Data Factory, Event Hubs, R Server for HDInsight, Microsoft Graph Data Connect, Azure Purview, etc.                                                                                                                               |
| Compute                                              | Build robust applications with high-level cloud compute capacity and scalability features  | API Apps, App Service, Azure Cycle Cloud, Azure Functions, Azure Kubernetes Service (AKS), Azure Quantum Preview, Azure Spot Virtual Machines, Azure Spring Cloud, Azure VMware Solution, Azure Batch, Cloud Services, Linux Virtual Machines, Azure Container Instances, Azure Static Web Apps, VM Scale Sets, Azure Virtual Machines, Azure Virtual Desktop, Web Apps, Azure Dedicated Host, Azure VM Image Builder, etc |
| Containers                                           | Create, build, develop and manage containerized applications with modern integration tools | Azure Kubernetes Services (AKS), Azure Container Instances, Azure Container Registry, Azure Service Fabric, Web App for Containers                                                                                                                                                                                                                                                                                         |
| Databases                                            | Fully managed and secure cloud database services                                           | Azure SQL Database, Azure Cosmos DB, Azure Cache for Redis, Azure Database for PostgresSQL, Azure Database for MySQL, Apache Cassandra MI, SQL Server on Virtual Machines, Azure Database Migration Service, Table Storage, Azure API for FHIR, Azure SQL Database Edge, etc.                                                                                                                                              |
| Integration                                          | Services on Azure for different types of integration within Azure, hybrid or multi-cloud   | Azure API Management (APIM), Azure Event Grid, Azure Service Bus, Azure Logic Apps, Azure Web PubSub Preview, Azure Healthcare APIs Preview                                                                                                                                                                                                                                                                                |
| Networking                                           | Connect cloud and on-premises infrastructure and resources using networking services       | Application Gateway, Azure Bastion, Azure DNS, Azure Express Route, Azure Content Delivery Network, Load Balancer, Azure Front Door, Azure Firewall, Internet Analyzer, Azure Orbital, Private Link, VPN Gateway, Virtual WAN, Virtual Network, Traffic Manager                                                                                                                                                            |
| Identity + Security                                  | Protect resources, data and identity on the cloud                                          | Microsoft Entra ID, Microsoft Defender for Cloud, Azure Security Center, Azure Key Vault, Azure Sentinel, Information Protection, DDoS Protection, etc.                                                                                                                                                                                                                                                                    |

## Compute Services in Azure&#x20;

Compute is the term used for computing resources. Compute services hosted in Azure provide computing resources like operating systems, networking, disks, processors, and memory. These compute resources are available quickly and on-demand for users. Every application is unique. An application can have many workloads that need more than one compute service.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Compute Service </p></figcaption></figure>



| Azure Compute Service            | What is used for ?                                                                                                     |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Azure App Service                | Build and develop web and mobile apps in a fully managed cloud environment                                             |
| Azure Static Web Apps            | Develop modern full stack web application quickly with Azure from a code repository                                    |
| Azure Virtual Machines           | Quick and manageable provisioning of virtual machines (Azure VMs) in different operating systems like Windows or Linux |
| Azure Virtual Machine Scale Sets | Create and provision multiple virtual machines (Azure VMs) with high availability advantage                            |
| Azure Functions                  | Develop serverless, event-driven applications, and stateful workflows                                                  |
| Azure Container Apps             | Build and deploy fully managed modern apps and microservices using serverless containers                               |
| Azure Kubernetes Service(AKS)    | Build managed Kubernetes containers on the cloud                                                                       |

## Networking Services in Azure

Networking services help secure both private and public cloud infrastructure. Users can customize their cloud networking setup and manage their network resources on demand.



| Azure Networking      | What is it for?                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------------------ |
| Azure Virtual Network | Connect virtual machines using VPN connections                                                   |
| Azure Bastion         | Secure and easy access to your virtual machines using private RDF and SSH that are fully managed |
| Azure Private Link    | Access cloud Azure-hosted services with privacy                                                  |
| Azure Firewall        | Protect your resources in the cloud with high availability and low maintenance firewall          |
| Azure Load Balancer   | Load balance your application connections and requests, both inbound and outbound                |
| Azure ExpressRoute    | Create private network connections between Azure data centers and on-premises infrastructure     |
| Azure Traffic Manager | Route your network traffic for better performance                                                |
| Azure VPN Gateway     | Create secure private network connections in the cloud VPN                                       |

## Core Azure Storage Services

The storage services in Azure offer great storage for any type of data objects, Azure Virtual Machine disk storage, reliable messaging storage, and other modern data types. They provide the benefits of high availability, durability, security, accessibility, and manageability.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Azure Storage A/c</p></figcaption></figure>
