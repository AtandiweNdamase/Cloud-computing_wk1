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


Cloud computing weeek 2

- what does Azure offer: Limitless innovation. Build intelligent apps and solutions with advanced technology, tools, and services to take your business to the next level. Seamlessly unify your technology to simplify platform management and to deliver innovations efficiently and securely on a trusted cloud.

- Azure provides more than 100 services that enable you to do everything from running your existing applications on virtual machines to exploring new software paradigms, such as intelligent bots and mixed reality
- Many teams start exploring the cloud by moving their existing applications to virtual machines (VMs) that run in Azure. Migrating your existing apps to VMs is a good start, but the cloud is much more than a different place to run your VMs.
  
  Physical infrastructure
  
- The physical infrastructure for Azure starts with datacenters. Conceptually, the datacenters are the same as large corporate datacenters. They’re facilities with resources arranged in racks, with dedicated power, cooling, and networking infrastructure.

- As a global cloud provider, Azure has datacenters around the world. However, these individual datacenters aren’t directly accessible. Datacenters are grouped into Azure Regions or Azure Availability Zones that are designed to help you achieve resiliency and reliability for your business-critical workloads.

A region is a geographical area on the planet that contains at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network.

VMs are an ideal choice when you need:

Total control over the operating system (OS).
The ability to run custom software.
To use custom hosting configurations.

Virtual machine scale sets let you create and manage a group of identical, load-balanced VMs. If you simply created multiple VMs with the same purpose, you’d need to ensure they were all configured identically and then set up network routing parameters to ensure efficiency. 
Virtual machine scale sets let you create and manage a group of identical, load-balanced VMs. If you simply created multiple VMs with the same purpose, you’d need to ensure they were all configured identically and then set up network routing parameters to ensure efficiency. 

Virtual machine availability sets are another tool to help you build a more resilient, highly available environment vailability sets are designed to ensure that VMs stagger updates and have varied power and network connectivity, preventing you from losing all your VMs with a single network or power failure.

Update domain: The update domain groups VMs that can be rebooted at the same time. This allows you to apply updates while knowing that only one update domain grouping will be offline at a time. All of the machines in one update domain will be updated. 

Fault domain: The fault domain groups your VMs by common power source and network switch. By default, an availability set will split your VMs across up to three fault domains.

When to use VMs 
- During testing and Development
- running applications in the cloud

Azure App service
App Service enables you to build and host web apps, background jobs, mobile back-ends, and RESTful APIs in the programming language of your choice without managing infrastructure.offers automatic scaling and high availability.  
With App Service, you can host most common app service styles like:

- Web apps
- API apps
- WebJobs
- Mobile apps
  App Service handles most of the infrastructure decisions you deal with in hosting web-accessible apps:

- Deployment and management are integrated into the platform.
- -Endpoints can be secured.
-Sites can be scaled quickly to handle high traffic loads.
-jThe built-in load balancing and traffic manager provide high availability.

Web apps 
- App Service includes full support for hosting web apps by using ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP, or Python. 
  You can choose either Windows or Linux as the host operating system.
  API apps
- Much like hosting a website, you can build REST-based web APIs by using your choice of language and framework. You get full --- Swagger support and the ability to package and publish your API in Azure Marketplace. The produced apps can be consumed from 
  any HTTP- or HTTPS-based client.

Use the Mobile Apps feature of App Service to quickly build a back end for iOS and Android apps. With just a few actions in the Azure portal, you can:

Store mobile app data in a cloud-based SQL database.
-Authenticate customers against common social providers, such as MSA, Google, Twitter, and Facebook.
-Send push notifications.
-Execute custom back-end logic in C# or Node.js.

Azure Virtual Networks 
- Isolation and segmentation: allows creatation of multiple virtual networks defining private IP address space by using either private network ranges.
- Internet communications : you cn enable incoming connections from the internet by assigning  publi address to Azure.
- Communicate between azure resoures:virtual networks  can connect to other Azure resources.
- Azure EXpressRoute provides a dedicated private connectivity to Azure that doesnt travel over the internt
- Route Network Traffic: Route tables allow you to dfin ruls about how traffic should be directed.
- Azure Virtual Desktop is a desktop and application virtualization service that runs on the cloud.

- A virtual private network (VPN) uses an encrypted tunnel within another network. VPNs are typically deployed to connect two or more trusted private networks to one another over an untrusted network (typically the public internet)
  VPN GATEWAY
Connect on-premises datacenters to virtual networks through a site-to-site connection.
Connect individual devices to virtual networks through a point-to-site connection.
Connect virtual networks to other virtual networks through a network-to-network connection.

VPN gateway, you must specify the type of VPN - either policy-based or route-based. The primary distinction between these two types is how they determine which traffic needs encryption.

- Policy-based VPN gateways specify statically the IP address of packets that should be encrypted through each tunnel. This type of device evaluates every data packet against those sets of IP addresses to choose the tunnel where that packet is going to be sent through.
- In Route-based gateways, IPSec tunnels are modeled as a network interface or virtual tunnel interface. IP routing (either static routes or dynamic routing protocols) decides which one of these tunnel interfaces to use when sending each packet. Route-based VPNs are the preferred connection method for on-premises devices. 
