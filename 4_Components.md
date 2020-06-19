[Back to Syllabus](./README.md#course-syllabus)

## :cloud: Learning Objectives
- Describe the key __Components of Cloud Infrastructure__
- Explain __Virtualization__
- List the features and benefits of __VM__
- List the features and benefits of __Bare Netal Servers__ and how they differ from virtual servers
- Describe how to build a __Secure Cloud Networking Presence__
- Explain how __Contain-Based Technology__ works
<br>

## :cloud: Overview of Cloud Infrastructure
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/57d8120d5a424213875dc7f57ea6e63d/?child=first) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@6236980184f14fe6a71bf60219a76638/handler/transcript/download)
- __Cloud Region__
    - a geographic area or location where a Cloud provider’s infrastructure is clustered
    - isolated from each other so that Cloud operations in other Regions would keep running even if impacted by a natural disaster.
    - e.g. NA South or US East
- __Availability Zones__ _(AZ)_
    - Each Cloud Region can have multiple AZ
    - typically distinct Data Centers with their own power, cooling and networking resources.
    - connected to other AZs using very high bandwidth network connectivity.
    - e.g. DAL-09 or us-east-1
- __Cloud Data center__
    - a huge room containing cloud infrastructure<p><img src="https://user-images.githubusercontent.com/60066472/85117106-48b6e280-b259-11ea-96d1-4b8f18752f79.PNG" width="500"></p>
- __Compute Options__
    - Virtual Servers (VMs): software-based
    - Bare Metal Servers: physical servers (not virtualized)
    - Serverless : abstraction layer on top of virtual machines
- __Storage Options__: Block, File, Object
- __Networking Options__: routers, switchs, security groups, ACLs, VLANs, VPCs, VPNs, firewalls, load balancers, gateways, traffic analyzers, CDNs
<br>

## :cloud: Virtualization and Virtual Machines Explained
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@62ab0ac191ea4a1fa3ce331d647f32eb/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/3bfdcb6156764d8fa7d7a400301281ea/?child=first)
- __Virtualization__
    - the process of creating a software based, or virtual, version of something,
- __Hypervisors__
    - manages the resources that are allocated to VMs.
    - Type1(Bare Metal): VMware, ESXi, or Microsoft Hyper-v, or even open-source KVM
    - Type2(Hosted): Oracle, VirtualBox, or VMware Workstation
- __VM__
    - a software based computer, run like a physical computer
    - can run multiple of VMs on a hypervisor<p><img src="https://user-images.githubusercontent.com/60066472/85118840-d267af80-b25b-11ea-8251-f73c2c6142a8.PNG" width="500"></p>
- __Advantages__: cost-saving, agility & speed, less downtime
<br>

## :cloud: Types of Virtual Machines
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@d9406acb05cb43f697c9292bf1119df9/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/143872e898c745c387b5b3cc1e659cf7/?child=first)
- __Virtual Machines__
    - Also called as...: Virtual Servers, Virtual Instances, Instances
    - User Options: Region and Zone, OS, Multi or Single-tenant, Billing Hourly or Monthly
- __Shared or Public Cloud VMs__
    - Underlying physical server is virtualized and is shared
    - Also offer custom configurations<p><img src="https://user-images.githubusercontent.com/60066472/85119549-e6f87780-b25c-11ea-9bda-e28160f6e26f.PNG" width="400"></p>
- __Transient or Spot VMs__
    - take advantage of unused capacity in a cloud data center
    - much lower cost than regular VMs of similar sizes
    - risk of losing these VMs when capacity in the data center decreases
- __Reserved Virtual Server Instances__
    - allow you to reserve capacity and guarantee resources for future deployments.
    - useful when you know you require at least a certain level of cloud capacity
for a specific duration.
- __Dedicated Host__
    - run on a given host so they can make exclusive use of full capacity and resources
    - typically used for meeting compliance and regulatory requirements or meet specific licensing terms.
<br>

## :cloud: Bare Metal Servers
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@a762042f32f34547bb704ecf36057c6d/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/fac564e25810496aaf04254375af7068/?child=first)
- __Bare Metal Server__
    - a single-tenant, dedicated physical server.
    - providers will fix if anything goes wrong with the hardware or rack connection
    - customers are responsible for administering and managing everything else on the server.
    - both preconfigured / custom-configured possible
- __Characteristics__
    - may take longer to provision than virtual servers
    - tend to be more expensive 
    - not all providers provide bare metal servers
    - fulfil the demanding needs of high-performance computing (HPC) and data intense applications that require
“minimal latency-related delays”
        - workload examples: ERP, CRM, AI, Deep Learning, and Virtualization.
    - High degrees of Security Controls<p><img src="https://user-images.githubusercontent.com/60066472/85121007-05f80900-b25f-11ea-99f2-05ed1eebcfb6.PNG" width="400"></p>
<br>

## :cloud: Secure Cloud Networking
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@759961f8aabb497ca9d1e69ff6e3b31e/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/19964f82705f4ce58f1844e7fdaa341e/?child=first)
- __Secure Network__
    - building a cloud network vs deploying a network in an on-premises data center<p><img src="https://user-images.githubusercontent.com/60066472/85121199-58392a00-b25f-11ea-96f7-af851fbf025b.PNG" width="400"></p>
    - how to build a secure cloud networking presence<p><img src="https://user-images.githubusercontent.com/60066472/85121536-e6151500-b25f-11ea-969d-f5e9a2409699.PNG" width="400"></p>
<br>

## :cloud: Containers
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@d60637837db24016b695ff1afe780721/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/7911d77997974117b947310ccf27dd5f/e0ae9fd1f7ad4f9fbdf18f4c12baa026/?child=first)
- __Containers__
    - an executable unit of software 
    - application code is packaged, along with its libraries and dependencies
    - can be run anywhere, whether it be on desktop, traditional IT, or the cloud.
    - small, fast, and portable,
    - do not need to include a guest OS in every instance and unlike virtual machines <p><img src="https://user-images.githubusercontent.com/60066472/85122251-380a6a80-b261-11ea-962c-b7bf821b59ac.PNG" width="400"></p>
<br>

## :cloud: Module Summary
- Cloud infrastructure consists of data centers, storage, networking components, and compute resources.
- Virtualization is the process of creating a software-based version of physical resources, made possible through the use of hypervisors. 
- A few different types of Virtual Machines can be provisioned on the cloud. These include:
    - Shared or Public Cloud VMs that are provider-managed, multi-tenant deployments that can be provisioned on-demand with predefined sizes
    - Transient or Spot VMs that take advantage of unused capacity in a cloud data center
    - Reserved VMs that allow you to reserve capacity and guarantee resources for future deployments 
    - Dedicated hosts that offer single-tenant isolation
- Bare metal servers are single-tenant physical servers that are dedicated to a single customer. Bare metal servers fulfil the demanding needs of high-performance computing (HPC) and data intense applications and are ideal for applications that have a high degree of security or compliance requirements.
- Networking capabilities in the cloud are delivered as a service rather than in the form of rack-mounted devices. Cloud resources, such as VMs (or VSIs), storage, network connectivity, and load balancers, are deployed into subnets within Virtual Private Clouds (VPCs). Using private and public subnets allows users to deploy multi-tier enterprise applications securely. Load balancers distribute the traffic and allow applications to be responsive.
- Containers are an executable unit of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere—desktops, traditional IT, or the cloud. Containers are lighter weight and consume fewer resources than Virtual Machines - helping streamline the development and deployment of cloud native applications.
<br>

## :cloud: Graded Quiz
- Is it possible to run completely different operating systems on Virtual Machines (VMs) that are on a single host? If yes, what makes this possible?
    ```
    ▷ Yes, Containerization makes it possible—to have VMs that are unique physical entities, so you can have completely different Operating Systems on them.
    ▷ No, it is not possible—VMs are software-based versions of a single host. They cannot have different environments from one another.
    ▷ No, it is not possible—A single host can only work as one single virtual environment, and can, therefore, have only one environment.
    ▶ Yes, Virtualization makes it possible— to have VMs, running different operating systems, on a single host.
    ```
- Which of these scenarios is ideal for the use of bare metal servers, as opposed to virtual servers? Select two.
    ```
    ▶ CPU and I/O intensive workloads
    ▷ Low cost to use
    ▶ Huge performance and strict security and compliance requirements
    ▷ Workloads that require limited throughput and performance
    ```
- Subnets are the main area where security is implemented in the cloud. What is used to provide security at the virtual instance level in subnets?
    ```
    ▷ Virtual Private Cloud or VPC
    ▷ Load Balancers
    ▶ Security Groups or SGs
    ▷ Access Control Lists or ACLs
    ```
[Go to Next Module](./5_Storage_and_Content_Delivery_Networks.md)
