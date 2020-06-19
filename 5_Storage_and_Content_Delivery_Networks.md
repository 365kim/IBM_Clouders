[Back to Syllabus](./README.md#course-syllabus)

## :cloud: Learning Objectives
- Describe and differentiate between the 4 main types of __Cloud Storage__
- Explain the benefits of __Content Delivery Networks__
<br>

## :cloud: Basics of Cloud Storage
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@30dbf5c22a1443f2a084f6dd3e4be7c4/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/d66368f99881453faeaa1458eeaefe4f/f43e0652da6b4e5786381a52f1dfa8b3/?child=first)
- __Cloud Storage__
    - where data and files is saved in the cloud.
- __4 Main Types__
    - Direct Attached Storage _(Local Storage)_
        - ephemeral(temporary), not shared, non-resilient<p><img src="https://user-images.githubusercontent.com/60066472/85124382-cd5b2e00-b264-11ea-8a83-05e8cbb5e59c.PNG" width="500"></p>
    - File Storage
    - Block Storage
    - Object Storage
- __Snapshot__
    - a point in time image of the storage.
    - one way to back up File and Block storage
    - usually fast to create (they don’t actually write any data, or rather they create metadata)
    - don’t require downtime and subsequent snapshots record only changes to the data.
<br>

## :cloud: File Storage
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@ec771ed5b5c2480f8b8b17f16fc69ba2/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/d66368f99881453faeaa1458eeaefe4f/c1a70a8950ca468098b9d3ad7595d69a/?child=first)
- __File Storage__
    - must be attached to a compute node before it can be accessed and have data stored on it.
    - physical disks are contained in a specialised piece of hardware, connected to the compute node.
- __NFS (Network File System)__
    - storage is connected to compute nodes over a standard ethernet network.
    - speeds vary based on network traffic
- __IOPS__ _(Input/Output Operations Per Second)_
    - the speed at which the isks can write and read data
    - the higher, the faster the speed of the underlying disk, and normally cost more.
    - low IOPS value can cause a bottleneck<p><img src="https://user-images.githubusercontent.com/60066472/85135080-74959080-b278-11ea-8d24-14b13eb96526.PNG" width="400"></p>
- __Use Cases__
    - a departmental file share
    - a ‘landing zone’ for incoming files that need to be processed by an application
    - a repository of files that a web service might access. 
<br>

## :cloud: Block Storage
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@dcd1cf5c5c09491c9da11fb84c82cc84/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/d66368f99881453faeaa1458eeaefe4f/f06926dda48846e1a2a9dbaa4d57237d/?child=first)
- __Block Storage__
    - breaks files into chunks (or blocks) of data and Stores each block separately under a unique address.
    - mounted as a volume to compute nodes using a dedicated network of fibres, through which signals move at the speed of light.
    - fibre optic networks are more expensive to build than the ethernet ones which deliver
    - normally mounted onto only one compute node at a time.<p><img src="https://user-images.githubusercontent.com/60066472/85135644-62682200-b279-11ea-8f07-913bffa7b689.PNG" width="500"></p>
- __Use Cases__
    - Databases
    - Mail servers
<br>

## :cloud: Object Storage Overview
- [Transcript]() / [Video]()
- __Object Storage__
    - not attached to a compute node, rather it is accessed via an API.
        - differs from the more traditional storage types such as File and Block Storage.
    - the cheapest, and the slowest _(no IOPS option)_
    - infinite in size to the end-user.
    - objects are stored within `buckets` in a structurally flat way.
    - metadata(data about the data, such as an object ID) helps applications to both locate and access the object
- __Resilience Options__
    - resilient, but the data is only stored in one data center
    - the data is stored multiple times in different data centers
        - cost more but they provide both the highest level of resilience
- __Use Cases__
    - a repository for all sorts of unstructured(not hierarchical) data types
    - any static data from text files to audio and video files, from IOT data to virtual machine images, from backup files to data archives.
    - not be suitable for running operating systems, nor applications such as databases where contents changes.
    - backup & disaster recovery
    - replacement for offsite backups
<br>

## :cloud: Object Storage - Tiers and APIs
- [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/d66368f99881453faeaa1458eeaefe4f/cdbc2e4321a0491ca26f35b79ce442a9/?child=first)
- __Object Storage Tiers__
    - based on hoe frequently the data is accessed
    - Standard Tier: frequently accessed
    - Vault/Archive Tier: once a month
    - Cold Vault Tier: once a year
    - Automatic archiving rules: automatically moved to a cheaper storage tier if not accessed for long
- __Object Storage APIs__
    - used to access object storage
    - many object storage providers have an 'S3 Compatible AI'<p><img src="https://user-images.githubusercontent.com/60066472/85137216-cb509980-b27b-11ea-87b3-4db6587c23ed.PNG" width="400"></p>
<br>

## :cloud: Content Delivery Networks
- [Transcript](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/xblock/block-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1+type@video+block@bc1540640aaa47aca53d93365aaf07cc/handler/transcript/download) / [Video](https://courses.cognitiveclass.ai/courses/course-v1:IBMDeveloperSkillsNetwork+CC0101EN+2020T1/courseware/d66368f99881453faeaa1458eeaefe4f/6fa3d2b9a7cb4fccb130722b3505623c/?child=first)
- __CDN__
    - a distributed server network that accelerates Internet content delivery.
    - content delivery network endpoints are placed in as many locations around the world as possible
    - stores contents in distributed locations and reduces the distance between website visitors and server.
    - delivers temporarily stored, or cached, copies of website content to users, based on the user's geographic location.
- __Direct Benefits__
    - increases the speed
- __Indirect Benefits__
    - reduces the amount of traffic that acually hits the server
    - increases the uptime
    - increases in security through obscurity<p><img src="https://user-images.githubusercontent.com/60066472/85138510-d86e8800-b27d-11ea-9259-f67d31be9604.PNG" width="400"></p>
<br>

## :cloud: Module Summary
- Cloud storage is available in four main types–Direct Attached, File, Block, and Object Storage. These storage types differ in how they can be accessed, the capacity they offer, how much they cost, the types of data they are best suited to store, and their read-write speed.
- Direct Attached (or Local) Storage is storage that is presented directly to a cloud-based server and is effectively either within the host server chassis or within the same rack.
- File Storage is typically presented to compute nodes as a Network File System (NFS), which means that the storage is connected to compute nodes over a standard ethernet network.
- Block Storage is presented to compute nodes using high-speed fibre connections, typically provisioned in volumes, which are mounted onto a compute node.  
- Object Storage is accessed via an API and doesn’t need an underlying compute node. Object Storage offers infinite capacity as you can keep adding files to it and just pay for what you use. Compared to the other storage types, object storage is slowest in terms of read and write speeds.
- A Content Delivery Network (CDN is a distributed server network that accelerates internet content delivery by delivering temporarily stored or cached copies of website or media content to users based on their geographic location.
<br>

## Hands-on Lab: Create an Object Storage Instance and add items
- Create an instance of IBM Cloud Object Storage: [link](https://cocl.us/objectstorage_cc_cc0101en)
    - Create an Object Storage instance
    - Create a Bucket to store data
    - Add objects to your bucket
    - Share objects in your bucket
![scre](https://user-images.githubusercontent.com/60066472/85139290-28018380-b27f-11ea-896b-cb4bddb3f7aa.PNG)
<br>

## :cloud: Graded Quiz
- Which of these are features of Object Storage? Select two.
    ```
    ▷ Storage is attached to compute nodes using a fibre network
    ▶ You can directly use Object Storage without attaching it to a compute node
    ▷ Object Storage can be mounted on multiple compute nodes via an ethernet network
    ▶ Object storage is effectively infinite
    ```
- There are four types of cloud storage available. Which storage type is ephemeral or non-persistent?
    ```
    ▷ Block storage
    ▷ File storage
    ▷ Object storage
    ▶ Direct Attached storage
    ```
- What is the main benefit of a Content Delivery Network (CDN)?
    ```
    ▷ Enhanced control over network traffic by routing traffic to specified resources
    ▶ Speed, it makes your website faster by serving files from a location closer to the user.
    ▷ Distribute tasks, workloads, and network traffic
    ▷ Network topology
    ```
<br>

[Go to Next Module](./6_Emergent_Trends.md)
