# Azure Interview Questions

---

## Cloud Fundamentals

- What are the Cloud Service Models (IaaS, PaaS, SaaS)?
- What are Regions, Region Pairs, and Availability Zones in Azure?
- What is the hierarchy of Management Groups, Subscriptions, Resource Groups, and Resources?
- What is Azure Resource Manager (ARM)?

---

## Virtual Machines & Compute

- What is an Azure Virtual Machine?
- What are the Azure VM Sizes / Series?
- What is a VM Image, and what is Azure Compute Gallery?
- What is the difference between a Public IP and a Private IP in Azure?
- What is an NSG (Network Security Group)?
- What is the difference between an Availability Set and an Availability Zone?
- What are the Purchasing Options for an Azure VM (Pay-as-you-go, Reserved Instances, Spot VMs, Savings Plan)?
- What is Azure Bastion?

---

## Storage (Managed Disks, Blob, Files)

- What is an Azure Storage Account, and what services does it provide?
- What are the Managed Disk Types?
- What is the difference between a VM Image and a Disk Snapshot?
- What is Azure Files?
- What is Azure Blob Storage?
- What are the Blob Access Tiers (Hot, Cool, Cold, Archive)?
- What is Blob Lifecycle Management?
- What are the Storage Redundancy Options (LRS, ZRS, GRS, GZRS)?
- What is a SAS (Shared Access Signature) token?

---

## Identity & Access Control (Entra ID, RBAC)

- What is Microsoft Entra ID (formerly Azure Active Directory)?
- What is Azure RBAC, and what are the built-in roles (Owner, Contributor, Reader)?
- What is the difference between a Service Principal and a Managed Identity?
- What is the difference between a System-Assigned and a User-Assigned Managed Identity?
- What is Azure Policy, and how is it different from RBAC?
- What is Azure Key Vault?

---

## Networking (VNet)

- What is a VNet (Virtual Network)?
- What is a Subnet in Azure?
- What is the difference between a Public Subnet and a Private Subnet in Azure?
- What is a NAT Gateway in Azure?
- What is the difference between VNet Peering and Virtual WAN / Hub-Spoke topology?
- What is the difference between an NSG and Azure Firewall?
- What is a Route Table (UDR - User Defined Route)?
- What is the difference between a Service Endpoint and a Private Endpoint?
- What is the difference between a VPN Gateway and ExpressRoute?

---

## Load Balancing & Scaling

- What are the Load Balancing options in Azure (Load Balancer, Application Gateway, Front Door, Traffic Manager)?
- What is the difference between Azure Load Balancer and Application Gateway?
- What is a VM Scale Set (VMSS)?
- What is Autoscaling in Azure?

---

## Database

- What is Azure SQL Database?
- What is the difference between Azure SQL Database, SQL Managed Instance, and SQL Server on VM?
- What is the difference between Read Replicas and Zone-Redundant / Geo-Replication deployments?
- What is Azure Cosmos DB?

---

## Monitoring & DNS

- What are the components of Azure Monitor?
- What is a Log Analytics Workspace?
- What is Application Insights?
- What is Azure DNS, and what is a Private DNS Zone?
- What are DNS Records?
- What are the Routing Methods in Azure Traffic Manager?

---

## Advanced Services (CDN, Functions, App Service, AKS)

- What is Azure Front Door / Azure CDN?
- What is Azure Functions?
- What is Azure App Service, and what is an App Service Plan?
- What are Deployment Slots in App Service?
- What is Azure Kubernetes Service (AKS)?
- What is Azure Container Registry (ACR)?

---

## Infrastructure as Code

- What is an ARM Template?
- What is Bicep, and how is it different from ARM Templates?
- How does Terraform work with Azure (AzureRM provider, remote state in a Storage Account)?

---

# Azure DevOps Interview Questions

---

## Azure DevOps Fundamentals

- What is Azure DevOps, and what are its services (Boards, Repos, Pipelines, Test Plans, Artifacts)?
- What is the difference between Azure DevOps Services and Azure DevOps Server?
- What is the hierarchy of Organization, Project, and Team in Azure DevOps?

---

## Azure Boards

- What is Azure Boards?
- What are Work Items (Epic, Feature, User Story, Task, Bug)?
- What are the Process Templates (Basic, Agile, Scrum, CMMI)?
- What is the difference between a Sprint and a Backlog?

---

## Azure Repos

- What is Azure Repos?
- What is the difference between Git and TFVC in Azure Repos?
- What are Branch Policies?
- What is a Pull Request, and how do you enforce reviewers and build validation on it?
- What branching strategies have you used (GitFlow, Trunk-Based, Feature Branching)?

---

## Azure Pipelines

- What is Azure Pipelines?
- What is the difference between Classic Pipelines and YAML Pipelines?
- What is the structure of a YAML pipeline (Stages, Jobs, Steps, Tasks)?
- What is the difference between a Build Pipeline (CI) and a Release Pipeline (CD)?
- What are Triggers (CI Trigger, PR Trigger, Scheduled Trigger)?
- What is the difference between Microsoft-hosted Agents and Self-hosted Agents?
- What is an Agent Pool?
- What are Pipeline Variables and Variable Groups?
- What is the difference between a Variable and a Parameter in YAML pipelines?
- What are Pipeline Templates, and why are they used?
- What are Environments and Approvals & Checks?
- What is a Deployment Job, and what deployment strategies are supported (RunOnce, Rolling, Canary)?
- What are Pipeline Artifacts, and how do you pass them between stages?

---

## Security & Connections

- What is a Service Connection?
- How do you use secrets from Azure Key Vault in a pipeline?
- What is Workload Identity Federation for Service Connections?
- What is a PAT (Personal Access Token)?

---

## Azure Artifacts & Test Plans

- What is Azure Artifacts, and what package types does it support?
- What is a Feed, and what are Upstream Sources?
- What is Azure Test Plans?

---

## Scenario-Based Questions

- How would you build a CI/CD pipeline to deploy a Docker application to AKS?
- How would you deploy infrastructure using Terraform from an Azure Pipeline?
- How would you implement a Blue-Green deployment using App Service Deployment Slots?
- A pipeline is failing only on a Microsoft-hosted agent but works locally. How would you troubleshoot?
- How would you prevent direct pushes to the main branch?
- How would you roll back a failed production deployment?
