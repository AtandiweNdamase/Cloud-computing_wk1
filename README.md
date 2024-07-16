# Cloud-computing_wk1
Cloud computing is the delivery computing services over the internet. such as IT infrastructures , virtual machinnes,storage ,databases and networking.Cloud services also expand to IOT and machine learning and AI
Compute power - how much processing your computer can do.eg RAM
Storage - volume of data YOU CAN STORE ON YOUR COMPUTER.
cloud computing - reqaust more storage , backup and prossessing power
SLA - service level agreements - the availiablity of the service provided 
99% uptime - availablity means the serive can be down  available 432min/month - 10min per week. 
99.9 % uptime - availabilty means the service can have a downtime of 43.2 min/month per week.
Scaling generally comes in two varieties vertical and horizontal . Vertical - increasing and decreasing capabilities of resources. Horizontal scaling is adding or subtracting the number of resouces.
Vertical Scaling 
with vertical scaling , if you were developing an app and you needed nore processing power, scale up by putting more CPUs or RAM.
Reliablility - is the ability of a system to recover from failures and continue to function.
Cloud-based auditing helps flag any resource that’s out of compliance with your corporate standards and provides mitigation strategies.
If you want patches and maintenance taken care of automatically, platform as a service or software as a service deployments may be the best cloud strategies for you.
 Management in the cloud :
 through a web portal 
 using command lne interface
 using APis
 Using PowerShell
That OpEx cost can be impacted by many factors. Some of the impacting factors are:
Resource type - resource setting and the Azure region have an impact on resource cost
Consumption
Maintenance
Geography -The cost of power, labor, taxes, and fees vary depending on the location. Due to these variations, Azure resources can differ in costs to deploy depending on the region.
Subscription type
Neteork traffic- A zone is a geographical grouping of Azure regions for billing purposes. 
Azure Marketplace
Azure infrastructure is distributed globally, which enables you to deploy your services centrally or closest to your customers, or something in between. With this global deployment comes global pricing differences.
The pricing calculator and the total cost of ownership (TCO) calculator are two calculators that help you understand potential Azure expenses
The TCO calculator is designed to help you compare the costs for running an on-premises infrastructure compared to an Azure Cloud infrastructure.

Microsoft Purview’s unified data governance helps your organization:

Create an up-to-date map of your entire data estate that includes data classification and end-to-end lineage.
Identify where sensitive data is stored in your estate.
Create a secure environment for data consumers to find valuable data.
Generate insights about how your data is stored and used.
Manage access to the data in your estate securely and at scale.
Azure PowerShell is a shell with which developers, DevOps, and IT professionals can run commands called command-lets (cmdlets). These commands call the Azure REST API to perform management tasks in Azure. Cmdlets can be run independently to handle one-off changes, or they may be combined to help orchestrate complex actions such as:

The routine setup, teardown, and maintenance of a single resource or multiple connected resources.
The deployment of an entire infrastructure, which might contain dozens or hundreds of resources, from imperative code.
- While Azure PowerShell uses PowerShell commands, the Azure CLI uses Bash commands.

- Azure provides multiple tools for managing your environment, including the:
Azure portal
Azure PowerShell
Azure Command Line Interface (CLI)

Currently, Azure Arc allows you to manage the following resource types hosted outside of Azure:

Servers
Kubernetes clusters
Azure data services
SQL Server
Virtual machines (preview)
With Azure Resource Manager, you can:

Manage your infrastructure through declarative templates rather than scripts. A Resource Manager template is a JSON file that defines what you want to deploy to Azure.
Deploy, manage, and monitor all the resources for your solution as a group, rather than handling these resources individually.
Re-deploy your solution throughout the development life-cycle and have confidence your resources are deployed in a consistent state.
Define the dependencies between resources, so they're deployed in the correct order.
Apply access control to all services because RBAC is natively integrated into the management platform.
Apply tags to resources to logically organize all the resources in your subscription.
Clarify your organization's billing by viewing costs for a group of resources that share the same tag.

Infrastructure as code is a concept where you manage your infrastructure as lines of code. At an introductory level, it's things like using Azure Cloud Shell, Azure PowerShell, or the Azure CLI to manage and configure your resources.

 ARM templates and Bicep are two examples of using infrastructure as code with the Azure Resource Manager to maintain your environment.

 Benefits of using ARM templates 
 - declaratives syntax : means you declare what you to deploy but dont need to write programming commands and sequence to deploy resources
 - repeatable results: repeatly deploy your infrassture throuhout thr development lifecycle.
 - orchestration: you deploy the template through one commend, rather than through multiple imperative commands . deployements occure faster
 - Modular Files:break templates into smaller , resuable components and link them together at deployment time.
 - Extensibilitywith deplyment scripts you can add powershell or Bash scripts to your templates,
   Bicep
Describe Azure Service Health
- Azure status:broad picture of Azure globally.informs of service outages in azure on the azure page.
- Service Health focuses on the azure services and regions youre using.
- Resource Health :is tailored view of ypur actual azure serviesjk,j;fgc
