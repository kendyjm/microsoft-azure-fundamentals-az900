# AZ-900 Azure Fundamentals Certification

## Microsoft resources

- [Exam AZ-900: Microsoft Azure Fundamentals](https://docs.microsoft.com/en-us/certifications/exams/az-900)
  - [Sample Questions AZ-900: Microsoft Azure Fundamentals](https://docs.microsoft.com/en-us/certifications/resources/az-900-sample-questions?azure-portal=true)
  - [Study Guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VwUY)
  - [Exam Sandbox](https://aka.ms/examdemo)

## John Savill's Technical Training

- [AZ-900 Azure Fundamentals Certification Course (youtube playlist, 8.5 hours)](https://www.youtube.com/playlist?list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3)
  - [handout with all links and whiteboards](https://github.com/johnthebrit/AZ900CertCourse/blob/main/John%20Savill's%20AZ-900%20Azure%20Fundamentals%20Certification%20Course%20Handout.pdf)
- [AZ-900 Azure Fundamentals Study Cram (youtube, 3.5 hours)](https://www.youtube.com/watch?v=tQp1YkB2Tgs&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=63)
  - [AZ-900 Study Cram Whiteboard](https://github.com/johnthebrit/CertificationMaterials/blob/main/whiteboards/AZ-900-Whiteboard.png)
- [Microsoft Azure Master Class (youtube, 20 hours)](https://www.youtube.com/playlist?list=PLlVtbbG169nGccbp8VSpAozu3w9xSQJoY)

## Main ideas

- Identify the Benefits of Cloud Computing: agility, high availability, disaster recovery, scalability, agility, consumption based
  - High availability: Depending on the service-level agreement (SLA) that you choose, your cloud-based apps can provide a continuous user experience with no apparent downtime, even when things go wrong.
  - Scalability: Apps in the cloud can scale vertically and horizontally:
    - Scale vertically to increase compute capacity by adding RAM or CPUs to a virtual machine.
    - Scaling horizontally increases compute capacity by adding instances of resources, such as adding VMs to the configuration.
  - Elasticity: You can configure cloud-based apps to take advantage of autoscaling, so your apps always have the resources they need.
  - Agility: Deploy and configure cloud-based resources quickly as your app requirements change.
  - Geo-distribution: You can deploy apps and data to regional datacenters around the globe, thereby ensuring that your customers always have the best performance in their region.
  - Disaster recovery: By taking advantage of cloud-based backup services, data replication, and geo-distribution, you can deploy your apps with the confidence that comes from knowing that your data is safe in the event of disaster.
  - Capital Expenditure (CapEx) is the up-front spending of money on physical infrastructure, and then deducting that up-front expense over time. The up-front cost from CapEx has a value that reduces over time.
  - Operational Expenditure (OpEx) is spending money on services or products now, and being billed for them now. You can deduct this expense in the same year you spend it. There is no up-front cost, as you pay for a service or product as you use it.
- [Azure Regions](https://infrastructuremap.microsoft.com/)
  - [regions availability zones](https://learn.microsoft.com/fr-fr/training/modules/azure-architecture-fundamentals/regions-availability-zones)
- [abonnements, groupes d’administration et ressources Azure](https://learn.microsoft.com/training/modules/azure-architecture-fundamentals/overview)
- [azure virtual machines](https://learn.microsoft.com/training/modules/azure-compute-fundamentals/azure-virtual-machines)
  - [VM SKUs](https://docs.microsoft.com/azure/virtual-machines/sizes)
  - [Azure Isolated VMs](https://docs.microsoft.com/azure/virtual-machines/isolation)
- [Azure Dedicated Host](https://azure.microsoft.com/pricing/details/virtual-machines/dedicated-host/)
- [Managed Disks](https://azure.microsoft.com/pricing/details/managed-disks/)
- [Sample ARM template](https://github.com/johnthebrit/AzureMasterClass/blob/master/Part11IaCandDevOps/StorageRepo/ARMTemplates/StorageAccount.json)
- [Defense in depth](https://learn.microsoft.com/training/modules/secure-network-connectivity-azure/2-what-is-defense-in-depth)
  - The physical security layer is the first line of defense to protect computing hardware in the datacenter.
  - The identity and access layer controls access to infrastructure and change control.
  - The perimeter layer uses distributed denial of service (DDoS) protection to filter large-scale attacks before they can cause a denial of service for users.
  - The network layer limits communication between resources through segmentation and access controls.
  - The compute layer secures access to virtual machines.
  - The application layer helps ensure that applications are secure and free of security vulnerabilities.
  - The data layer controls access to business and customer data that you need to protect.
- [DDoS Overview](https://docs.microsoft.com/azure/ddos-protection/ddos-protection-overview)
- [express route fundamentals](https://learn.microsoft.com/training/modules/azure-networking-fundamentals/express-route-fundamentals)
  - CloudExchange colocation
  - Point-to-point Ethernet connection
  - Any-to-any connection
  - Directly from ExpressRoute sites
- [Cloud Adoption Framework](https://docs.microsoft.com/azure/cloud-adoption-framework/)
- Describe Microsoft Privacy Statement, Online Services Terms (OST) and Data Protection
  - [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement)
  - [OST](https://www.microsoft.com/licensing/terms/product/ForallOnlineServices?azure-portal=true)
  - [DPA](https://www.microsoft.com/licensing/docs/view/Microsoft-Products-and-Services-Data-Protection-Addendum-DPA)
- Factors to Reduce Cost
  - [Pricing Calculator Deep Dive](https://youtu.be/rMKmbZ1SYQg)
  - [Azure Reservations Deep Dive](https://youtu.be/vpTDXenagcM)
- Functionality and Usage of Pricing and TCO Calculators
  - [Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/)
  - [Azure TCO Calculator](https://azure.microsoft.com/pricing/tco/calculator/)
- Purpose of Service Level Agreements
  - [Azure SLAs](https://azure.microsoft.com/support/legal/sla/)
  - [Azure Status](https://status.azure.com/status)
- [Azure Advisor, Monitor, Service Health](https://learn.microsoft.com/fr-fr/training/modules/monitoring-fundamentals/2-identify-product-options)
