![Cover image for Getting Started with Terraform - Second Edition](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781788623537.jpg)

[Getting Started with Terraform - Second Edition](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_1.html "Getting Started with Terraform - Second Edition")
====================================================================================================================

Author : [Kirill Shirinkin](https://ebookreading.net/search/author/Kirill+Shirinkin)

Release Date : 2017/07/01

ISBN : 9781788623537

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Build, Manage and Improve your infrastructure effortlessly.
About This Book
An up-to-date and comprehensive resource on Terraform that lets you quickly and efficiently launch your infrastructureLearn how to implement your infrastructure as code and make secure, effective changes to your infrastructureLearn to build multi-cloud fault-tolerant systems and simplify the management and orchestration of even the largest scale and most complex cloud infrastructuresWho This Book Is For
This book is for developers and operators who already have some exposure to working with infrastructure but want to improve their workflow and introduce infrastructure as a code practice. Knowledge of essential Amazon Web Services components (EC2, VPC, IAM) would help contextualize the examples provided. Basic understanding of Jenkins and Shell scripts will be helpful for the chapters on the production usage of Terraform.
What You Will Learn
Understand what Infrastructure as Code (IaC) means and why it mattersInstall, configure, and deploy TerraformTake full control of your infrastructure in the form of codeManage complete infrastructure, starting with a single server and scaling beyond any limitsDiscover a great set of production-ready practices to manage infrastructureSet up CI/CD pipelines to test and deliver Terraform stacksConstruct templates to simplify more complex provisioning tasksIn Detail
Terraform is a tool used to efficiently build, configure, and improve the production infrastructure. It can manage the existing infrastructure as well as create custom in-house solutions.
This book shows you when and how to implement infrastructure as a code practices with Terraform. It covers everything necessary to set up the complete management of infrastructure with Terraform, starting with the basics of using providers and resources. It is a comprehensive guide that begins with very small infrastructure templates and takes you all the way to managing complex systems, all using concrete examples that evolve over the course of the book. The book ends with the complete workflow of managing a production infrastructure as code???this is achieved with the help of version control and continuous integration. The readers will also learn how to combine multiple providers in a single template and manage different code bases with many complex modules. It focuses on how to set up continuous integration for the infrastructure code.
The readers will be able to use Terraform to build, change, and combine infrastructure safely and efficiently.
Style and approach
This book will help and guide you to implement Terraform in your infrastructure. The readers will start by working on very small infrastructure templates and then slowly move on to manage complex systems, all by using concrete examples that will evolve during the course of the book.
Downloading the example code for this book. You can download the example code files for all Packt books you have purchased from your account at http://www.PacktPub.com. If you purchased this book elsewhere, you can visit http://www.PacktPub.com/support and register to have the code file.
        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_15.html)
    1. [What this book covers](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_16.html)
    1. [What you need for this book](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_17.html)
    1. [Who this book is for](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_18.html)
    1. [Conventions](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_19.html)
    1. [Reader feedback](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_20.html)
    1. [Customer support](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_21.html)
        1. [Downloading the example code](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_22.html)
        1. [Downloading the color images of this book](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_23.html)
        1. [Errata](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_24.html)
        1. [Piracy](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_25.html)
        1. [Questions](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_26.html)
1. [Infrastructure Automation](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_27.html)
    1. [What is Infrastructure as Code and why is it needed?](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_28.html)
    1. [Declarative versus procedural tools for Infrastructure as Code](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_29.html)
    1. [Infrastructure as Code in the Cloud](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_30.html)
    1. [Requirements for infrastructure provisioner](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_31.html)
        1. [Supports a wide variety of services](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_32.html)
        1. [Idempotency](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_33.html)
        1. [Dependency resolution](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_34.html)
        1. [Robust integration with existing tools](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_35.html)
        1. [Platform agnosticism](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_36.html)
        1. [Smart update management](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_37.html)
        1. [Ease of extension](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_38.html)
    1. [Which tools exist for infrastructure provisioning?](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_39.html)
        1. [Scripting](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_40.html)
        1. [Configuration management](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_41.html)
        1. [CloudFormation/Heat](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_42.html)
        1. [Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_43.html)
    1. [A short overview of Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_44.html)
    1. [Journey ahead and how to read this book](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_45.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_46.html)
1. [Deploying First Server](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_47.html)
    1. [History of Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_48.html)
    1. [Preparing work environment](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_49.html)
    1. [The many Terraform providers](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_50.html)
    1. [Short introduction to AWS](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_51.html)
    1. [Using Elastic Compute Cloud](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_52.html)
        1. [Creating an instance through the Management Console](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_53.html)
        1. [Creating an instance with AWS CLI](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_54.html)
    1. [Configuring AWS provider](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_55.html)
        1. [Static credentials](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_56.html)
        1. [Environment variables](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_57.html)
        1. [Credentials file](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_58.html)
    1. [Creating an EC2 instance with Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_59.html)
    1. [Working with state](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_60.html)
    1. [Handling resource updates](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_61.html)
    1. [Destroying everything we&#39;ve built](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_62.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_63.html)
1. [Resource Dependencies and Modules](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_64.html)
    1. [Creating an AWS Virtual Private Cloud](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_65.html)
    1. [Understanding dependency graph](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_66.html)
    1. [Playing with Terraform graphs](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_67.html)
    1. [Controlling dependencies with depends_on and ignore_changes](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_68.html)
    1. [Making sense of our template](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_69.html)
    1. [Removing duplication with modules](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_70.html)
    1. [Configuring modules](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_71.html)
    1. [Retrieving module data with outputs](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_72.html)
    1. [Using root module outputs](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_73.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_74.html)
1. [Storing and Supplying Configuration](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_75.html)
    1. [Understanding variables](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_76.html)
        1. [Using map variables](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_77.html)
        1. [Using list variables](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_78.html)
        1. [Supplying variables inline](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_79.html)
        1. [Using Terraform environment variables](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_80.html)
        1. [Using variable files](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_81.html)
    1. [Configuring data sources](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_82.html)
        1. [Providing configuration with template_file](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_83.html)
        1. [Providing data from anywhere with external_data](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_84.html)
    1. [Exploring Terraform configuration resources](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_85.html)
    1. [Taking a quick look at Consul](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_86.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_87.html)
1. [Connecting with Other Tools](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_88.html)
    1. [Returning data with outputs](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_89.html)
    1. [Testing servers with Inspec](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_90.html)
    1. [Provisioners](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_91.html)
        1. [Provisioning with local-exec and Ansible](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_92.html)
        1. [Provisioning with Chef](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_93.html)
        1. [Provisioning with remote-exec and Puppet](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_94.html)
        1. [Uploading files with a file provisioner](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_95.html)
    1. [Reprovisioning machines with null_resource](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_96.html)
    1. [Using third-party plugins](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_97.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_98.html)
1. [Scaling and Updating Infrastructure](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_99.html)
    1. [Counting servers](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_100.html)
    1. [Bringing in high availability](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_101.html)
    1. [Load balancing and simulating conditionals](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_102.html)
    1. [Immutable infrastructure](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_103.html)
    1. [Baking images with Packer](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_104.html)
    1. [Rolling out AMI upgrades with Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_105.html)
    1. [Performing blue-green deployments](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_106.html)
    1. [Refreshing infrastructure](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_107.html)
    1. [Importing resources](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_108.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_109.html)
1. [Collaborative Infrastructure](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_110.html)
    1. [Version control with Git 101](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_111.html)
    1. [Moving templates to Git](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_112.html)
    1. [Protecting secrets in a Git repository](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_113.html)
    1. [Storing state files remotely](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_114.html)
    1. [Connecting remote states together](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_115.html)
    1. [Storing modules remotely](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_116.html)
    1. [Locking state files with Terragrunt](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_117.html)
    1. [Moving infrastructure updates to the CI pipeline](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_118.html)
    1. [Integration testing of Terraform modules](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_119.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_120.html)
1. [Future of Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_121.html)
    1. [Infrastructure as code and Terraform replacements](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_122.html)
    1. [Learning AWS and compiling Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_123.html)
    1. [Learning Consul](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_124.html)
    1. [Provisioning and configuration management](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_125.html)
    1. [Immutable infrastructure](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_126.html)
    1. [Collaboration and CI/CD](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_127.html)
    1. [The many tools around Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_128.html)
    1. [The rapid development of Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_129.html)
    1. [Closing thoughts on the future of Terraform](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_130.html)
    1. [Summary](https://ebookreading.net/view/book/Getting+Started+with+Terraform+-+Second+Edition-EB9781788623537_131.html)
