![Cover image for Deploying a Database Instance in an IBM Cloud Private Cluster on IBM Z](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9780738457833.jpg)

[Deploying a Database Instance in an IBM Cloud Private Cluster on IBM Z](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_1.html "Deploying a Database Instance in an IBM Cloud Private Cluster on IBM Z")
====================================================================================================================

Author : [Christian May](https://ebookreading.net/search/author/Christian+May)

Release Date : 2019/07/01

ISBN : 9780738457833

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 This IBM® Redpaper™ publication shows you how to deploy a database instance within a container using an IBM Cloud™ Private cluster on IBM Z®. A preinstalled IBM Spectrum™ Scale 5.0.3 cluster file system provides back-end storage for the persistent volumes bound to the database.
A container is a standard unit of software that packages code and all its dependencies, so the application runs quickly and reliably from one computing environment to another. By default, containers are ephemeral. However, stateful applications, such as databases, require some type of persistent storage that can survive service restarts or container crashes.
IBM provides several products helping organizations build an environment on an IBM Z infrastructure to develop and manage containerized applications, including dynamic provisioning of persistent volumes.
As an example for a stateful application, this paper describes how to deploy the relational database MariaDB using a Helm chart. The IBM Spectrum Scale V5.0.3 cluster file system is providing back-end storage for the persistent volumes.
This document provides step-by-step guidance regarding how to install and configure the following components:
IBM Cloud Private 3.1.2 (including Kubernetes)Docker 18.03.1-ceIBM Storage Enabler for Containers 2.0.0 and 2.1.0 This Redpaper demonstrates how we set up the example for a stateful application in our lab. The paper gives you insights about planning for your implementation. IBM Z server hardware, the IBM Z hypervisor z/VM®, and the IBM Spectrum Scale cluster file system are prerequisites to set up the example environment. The Redpaper is written with the assumption that you have familiarity with and basic knowledge of the software products used in setting up the environment.The intended audience includes the following roles:
Storage administratorsIT/Cloud administratorsTechnologistsIT specialists            Show and hide more                
Table of Contents
-----------------

1. [Front cover](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_1.html#ww457511)
1. [Notices](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_3.html#ww460066)
    1. [Trademarks](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_3.html#ww459879)
1. [Preface](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_4.html#ww786224)
    1. [Authors](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_4.html#ww786226)
    1. [Now you can become a published author, too](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_4.html#ww782335)
    1. [Comments welcome](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_4.html#ww775129)
        1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_4.html#ww782351)
1. [Chapter 1. Introduction](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww458935)
    1. [1.1 Docker](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww460928)
    1. [1.2 Kubernetes](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww461075)
    1. [1.3 IBM Cloud Private](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww461579)
    1. [1.4 IBM Spectrum Scale](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww461919)
    1. [1.5 IBM Storage Enabler for Containers](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_5.html#ww461922)
1. [Chapter 2. Use Case: Deploying MariaDB on IBM Cloud Private with IBM Spectrum Scale storage on IBM Z](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww460830)
    1. [2.1 Example configuration](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww460860)
        1. [2.1.1 General requirements](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww460925)
    1. [2.2 Docker Installation (on boot node only)](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww461037)
    1. [2.3 Set up the IBM Cloud Private installation environment](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww461414)
    1. [2.4 Customize the Cluster](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww461919)
    1. [2.5 Set up Docker for your cluster nodes](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww462038)
    1. [2.6 Deploy the environment](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww462683)
    1. [2.7 Install IBM Spectrum Scale](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww463189)
    1. [2.8 Install IBM Storage Enabler for Containers](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww463557)
        1. [2.8.1 Install IBM Storage Enabler for Containers 2.0.0](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww464725)
        1. [2.8.2 Install IBM Storage Enabler for Containers 2.1.0](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww465076)
    1. [2.9 Deploying MariaDB instance](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_6.html#ww467873)
1. [Related publications](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_7.html#ww454348)
    1. [IBM Redbooks](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_7.html#ww454350)
    1. [Online resources](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_7.html#ww455988)
    1. [Help from IBM](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_7.html#ww456261)
1. [Back cover](https://ebookreading.net/view/book/Deploying+a+Database+Instance+in+an+IBM+Cloud+Private+Cluster+on+IBM+Z-EB9780738457833_8.html#ww465861)
