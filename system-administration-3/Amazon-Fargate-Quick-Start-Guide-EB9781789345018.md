![Cover image for Amazon Fargate Quick Start Guide](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781789345018.jpg)

[Amazon Fargate Quick Start Guide](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_1.html "Amazon Fargate Quick Start Guide")
====================================================================================================================

Author : [Deepak Vohra](https://ebookreading.net/search/author/Deepak+Vohra)

Release Date : 2018/07/01

ISBN : 9781789345018

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 This book gets you started and gives you knowledge about AWS Fargate in order to successfully incorporate it in your ECS container application.
Key FeaturesGives you a quick walk-through over the Amazon Elastic Container Services (ECS) Provides  an in depth  knowledge of the components that Amazon Fargate has to offer.  Learn the practical aspects of Docker application development with a managed service Amazon Fargate is new launch type for the Amazon Elastic Container Service (ECS). ECS is an AWS service for Docker container orchestration. Docker is the de facto containerization framework and has revolutionized packaging and deployment of software. The introduction of Fargate has made the ECS platform serverless. 
The book takes you through how Amazon Fargate runs ECS services composed of tasks and Docker containers and exposes the containers to the user. Fargate has simplified the ECS platform. We will learn how Fargate creates an Elastic Network Interface (ENI) for each task and how auto scaling can be enabled for ECS tasks.  
You will also learn about using an IAM policy to download Docker images and send logs to CloudWatch.  
Finally, by the end of this book, you will have learned about how to use ECS CLI to create an ECS cluster and deploy tasks with Docker Compose.  
What you will learnRunning Docker containers with a managed service Use Amazon ECS in Fargate launch mode Configure CloudWatch Logging with Fargate Use an IAM Role with Fargate Understand how ECS CLI is used with Fargate Learn how to use an Application Load Balancer with Fargate Learn about Auto Scaling with FargateWho this book is forThis book is for Docker users and developers who want  to learn about the Fargate platform. Typical job roles for which the book is suitable are DevOps Architect, Docker Engineer, and AWS Cloud Engineer. Prior knowledge of AWS and ECS is helpful but not mandatory. 
        Show and hide more                
Table of Contents
-----------------

1. [Title Page](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_2.html)
1. [Copyright and Credits](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_3.html)
    1. [Amazon Fargate Quick Start Guide](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_4.html)
1. [Packt Upsell](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_5.html)
    1. [Why subscribe?](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_6.html)
    1. [PacktPub.com](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_7.html)
1. [Contributors](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_8.html)
    1. [About the author](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_9.html)
    1. [About the reviewer](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_10.html)
    1. [Packt is searching for authors like you](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_11.html)
1. [Preface](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_13.html)
    1. [Who this book is for](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_14.html)
    1. [What this book covers](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_15.html)
    1. [To get the most out of this book](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_16.html)
        1. [Download the example code files](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_17.html)
        1. [Download the color images](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_18.html)
        1. [Conventions used](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_19.html)
    1. [Get in touch](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_20.html)
        1. [Reviews](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_21.html)
1. [Getting Started with Amazon ECS and Amazon Fargate](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_22.html)
    1. [What Amazon Fargate is](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_23.html)
    1. [Benefits of Fargate](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_24.html)
    1. [&amp;#xA0;Amazon ECS objects](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_25.html)
    1. [Compute resources in Amazon ECS Fargate](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_26.html)
    1. [What is new in the Amazon Fargate launch type mode?](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_27.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_28.html)
1. [Networking](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_29.html)
    1. [Creating an ECS cluster and service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_30.html)
        1. [Configuring a Container definition](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_31.html)
        1. [Configuring a Task definition](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_32.html)
        1. [Configuring a service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_33.html)
        1. [Configuring and creating a cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_34.html)
    1. [Running additional tasks](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_35.html)
    1. [Accessing the service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_36.html)
    1. [Deleting a cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_37.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_38.html)
1. [Using CloudWatch Logs](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_39.html)
    1. [Overview of CloudWatch Logs and aws log driver](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_40.html)
    1. [Creating an ECS service for MySQL database](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_41.html)
    1. [Configuring a Container definition](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_42.html)
    1. [Configuring logging](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_43.html)
    1. [Configuring a Task definition](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_44.html)
    1. [Configuring a service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_45.html)
    1. [Configuring a cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_46.html)
    1. [Creating an ECS service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_47.html)
    1. [Exploring Task logs](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_48.html)
    1. [Exploring CloudWatch Logs](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_49.html)
    1. [Exploring CloudWatch metrics](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_50.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_51.html)
1. [Using Auto Scaling](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_52.html)
    1. [Creating an ECS service for a Hello world application](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_53.html)
    1. [Types of auto scaling](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_54.html)
        1. [Target tracking scaling policies](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_55.html)
        1. [Step scaling policies](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_56.html)
    1. [Configuring an auto scaling policy](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_57.html)
        1. [Defining the range of tasks](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_58.html)
        1. [Adding an auto scaling policy](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_59.html)
        1. [Adding a step scaling policy](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_60.html)
        1. [Creating a CloudWatch alarm](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_61.html)
        1. [Configuring a scaling action](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_62.html)
    1. [Demonstrating the use of auto scaling](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_63.html)
    1. [Exploring CloudWatch metrics and Logs](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_64.html)
    1. [Updating auto scaling policy&amp;#xA0;](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_65.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_66.html)
1. [Using IAM](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_67.html)
    1. [Creating an IAM user](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_68.html)
    1. [Adding a custom policy for Elastic Load Balancing](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_69.html)
    1. [Logging in as the IAM user](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_70.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_71.html)
1. [Using an Application Load Balancer](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_72.html)
    1. [Creating an application load balancer](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_73.html)
    1. [Creating a task definition](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_74.html)
    1. [Creating a service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_75.html)
    1. [Configuring an application load balancer](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_76.html)
    1. [Invoking the Hello World application](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_77.html)
    1. [Stopping tasks and deleting a load balancer](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_78.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_79.html)
1. [Using Amazon ECS CLI](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_80.html)
    1. [Setting up the environment](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_81.html)
    1. [Installing ECS CLI](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_82.html)
    1. [Installing AWS Tools for Windows PowerShell](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_83.html)
    1. [Configuring ECS CLI](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_84.html)
        1. [Setting up a CLI profile](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_85.html)
    1. [Setting up prerequisites for Fargate](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_86.html)
    1. [Registering the task execution policy](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_87.html)
    1. [Creating an ECS cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_88.html)
    1. [Creating a security group](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_89.html)
    1. [Granting security group Ingress](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_90.html)
    1. [Creating a compose file](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_91.html)
    1. [Configuring ECS specific parameters](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_92.html)
    1. [Deploying the compose file to the cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_93.html)
    1. [Listing the running containers on the cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_94.html)
    1. [Listing the container logs](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_95.html)
    1. [Scaling the tasks on the cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_96.html)
    1. [Accessing the WordPress service](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_97.html)
    1. [Deleting the service and the cluster](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_98.html)
    1. [Summary](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_99.html)
1. [Other Books You May Enjoy](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_100.html)
    1. [Leave a review - let other readers know what you think](https://ebookreading.net/view/book/Amazon+Fargate+Quick+Start+Guide-EB9781789345018_101.html)
