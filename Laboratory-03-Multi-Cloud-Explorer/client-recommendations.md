# Checkpoint 4 – Cloud Platform Recommendation Scenarios

## Client A – Startup Company
* **Recommended Platform:** Amazon Web Services (AWS)
* **Recommendation Explanation:**
  AWS is the optimal choice for Client A because of its **AWS Activate** program, which provides early-stage startups with promotional credits and technical support to manage initial infrastructure costs without upfront capital. AWS offers auto-scaling and serverless options like AWS Lambda and Elastic Beanstalk, allowing the startup to handle sudden growth without paying for idle capacity. The vast ecosystem and broad platform documentation ensure that developers can quickly build, deploy, and iterate on their mobile application backends with minimal operational overhead.
* **Key Recommended Services:**
  1. **AWS Amplify / Elastic Beanstalk** (Mobile Backend / App Deployment)
  2. **Amazon DynamoDB** (Scalable NoSQL Database)
  3. **AWS Lambda** (Serverless Backend Execution)



## Client B – University
* **Recommended Platform:** Microsoft Azure
* **Recommendation Explanation:**
  Microsoft Azure is the natural fit for the university because of its native support for existing enterprise environments like Windows Server, Active Directory, and Microsoft 365. Azure allows seamless hybrid identity management integration via **Microsoft Entra ID** (formerly Azure Active Directory) without requiring complex re-architecture. Furthermore, Microsoft offers dedicated academic licensing and identity integration models for educational institutions transitioning existing workloads to the cloud.
* **Key Recommended Services:**
  1. **Microsoft Entra ID** (Identity and Access Management)
  2. **Azure Virtual Machines** (Hosting existing Windows Server workloads)
  3. **Azure SQL Database** (Cloud relational database storage)



## Client C – AI Research Company
* **Recommended Platform:** Google Cloud Platform (GCP)
* **Recommendation Explanation:**
  Google Cloud Platform provides specialized infrastructure tailored specifically for Artificial Intelligence and Machine Learning workloads. GCP offers high-performance **Tensor Processing Units (TPUs)** alongside dedicated GPU configurations designed specifically to accelerate matrix operations and deep learning computations. Additionally, GCP's unified AI ecosystem—Vertex AI—streamlines the ML lifecycle from data ingestion to automated model deployment.
* **Key Recommended Services:**
  1. **Vertex AI** (Managed AI / Machine Learning platform)
  2. **Compute Engine with Cloud TPUs / GPUs** (High-Performance Machine Learning Accelerators)
  3. **BigQuery** (Large-scale data warehouse and analytics engine)



## Client D – Global E-Commerce Company
* **Recommended Platform:** Amazon Web Services (AWS)
* **Recommendation Explanation:**
  AWS provides global infrastructure spanning multiple geographic Regions and Availability Zones, enabling low-latency access for international customers. Built on the same infrastructure foundation powering Amazon.com, AWS features dynamic auto-scaling designed to withstand massive traffic surges during peak shopping events. Additionally, AWS provides high-availability multi-region database replication via **Amazon Aurora Global Database** and low-latency global edge caching through **Amazon CloudFront**.
* **Key Recommended Services:**
  1. **Amazon EC2 Auto Scaling** (Dynamic capacity adjustment)
  2. **Amazon Aurora Global Database** (High-performance multi-region relational database)
  3. **Amazon CloudFront** (Global Content Delivery Network)


CITETATION

https://aws.amazon.com/activate/terms/

https://learn.microsoft.com/en-us/entra/identity/hybrid/

https://docs.cloud.google.com/tpu/docs

https://www.amazonaws.cn/en/rds/aurora/global-database/


## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | AWS | Offers vast startup credit programs, rapid deployment tools, and serverless options that minimize upfront costs. |
| **Enterprise Organization** | AWS / Azure | AWS provides broad ecosystem stability; Azure integrates seamlessly with existing enterprise IT policies and legacy systems. |
| **Microsoft Environment** | Azure | Natively integrates with Windows Server, Active Directory, SQL Server, and Microsoft 365 licenses. |
| **AI / Machine Learning** | GCP | Offers specialized hardware (TPUs), integrated Vertex AI platform, and superior deep learning frameworks. |
| **Kubernetes Deployment** | GCP | Creators of Kubernetes; GKE offers the most mature, automated, and feature-rich managed Kubernetes environment. |
| **Global Web Application** | AWS | Global network distribution with Amazon CloudFront, multi-region databases, and proven high-availability scaling. |



CITETATION

https://aws.amazon.com/startups/credits/

https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id

https://docs.cloud.google.com/tpu/docs

https://docs.cloud.google.com/kubernetes-engine/docs/about
