![Cover image for zPDT 2016 Sysplex Extensions](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9780738441443.jpg)

[zPDT 2016 Sysplex Extensions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_1.html "zPDT 2016 Sysplex Extensions")
====================================================================================================================

Author : [Bill Ogden](https://ebookreading.net/search/author/Bill+Ogden),[ Frank Kyne](https://ebookreading.net/search/author/+Frank+Kyne)

Release Date : 2016/02/01

ISBN : 9780738441443

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 This IBM® Redbooks® publication describes the IBM zPDT® 2016 Sysplex Extensions, which is a package that consists of sample files and supporting documentation to help you get a functioning, data sharing, sysplex up and running with minimal time and effort.
This package is designed and tested to be installed on top of a standard ADCD environment. It provides the extra files that you need to create a two-way data sharing IBM z/OS® 2.1 sysplex that runs under ADCD in a zPDT environment.
This package differs from the previous zPDT sysplex package in that it provides working examples of more sysplex exploiters. It also is designed to adhere to IBM's sysplex best practice recommendations, in as far as is possible in a zPDT environment.
Although the package was not tested with IBM Rational® Development and Test for IBM System z® (RD&amp;T), it might be used to reduce the effort to create a fully functional sysplex under RD&amp;T.
Conceptually, the package might also be restored and used as a template to create a sysplex environment that is running on a real IBM z™ Systems CPC.
The target audience for this document is system programmers that are responsible for designing, creating, and maintaining IBM Parallel Sysplex® environments. It can also be beneficial to developers that currently maintain their own ADCD environments and want to extend them to add sysplex functions.
        Show and hide more                
Table of Contents
-----------------

1. [Front cover](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_1.html)
1. [Notices](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_3.html)
    1. [Trademarks](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_3.html#ww459879)
1. [IBM Redbooks promotions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_4.html)
1. [Preface](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_5.html)
    1. [Authors](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_5.html#ww776025)
    1. [Now you can become a published author, too!](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_5.html#ww782335)
    1. [Comments welcome](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_5.html#ww775129)
    1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_5.html#ww782351)
1. [Chapter 1. Introduction](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html)
    1. [1.1 What is sysplex?](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww458971)
    1. [1.2 Base sysplex versus Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww463221)
    1. [1.3 Why did we create this document?](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww461364)
    1. [1.4 Who is this deliverable aimed at?](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww461950)
    1. [1.5 Differences between 2016 Sysplex Extensions and previous version](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww456925)
    1. [1.6 Contents of this document](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_6.html#ww462195)
1. [Chapter 2. System migration considerations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html)
    1. [2.1 System layout recommendations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww458965)
        1. [2.1.1 Avoiding updates to ADCD-provided volumes if possible](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww460891)
        1. [2.1.2 Catalogs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww461166)
        1. [2.1.3 Minimizing changes to provided parmlib members](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww461445)
        1. [2.1.4 Simplifying your system structure](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww462806)
        1. [2.1.5 Summary](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_7.html#ww461834)
1. [Chapter 3. Sysplex configurations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html)
    1. [3.1 zPDT sysplex configurations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww498283)
    1. [3.2 Running a sysplex under zPDT](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww466272)
        1. [3.2.1 High-level concepts](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww468423)
        1. [3.2.2 Planning for CFs under zPDT](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww466287)
        1. [3.2.3 Hardware](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww466320)
        1. [3.2.4 Performance](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww466335)
    1. [3.3 Sysplex goals](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww468845)
        1. [3.3.1 General system characteristics](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww469028)
        1. [3.3.2 z/VM-related sysplex limitations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww514900)
    1. [3.4 System logger](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516741)
        1. [3.4.1 Resource Recovery Services](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516769)
        1. [3.4.2 LOGREC](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516788)
        1. [3.4.3 OPERLOG](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516798)
        1. [3.4.4 System Management Facility](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516821)
    1. [3.5 RACF sysplex usage](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_8.html#ww516828)
1. [Chapter 4. Installing the 2016 Sysplex Extensions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html)
    1. [4.1 Implementing a sysplex under zPDT](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww469485)
    1. [4.2 Implementation overview](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww534555)
    1. [4.3 Setup steps](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww542411)
        1. [4.3.1 Installing the base ADCD system](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww474192)
        1. [4.3.2 Installing z/VM](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww501042)
        1. [4.3.3 Download and create volumes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww520390)
        1. [4.3.4 Establish a known restart point](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww523086)
        1. [4.3.5 Updating devmap to add new volumes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww559236)
        1. [4.3.6 Configuring z/VM guests](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww473026)
        1. [4.3.7 Initializing new volumes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww502771)
        1. [4.3.8 Importing user catalogs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww521494)
        1. [4.3.9 Creating system-specific system data sets](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww469566)
        1. [4.3.10 Creating zFS file systems for system S0W2](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww521189)
        1. [4.3.11 Creating Health Checker persistent data data set for S0W2](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww520547)
        1. [4.3.12 Recataloging master catalog data sets](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww520755)
        1. [4.3.13 SMS changes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww510039)
        1. [4.3.14 JES2 MAS configuration](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww470305)
        1. [4.3.15 Creating PARMLIB members](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww569492)
        1. [4.3.16 Network definitions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww600768)
        1. [4.3.17 Creating PROCLIB members](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww537995)
        1. [4.3.18 Creating TCPPARMS](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww476626)
        1. [4.3.19 Creating VTAMLST members](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww477724)
        1. [4.3.20 Customization for Parallel Sysplex complete](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww570601)
    1. [4.4 Bringing up your Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww478490)
        1. [4.4.1 Parallel sysplex implementation checklist](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww540475)
    1. [4.5 Other steps for base sysplex under z/VM](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww536785)
        1. [4.5.1 Changes to z/VM directory](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww536788)
        1. [4.5.2 Changes in parmlib](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww536803)
        1. [4.5.3 Bringing up your base sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww536815)
    1. [4.6 Implementing a base sysplex without z/VM](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww481004)
        1. [4.6.1 Setting up and starting STP](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww545876)
        1. [4.6.2 Defining CTCs for XCF communication](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww545877)
        1. [4.6.3 Sharing zPDT DASD across PCs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww548528)
        1. [4.6.4 Required parmlib changes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww485805)
        1. [4.6.5 Loading the systems](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww487669)
    1. [4.7 Operating your sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww550065)
        1. [4.7.1 Managing your x3270 sessions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww551744)
        1. [4.7.2 Post-loading messages](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww494819)
        1. [4.7.3 SMF considerations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww601782)
        1. [4.7.4 Sysplex policies](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww561293)
        1. [4.7.5 Shutdown](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww487713)
        1. [4.7.6 Useful commands](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww487703)
        1. [4.7.7 Defining new CDSs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww557446)
        1. [4.7.8 Adding 3390 volumes in Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww543848)
        1. [4.7.9 Adding 3270 terminals in Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww543867)
        1. [4.7.10 Scaling up in Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_9.html#ww543881)
1. [Chapter 5. Sample DB2 data sharing environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html)
    1. [5.1 Setting up the 2016 Sysplex Extensions DB2 data sharing environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww462639)
        1. [5.1.1 Overview of the DB2 environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww462224)
        1. [5.1.2 Implementation](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww460921)
    1. [5.2 Controlling the DB2 data sharing group](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww463119)
    1. [5.3 Maintaining the DB2 environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww462376)
    1. [5.4 Sample batch job to test DB2 data sharing](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_10.html#ww456925)
1. [Chapter 6. Sample CICSplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html)
    1. [6.1 CICSplex overview](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww458965)
    1. [6.2 Setting up the 2016 Sysplex Extensions CICSplex environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww462881)
        1. [6.2.1 SMS changes](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww460905)
        1. [6.2.2 Parmlib changes for CICS](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww461139)
        1. [6.2.3 Adding CICS definitions to VTAMLST](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww460938)
        1. [6.2.4 Importing connect CICS user catalog](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww461457)
        1. [6.2.5 Defining CICS model log streams](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww460951)
        1. [6.2.6 Copying CICS procs to USER.PROCLIB](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww461810)
    1. [6.3 Controlling your CICSplex environment](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww461675)
    1. [6.4 Migration considerations](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_11.html#ww461021)
1. [Appendix A. Sample definitions](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html)
    1. [Sample devmap file](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww457124)
    1. [Sample z/VM Directory entries](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww459026)
    1. [Devices defined in the ADCD-provided IODF](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww462298)
    1. [Sample IEASYMxx member for sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww461934)
    1. [Sample JCL to allocate system-specific data sets](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww461882)
    1. [Job to create USS data sets for second system](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww460781)
    1. [zPDT Disk versioning sample script](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_12.html#ww456145)
1. [Appendix B. Sysplex couple data sets and policies](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_13.html)
    1. [ADCD CDSs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_13.html#ww457948)
    1. [2016 Sysplex Extensions CDSs for Parallel Sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_13.html#ww457966)
    1. [Job to create CDSs](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_13.html#ww458639)
    1. [2016 Sysplex Extensions-provided policies](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_13.html#ww458938)
1. [Appendix C. Alternative disk configuration](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_14.html)
    1. [Alternative configuration for base sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_14.html#ww457948)
1. [Appendix D. Sample IPL flow for sysplex under z/VM](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_15.html)
    1. [Alternative configuration for base sysplex](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_15.html#ww459127)
1. [Appendix E. Additional material](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_16.html)
    1. [Locating the Web material](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_16.html#ww453964)
    1. [Using the Web material](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_16.html#ww453974)
1. [Related publications](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_17.html)
    1. [IBM Redbooks](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_17.html#ww454350)
    1. [Other publications](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_17.html#ww455983)
    1. [Online resources](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_17.html#ww455988)
    1. [Help from IBM](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_17.html#ww456261)
1. [Back cover](https://ebookreading.net/view/book/zPDT+2016+Sysplex+Extensions-EB9780738441443_19.html)
