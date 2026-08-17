## Client A – Startup Company
**Recommended Platform:** AWS

**Justification:** As a startup with a limited budget but expectations of rapid growth, AWS is a strong fit due to its free tier and flexible pay-as-you-go pricing, which keeps initial costs low. AWS also offers the widest range of services, meaning the company won't need to switch providers as it scales and adds new features. Its large community and extensive documentation make it easier for a small team to find support without hiring specialized cloud staff.

**Services to use:**
1. EC2 (Elastic Compute Cloud) – for hosting the mobile app's backend
2. S3 (Simple Storage Service) – for storing user data, images, and backups
3. Lambda – for serverless functions that scale automatically with user growth, avoiding upfront server costs

---

## Client B – University
**Recommended Platform:** Microsoft Azure

**Justification:** Since the university already relies on Windows Server, Microsoft 365, and Active Directory, Azure is the natural choice because of its native integration with these existing tools. Migrating to Azure minimizes compatibility issues and retraining, since staff and IT teams are already familiar with the Microsoft ecosystem. Azure's hybrid cloud tools also allow the university to migrate services gradually rather than all at once.

**Services to use:**
1. Azure Active Directory (Entra ID) – to extend the university's existing identity management into the cloud
2. Azure Virtual Machines – to migrate existing Windows Server workloads
3. Azure SQL Database – for managing student and administrative data

---

## Client C – AI Research Company
**Recommended Platform:** Google Cloud Platform (GCP)

**Justification:** GCP is the strongest choice for a company developing AI and Machine Learning applications, since Google built the platform around its own internal AI research. GCP's high-performance computing options and specialized AI tooling give the company access to infrastructure optimized specifically for training and running ML models. GCP's Kubernetes offering is also considered the most mature, useful for deploying containerized AI workloads at scale.

**Services to use:**
1. Vertex AI – for building, training, and deploying machine learning models
2. Compute Engine – for high-performance computing workloads
3. Google Kubernetes Engine (GKE) – for deploying and scaling containerized AI applications

---

## Client D – Global E-Commerce Company
**Recommended Platform:** AWS

**Justification:** AWS's global infrastructure, with the highest number of regions and availability zones among the three providers, makes it well-suited for a multinational company needing low-latency access for customers worldwide. AWS also offers mature auto-scaling and load-balancing tools that handle traffic spikes common in e-commerce, especially during peak shopping periods. Its proven reliability at scale makes it a safe choice for a business where downtime directly affects revenue.

**Services to use:**
1. EC2 with Auto Scaling – to automatically adjust server capacity based on traffic
2. CloudFront – a content delivery network (CDN) for fast content delivery worldwide
3. RDS (Relational Database Service) – for managing product and order data reliably

---

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Free tier and pay-as-you-go pricing suit limited budgets, with the widest range of services to scale into as the company grows |
| Enterprise Organization | AWS or Azure | Both offer mature enterprise support, extensive service catalogs, and proven track records for large-scale operations |
| Microsoft Environment | Azure | Deepest native integration with Windows Server, Active Directory, and Microsoft 365, minimizing migration friction |
| AI / Machine Learning | GCP | Strongest AI/ML tooling (Vertex AI) and data analytics platform (BigQuery), built on Google's own AI research |
| Kubernetes Deployment | GCP | Google created Kubernetes, and GKE is widely considered the most mature managed Kubernetes service |
