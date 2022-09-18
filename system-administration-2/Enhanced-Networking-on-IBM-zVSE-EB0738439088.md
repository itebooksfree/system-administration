![Cover image for Enhanced Networking on IBM z/VSE](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB0738439088.jpg)

[Enhanced Networking on IBM z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_1.html "Enhanced Networking on IBM z/VSE")
====================================================================================================================

Author : [Rene Trumpp](https://ebookreading.net/search/author/Rene+Trumpp),[ Don Stoever](https://ebookreading.net/search/author/+Don+Stoever),[ Karsten Graul](https://ebookreading.net/search/author/+Karsten+Graul),[ Ingo Franzki](https://ebookreading.net/search/author/+Ingo+Franzki),[ Jeffrey Barnard](https://ebookreading.net/search/author/+Jeffrey+Barnard),[ Joerg Sc](https://ebookreading.net/search/author/+Joerg+Sc)

Release Date : 2014/02/01

ISBN : 0738439088

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

The importance of modern computer networks is steadily growing as increasing amounts of data are exchanged over company intranets and the Internet. Understanding current networking technologies and communication protocols that are available for the IBM® mainframe and System z® operating systems is essential for setting up your network infrastructure with z/VSE®.
This IBM Redbooks® publication helps you install, tailor, and configure new networking options for z/VSE that are available with TCP/IP for VSE/ESA, IPv6/VSE, and Fast Path to Linux on System z (Linux Fast Path). We put a strong focus on network security and describe how the new OpenSSL-based SSL runtime component can be used to enhance the security of your business.
This IBM Redbooks publication extends the information that is provided in Security on IBM z/VSE, SG24-7691.
              
Table of Contents
-----------------

1. [Front cover](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_1.html)
1. [Notices](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_3.html)
    1. [Trademarks](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_3.html#ww459879)
1. [Preface](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_4.html)
    1. [The team who wrote this book](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_4.html#ww785128)
    1. [Now you can become a published author, too!](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_4.html#ww782335)
    1. [Comments welcome](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_4.html#ww775129)
    1. [Stay connected to IBM Redbooks](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_4.html#ww782351)
1. [Chapter 1. Networking options overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html)
    1. [1.1 Overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww458965)
    1. [1.2 Hardware options](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww461030)
        1. [1.2.1 OSA-Express](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww463667)
        1. [1.2.2 OSA-Integrated Console Controller](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww471933)
        1. [1.2.3 OSA-Express in QDIO mode](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww493674)
        1. [1.2.4 OSA-Express](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww480520)
        1. [1.2.5 OSA for NCP support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww476704)
        1. [1.2.6 Intra-Ensemble Data Network support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww484703)
        1. [1.2.7 OSA-Express multi-port support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww484511)
        1. [1.2.8 HiperSockets (IQD)](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww463135)
        1. [1.2.9 Virtual local area network](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww463089)
        1. [1.2.10 Shared OSA adapter versus HiperSockets](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww462619)
        1. [1.2.11 Using HiperSockets to communicate with Linux on System z](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww462647)
        1. [1.2.12 QDIO buffer configuration](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww494259)
        1. [1.2.13 Virtual OSA devices and VMAC](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww489413)
    1. [1.3 Software options](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww489372)
        1. [1.3.1 IPv4](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww464898)
        1. [1.3.2 IPv6](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww464719)
        1. [1.3.3 Why IPv6?](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww467801)
        1. [1.3.4 Dual stack support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww467944)
        1. [1.3.5 Migration from IPv4 to IPv6](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww487669)
        1. [1.3.6 IPv6 products for z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww464524)
        1. [1.3.7 Securing your connections with Secure Sockets Layer](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww468021)
        1. [1.3.8 Options for printing](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww468876)
        1. [1.3.9 Overview of APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww468260)
        1. [1.3.10 Available applications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww482140)
        1. [1.3.11 Choosing a socket API when designing your applications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww462675)
        1. [1.3.12 Enabling your applications for IPv6](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_5.html#ww486577)
1. [Chapter 2. TCP/IP for VSE/ESA](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html)
    1. [2.1 Overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww458965)
    1. [2.2 Standard features](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww458971)
    1. [2.3 Other optional features](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww458972)
    1. [2.4 Applications that are provided with TCP/IP for VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww458973)
    1. [2.5 Application programming interfaces](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww461196)
    1. [2.6 Setting up and running TCP/IP for VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww461273)
    1. [2.7 FTP hints](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww460861)
        1. [2.7.1 Internal FTP server suggestions](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww463455)
        1. [2.7.2 Using external FTPBATCH servers](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww463466)
    1. [2.8 Partition priorities](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww463567)
    1. [2.9 Security](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww464303)
    1. [2.10 Remote running with REXX](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww465061)
    1. [2.11 Version checking](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww463595)
    1. [2.12 Datagram analysis](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww468850)
    1. [2.13 Known problems](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww463406)
        1. [2.13.1 Routing in a subnet](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww460854)
        1. [2.13.2 Using SSL ciphers](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww460823)
        1. [2.13.3 Secure SSL port](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww462343)
        1. [2.13.4 SSL client does not verify the server certificate](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww462519)
        1. [2.13.5 TLS issue with IBM Personal Communications 6.0.7](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_6.html#ww462548)
1. [Chapter 3. IPv6/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html)
    1. [3.1 Overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww458965)
    1. [3.2 Obtaining and activating a license key](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww458971)
    1. [3.3 Stack setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww552565)
        1. [3.3.1 IPv4 stack setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww533893)
        1. [3.3.2 IPv6 stack setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww514982)
        1. [3.3.3 Mixed IPv4 and IPv6 network setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww460915)
        1. [3.3.4 Setting up a dual-stacked system](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww564100)
        1. [3.3.5 UDPv4 in a coupled stack environment](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww508704)
        1. [3.3.6 Connectivity considerations](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww523223)
    1. [3.4 Setting up FTP](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww465314)
        1. [3.4.1 Security](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww518551)
        1. [3.4.2 VSE as a server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww481553)
        1. [3.4.3 VSE as a client](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww481565)
    1. [3.5 Setting up TN3270](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww460929)
        1. [3.5.1 Setting up VTAM](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww460943)
        1. [3.5.2 Starting a TN3270 server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww461031)
        1. [3.5.3 Controlling the terminal type](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww461796)
        1. [3.5.4 Connecting with IBM Personal Communications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww511036)
        1. [3.5.5 Connecting with Open Text Exceed](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww462080)
        1. [3.5.6 Connecting with wc3270](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww462367)
    1. [3.6 Setting up TN3270E printing](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww461002)
        1. [3.6.1 TN3270E setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww465587)
        1. [3.6.2 BSTTVNET JCL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww466678)
        1. [3.6.3 Node error program](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww466778)
    1. [3.7 Setting up SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww461104)
        1. [3.7.1 Installing the prerequisite programs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww466950)
        1. [3.7.2 Creating the keystore](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww467055)
        1. [3.7.3 Removing the private CA key from the client keyring file](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww481010)
        1. [3.7.4 Deciding whether to use the SSL proxy server or AT-TLS](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww529604)
        1. [3.7.5 Specifying parameters](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww468597)
        1. [3.7.6 Configuring the SSL proxy server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww555961)
        1. [3.7.7 Configuring the AT-TLS server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww468673)
        1. [3.7.8 Considerations on blocking clear ports](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww468765)
        1. [3.7.9 Configuring wc3270 for SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww512090)
        1. [3.7.10 Configuring IBM Personal Communications for SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww531601)
        1. [3.7.11 Configuring secure FTP](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470006)
        1. [3.7.12 Configuring VSE Connector Server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww553438)
        1. [3.7.13 SSL client authentication](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww534344)
        1. [3.7.14 Using TLSv1.2](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww543588)
    1. [3.8 Setting up CICS Web Support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww546123)
        1. [3.8.1 Modifying the CICS startup job](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww519517)
        1. [3.8.2 Defining the TCP/IP host name](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww519525)
        1. [3.8.3 Considerations for SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww519529)
    1. [3.9 Known problems](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww519578)
        1. [3.9.1 VSE cannot be reached](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470055)
        1. [3.9.2 BSTT075E LUNAME NOT AVAIL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470305)
        1. [3.9.3 SSL connect error with wc3270](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470323)
        1. [3.9.4 Other SSL connect errors](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470337)
        1. [3.9.5 Hang situation with BSTTATLS/BSTTPRXY](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470358)
        1. [3.9.6 Return codes 3100 / 1700 from IJBCRLIB](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470370)
        1. [3.9.7 BSTTFTPC fails to connect to Windows Server 2008](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww489974)
        1. [3.9.8 Batch email cannot relay mail](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww496397)
        1. [3.9.9 LDAP sign on by using SSL does not work](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww517190)
        1. [3.9.10 GnuTLS error -53: Error in the push function](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_7.html#ww470610)
1. [Chapter 4. Fast Path to Linux on System z](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html)
    1. [4.1 Overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww469872)
    1. [4.2 Concept of LFP instances and LFP daemons](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww493122)
    1. [4.3 LFP in a z/VM environment](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww460867)
        1. [4.3.1 Linux guest setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww491781)
        1. [4.3.2 VSE guest setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww500825)
    1. [4.4 z/VM IP Assist](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww460881)
        1. [4.4.1 Configuration user setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww460996)
        1. [4.4.2 Setting up the VIA guest](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww483887)
        1. [4.4.3 Setting up VSE guest](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww461976)
        1. [4.4.4 Using the LFP trace with VIA](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww491032)
    1. [4.5 LFP in an LPAR environment](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww460909)
        1. [4.5.1 Prerequisites](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww501659)
        1. [4.5.2 Hardware setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww473557)
        1. [4.5.3 VSE setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww473616)
        1. [4.5.4 Linux setup](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww473628)
    1. [4.6 IBM applications that support LFP](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww498329)
        1. [4.6.1 VSE Connector Server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww462621)
        1. [4.6.2 Using the Virtual z/VSE FTP Daemon](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww462738)
    1. [4.7 Using secure connections with SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww462983)
        1. [4.7.1 Using a VIA guest](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463130)
        1. [4.7.2 Using a Linux on System z guest](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463120)
        1. [4.7.3 Configuring the z/VSE virtual FTP daemon for SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463249)
    1. [4.8 Known problems](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463354)
        1. [4.8.1 Error accessing the config disk](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463521)
        1. [4.8.2 SE file transfer had a problem](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463532)
        1. [4.8.3 User ID not authorized for SMSG](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463546)
        1. [4.8.4 Invalid command response from VIA user](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463559)
        1. [4.8.5 No response from VIA user](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463576)
        1. [4.8.6 Profile cannot be loaded](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_8.html#ww463591)
1. [Chapter 5. OpenSSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html)
    1. [5.1 Overview](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww458965)
        1. [5.1.1 What is available on z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww480369)
        1. [5.1.2 What is unique in z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww483811)
        1. [5.1.3 Runtime variables](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462787)
        1. [5.1.4 What is not available in z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww463219)
    1. [5.2 Access to the OpenSSL API](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww458973)
    1. [5.3 Creating random numbers](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww486650)
        1. [5.3.1 Characteristics of random number generators](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww478521)
        1. [5.3.2 Random number generation in OpenSSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww478552)
        1. [5.3.3 Alternatives](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462962)
        1. [5.3.4 Considerations for the z/VSE crypto device driver](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww478699)
        1. [5.3.5 Performance](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww479027)
    1. [5.4 Keystore considerations](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww461182)
        1. [5.4.1 Creating a PEM keystore](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww461189)
        1. [5.4.2 Exporting PEM to PFX](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww483547)
        1. [5.4.3 Importing PFX to PEM](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww483551)
        1. [5.4.4 Password-protected keystores](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww483414)
    1. [5.5 Programming](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462258)
        1. [5.5.1 Include files](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww475115)
        1. [5.5.2 Passed socket number](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww475185)
        1. [5.5.3 Socket calls](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww477238)
        1. [5.5.4 Switching between GSK and OpenSSL socket calls](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww477058)
        1. [5.5.5 Specifying the key ring](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww469190)
        1. [5.5.6 Using a password-protected keyring](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww470396)
        1. [5.5.7 Supported cipher suites](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462281)
        1. [5.5.8 Specifying cipher suites](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462314)
        1. [5.5.9 Supported RSA key lengths](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462330)
        1. [5.5.10 Debugging](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww463933)
        1. [5.5.11 Hardware crypto support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww468566)
        1. [5.5.12 Programming example](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww468544)
    1. [5.6 Performing the OpenSSL speed test](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww468548)
        1. [5.6.1 Test parameters](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww461379)
        1. [5.6.2 Test results](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww464402)
    1. [5.7 How OpenSSL is used on z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww461685)
    1. [5.8 OpenSSL vulnerabilities](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww461692)
    1. [5.9 Considerations on TLSv1.2](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462435)
    1. [5.10 Restrictions](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww462449)
        1. [5.10.1 No SHA-512 support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_9.html#ww466721)
1. [Chapter 6. Comparison of stacks and protocols](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html)
    1. [6.1 Stacks comparison](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww485823)
        1. [6.1.1 Installation libraries](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww483788)
        1. [6.1.2 Virtual storage organization](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww461572)
        1. [6.1.3 Commands](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww460946)
        1. [6.1.4 Comparison of protocols](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww477643)
    1. [6.2 Applications comparison](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww460930)
        1. [6.2.1 FTP server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww476674)
        1. [6.2.2 FTP clients](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww461033)
        1. [6.2.3 AutoFTP](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww465329)
        1. [6.2.4 TN3270](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww460960)
        1. [6.2.5 Printing](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww461103)
        1. [6.2.6 AutoLPR](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww461088)
        1. [6.2.7 Inserts coding](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww484794)
        1. [6.2.8 Email](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww469517)
        1. [6.2.9 Creating PDF documents](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww476358)
        1. [6.2.10 Remote EXEC client](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww482311)
    1. [6.3 Performance](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww470029)
    1. [6.4 SSL](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww469509)
    1. [6.5 Comparison of APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww461154)
        1. [6.5.1 Socket APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww486862)
        1. [6.5.2 SSL APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww462163)
        1. [6.5.3 Crypto APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww481342)
    1. [6.6 Considerations for DB2 Server for VSE interfaces](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww477982)
    1. [6.7 Considerations for IBM applications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww462181)
        1. [6.7.1 VSE Connector Server](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww466660)
        1. [6.7.2 Virtual tape](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww463205)
        1. [6.7.3 CICS Web Support](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww463227)
        1. [6.7.4 Encryption Facility for z/VSE](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww467037)
        1. [6.7.5 Basic Security Manager](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww474014)
    1. [6.8 Known problem: ftp.exe hangs on Windows 7](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww495735)
        1. [6.8.1 Symptom](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww495731)
        1. [6.8.2 Solution](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_10.html#ww495906)
1. [Appendix A. API reference](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_11.html)
    1. [Socket APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_11.html#ww457124)
    1. [SSL APIs](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_11.html#ww461312)
1. [Related publications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_12.html)
    1. [IBM Redbooks](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_12.html#ww454350)
    1. [Other publications](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_12.html#ww455983)
    1. [Online resources](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_12.html#ww455988)
    1. [Help from IBM](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_12.html#ww459756)
1. [Back cover](https://ebookreading.net/view/book/Enhanced+Networking+on+IBM+z%2FVSE-EB0738439088_14.html#ww465861)