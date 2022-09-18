![Cover image for SRE with Java Microservices](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9781492073918.jpg)

[SRE with Java Microservices](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_1.html "SRE with Java Microservices")
====================================================================================================================

Author : [Jon Schneider](https://ebookreading.net/search/author/Jon+Schneider)

Release Date : 2020/12/01

ISBN : 9781492073918

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 In a microservices architecture, the whole is indeed greater than the sum of its parts. But in practice, individual microservices can inadvertently impact others and alter the end user experience. Effective microservices architectures require standardization on an organizational level with the help of a platform engineering team.
This practical book provides a series of progressive steps that platform engineers can apply technically and organizationally to achieve highly resilient Java applications. Author Jon Schneider covers many effective SRE practices from companies leading the way in microservices adoption. You’ll examine several patterns that were created after much trial and error in recent years, complete with Java code examples.
Chapters are organized according to specific patterns, including:
Application Metrics: Availability, debuggability, and MicrometerDebugging with observability: Three pillars of observability; components of a distributed traceCharting and alerting: Building effective charts; KPIs for Java microservicesSafe multi-cloud delivery: Automated canary analysisSource code observability: The problem of dependencies; API utilizationTraffic management: Concurrency of systems; platform, gateway, and client-side load balancing        Show and hide more                
Table of Contents
-----------------

1. [1. Application Metrics](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#ch2_app_monitoring)
    1. [Availability](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878249623768)
    1. [Debuggability](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878248929480)
    1. [Black Box vs. White Box Monitoring](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#blackbox_whitebox)
    1. [Dimensional Metrics](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#dimensional_metrics)
        1. [Hierarchical metrics systems](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#hierarchical_metric)
    1. [Introduction to Micrometer](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#intro_to_micrometer)
        1. [Meter registries](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878249547608)
        1. [Creating meters](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878249536216)
        1. [Meter filters](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878248393192)
    1. [Naming Metrics](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#naming_metrics)
    1. [Classes of meters](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247892760)
    1. [Gauges](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247804552)
        1. [Alert criteria](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247740488)
    1. [Counters](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247803608)
        1. [Alert criteria](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247711176)
    1. [Timers](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#timers)
        1. [Common features of latency distributions](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247250040)
        1. [Percentiles/quantiles](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#percentiles_quantil)
        1. [Histograms](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#histograms)
        1. [Service level objective boundaries](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#slo_boundaries)
        1. [Alert criteria](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247114168)
    1. [Distribution summaries](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247695048)
        1. [Alert criteria](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247062216)
    1. [Long task timers](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247057016)
        1. [Alert criteria](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878247011400)
    1. [Choosing the Right Meter Type](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#choosing_meter_type)
    1. [Controlling cost](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#idm45878246992056)
    1. [Coordinated omission](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#coordinated_omissio)
    1. [Load testing](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_4.html#load_testing)
1. [2. Traffic Management](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#ch_traffic_manageme)
    1. [Concurrency of Systems](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246904264)
    1. [Platform Load Balancing](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246900392)
    1. [Gateway Load Balancing](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246896648)
        1. [Join the shortest queue](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246876952)
        1. [Instance-reported utilization](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246864008)
        1. [Choice of two](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246863384)
        1. [Instance probation](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246809032)
        1. [Knock-on effects of smarter load balancing](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246806200)
    1. [Client-side Load Balancing](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246896024)
    1. [Hedge requests](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#hedge_requests)
    1. [Call Resiliency Patterns](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246770312)
        1. [Retries](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246764840)
        1. [Rate limiters](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246750280)
        1. [Bulkheads](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246749656)
        1. [Circuit breakers](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246709384)
        1. [Adaptive concurrency limits](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#adaptive_concurrenc)
        1. [Choosing the right call resiliency pattern](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246626984)
        1. [Implementation in service mesh](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246608856)
        1. [Implementation in RSocket](https://ebookreading.net/view/book/SRE+with+Java+Microservices-EB9781492073918_5.html#idm45878246608296)
