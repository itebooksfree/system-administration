![Cover image for sendmail Cookbook](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB0596004710.jpg)

[sendmail Cookbook](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_1.html "sendmail Cookbook")
====================================================================================================================

Author : [Craig Hunt](https://ebookreading.net/search/author/Craig+Hunt)

Release Date : 2003/12/01

ISBN : 0596004710

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

More often than not, the words "sendmail configuration" strikedread in the hearts of sendmail and system administrators--and notwithout reason. sendmail configuration languages are as complex asany other programming languages, but used much moreinfrequently--only when sendmail is installed or configured. Theaverage system administrator doesn't get enough practice to trulymaster this inscrutable technology. Fortunately, there's help. Thesendmail Cookbook provides step-by-step solutions for theadministrator who needs to solve configuration problems fast. Sayyou need to configure sendmail to relay mail for your clientswithout creating an open relay that will be abused by spammers. Arecipe in the Cookbook shows you how to do just that. No morewading through pages of dense documentation and tutorials andcreating your own custom solution--just go directly to the recipethat addresses your specific problem. Each recipe in thesendmail Cookbook outlines a configuration problem, presentsthe configuration code that solves that problem, and then explainsthe code in detail. The discussion of the code is critical becauseit provides the insight you need to tweak the code for your owncircumstances. The sendmail Cookbook begins with an overviewof the configuration languages, offering a quick how-to fordownloading and compiling the sendmail distribution. Next, you'llfind a baseline configuration recipe upon which many of thesubsequent configurations, or recipes, in the book are based.Recipes in the following chapters stand on their own and offersolutions for properly configuring important sendmail functionssuch as:
Delivering and forwarding mail
Relaying
Masquerading
Routing mail
Controlling spam
Strong authentication
Securing the mail transport
Managing the queue
Securing sendmail
sendmail Cookbook is more than just a new approach todiscussing sendmail configuration. The book also provides lots ofnew material that doesn't get much coverage elsewhere--STARTTLS andAUTH are given entire chapters, and LDAP is covered in recipesthroughout the book. But most of all, this book is about savingtime--something that most system administrators have in shortsupply. Pick up the sendmail Cookbook and say good-bye tosendmail dread.
              
Table of Contents
-----------------

1. [Dedication](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_3.html)
1. [Preface](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Using This Cookbook](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Audience](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Organization](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Software Versions](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Conventions](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [We’d Like to Hear from You](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
    1. [Acknowledgments](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_4.html#sendmailckbk-PREFAC)
1. [1. Getting Started](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.1. Downloading the Latest Release](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.2. Installing sendmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.3. Compiling sendmail to Use LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.4. Adding the regex Map Type to sendmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.5. Compiling sendmail with SASL Support](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.6. Compiling sendmail with STARTTLS Support](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.7. Compiling in STARTTLS File Paths](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.8. Building a sendmail Configuration](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.9. Testing a New Configuration](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
    1. [1.10. Logging sendmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_5.html#sendmailckbk-CHP-1-)
1. [2. Delivery and Forwarding](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.1. Accepting Mail for Other Hosts](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.2. Fixing the Alias0 Missing Map Error and Creating Simple Aliases](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.3. Reading Aliases via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.4. Configuring Red Hat 7.3 to Read Aliases from a NIS Server](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.5. Configuring Solaris 8 to Read Aliases from a NIS Server](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.6. Forwarding to an External Address](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.7. Creating Mailing Lists](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.8. Migrating Ex-Users to New Addresses](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.9. Delivering Mail to a Program](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.10. Using Program Names in Mailing Lists](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.11. Allowing Nonlogin Users to Forward to Programs](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.12. Fixing a .forward Loop](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
    1. [2.13. Enabling the User Database](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_6.html#sendmailckbk-CHP-2-)
1. [3. Relaying](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.1. Passing All Mail to a Relay](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.2. Passing Outbound Mail to a Relay](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.3. Passing Local Mail to a Mail Hub](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.4. Passing Apparently Local Mail to a Relay](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.5. Passing UUCP Mail to a Relay](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.6. Relaying Mail for All Hosts in a Domain](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.7. Relaying Mail for Individual Hosts](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.8. Configuring Relaying on a Mail Exchanger](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.9. Loading Class $=R via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
    1. [3.10. Relaying Only Outbound Mail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_7.html#sendmailckbk-CHP-3-)
1. [4. Masquerading](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.1. Adding Domains to All Sender Addresses](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.2. Masquerading the Sender Hostname](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.3. Eliminating Masquerading for the Local Mailer](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.4. Forcing Masquerading of Local Mail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.5. Masquerading Recipient Addresses](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.6. Masquerading at the Relay Host](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.7. Limiting Masquerading](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.8. Masquerading All Hosts in a Domain](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.9. Masquerading Most of the Hosts in a Domain](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.10. Masquerading the Envelope Address](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.11. Rewriting the From Address with the genericstable](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.12. Rewriting Sender Addresses for an Entire Domain](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.13. Masquerading with LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
    1. [4.14. Reading the genericstable via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_8.html#sendmailckbk-CHP-4-)
1. [5. Routing Mail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.1. Routing Mail to Special Purpose Mailers](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.2. Sending Error Messages from the mailertable](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.3. Disabling MX Processing to Avoid Loops](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.4. Routing Mail for Local Delivery](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.5. Reading the mailertable via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.6. Routing Mail for Individual Virtual Hosts](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.7. Routing Mail for Entire Virtual Domains](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.8. Reading the virtusertable via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.9. Routing Mail with LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
    1. [5.10. Using LDAP Routing with Masquerading](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_9.html#sendmailckbk-CHP-5-)
1. [6. Controlling Spam](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.1. Blocking Spam with the access Database](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.2. Preventing Local Users from Replying to Spammers](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.3. Reading the access Database via LDAP](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.4. Using a DNS Blackhole List Service](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.5. Building Your Own DNS Blackhole List](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.6. Whitelisting Blacklisted Sites](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.7. Filtering Local Mail with procmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.8. Filtering Outbound Mail with procmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.9. Invoking Special Header Processing](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.10. Using Regular Expressions in sendmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.11. Identifying Local Problem Users](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.12. Using MILTER](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.13. Bypassing Spam Checks](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
    1. [6.14. Enabling Spam Checks on a Per-User Basis](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_10.html#sendmailckbk-CHP-6-)
1. [7. Authenticating with AUTH](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.1. Offering AUTH Authentication](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.2. Authenticating with AUTH](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.3. Storing AUTH Credentials in the authinfo File](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.4. Limiting Advertised Authentication Mechanisms](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.5. Using AUTH to Permit Relaying](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.6. Controlling the AUTH= Parameter](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.7. Avoiding Double Encryption](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.8. Requiring Authentication](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
    1. [7.9. Selectively Requiring Authentication](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_11.html#sendmailckbk-CHP-7-)
1. [8. Securing the Mail Transport](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.1. Building a Private Certificate Authority](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.2. Creating a Certificate Request](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.3. Signing a Certificate Request](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.4. Configuring sendmail for STARTTLS](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.5. Relaying Based on the CA](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.6. Relaying Based on the Certificate Subject](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.7. Requiring Outbound Encryption](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.8. Requiring Inbound Encryption](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.9. Requiring a Verified Certificate](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.10. Requiring TLS for a Recipient](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.11. Refusing STARTTLS Service](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.12. Selectively Advertising STARTTLS](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
    1. [8.13. Requesting Client Certificates](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_12.html#sendmailckbk-CHP-8-)
1. [9. Managing the Queue](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.1. Creating Multiple Queues](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.2. Using qf, df, and xf Subdirectories](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.3. Defining Queue Groups](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.4. Assigning Recipients to Specific Queues](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.5. Using Persistent Queue Runners](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.6. Using a Queue Server](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
    1. [9.7. Setting Protocol Timers](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_13.html#sendmailckbk-CHP-9-)
1. [10. Securing sendmail](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html)
    1. [Introduction](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.1. Limiting the Number of sendmail Servers](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.2. Limiting the Number of Network Accessible Servers](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.3. Updating to Close Security Holes](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.4. Patching to Close Security Holes](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.5. Disabling Delivery to Programs](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.6. Controlling Delivery to Programs](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.7. Disabling Delivery to Files](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.8. Bypassing User .forward Files](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.9. Controlling Delivery to Files](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.10. Running sendmail Non-Set-User-ID root](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.11. Setting a Safe Default User ID](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.12. Defining Trusted Users](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.13. Identifying the sendmail Administrator](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.14. Limiting the SMTP Command Set](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.15. Requiring a Valid HELO](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.16. Restricting Command-Line Options](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
    1. [10.17. Denying DoS Attacks](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_14.html#sendmailckbk-CHP-10)
1. [About the Author](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_15.html)
1. [Colophon](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_16.html)
1. [Copyright](https://ebookreading.net/view/book/sendmail+Cookbook-EB0596004710_17.html)