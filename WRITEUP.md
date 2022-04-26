# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- scalability: Virtual machine scale sets - App Service Built-in service\
- availability: SLA for Virtual Machines - SLA for App Service
- costs: Windows, Linux - App Service pricing chipper
- Choose App Service for deploying the app FlaskWebProject
VM benifit: 
- Instant deployment.
- Vertical scaling, without having to redeploy.
- Support for multiple deployments (like staging and production).
- Automatic OS upgrades for your infrastructure.
- Integration capability with Git.Integration capability with MySQL.
- Configuration of the application server/framework in the VM.
- Integration with Azure services.OS patch management.
- Design and configure the application and infrastructure to handle fluctuating traffic.Seamless platform switching (including the ability to - - move between 32 bit and 64 bit environments).
- Security configuration.Identify and apply monitoring strategy for applications.
- Access services like Service Bus, Storage, and SQL Database.
- Host a web or web services tier of a multi-tier architecture.
- Host a middle tier of a multi-tier architecture.Support for ASP.NET, classic ASP, Node.js, PHP, and Python.
- Scale out to multiple instances without having to redeploy.Support for SSL.
- Visual Studio integration.Remote Debugging.Network isolation with Azure Virtual Network.Integrated Endpoint monitoring.
### Assess app changes that would change your decision.

- price
- scale db, storage
- thirt party (notify, dependency)
- security
- microservices
- CICD
- database