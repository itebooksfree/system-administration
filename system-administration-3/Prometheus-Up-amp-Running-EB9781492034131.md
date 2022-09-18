![Cover image for Prometheus: Up &amp; Running](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781492034131.jpg)

[Prometheus: Up &amp; Running](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_1.html "Prometheus: Up &amp; Running")
====================================================================================================================

Author : [Brian Brazil](https://ebookreading.net/search/author/Brian+Brazil)

Release Date : 2018/07/01

ISBN : 9781492034131

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Get up to speed with Prometheus, the metrics-based monitoring system used by tens of thousands of organizations in production. This practical guide provides application developers, sysadmins, and DevOps practitioners with a hands-on introduction to the most important aspects of Prometheus, including dashboarding and alerting, direct code instrumentation, and metric collection from third-party systems with exporters.
This open source system has gained popularity over the past few years for good reason. With its simple yet powerful data model and query language, Prometheus does one thing, and it does it well. Author and Prometheus developer Brian Brazil guides you through Prometheus setup, the Node exporter, and the Alertmanager, then demonstrates how to use them for application and infrastructure monitoring.
Know where and how much to apply instrumentation to your application codeIdentify metrics with labels using unique key-value pairsGet an introduction to Grafana, a popular tool for building dashboardsLearn how to use the Node Exporter to monitor your infrastructureUse service discovery to provide different views of your machines and servicesUse Prometheus with Kubernetes and examine exporters you can use with containersConvert data from other monitoring systems into the Prometheus format        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#idm46043484494872)
    1. [Expanding the Known](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#idm46043484493192)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#_conventions_used_i)
    1. [Using Code Examples](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#_using_code_example)
    1. [O’Reilly Safari](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#_safari_books_onlin)
    1. [How to Contact Us](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#_how_to_contact_us)
    1. [Acknowledgments](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_4.html#_acknowledgments)
1. [I. Introduction](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_5.html#part1)
1. [1. What Is Prometheus?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#what_is_prometheus_)
    1. [What Is Monitoring?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#what_is_monitoring)
        1. [A Brief and Incomplete History of Monitoring](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484281112)
        1. [Categories of Monitoring](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484266184)
    1. [Prometheus Architecture](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484322952)
        1. [Client Libraries](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484626040)
        1. [Exporters](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484616312)
        1. [Service Discovery](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484607272)
        1. [Scraping](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484598536)
        1. [Storage](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484590072)
        1. [Dashboards](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484586040)
        1. [Recording Rules and Alerts](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484242344)
        1. [Alert Management](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484238072)
        1. [Long-Term Storage](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484228056)
    1. [What Prometheus Is Not](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_6.html#idm46043484322328)
1. [2. Getting Started with Prometheus](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_7.html#chapter_getting_sta)
    1. [Running Prometheus](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_7.html#idm46043484209704)
    1. [Using the Expression Browser](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_7.html#idm46043483633800)
    1. [Running the Node Exporter](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_7.html#idm46043483681928)
    1. [Alerting](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_7.html#intro_alerting)
1. [II. Application Monitoring](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_8.html#part2)
1. [3. Instrumentation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#instrumentation_cha)
    1. [A Simple Program](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043480059032)
    1. [The Counter](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043480058408)
        1. [Counting Exceptions](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043479740872)
        1. [Counting Size](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043479608552)
    1. [The Gauge](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043479847352)
        1. [Using Gauges](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043479403576)
        1. [Callbacks](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043479172872)
    1. [The Summary](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#summary_metric)
    1. [The Histogram](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#histogram)
        1. [Buckets](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043472640648)
    1. [Unit Testing Instrumentation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043472709848)
    1. [Approaching Instrumentation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043472448088)
        1. [What Should I Instrument?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#idm46043472375576)
        1. [How Much Should I Instrument?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#instrumentation_sca)
        1. [What Should I Name My Metrics?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_9.html#metric_naming)
1. [4. Exposition](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#exposition_chapter)
    1. [Python](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043472224584)
        1. [WSGI](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043472202600)
        1. [Twisted](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043472076120)
        1. [Multiprocess with Gunicorn](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#multiprocess_gunico)
    1. [Go](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#go_exposition)
    1. [Java](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043471529464)
        1. [HTTPServer](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043471521912)
        1. [Servlet](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043471385320)
    1. [Pushgateway](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#pushgateway)
    1. [Bridges](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470945848)
    1. [Parsers](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470711768)
    1. [Exposition Format](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#exposition_format)
        1. [Metric Types](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470652952)
        1. [Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470631192)
        1. [Escaping](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470598104)
        1. [Timestamps](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#format_timestamps)
        1. [check metrics](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_10.html#idm46043470585432)
1. [5. Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#labels_chapter)
    1. [What Are Labels?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470571992)
    1. [Instrumentation and Target Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470562952)
    1. [Instrumentation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470552488)
        1. [Metric](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470428872)
        1. [Multiple Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470417048)
        1. [Child](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#child)
    1. [Aggregating](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#idm46043470552024)
    1. [Label Patterns](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#label_patterns)
        1. [Enum](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#enum_metrics)
        1. [Info](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#info_metrics)
    1. [When to Use Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#when_to_use_labels)
        1. [Cardinality](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_11.html#cardinality_section)
1. [6. Dashboarding with Grafana](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#grafana_chapter)
    1. [Installation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469521800)
    1. [Data Source](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469505192)
    1. [Dashboards and Panels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469492792)
        1. [Avoiding the Wall of Graphs](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469480136)
    1. [Graph Panel](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469468888)
        1. [Time Controls](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469447048)
    1. [Singlestat Panel](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#grafana_singlestat)
    1. [Table Panel](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469415080)
    1. [Template Variables](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_12.html#idm46043469404648)
1. [III. Infrastructure Monitoring](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_13.html#part3)
1. [7. Node Exporter](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#node_exporter_chapt)
    1. [CPU Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#node_cpu)
    1. [Filesystem Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469328392)
    1. [Diskstats Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469295832)
    1. [Netdev Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469295208)
    1. [Meminfo Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469258664)
    1. [Hwmon Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#hwmon)
    1. [Stat Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469231096)
    1. [Uname Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469219432)
    1. [Loadavg Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469210184)
    1. [Textfile Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#textfile_collector)
        1. [Using the Textfile Collector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469180008)
        1. [Timestamps](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_14.html#idm46043469179384)
1. [8. Service Discovery](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#service_discovery_c)
    1. [Service Discovery Mechanisms](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#idm46043469135960)
        1. [Static](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#idm46043469123272)
        1. [File](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#file_sd)
        1. [Consul](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#consul_sd)
        1. [EC2](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#idm46043468927544)
    1. [Relabelling](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#relabelling)
        1. [Choosing What to Scrape](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#idm46043468780024)
        1. [Target Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#target_labels)
    1. [How to Scrape](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#how_to_scrape)
        1. [metric_relabel_configs](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#metric_relabel_conf)
        1. [Label Clashes and honor_labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_15.html#honor_labels)
1. [9. Containers and Kubernetes](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#containers_k8_chapt)
    1. [cAdvisor](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467353016)
        1. [CPU](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467272184)
        1. [Memory](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467284536)
        1. [Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467246392)
    1. [Kubernetes](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467227336)
        1. [Running in Kubernetes](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467202728)
        1. [Service Discovery](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#idm46043467202136)
        1. [kube-state-metrics](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_16.html#kube_state_metrics)
1. [10. Common Exporters](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#common_exporters_ch)
    1. [Consul](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#consul_exporter)
    1. [HAProxy](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#haproxy_exporter)
    1. [Grok Exporter](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#grok_exporter)
    1. [Blackbox](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#blackbox)
        1. [ICMP](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#idm46043466230184)
        1. [TCP](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#idm46043466229240)
        1. [HTTP](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#idm46043466110728)
        1. [DNS](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#idm46043466072120)
        1. [Prometheus Configuration](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_17.html#idm46043466031512)
1. [11. Working with Other Monitoring Systems](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_18.html#other_monitoring_sy)
    1. [Other Monitoring Systems](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_18.html#idm46043465811256)
    1. [InfluxDB](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_18.html#idm46043465810600)
    1. [StatsD](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_18.html#idm46043465694520)
1. [12. Writing Exporters](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_19.html#writing_exporters_c)
    1. [Consul Telemetry](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_19.html#idm46043465605912)
    1. [Custom Collectors](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_19.html#custom_collectors)
        1. [Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_19.html#idm46043464264600)
    1. [Guidelines](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_19.html#idm46043463875112)
1. [IV. PromQL](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_20.html#part4)
1. [13. Introduction to PromQL](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#promql_introduction)
    1. [Aggregation Basics](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#aggregation_basics)
        1. [Gauge](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463626808)
        1. [Counter](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463625896)
        1. [Summary](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#summary_aggregation)
        1. [Histogram](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#histogram_intro)
    1. [Selectors](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#selectors)
        1. [Matchers](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463493128)
        1. [Instant Vector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#instant_vector)
        1. [Range Vector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463433544)
        1. [Offset](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463432952)
    1. [HTTP API](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#idm46043463506696)
        1. [query](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#query_api)
        1. [query_range](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_21.html#query_range)
1. [14. Aggregation Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#promql_aggregation_)
    1. [Grouping](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#grouping)
        1. [without](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462856616)
        1. [by](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#by)
    1. [Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462836264)
        1. [sum](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462738040)
        1. [count](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462728472)
        1. [avg](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462719752)
        1. [stddev and stdvar](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462703912)
        1. [min and max](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462664056)
        1. [topk and bottomk](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462663752)
        1. [quantile](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462647096)
        1. [count_values](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_22.html#idm46043462621528)
1. [15. Binary Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#promql_operators_ch)
    1. [Working with Scalars](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#idm46043462557304)
        1. [Arithmetic Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#idm46043462546600)
        1. [Comparison Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#idm46043462546008)
    1. [Vector Matching](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#vector_matching)
        1. [One-to-One](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#idm46043462449000)
        1. [Many-to-One and group_left](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#group_left)
        1. [Many-to-Many and Logical Operators](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#logical_operators)
    1. [Operator Precedence](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_23.html#idm46043462254136)
1. [16. Functions](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#promql_functions_ch)
    1. [Changing Type](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462216456)
        1. [vector](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462212952)
        1. [scalar](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462201976)
    1. [Math](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462185032)
        1. [abs](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462181128)
        1. [ln, log2, and log10](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462175240)
        1. [exp](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462151976)
        1. [sqrt](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462142984)
        1. [ceil and floor](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462129560)
        1. [round](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462118232)
        1. [clamp_max and clamp_min](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462117576)
    1. [Time and Date](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462096856)
        1. [time](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462091368)
        1. [minute, hour, day_of_week, day_of_month, days_in_month, month, and year](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#date_functions)
        1. [timestamp](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462073928)
    1. [Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462007032)
        1. [label_replace](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043462003240)
        1. [label_join](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461989192)
    1. [Missing Series and absent](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#absent)
    1. [Sorting with sort and sort_desc](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461948488)
    1. [Histograms with histogram_quantile](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461933448)
    1. [Counters](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461920328)
        1. [rate](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#rate)
        1. [increase](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461912728)
        1. [irate](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461875352)
        1. [resets](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461856472)
    1. [Changing Gauges](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461846088)
        1. [changes](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461842312)
        1. [deriv](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#deriv)
        1. [predict_linear](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461816952)
        1. [delta](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461802600)
        1. [idelta](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461794808)
        1. [holt_winters](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#idm46043461785992)
    1. [Aggregation Over Time](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_24.html#_over_time)
1. [17. Recording Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#promql_rules_chapte)
    1. [Using Recording Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#idm46043461713144)
    1. [When to Use Recording Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#idm46043461712552)
        1. [Reducing Cardinality](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#reducing_cardinalit)
        1. [Composing Range Vector Functions](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#idm46043461565960)
        1. [Rules for APIs](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#rules_for_apis)
        1. [How Not to Use Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#idm46043461499896)
    1. [Naming of Recording Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_25.html#naming_rules)
1. [V. Alerting](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_26.html#part5)
1. [18. Alerting](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#alerting_rules_chap)
    1. [Alerting Rules](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#alerting_rules)
        1. [for](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#for)
        1. [Alert Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#idm46043461372056)
        1. [Annotations and Templates](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#alert_templates)
        1. [What Are Good Alerts?](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#good_alerts)
    1. [Configuring Alertmanagers](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#configuring_alertma)
        1. [External Labels](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_27.html#external_labels)
1. [19. Alertmanager](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#alertmanager_chapte)
    1. [Notification Pipeline](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#idm46043461200536)
    1. [Configuration File](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#idm46043461176472)
        1. [Routing Tree](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#routing)
        1. [Receivers](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#receivers_chap_nine)
        1. [Inhibitions](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#idm46043460565928)
    1. [Alertmanager Web Interface](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_28.html#idm46043459789064)
1. [VI. Deployment](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_29.html#part6)
1. [20. Putting It All Together](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#operating_chapter)
    1. [Planning a Rollout](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459752504)
        1. [Growing Prometheus](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#growing_prometheus)
    1. [Going Global with Federation](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#federation)
    1. [Long-Term Storage](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#long_term_storage)
    1. [Running Prometheus](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459636664)
        1. [Hardware](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459574344)
        1. [Configuration Management](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459573720)
        1. [Networks and Authentication](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#prometheus_network)
    1. [Planning for Failure](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#planning_for_failur)
        1. [Alertmanager Clustering](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#alertmanager_cluste)
        1. [Meta- and Cross-Monitoring](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#metamonitoring)
    1. [Managing Performance](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#managing_performanc)
        1. [Detecting a Problem](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459410952)
        1. [Finding Expensive Metrics and Targets](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459394952)
        1. [Reducing Load](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#reducing_load_chap_)
        1. [Horizontal Sharding](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459372440)
    1. [Managing Change](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459334312)
    1. [Getting Help](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_30.html#idm46043459325896)
1. [Index](https://ebookreading.net/view/book/Prometheus%3A+Up+%26amp%3B+Running-EB9781492034131_31.html#idm46043459315400)