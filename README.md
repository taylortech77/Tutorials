# Tutorials, Projects and Guides

last update 10/13/2025

Introduction to Microsoft Azure: Describe cloud concepts
- ***START HERE***

  Thank you for beginning your journey into learning cloud. 94% of companies use 1 of 3 cloud platforms (Google Cloud, Microsoft Azure and Amazon Web Services). These tutorials are focused on learning Microsoft Azure.

  this link below will help you spend an hour learning about the basics of the cloud and Azure.
https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/?WT.mc_id=aqc_azfun1_inproduct_azureportal

---------------
This is a bonus beginner friendly learning setup. It is not required to move forward but a great resource if you want to take your skills higher.

Introduction to Microsoft Azure: Describe Azure architecture and services
https://learn.microsoft.com/en-us/training/paths/azure-fundamentals-describe-azure-architecture-services/

------------
This section is focused on networking within the cloud. This section does have exercises (projects) but you dont have to complete them. whats important is that you understand how Azure works.


Azure networking documentation
https://learn.microsoft.com/en-us/azure/networking/

The 3 links you need to click/learn from this networking documentation above are.....


Recommended Azure Networking Learning Path

Step 1 – Networking Foundation (Core Concepts)

➡️ Goal: Understand how Azure connects resources internally and to the internet.
 📘 Learn in this order:
 
1.	Azure Virtual Network (VNet) – the core building block.
2.	Azure Private Link / Private Endpoint – secure service access without public IP.
3.	Azure DNS – how name resolution works in Azure.
💡 Outcome: You’ll understand address spaces, subnets, peering, and private connectivity.

Step 2 – Load Balancing & Application Delivery
➡️ Goal: Learn how Azure distributes traffic and manages high availability.

 📘 Topics:
•	Azure Load Balancer (Layer 4)
•	Azure Application Gateway (Layer 7)
•	Azure Front Door (global CDN + WAF)
💡 Outcome: You’ll know when to use each and how they fit into resilient, global designs.

Step 3 – Hybrid Connectivity
➡️ Goal: Learn how to connect on-premises or other clouds to Azure.

 📘 Topics:
•	Azure VPN Gateway
•	Azure ExpressRoute
•	Azure Virtual WAN
💡 Outcome: Understand site-to-site, point-to-site, and private dedicated connections — great for global architecture roles.

----------------------------
Additional documentation, not required!!

Microsoft Azure Cloud Concepts
https://learn.microsoft.com/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/

----------
These are basic projects! You can advance these however youd like. As you work ***take screenshots*** for your portfolio later. 

Project Quickstart: Create an Azure resource 
https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/7-exercise-create-azure-resource?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services

Project Quickstart: Create a Windows virtual machine in the Azure portal
https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal

-------
***ADVANCED VIRTUAL MACHINE PROJECT - CYBERSECURITY***

https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/9-exercise-configure-network-access

-------
***ADVANCED DOCKER PROJECT CYBERSECURITY***
Project Quickstart -Deploying a Docker container
https://learn.microsoft.com/en-us/azure/container-instances/container-instances-quickstart-portal?WT.mc_id=portaledu_inproduct_popularsolutions

------------------
***EXPERT LEVEL CYBERSECURITY PROJECT***
Onboard for Microsoft Defender
https://learn.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-machines

------------------
***ADVANCED PROJECTS FOR WEB APP CREATION***

Project: Deploy a Node.js web app in Azure
 https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode

--------

****ADVANCED AI PROJECT***
Project Tutorial: Train a model in Azure Machine Learning
https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-train-model?view=azureml-api-2

---------

Microsoft Free services
https://portal.azure.com/?Microsoft_Azure_Education_correlationId=013e6926-9784-44e6-90f4-e217963fb05f#view/Microsoft_Azure_Billing/FreeServicesBlade

---------

LEVEL 1: Cloud Basics
Goal: Learn how Azure resources connect, deploy, and communicate securely.
Duration: 2–3 hours total
🧱 Project 1: Create an Azure Resource + VM
What you’ll do:
Create a new Resource Group.
Create a Virtual Network (VNet) and Subnet.
Deploy a Windows VM into that subnet.
Connect using RDP.
Skills learned: Resource groups, regions, networking, compute basics.
Portfolio title: Deploying a Virtual Machine in Microsoft Azure
Link to start:
👉 Create a Windows virtual machine in Azure
🌐 LEVEL 2: Networking Basics
Goal: Understand how resources communicate within Azure and stay secure.
Duration: 2–4 hours
🛠 Project 2: Secure a Virtual Network
What you’ll do:
Create a new VNet and two subnets (frontend and backend).
Add two VMs, one in each subnet.
Create a Network Security Group (NSG) to block all inbound traffic except RDP.
Test connectivity between the VMs (Ping test).
Skills learned: Subnets, NSGs, IP addressing, private connectivity.
Portfolio title: Building a Secure Network with Azure Virtual Network and NSGs
Learning path:
👉 Azure Networking Documentation – Virtual Network
⚙️ LEVEL 3: Load Balancing & Redundancy
Goal: Learn how to keep applications available and scale traffic.
Duration: 3–4 hours
⚖️ Project 3: Create a Load Balancer
What you’ll do:
Use your two frontend VMs from before.
Add an Azure Load Balancer.
Configure a backend pool and health probe.
Test by visiting the Load Balancer’s public IP.
Skills learned: High availability, Layer 4 load balancing, scaling.
Portfolio title: Deploying a Load-Balanced Web Tier in Azure
Tutorial:
👉 Azure Load Balancer Quickstart
🔒 LEVEL 4: Cloud Security Essentials
Goal: Learn how to secure resources and monitor for threats.
Duration: 2–3 hours
🧩 Project 4: Onboard a VM to Microsoft Defender for Cloud
What you’ll do:
Use an existing VM.
Turn on Microsoft Defender for Cloud.
Connect the VM to a Log Analytics workspace.
Review security alerts and recommendations.
Skills learned: Threat monitoring, cloud security posture, compliance.
Portfolio title: Enabling Microsoft Defender for Cloud for Virtual Machines
Tutorial:
👉 Onboard machines to Microsoft Defender for Cloud
☁️ LEVEL 5: Web App Deployment
Goal: Learn to host an app entirely in Azure.
Duration: 2–3 hours
🌍 Project 5: Deploy a Simple Web App
What you’ll do:
Deploy a Node.js or Python web app from the Azure Portal.
Add a custom domain or test URL.
Enable HTTPS for secure communication.
Skills learned: App Services, scaling, certificates, PaaS basics.
Portfolio title: Deploying a Secure Web Application in Azure App Service
Tutorial:
👉 Deploy a Node.js web app in Azure
💡 LEVEL 6: AI + Data (Optional Bonus)
Goal: Explore cloud-based AI in an easy way.
Duration: 2–3 hours
🧠 Project 6: Train a Simple Model in Azure Machine Learning
What you’ll do:
Use the Azure ML Studio interface.
Train a basic dataset (classification).
Visualize results in the web portal.
Skills learned: AI basics, Azure ML environment, data visualization.
Portfolio title: Training an AI Model in Azure Machine Learning Studio
Tutorial:
👉 Train a model in Azure Machine Learning
🧾 Summary Table
Level	Project	Focus	Type	Est. Time
1	Create a VM	Compute	IaaS	1–2 hrs
2	Secure VNet + NSG	Networking	IaaS	2–3 hrs
3	Add Load Balancer	Availability	IaaS	2–4 hrs
4	Defender for Cloud	Security	SaaS	2–3 hrs
5	Deploy Web App	App Hosting	PaaS	2–3 hrs
6	Train AI Model	AI + Data	PaaS	2–3 hrs


