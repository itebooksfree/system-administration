![Cover image for Terraform: Up and Running](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781491977071.jpg)

[Terraform: Up and Running](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_1.html "Terraform: Up and Running")
====================================================================================================================

Author : [Yevgeniy Brikman](https://ebookreading.net/search/author/Yevgeniy+Brikman)

Release Date : 2017/03/01

ISBN : 9781491977071

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Terraform has emerged as a key player in the DevOps world for defining, launching, and managing infrastructure as code (IAC) across a variety of cloud and virtualization platforms, including AWS, Google Cloud, and Azure. This hands-on book is the fastest way to get up and running with Terraform.
Gruntwork co-founder Yevgeniy (Jim) Brikman walks you through dozens of code examples that demonstrate how to use Terraform’s simple, declarative programming language to deploy and manage infrastructure with just a few commands. Whether you’re a novice developer, aspiring DevOps engineer, or veteran sysadmin, this book will take you from Terraform basics to running a full tech stack capable of supporting a massive amount of traffic and a large team of developers.
Compare Terraform to other IAC tools, such as Chef, Puppet, Ansible, and Salt StackUse Terraform to deploy server clusters, load balancers, and databasesLearn how Terraform manages the state of your infrastructure and how it impacts file layout, isolation, and lockingCreate reusable infrastructure with Terraform modulesTry out advanced Terraform syntax to implement loops, if-statements, and zero-downtime deploymentUse Terraform as a team, including best practices for writing, testing, and versioning Terraform code        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207913932800)
    1. [Who Should Read This Book](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207911858512)
    1. [Why I Wrote This Book](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207911645136)
    1. [What You Will Find in This Book](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207911010848)
    1. [What You Won’t Find in This Book](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910900976)
    1. [Open Source Code Examples](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910896000)
    1. [Using the Code Examples](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910882992)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910877952)
    1. [O’Reilly Safari](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910865920)
    1. [How to Contact O’Reilly Media](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910859392)
    1. [Acknowledgments](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_5.html#idm140207910858864)
1. [1. Why Terraform](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#why_terraform)
    1. [The Rise of DevOps](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907752704)
    1. [What Is Infrastructure as Code?](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907752144)
        1. [Ad Hoc Scripts](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907700864)
        1. [Configuration Management Tools](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907685312)
        1. [Server Templating Tools](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#server-templating-t)
        1. [Server Provisioning Tools](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907534208)
    1. [Benefits of Infrastructure as Code](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907246432)
    1. [How Terraform Works](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907220704)
    1. [How Terraform Compares to Other Infrastructure as Code Tools](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#how-terraform-compa)
        1. [Configuration Management Versus Provisioning](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907169632)
        1. [Mutable Infrastructure Versus Immutable Infrastructure](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907157776)
        1. [Procedural Language Versus Declarative Language](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907146848)
        1. [Master Versus Masterless](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907146224)
        1. [Agent Versus Agentless](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907058528)
        1. [Large Community Versus Small Community](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207906885776)
        1. [Mature Versus Cutting Edge](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207906800928)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_6.html#idm140207907191888)
1. [2. Getting Started with Terraform](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#an_intro_to_terrafo)
    1. [Set Up Your AWS Account](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906675888)
    1. [Install Terraform](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906675184)
    1. [Deploy a Single Server](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906608896)
    1. [Deploy a Single Web Server](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906607984)
    1. [Deploy a Configurable Web Server](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906401712)
    1. [Deploy a Cluster of Web Servers](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207906027440)
    1. [Deploy a Load Balancer](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207905250256)
    1. [Cleanup](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207905270672)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_7.html#idm140207904743536)
1. [3. How to Manage Terraform State](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#how_to_manage_terra)
    1. [What Is Terraform State?](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904723184)
    1. [Shared Storage for State Files](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904722592)
    1. [Locking State Files](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904561280)
    1. [Isolating State Files](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904320800)
    1. [File Layout](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#file_layout)
    1. [Read-Only State](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904243984)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_8.html#idm140207904135456)
1. [4. How to Create Reusable Infrastructure with Terraform Modules](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#how_to_create_reusa)
    1. [Module Basics](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207903429328)
    1. [Module Inputs](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207903428736)
    1. [Module Outputs](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207903150288)
    1. [Module Gotchas](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207902528864)
        1. [File Paths](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#use_module_relative)
        1. [Inline Blocks](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207902273520)
    1. [Module Versioning](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207902264896)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_9.html#idm140207901815280)
1. [5. Terraform Tips and Tricks: Loops, If-Statements, Deployment, and Gotchas](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#terraform_tips_tric)
    1. [Loops](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207901499936)
    1. [If-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207901498384)
        1. [Simple If-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900874816)
        1. [More Complicated If-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900874192)
    1. [If-Else-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900205360)
        1. [Simple If-Else-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900172512)
        1. [More Complicated If-Else-Statements](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900172048)
    1. [Zero-Downtime Deployment](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207900060960)
    1. [Terraform Gotchas](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207899221760)
        1. [Count Has Limitations](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898829792)
        1. [Zero-Downtime Deployment has Limitations](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898829296)
        1. [Valid Plans Can Fail](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898564784)
        1. [Refactoring Can Be Tricky](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898564160)
        1. [Eventual Consistency Is Consistent…Eventually](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898533808)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_10.html#idm140207898436928)
1. [6. How to Use Terraform as a Team](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#how_to_use_terrafor)
    1. [Version Control](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898399056)
        1. [A Repository for Modules](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898393136)
        1. [A Repository for Live Infrastructure](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898385392)
        1. [The Golden Rule of Terraform](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898343744)
    1. [Automated Tests](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898254800)
        1. [Prepare Your Code](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898246912)
        1. [Write the Test Code](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207898246096)
        1. [Use Multiple Types of Automated Tests](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897500928)
    1. [Coding Guidelines](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897484560)
        1. [Documentation](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897473344)
        1. [File Layout](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897452352)
        1. [Style Guide](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897440096)
    1. [Workflow](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#workflow_section)
        1. [Plan](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897420448)
        1. [Staging](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897406608)
        1. [Code Review](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897392800)
        1. [Production](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897377360)
        1. [Some Types of Terraform Changes Can Be Automated](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897366720)
        1. [Some Types of Terraform Changes Lead to Conflicts](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897366096)
        1. [Larger Teams May Need to Use a Development Pipeline](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#deployment_pipeline)
    1. [Conclusion](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_11.html#idm140207897428272)
1. [A. Recommended Reading](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#recommended_reading)
    1. [Books](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#idm140207896882464)
    1. [Blogs](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#idm140207896868464)
    1. [Talks](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#idm140207896854912)
    1. [Newsletters](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#idm140207896839792)
    1. [Online Forums](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_12.html#idm140207896832768)
1. [Index](https://ebookreading.net/view/book/Terraform%3A+Up+and+Running-EB9781491977071_13.html#idm140207896697856)
