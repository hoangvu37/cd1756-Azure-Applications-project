# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- scalability: Virtual machine scale sets - App Service Built-in service\
- availability: SLA for Virtual Machines - SLA for App Service
- costs: Windows, Linux - App Service pricing
- Choose App Service for deploying the app

### Assess app changes that would change your decision.

- price
- scale db, storage
- thirt party (notify, dependency)
- microservices
- CICD