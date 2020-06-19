[Back to Syllabus](./README.md#course-syllabus)

## :cloud: Learning Objectives
- Describe the emergent cloud trends such as __Hybrid Multicloud, Microservices, and Serverless__
- Explain how __Cloud Native Applications__ work
- Explain how __DevOps__ helps tackle some of the complexities posed by cloud
- Describe the benefits of __Application Modernization__ and how organizations can modernize their applications
<br>

## :cloud: Hybrid Multi-Cloud
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@e69f762163344163ac26f6b2ec0bc7c3/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/73f2d32c3cc74ee79f26769dbe5f365b/?child=first)
- __Hybrid Multi-Cloud__
    - leverage the best of cloud models and services across different service providers, and have your applications and workloads working seamlessly across multiple different clouds.
    - prevent lock-in to a specific vendor's cloud platform and have more flexibility.
    - _Hybrid Cloud_
        - a computing environment that connects a private cloud and public cloud into a single infrastructure.
    - _Multi-Cloud_
        - a cloud adoption strategy that embraces a mix of cloud models from different service providers. <p><img src="https://user-images.githubusercontent.com/60066472/85141741-37360080-b282-11ea-9444-06b1bb387429.PNG" width="500"></p>
- __Use Cases__
    - cloud scaling
    - building a composite cloud at a global level
    - modernization
    - machine learning with legacy data
<br>

## :cloud: Micro-Services
- [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/17ee28b7a30e4ba98f35bef10b01fdbb/?child=first)
- __Micro-Services__<p><img src="https://user-images.githubusercontent.com/60066472/85143030-2be3d480-b284-11ea-9faa-c3abe7c59137.PNG" width="500"></p>
    - have their own stack running on their own containers
    - communicate with one another over a combination of api's events streaming and message brokers
    - Thanks to microservices...
        - application components can be developed more efficiently by multiple developers working independently
        - teams can use different stacks and runtime environments for different components
        - components facing too much load can be scaled independently
- __How Micro-Services have shaped Application Development__
    - developers no longer have to create every line of code from scratch
    - break into small independent teams where they write smaller amounts of code called micro services
    - cloud development platforms provide developers with an ecosystem of code that can be easily and securely integrated into applications
    - each microservice is in a separate container
    - join the application with service discovery which creates a roadmap for microservices to communicate
<br>

## :cloud: Serverless Computing
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@5e0ea4e5ba5148b897c20cd5477d47c8/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/455e2cbdda664173b3a17a7dc42b3601/?child=first)
- __Serverless__
    - an approach to computing that offloads responsibility for common infrastructure management tasks 
    - doesn’t mean there are no servers
    - only that the management of the underlying physical or virtual servers is removed from their users.
- __Key Attributes__
    - no provisioning of servers, runtimes
    - runs code on-demand, scaling as needed
    - never pay for idle capacity (unlike virtual servers on the cloud)
    - abstracts the infrastructure away from developers
- __Service Providers__
    - IBM Cloud Functions (based on Apache OpenWhisk), AWS Lamb-da, and Microsoft Azure Functions.
- __Use Cases__<p><img src="https://user-images.githubusercontent.com/60066472/85146177-78c9aa00-b288-11ea-8646-1881b8a5a26a.PNG" width="600"></p>
    - Short-running stateless functions (seconds or minutes).
    - Seasonal workloads with varying off-peak and peaks.
    - Production volumetric data that shows too much idle time.
    - Event-based processing or asynchronous request processing for implementing use cases.
    - Microservices that can be built as functions that are stateless
        - automatic scaling, rapid provisioning, and a pricing model that does not charge for idle time
- __Concerns__: vendor-dependent, sometimes need to start up from zero to serve a new request
<br>

## :cloud: Cloud Native
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@9ef1b73c51ad48ce8e622a59190cfa90/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/834275e9df49433abac1bf5853ff79fb/?child=first)
- __Cloud Navtive Application__
    - developed from the outset to work only in the cloud environment
    - or, an existing app that has been refactored and reconfigured with cloud native principles
    - consists of microservices working together as a whole to comprise an application
    - independence enables frequent, iterative improvement of cloud native applications, without disrupting the experience of end-users
- __Principles__
    - Whether creating a new cloud native application or modernizing an existing application
        - Follow the microservices architecture approach by breaking applications down to single-function microservices. 
        - Rely on containers for maximum flexibility, scalability, and portability.
        - Adopt Agile methods that speed the creation and improvement process through quick iterative updates based on user feedback.
- __Benefits__: innovation, agility, commoditization
- __Use Cases__: everything<p><img src="https://user-images.githubusercontent.com/60066472/85147510-ef1adc00-b289-11ea-8713-566f6b1e58f0.PNG" width="600"></p>
<br>

## :cloud: DevOps on the Cloud
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@10c255387b2e4188b08f015c96a80639/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/fe5f22d6462945b4957065f1dd7ddab5/?child=first)
- __DevOps__
    - Development teams + Operation teams
    - a collaborative approach where business owners and the development, operations, and quality assurance teams collaborate to continuously deliver software.
    - DevOps approach applies agile and lean thinking principles to all stakeholders
    - DevOps provides to help building and running applications in the cloud a lot more manageable
    - process: Continuous Delivery, Integration, Deployment, Monitoring and Delivery Pipeline
suppliers, partners.<p><img src="https://user-images.githubusercontent.com/60066472/85147713-3b661c00-b28a-11ea-99b2-94a45ed43645.PNG" width="500"></p>
- __Advantages__
    - developers can produce software in short iterations on a continuous delivery schedule of new features and bug fixes in rapid cycles;
    - businesses can seize market opportunities and reduce time to include customer feedback in their products.
<br>

## :cloud: Application Modernization
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@285fd521a2db46ab82121b270a0796b0/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/cc961f317bf648b0b55b33637ef95e34/10ff20161c4e40979ee46bc36e397cf4/?child=first)
- __Application Modernization__<p><img src="https://user-images.githubusercontent.com/60066472/85149298-15da1200-b28c-11ea-918d-541bc1ab35cb.PNG" width="500"></p>
- __Architecture__
    - Monoliths > SOA(service-oriented architecture) > Microservice
- __Infrastructure__
    - Physical Servers > VM > Cloud
- Delivery
    - Waterfall > Agile > DevOps and SRE_(Site Reliability Engineering)_
<br>

## :cloud: Module Summary
- Hybrid Multicloud is a cloud adoption strategy that makes it possible for public clouds, private clouds, and on-premises IT to interoperate seamlessly while leveraging the best cloud-based services from different public cloud providers.
- Microservices architecture is an approach in which an application is built as a collection of loosely coupled and independently deployable components or services, leading to efficient development, maintenance, and upgradation cycles.
- Serverless Computing is an approach to computing that offloads responsibility for common infrastructure management tasks for application runtimes to cloud providers, allowing developers to focus their time and effort on development and testing, and not have to worry about provisioning, maintaining and scaling compute resources.
- Cloud native applications are applications that are built or refactored to work in the cloud environment. These applications, developed using DevOps methodologies, consist of microservices packaged in containers that can run in any environment—making it possible to create and update features in quick iterative cycles.
- DevOps is a collaborative approach that enables development and operations teams to continuously deliver software in quick iterative cycles while reducing overhead, duplication, and rework. DevOps’ tools, practices, and processes help tackle the complexities and challenges posed by the cloud, allowing solutions to be delivered and updated —quickly and reliably.
- Application Modernization helps organizations accelerate their digital transformation, take advantage of new technologies and services, and become more responsive to changing market dynamics. Cloud computing is one of the key enablers of application modernization.

## :cloud: Graded Quiz
- What are the key elements of a hybrid Multicloud strategy?
    ```
    ▷ For seamless working, it is recommended that if you’re subscribed to the infrastructure services of a cloud provider, you should subscribe to the application services provided by the same vendor.
    ▷ Embraces a mix of cloud models and services as long as they are from the same cloud service provider
    ▷ Embraces a mix of cloud models while creating a vendor lock-in with the cloud provider
    ▶ Connects an organization’s on-premise private cloud and third-party public cloud into a single infrastructure
    ```
- What is an attribute that distinguishes serverless computing from other compute models?
    ```
    ▷ Serverless computing does not require any underlying servers for executing workloads
    ▷ End users pay for resources as long as they are running, even if idle
    ▶ The serverless model requires NO provisioning of servers, installation of application stacks, or operation of the infrastructure BY the users/developers
    ▷ In the serverless computing environment, compute resources cannot be scaled up or down
    ```
- Cloud adoption is an integral part of application modernization. What are the other two important components of modernization?
    ```
    ▶ Microservices and DevOps
    ▷ VMs and Agile Methodology
    ▷ Serverless and Virtual Machines
    ▷ Service Oriented Architecture and Waterfall Methodology
    ```
[Go to Next Module](./7_Final_Exam.md)
