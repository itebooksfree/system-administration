![Cover image for IBM DS8880 and z/OS DFSMS: Transparent Cloud Tiering](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9780738442174.jpg)

[IBM DS8880 and z/OS DFSMS: Transparent Cloud Tiering](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_1.html "IBM DS8880 and z/OS DFSMS: Transparent Cloud Tiering")
====================================================================================================================

Author : [Lydia Parziale](https://ebookreading.net/search/author/Lydia+Parziale),[ Eddie Lin](https://ebookreading.net/search/author/+Eddie+Lin),[ Robert Gensler](https://ebookreading.net/search/author/+Robert+Gensler),[ Orlando Ariel Fernandez](https://ebookreading.net/search/author/+Orlando+Ariel+Fernandez),[ Jose Gilbert](https://ebookreading.net/search/author/+Jose+Gilbert)

Release Date : 2018/04/01

ISBN : 9780738442174

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Abstract
This IBM® Redbooks® publication gives a broad understanding of storage clouds and the initial functionality that was introduced for mainframes to have Transparent Cloud Tiering. IBM DFSMS and the IBM DS8880 added functionality to provide elements of serverless data movement, and for IBM z/OS® to communicate with a storage cloud. They introduced the following key areas:
A gateway in the DS8880, which allows the movement of data to and from Object Storage be using a network connection.
DFSMShsm enhancements to support Migrate and Recall functions to and from the Object Storage. Other commands were enhanced to monitor and report on the new functionality.
DFSMShsm uses the Web Enablement toolkit for z/OS to create and access the metadata for specific clouds, containers, and objects.
DFSMSdss enhancements to provide some basic backup and restore functions to and from the cloud.
 This IBM Redbooks publication is divided into the following parts:
Part 1 provides you with an introduction to clouds. You might be new to clouds or have a confused view of cloud terminology. If so, Part 1 is helpful in providing you with the basic knowledge you need.
Part 2 shows you how we set up the Transparent Cloud Tiering in a controlled laboratory and how the new functions work. We provide points to consider to help you set up your storage cloud and integrate it into your operational environment.
Part 3 shows you how we used the new functionality to communicate with the cloud and to send data and retrieve data from it..
        Show and hide more                
Table of Contents
-----------------

1. [Front cover](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_1.html#ww457511)
1. [Notices](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_3.html#ww460066)
    1. [Trademarks](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_3.html#ww459879)
1. [Preface](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_4.html#ww769426)
    1. [Authors](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_4.html#ww788065)
    1. [Now you can become a published author, too!](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_4.html#ww782335)
    1. [Comments welcome](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_4.html#ww775129)
    1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_4.html#ww782351)
1. [Part 1 Cloud Preparation](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_5.html#ww454805)
1. [Chapter 1. Storage Tiering History and the Value of TCT](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww458935)
    1. [1.1 Storage tiers](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww460803)
    1. [1.2 Hardware layers overview](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww460805)
    1. [1.3 Software layers](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww460989)
    1. [1.4 DFSMShsm behavior without TCT](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww463040)
    1. [1.5 Introducing TCT](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_6.html#ww463344)
1. [Chapter 2. Cloud Overview](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww458935)
    1. [2.1 What defines cloud in the context of TCT?](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww458965)
    1. [2.2 Compute cloud versus storage cloud](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww464972)
    1. [2.3 Types of Storage](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww465013)
    1. [2.4 Cloud Storage delivery models](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww465224)
    1. [2.5 Object Storage hierarchy](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww465247)
        1. [2.5.1 Storage cloud hierarchy](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww465075)
        1. [2.5.2 Metadata](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_7.html#ww465123)
1. [Chapter 3. Transparent cloud tiering](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww458935)
    1. [3.1 FICON and TCP/IP data movement](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww468272)
        1. [3.1.1 Data flow on Swift cloud type](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww468532)
        1. [3.1.2 Data flow on S3 and IBM COS types](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww471076)
        1. [3.1.3 Bandwidth considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww469778)
    1. [3.2 Storing and retrieving data by using DFSMS](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww469244)
        1. [3.2.1 Disaster Recovery considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww469301)
        1. [3.2.2 Migration considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww469601)
    1. [3.3 Data replication and copy services with transparent cloud tiering](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww470259)
    1. [3.4 Storage cloud communication](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww470057)
    1. [3.5 Selecting data for storage cloud](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_8.html#ww462090)
1. [Part 2 Cloud setup and use](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_9.html#ww454805)
1. [Chapter 4. Requirements](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww463946)
    1. [4.1 What do I need before running TCT?](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww458965)
        1. [4.1.1 Ethernet connections on DS8880](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww470252)
        1. [4.1.2 z/OS Level](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww470087)
        1. [4.1.3 DS8880 Release Level](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww464295)
        1. [4.1.4 Cloud APIs support](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww477496)
    1. [4.2 Authentication information](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww465974)
        1. [4.2.1 User name and Password](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww472146)
        1. [4.2.2 Endpoint](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww472225)
        1. [4.2.3 Tenant (if Swift)](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww464482)
        1. [4.2.4 Port Number](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww464483)
        1. [4.2.5 Certificates (if using SSL/TLS)](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww466129)
    1. [4.3 TLS/SSL considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww468186)
        1. [4.3.1 External CA versus self-signed certificates with DS8880 and DFSMS/RACF](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_10.html#ww464701)
1. [Chapter 5. Configuring the IBM DS8880 for TCT](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_11.html#ww458935)
    1. [5.1 Configuring the IBM DS8880 for TCT](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_11.html#ww461107)
        1. [5.1.1 Ethernet configuration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_11.html#ww461233)
        1. [5.1.2 Cloud configuration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_11.html#ww461291)
        1. [5.1.3 Configuring DS8880 User for REST API Proxy](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_11.html#ww461225)
1. [Chapter 6. Configuring DFSMS](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww465091)
    1. [6.1 Adding digital certificates to RACF](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww465141)
        1. [6.1.1 Uploading the Certificate files to the z/OS host](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww470066)
        1. [6.1.2 Adding External CA certificates to RACF](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww465143)
        1. [6.1.3 Adding self-signed certificates to RACF](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww465188)
    1. [6.2 Creating a Cloud Construct using ISMF](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww465201)
    1. [6.3 Configuring the DFSMShsm environment](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww472049)
    1. [6.4 Controlling access to the Cloud features](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww470281)
        1. [6.4.1 Controlling access to DFSMSdss](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww470295)
        1. [6.4.2 Controlling access to DFSMShsm](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_12.html#ww469532)
1. [Part 3 Operation and Usage](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_13.html#ww456218)
1. [Chapter 7. DFSMShsm](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww458935)
    1. [7.1 Cloud use overview](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww458965)
    1. [7.2 Cloud container management](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461309)
    1. [7.3 Object management](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461475)
        1. [7.3.1 Migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461769)
        1. [7.3.2 Recall](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461778)
    1. [7.4 Fast Subsequent Migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461782)
    1. [7.5 Migration update and considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww461787)
        1. [7.5.1 Command-driven migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww472448)
        1. [7.5.2 Automatic migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww473192)
        1. [7.5.3 CPU utilization considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww474857)
    1. [7.6 Recall considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww463035)
    1. [7.7 LIST command updates](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww463254)
    1. [7.8 Audit](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww464251)
    1. [7.9 REPORT command](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_14.html#ww463965)
1. [Chapter 8. Using automatic migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_15.html#ww466630)
    1. [8.1 SMS support for automatic migration](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_15.html#ww470914)
        1. [8.1.1 Management Class updates](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_15.html#ww470917)
    1. [8.2 Storage Group affinity enhancements](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_15.html#ww470950)
1. [Chapter 9. Operational integration and reporting considerations](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww458935)
    1. [9.1 Pre-implementation reporting](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460884)
    1. [9.2 Operational monitoring](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww461255)
        1. [9.2.1 Monitoring cloud setting changes](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460887)
        1. [9.2.2 Monitoring migration activities](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460909)
        1. [9.2.3 Monitoring reconnections](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460930)
        1. [9.2.4 Other messages to consider](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460951)
    1. [9.3 Operational reporting](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460965)
        1. [9.3.1 Building reports](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww460968)
        1. [9.3.2 DCOLLECT reports](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_16.html#ww461358)
1. [Back cover](https://ebookreading.net/view/book/IBM+DS8880+and+z%2FOS+DFSMS%3A+Transparent+Cloud+Tiering-EB9780738442174_18.html#ww465861)
