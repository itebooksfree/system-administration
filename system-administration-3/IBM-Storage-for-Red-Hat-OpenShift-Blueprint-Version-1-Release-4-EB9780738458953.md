![Cover image for IBM Storage for Red Hat OpenShift Blueprint Version 1 Release 4](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9780738458953.jpg)

[IBM Storage for Red Hat OpenShift Blueprint Version 1 Release 4](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_1.html "IBM Storage for Red Hat OpenShift Blueprint Version 1 Release 4")
====================================================================================================================

Author : [IBM](https://ebookreading.net/search/author/IBM)

Release Date : 2020/07/01

Book Description
-----------------


    
    This IBM® Blueprint is intended to facilitate the deployment of IBM Storage for Red Hat OpenShift Container Platform by using detailed hardware specifications to build a system. It describes the associated parameters for configuring persistent storage within a Red Hat OpenShift Container Platform environment. To complete the tasks, you should understand Red Hat OpenShift, IBM Storage, the IBM block storage Container Storage Interface (CSI) driver and the IBM Spectrum Scale CSI driver.
The information in this document is distributed on an "as is" basis without any warranty that is either expressed or implied. Support assistance for the use of this material is limited to situations where IBM Storwize® or IBM FlashSystem® storage devices, ESS and Spectrum Scale are supported and entitled, and where the issues are not specific to a blueprint implementation.
IBM Storage Suite for IBM Cloud® Paks is an offering bundle that includes software-defined storage from both IBM and Red Hat. Use this document for details on how to deploy IBM Storage product licenses obtained through Storage Suite for Cloud Paks (IBM Spectrum® Virtualize and IBM Spectrum Scale).

  

Table of Contents
-----------------

1. [About this document](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479029)
1. [Executive summary](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479035)
1. [Scope](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479045)
1. [Prerequisites](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479052)
1. [Lab topology](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479153)
1. [Red Hat OpenShift Container Platform 4.4 installation overview](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479288)
1. [Configuring iSCSI/Fibre Channel for worker nodes](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479571)
1. [Installing IBM block storage CSI driver on Red Hat OpenShift Container Platform](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479664)
1. [Installing IBM Spectrum Scale CSI Driver on Red Hat OpenShift Container Platform](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww519608)
1. [Deploying CockroachDB Operator and Database instance](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479761)
1. [Volume Snapshots with IBM Block CSI Driver](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww1017466)
1. [Appendix A: DNS file](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479799)
    1. [Appendix B: DHCP file](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479932)
    1. [Appendix C: HTTP file](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww479999)
    1. [Appendix D: haproxy file](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww480063)
    1. [Appendix E: node communication](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww480157)
    1. [Appendix F: bootstrap file](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww480182)
    1. [Appendix G: IBM Spectrum Scale usage restrictions](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_2.html#ww520844)
1. [Notices](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_3.html#ww460066)
    1. [Trademarks](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_3.html#ww459879)
    1. [Terms and conditions for product documentation](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_3.html#ww477351)
1. [szdzBack cover](https://ebookreading.net/view/book/IBM+Storage+for+Red+Hat+OpenShift+Blueprint+Version+1+Release+4-EB9780738458953_4.html#ww465861)
