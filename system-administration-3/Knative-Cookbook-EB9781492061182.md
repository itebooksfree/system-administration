![Cover image for Knative Cookbook](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781492061182.jpg)

[Knative Cookbook](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_1.html "Knative Cookbook")
====================================================================================================================

Author : [Burr Sutter](https://ebookreading.net/search/author/Burr+Sutter),[ 
            Kamesh Sampath](https://ebookreading.net/search/author/+%0D%0A++++++++++++Kamesh+Sampath)

Release Date : 2020/04/01

Book Description
-----------------


    
    Enterprise developers face several challenges when it comes to building serverless applications, such as integrating applications and building container images from source. With more than 60 practical recipes, this cookbook helps you solve these issues with Knative—the first serverless platform natively designed for Kubernetes. Each recipe contains detailed examples and exercises, along with a discussion of how and why it works.
If you have a good understanding of serverless computing and Kubernetes core resources such as deployment, services, routes, and replicas, the recipes in this cookbook show you how to apply Knative in real enterprise application development. Authors Kamesh Sampath and Burr Sutter include chapters on autoscaling, build and eventing, observability, Knative on OpenShift, and more.
With this cookbook, you’ll learn how to:
Efficiently build, deploy, and manage modern serverless workloadsApply Knative in real enterprise scenarios, including advanced eventingMonitor your Knative serverless applications effectivelyIntegrate Knative with CI/CD principles, such as using pipelines for faster, more successful production deploymentsDeploy a rich ecosystem of enterprise integration patterns and connectors in Apache Camel K as Kubernetes and Knative components
  

Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661151746552)
    1. [Why We Wrote This Book](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157553864)
    1. [Who Should Read This Book](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157397656)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157394904)
    1. [Using Code Examples](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157449000)
    1. [Staying Up to Date](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157533896)
    1. [O’Reilly Online Learning](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157429640)
    1. [How to Contact Us](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157423256)
    1. [Acknowledgments](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_4.html#idm45661157422632)
1. [1. Getting Started with Knative](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#ch01-getting-starte)
    1. [1.1. Installing the Required Tools](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661157328776)
    1. [1.2. Setting Up a Kubernetes Cluster](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661157668584)
    1. [1.3. Installing the Internal Kubernetes Container Registry](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661150248280)
    1. [1.4. Configuring Container Registry Aliases](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661150196568)
    1. [1.5. Installing Istio](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661149773288)
    1. [1.6. Installing Knative](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661149739016)
    1. [1.7. Verifying the Container Environment](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661149677240)
    1. [Creating Kubernetes Namespaces for This Book’s Recipes](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661149469272)
    1. [Querying Kubernetes Resources](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_5.html#idm45661149311096)
1. [2. Understanding Knative Serving](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#ch02-introduction-k)
    1. [Knative Serving Deployment Model](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#idm45661149253912)
    1. [2.1. Deploying a Knative Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#idm45661149119288)
    1. [2.2. Updating a Knative Service Configuration](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#idm45661148983112)
    1. [2.3. Distributing Traffic Between Knative Service Revisions](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#idm45661148511320)
    1. [2.4. Applying the Blue-Green Deployment Pattern](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#blue-green)
    1. [2.5. Applying the Canary Release Pattern](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_6.html#canary)
1. [3. Autoscaling Knative Services](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_7.html#ch03-introduction-k)
    1. [3.1. Configuring Knative Service for Autoscaling](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_7.html#idm45661147471032)
    1. [3.2. Observing Scale-to-Zero](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_7.html#idm45661147290264)
    1. [3.3. Configuring Your Knative Service to Handle Request Spikes](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_7.html#idm45661147134952)
    1. [3.4. Cold Start Latency](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_7.html#ch3-cold-start-late)
1. [4. Knative Eventing](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-knative-eventi)
    1. [Usage Patterns](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#idm45661146442296)
    1. [4.1. Producing Events with Eventing Sources](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#idm45661146445304)
    1. [4.2. Receiving Events with Knative Eventing Sinks](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#idm45661146215944)
    1. [4.3. Deploying a Knative Eventing Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-craft-a-servic)
    1. [4.4. Connecting a Source to the Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-source-to-serv)
    1. [4.5. Deploying an Apache Kafka Cluster](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-kafka-knative-)
    1. [4.6. Sourcing Apache Kafka Events with Knative Eventing](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-kafka-knative-)
    1. [4.7. Autoscaling with Apache Kafka and Knative Eventing](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-kafka-knative-)
    1. [4.8. Using a Kafka Channel as the Default Knative Channel](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#idm45661144532888)
    1. [4.9. Using Knative Channels and Subscriptions](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-channels-subsc)
    1. [4.10. Using Knative Eventing Brokers and Triggers](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_8.html#ch04-brokers-trigge)
1. [5. Observability](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#ch05-observability)
    1. [5.1. Deploying Prometheus and Grafana](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142839592)
    1. [5.2. Enable Prometheus for Metrics Collection](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142602184)
    1. [5.3. Installing Jaeger](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142497432)
    1. [5.4. Deploying Observable Test Services](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142282008)
    1. [5.5. Customizing the kubectl Output Columns](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142196872)
    1. [5.6. Restricting Knative Service Visibility](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#service-visibility)
    1. [Grafana Dashboards](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661142018440)
    1. [5.7. Monitoring Autoscaling Metrics of a Knative Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661141913368)
    1. [5.8. Monitoring HTTP Performance Metrics of a Knative Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661141842536)
    1. [5.9. Tracing Knative Services with Jaeger](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_9.html#idm45661141811880)
1. [6. Serverless Integration Patterns Using Apache Camel-K](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#ch06-serverless-pat)
    1. [6.1. Installing Camel-K](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661141699192)
    1. [6.2. Configuring Camel-K to Build Faster](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661141576600)
    1. [6.3. Writing a Camel-K Integration](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661141403800)
    1. [6.4. Running Camel-K Integrations as Knative Serverless Services](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661141219448)
    1. [6.5. Using Knative Eventing with Camel-K](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661141011848)
    1. [6.6. Logging and Displaying CloudEvents Messages](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661140636840)
    1. [6.7. Wiring a CamelSource to a Knative Eventing Sink](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661140572616)
    1. [6.8. Applying Enterprise Integration Patterns with Camel-K](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661140195752)
    1. [6.9. Deploying a Data Producer](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661140033976)
    1. [6.10. Deploying a Data Processor](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661139780264)
    1. [6.11. Deploying an Event Subscriber](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661139698840)
    1. [6.12. Filtering Data with Knative Eventing](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_10.html#idm45661139674040)
1. [7. Knative on OpenShift](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_11.html#ch07-knative-opensh)
    1. [7.1. Installing Knative Serving](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_11.html#idm45661138925784)
    1. [7.2. Deploying a Knative Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_11.html#idm45661138899544)
    1. [7.3. Verifying and Invoking a Knative Service](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_11.html#idm45661138573896)
1. [Index](https://ebookreading.net/view/book/Knative+Cookbook-EB9781492061182_12.html#idm45661138534408)
