![Cover image for Kubernetes Patterns](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781492050278.jpg)

[Kubernetes Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_1.html "Kubernetes Patterns")
====================================================================================================================

Author : [Roland Huß](https://ebookreading.net/search/author/Roland+Hu%C3%9F),[ Bilgin Ibryam](https://ebookreading.net/search/author/+Bilgin+Ibryam)

Release Date : 2019/04/01

ISBN : 9781492050278

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 The way developers design, build, and run software has changed significantly with the evolution of microservices and containers. These modern architectures use new primitives that require a different set of practices than most developers, tech leads, and architects are accustomed to. With this focused guide, Bilgin Ibryam and Roland Huß from Red Hat provide common reusable elements, patterns, principles, and practices for designing and implementing cloud-native applications on Kubernetes.
Each pattern includes a description of the problem and a proposed solution with Kubernetes specifics. Many patterns are also backed by concrete code examples. This book is ideal for developers already familiar with basic Kubernetes concepts who want to learn common cloud-native patterns.
You’ll learn about the following pattern categories:
Foundational patterns cover the core principles and practices for building container-based cloud-native applications.Behavioral patterns explore finer-grained concepts for managing various types of container and platform interactions.Structural patterns help you organize containers within a pod, the atom of the Kubernetes platform.Configuration patterns provide insight into how application configurations can be handled in Kubernetes.Advanced patterns cover more advanced topics such as extending the platform with operators.        Show and hide more                
Table of Contents
-----------------

1. [Foreword](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_4.html#idm46299083112392)
1. [Preface](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#preface)
    1. [Kubernetes](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#preface-kubernetes)
    1. [Design Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#preface-design-patt)
    1. [How This Book Is Structured](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299090875112)
    1. [Who This Book Is For](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299076921768)
    1. [What You Will Learn](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299076893064)
    1. [Conventions](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299076821928)
    1. [Using Code Examples](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#preface-code-exampl)
    1. [O’Reilly Online Learning](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299076882152)
    1. [How to Contact Us](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299057478600)
    1. [Acknowledgments](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_5.html#idm46299057477976)
1. [1. Introduction](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#kubernetes-core-con)
    1. [The Path to Cloud Native](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299076816120)
    1. [Distributed Primitives](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077076440)
        1. [Containers](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077043192)
        1. [Pods](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077105928)
        1. [Services](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077084984)
        1. [Labels](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077297960)
        1. [Annotations](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077278216)
        1. [Namespaces](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#concepts-namespaces)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077075848)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_6.html#idm46299077006664)
1. [I. Foundational Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_7.html#part_foundational)
1. [2. Predictable Demands](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#PredictableDemands)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299081006904)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299081000632)
        1. [Runtime Dependencies](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299080993464)
        1. [Resource Profiles](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299080992968)
        1. [Pod Priority](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299076261960)
        1. [Project Resources](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299076261400)
        1. [Capacity Planning](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299076214552)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299076044056)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_8.html#idm46299076037096)
1. [3. Declarative Deployment](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#DeclarativeDeployme)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299076015912)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299076010696)
        1. [Rolling Deployment](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299075985400)
        1. [Fixed Deployment](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299075984776)
        1. [Blue-Green Release](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299075789064)
        1. [Canary Release](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299075778600)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#idm46299075770856)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_9.html#declarative-deploym)
1. [4. Health Probe](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#HealthProbe)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075746312)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075742360)
        1. [Process Health Checks](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075738824)
        1. [Liveness Probes](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075735480)
        1. [Readiness Probes](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075560648)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075530360)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_10.html#idm46299075500760)
1. [5. Managed Lifecycle](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#ManagedLifecycle)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075486552)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075478744)
        1. [SIGTERM Signal](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075469976)
        1. [SIGKILL Signal](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075466792)
        1. [Poststart Hook](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075463416)
        1. [Prestop Hook](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075447128)
        1. [Other Lifecycle Controls](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075322680)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075229576)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_11.html#idm46299075226056)
1. [6. Automated Placement](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#AutomatedPlacement)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075212280)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075207320)
        1. [Available Node Resources](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075202280)
        1. [Container Resource Demands](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075192824)
        1. [Placement Policies](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075186888)
        1. [Scheduling Process](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075186648)
        1. [Node Affinity](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299074994200)
        1. [Pod Affinity and Antiaffinity](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299074786104)
        1. [Taints and Tolerations](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299074600872)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299075206824)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_12.html#idm46299074385240)
1. [II. Behavioral Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_13.html#part_behavioral)
1. [7. Batch Job](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_14.html#BatchJob)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_14.html#idm46299074344808)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_14.html#idm46299074327368)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_14.html#idm46299074326808)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_14.html#idm46299074138488)
1. [8. Periodic Job](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_15.html#PeriodicJob)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_15.html#idm46299074120056)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_15.html#idm46299074109304)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_15.html#idm46299073971544)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_15.html#idm46299074026776)
1. [9. Daemon Service](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_16.html#DaemonService)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_16.html#idm46299073936328)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_16.html#idm46299073930328)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_16.html#idm46299073929704)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_16.html#idm46299073747496)
1. [10. Singleton Service](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#SingletonService)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#idm46299073730280)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#idm46299073708328)
        1. [Out-of-Application Locking](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#singleton-locking-o)
        1. [In-Application Locking](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#singleton-locking-i)
        1. [Pod Disruption Budget](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#idm46299073669896)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#idm46299073602248)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_17.html#idm46299073570792)
1. [11. Stateful Service](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#StatefulService)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073556840)
        1. [Storage](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073545832)
        1. [Networking](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073540648)
        1. [Identity](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073537848)
        1. [Ordinality](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073535592)
        1. [Other Requirements](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073533608)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073556280)
        1. [Storage](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073456696)
        1. [Networking](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073450024)
        1. [Identity](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073449400)
        1. [Ordinality](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073228312)
        1. [Other Features](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073219208)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#idm46299073528264)
    1. [More information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_18.html#statefulset-more-in)
1. [12. Service Discovery](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#ServiceDiscovery)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299073165464)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299073149544)
        1. [Internal Service Discovery](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299073136920)
        1. [Manual Service Discovery](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299073136296)
        1. [Service Discovery from Outside the Cluster](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299072969672)
        1. [Application Layer Service Discovery](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299072805848)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299072535736)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_19.html#idm46299072306376)
1. [13. Self Awareness](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_20.html#SelfAwareness)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_20.html#idm46299072288392)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_20.html#idm46299072283688)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_20.html#idm46299072283032)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_20.html#idm46299071977528)
1. [III. Structural Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_21.html#part_structural)
1. [14. Init Container](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_22.html#InitContainer)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_22.html#idm46299071950024)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_22.html#idm46299071945016)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_22.html#idm46299071944392)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_22.html#idm46299071691080)
1. [15. Sidecar](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_23.html#Sidecar)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_23.html#idm46299071663448)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_23.html#idm46299071658632)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_23.html#idm46299071415688)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_23.html#idm46299071410424)
1. [16. Adapter](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_24.html#Adapter)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_24.html#idm46299071537112)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_24.html#idm46299071532744)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_24.html#idm46299071140568)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_24.html#idm46299071135560)
1. [17. Ambassador](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_25.html#Ambassador)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_25.html#idm46299071122536)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_25.html#idm46299071117272)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_25.html#idm46299071006600)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_25.html#idm46299070969544)
1. [IV. Configuration Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_26.html#part_configuration)
1. [18. EnvVar Configuration](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_27.html#EnvVarConfiguration)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_27.html#idm46299070942040)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_27.html#idm46299070936344)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_27.html#idm46299070935720)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_27.html#idm46299070640568)
1. [19. Configuration Resource](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_28.html#ConfigurationResour)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_28.html#idm46299070628424)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_28.html#idm46299070618456)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_28.html#idm46299070617480)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_28.html#idm46299070617080)
1. [20. Immutable Configuration](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#ImmutableConfigurat)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299070218328)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299070193144)
        1. [Docker Volumes](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299070190232)
        1. [Kubernetes Init Containers](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#immutable-configura)
        1. [OpenShift Templates](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299070159944)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299069693560)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_29.html#idm46299069810488)
1. [21. Configuration Template](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_30.html#ConfigurationTempla)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_30.html#idm46299069859704)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_30.html#idm46299069987448)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_30.html#idm46299069533080)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_30.html#idm46299069487752)
1. [V. Advanced Patterns](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_31.html#part_advanced)
1. [22. Controller](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_32.html#Controller)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_32.html#idm46299069314024)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_32.html#idm46299069301032)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_32.html#idm46299069299448)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_32.html#controller-more-inf)
1. [23. Operator](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#Operator)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#idm46299068330264)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#idm46299068318920)
        1. [Custom Resource Definitions](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#Operator-crd)
        1. [Controller and Operator Classification](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#idm46299068314856)
        1. [Operator Development and Deployment](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#idm46299067993928)
        1. [Example](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#Operator-example)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#idm46299067920072)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_33.html#operator-more-infor)
1. [24. Elastic Scale](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#ElasticScale)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299067349336)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299067344088)
        1. [Manual Horizontal Scaling](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299067341096)
        1. [Horizontal Pod Autoscaling](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#elasticscale-horizo)
        1. [Vertical Pod Autoscaling](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#elasticscale-vertic)
        1. [Cluster Autoscaling](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299067034856)
        1. [Scaling Levels](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299066918856)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#idm46299066868616)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_34.html#elastic-scale-more-)
1. [25. Image Builder](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#ImageBuilder)
    1. [Problem](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#idm46299066830168)
    1. [Solution](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#idm46299066808200)
        1. [OpenShift Build](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#image-builder-opens)
        1. [Knative Build](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#image-builder-knati)
    1. [Discussion](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#idm46299066419912)
    1. [More Information](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_35.html#idm46299065952872)
1. [Afterword](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_36.html#idm46299065926264)
    1. [Ubiquitous Platform](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_36.html#idm46299065925048)
    1. [Hybrid Responsibilities](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_36.html#idm46299065922776)
    1. [What We Covered](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_36.html#idm46299065920424)
    1. [Final Words](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_36.html#idm46299065910120)
1. [Index](https://ebookreading.net/view/book/Kubernetes+Patterns-EB9781492050278_37.html#idm46299065907336)
