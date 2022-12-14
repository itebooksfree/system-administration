![Cover image for IBM PowerKVM Configuration and Use](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB0738439940.jpg)

[IBM PowerKVM Configuration and Use](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_1.html "IBM PowerKVM Configuration and Use")
====================================================================================================================

Author : [Dinar Valeev](https://ebookreading.net/search/author/Dinar+Valeev),[ Breno Leitao](https://ebookreading.net/search/author/+Breno+Leitao),[ Rafael Folco](https://ebookreading.net/search/author/+Rafael+Folco),[ Thadeu Cascardo](https://ebookreading.net/search/author/+Thadeu+Cascardo)

Release Date : 2014/10/01

ISBN : 0738439940

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

This IBM® Redbooks® publication presents the new IBM PowerKVM virtualization for scale-out Linux systems. PowerKVM is open source server virtualization that is based on the IBM POWER8™ technology. It includes the Linux open source technology of KVM virtualization, and it complements the performance, scalability, and security qualities of Linux.
This book describes the concepts of PowerKVM and how you can deploy your virtual machines with the software stack included in the product. It helps you install and configure PowerKVM on your Power System server and provides guidance for managing the supported virtualization features by using the Web interface and command-line interface (CLI).
This information for professionals who want to acquire a better understanding of PowerKVM virtualization technology to optimize Linux workload consolidation and use the new POWER8 processor features. The intended audience also includes people in these roles:
Clients
Sales and marketing professionals
Technical support professionals
IBM Business Partners
Independent software vendors
Open source community
IBM OpenPower™ partners
It does not replace the latest marketing materials and configuration tools. It is intended as an additional source of information that, together with existing sources, can be used to enhance your knowledge of IBM virtualization solutions.
Before you start reading, you must be familiar with the general concepts of kernel-based virtual machine (KVM), Linux, and IBM Power architecture.
              
Table of Contents
-----------------

1. [Front cover](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_1.html)
1. [Figures](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_3.html)
1. [Tables](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_4.html)
1. [Examples](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_5.html)
1. [Preface](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_6.html)
    1. [Authors](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_6.html#ww785754)
    1. [Now you can become a published author, too](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_6.html#ww786029)
    1. [Comments welcome](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_6.html#ww775129)
    1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_6.html#ww782351)
1. [Notices](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_7.html)
    1. [Trademarks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_7.html#ww459879)
1. [Chapter 1. Introduction](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html)
    1. [1.1 IBM Power Systems](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469107)
        1. [1.1.1 POWER8 processors](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469112)
        1. [1.1.2 IBM scale-out servers](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469133)
        1. [1.1.3 Power virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469179)
        1. [1.1.4 Simultaneous multithreading](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469195)
        1. [1.1.5 Memory architecture](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469199)
        1. [1.1.6 Microthreading](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469220)
        1. [1.1.7 RAS features](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469233)
    1. [1.2 Virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469245)
        1. [1.2.1 PowerKVM hardware](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww479169)
        1. [1.2.2 PowerKVM versions](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469292)
        1. [1.2.3 PowerKVM 2.1 considerations](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469324)
        1. [1.2.4 Where to download PowerKVM](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469364)
    1. [1.3 Software stack](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469373)
        1. [1.3.1 QEMU](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469375)
        1. [1.3.2 KVM](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww479032)
        1. [1.3.3 Open Power Abstraction Layer](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469408)
        1. [1.3.4 Guest operating system](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469411)
        1. [1.3.5 Libvirt software](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469422)
        1. [1.3.6 Virsh interface](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469431)
        1. [1.3.7 Intelligent Platform Management Interface](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww471394)
        1. [1.3.8 Petitboot](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469500)
        1. [1.3.9 Kimchi](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469510)
        1. [1.3.10 Slimline Open Firmware](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469538)
        1. [1.3.11 Virtio drivers](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469554)
        1. [1.3.12 RAS stack](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww469604)
    1. [1.4 Comparison of PowerVM and PowerKVM features](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww472091)
    1. [1.5 Terminology](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_8.html#ww472199)
1. [Chapter 2. Host installation and configuration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html)
    1. [2.1 Host installation](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww465514)
        1. [2.1.1 NetBoot installations](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww465717)
        1. [2.1.2 Automated installation](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww465880)
        1. [2.1.3 Reinstallation](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww472207)
    1. [2.2 System configuration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww465973)
        1. [2.2.1 Console configuration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww466031)
    1. [2.3 Firmware upgrade](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww466050)
        1. [2.3.1 Kimchi](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww466059)
        1. [2.3.2 update_flash](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_9.html#ww466079)
1. [Chapter 3. Managing guests from a web interface](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html)
    1. [3.1 Kimchi](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww463961)
        1. [3.1.1 Accessing Kimchi](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww463969)
    1. [3.2 Storage pool](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww463996)
        1. [3.2.1 Local directory](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww465091)
        1. [3.2.2 NFS](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww465112)
        1. [3.2.3 iSCSI](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww465124)
        1. [3.2.4 Logical volume](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww465157)
    1. [3.3 Network](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464972)
        1. [3.3.1 NAT network](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464033)
        1. [3.3.2 Bridged network](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464044)
    1. [3.4 Templates](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464060)
        1. [3.4.1 Create a new template](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464071)
    1. [3.5 Guests](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464104)
        1. [3.5.1 Creating a new guest](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww471506)
        1. [3.5.2 Start and stop guests](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464110)
    1. [3.6 Accessing a graphical interface](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464115)
        1. [3.6.1 noVNC](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464117)
        1. [3.6.2 VNC](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_10.html#ww464124)
1. [Chapter 4. Managing guests from a CLI](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html)
    1. [4.1 virsh console](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465680)
        1. [4.1.1 virsh vncdisplay](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465752)
    1. [4.2 Managing storage pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465767)
        1. [4.2.1 Create new storage pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465769)
        1. [4.2.2 Query available storage pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465909)
        1. [4.2.3 List available volumes](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465968)
        1. [4.2.4 Create a new volume](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww465985)
        1. [4.2.5 Delete or wipe a volume](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466035)
    1. [4.3 Managing guest networks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466071)
        1. [4.3.1 Query guest networks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466073)
        1. [4.3.2 Create guest network](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466111)
    1. [4.4 Managing virtual machines](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466223)
        1. [4.4.1 Create a new virtual machine](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466225)
        1. [4.4.2 List virtual machines](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466298)
        1. [4.4.3 Start or stop a virtual machine](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466316)
        1. [4.4.4 Connect to a virtual machine](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_11.html#ww466359)
1. [Chapter 5. Processor and memory virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html)
    1. [5.1 CPU virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466233)
        1. [5.1.1 Types of virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466237)
        1. [5.1.2 Hardware-assisted virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466252)
    1. [5.2 CPU overcommitment](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466256)
    1. [5.3 CPU compatibility mode](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466270)
        1. [5.3.1 Simultaneous multithreading](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466302)
        1. [5.3.2 Microthreading](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466547)
        1. [5.3.3 Configuring NUMA](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466760)
    1. [5.4 CPU pinning](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466794)
    1. [5.5 CPU sharing](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466819)
    1. [5.6 Memory](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466838)
        1. [5.6.1 Memory allocation](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466842)
        1. [5.6.2 Memory ballooning](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466866)
        1. [5.6.3 Kernel SamePage Merging (KSM)](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww466937)
        1. [5.6.4 Huge pages](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww467055)
    1. [5.7 Time management](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_12.html#ww467107)
1. [Chapter 6. I/O virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html)
    1. [6.1 Types of virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466316)
        1. [6.1.1 PowerKVM supported devices](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466318)
        1. [6.1.2 PCI I/O passthrough](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww467780)
    1. [6.2 Network virtualization](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466343)
        1. [6.2.1 User mode networking](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466356)
        1. [6.2.2 Network address translation networking](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466367)
        1. [6.2.3 Bridged networking](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466369)
        1. [6.2.4 Open vSwitch](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww467527)
    1. [6.3 Storage pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww467169)
        1. [6.3.1 Storage volume](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww469528)
        1. [6.3.2 Block device pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466507)
        1. [6.3.3 File-backed pools](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466527)
    1. [6.4 I/O passthrough](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww464670)
        1. [6.4.1 SCSI passthrough](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww464767)
        1. [6.4.2 USB passthrough](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww464787)
        1. [6.4.3 PCI passthrough to a virtual machine](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww464911)
        1. [6.4.4 I/O limits](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww465087)
    1. [6.5 Hot plug](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466630)
        1. [6.5.1 Adding a new vSCSI adapter](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_13.html#ww466757)
1. [Chapter 7. Advanced topics](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html)
    1. [7.1 Guest migration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468129)
        1. [7.1.1 Transports](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468972)
        1. [7.1.2 Offline migration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468144)
        1. [7.1.3 Online migration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468169)
        1. [7.1.4 Live migration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468208)
    1. [7.2 Suspending and resuming](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468262)
    1. [7.3 Cloud management](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468316)
        1. [7.3.1 IBM PowerVC](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468357)
        1. [7.3.2 IBM Cloud Manager with OpenStack](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468786)
        1. [7.3.3 OpenStack controller services](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_14.html#ww468442)
1. [Related publications](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_16.html)
    1. [IBM Redbooks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_16.html#ww454350)
    1. [Online resources](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_16.html#ww455988)
    1. [Help from IBM](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_16.html#ww456261)
1. [Back cover](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_18.html#ww465861)
1. [IBM System x Reference Architecture for Hadoop: IBM InfoSphere BigInsights Reference Architecture](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html)
    1. [Introduction](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww510185)
    1. [Business problem and business value](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww468750)
    1. [Reference architecture use](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww549180)
    1. [Requirements](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww476823)
    1. [InfoSphere BigInsights predefined configuration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww501885)
    1. [InfoSphere BigInsights HBase predefined configuration](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww494430)
    1. [Deployment considerations](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww497300)
    1. [Customizing the predefined configurations](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww497358)
    1. [Predefined configuration bill of materials](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww552575)
    1. [References](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww477676)
    1. [The team who wrote this paper](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww471347)
    1. [Now you can become a published author, too!](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww471408)
    1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_19.html#ww471445)
1. [Notices](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_20.html)
    1. [Trademarks](https://ebookreading.net/view/book/IBM+PowerKVM+Configuration+and+Use-EB0738439940_20.html#ww459879)
