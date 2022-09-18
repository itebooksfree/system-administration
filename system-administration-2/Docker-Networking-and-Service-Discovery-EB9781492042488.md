![Cover image for Docker Networking and Service Discovery](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781492042488.jpg)

[Docker Networking and Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_1.html "Docker Networking and Service Discovery")
====================================================================================================================

Author : [Michael Hausenblas](https://ebookreading.net/search/author/Michael+Hausenblas)

Release Date : 2016/03/01

ISBN : 9781492042488

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 When you start building applications with Docker, you’ll come up against two significant challenges: networking and service discovery. You can find many recipes for dealing with these tasks if you’re prepared to scrounge through a pile of blog posts.
In this short guide, author Michael Hausenblas, Developer and Cloud Advocate at Mesosphere, explains how networking and service discovery work in the Docker world, and provides a series of practical solutions for dealing with these challenges.
Get an overview of Docker single- and multi-host networkingUnderstand why service discovery and container orchestration (scheduling) are two sides of the same coinExplore technologies for service discovery, including ZooKeeper, Consul, Airbnb’s SmartStack, and Netflix’s EurekaLearn which orchestration solutions—such as Kubernetes and Apache Mesos—work best for your deploymentBe prepared to experiment with different technologies until decent standards emerge        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_5.html#idm139761374471376)
    1. [The Book](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_5.html#idm139761374559952)
    1. [You](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_5.html#idm139761374535840)
    1. [Me](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_5.html#idm139761374542384)
    1. [Acknowledgments](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_5.html#idm139761374539808)
1. [1. Motivation](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_6.html#motivation)
    1. [Go Cattle!](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_6.html#idm139761374447024)
    1. [Docker Networking and Service Discovery Stack](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_6.html#idm139761374571904)
    1. [Do I Need to Go “All In”?](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_6.html#idm139761374736704)
1. [2. Docker Networking 101](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#containers-and-netw)
    1. [Bridge Mode Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#bridge-mode-network)
    1. [Host Mode Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#host-mode-networkin)
    1. [Container Mode Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#container-mode-netw)
    1. [No Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#no-networking)
    1. [Wrapping It Up](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_7.html#wrapping-it-up-netw)
1. [3. Docker Multihost Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#docker-multi-host-n)
    1. [Overlay](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#overlay)
    1. [Flannel](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#flannel)
    1. [Weave](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#weave)
    1. [Project Calico](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#project-calico)
    1. [Open vSwitch](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#open-vswitch)
    1. [Pipework](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#pipework)
    1. [OpenVPN](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#openvpn)
    1. [Future Docker Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#future-docker-netwo)
    1. [Wrapping It Up](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_8.html#wrapping-it-up-mult)
1. [4. Containers and Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#containers-and-serv)
    1. [The Challenge](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#service-discovery-t)
    1. [Technologies](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#service-discovery-t)
        1. [ZooKeeper](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#zookeeper)
        1. [etcd](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#etcd)
        1. [Consul](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#consul)
        1. [Pure-Play DNS-Based Solutions](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#pure-play-dns-based)
        1. [Airbnb’s SmartStack and Netflix’s Eureka](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#airbnbs-smartstack-)
    1. [Load Balancing](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#load-balancing)
    1. [Wrapping It Up](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_9.html#wrapping-it-up-sd)
1. [5. Containers and Orchestration](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#containers-and-orch)
    1. [What Does a Scheduler Actually Do?](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#idm139761370763296)
    1. [Vanilla Docker and Docker Swarm](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#docker)
        1. [Ambassadors](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#docker-ambassadors)
        1. [Docker Swarm](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#docker-swarm)
        1. [Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#docker-orchestratio)
        1. [Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#docker-orchestratio)
    1. [Kubernetes](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#kubernetes)
        1. [Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#kubernetes-networki)
        1. [Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#kubernetes-sd)
    1. [Apache Mesos](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#apache-mesos)
        1. [Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#apache-mesos-networ)
        1. [Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#apache-mesos-sd)
    1. [Hashicorp Nomad](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#hashicorp-nomad)
        1. [Networking](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#hashicorp-nomad-net)
        1. [Service Discovery](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#hashicorp-nomad-sd)
    1. [Which One Should I Use?](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#which-one-should-i-)
        1. [A Day in the Life of a Container](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#container-lifecycle)
        1. [Community Matters](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_10.html#community-matters)
1. [A. References](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_11.html#references-app)
    1. [Networking References](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_11.html#idm139761370544736)
    1. [Service Discovery References](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_11.html#idm139761370534992)
    1. [Related and Advanced References](https://ebookreading.net/view/book/Docker+Networking+and+Service+Discovery-EB9781492042488_11.html#idm139761370522976)
