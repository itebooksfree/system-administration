![Cover image for Container Security](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9781492056690.jpg)

[Container Security](https://ebookreading.net/view/book/Container+Security-EB9781492056690_1.html "Container Security")
====================================================================================================================

Author : [Liz Rice](https://ebookreading.net/search/author/Liz+Rice)

Release Date : 2020/05/01

ISBN : 9781492056690

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Many organizations now run applications in cloud native environments, using containers and orchestration to facilitate scalability and resilience. But how do you know whether your deployment is secure? To fully grasp the security implications of containers and their operation, you’ll need an understanding of what they are and how they work. In this excerpt from her forthcoming book Container Security, author Liz Rice takes you through the mechanisms that isolate and protect your applications within each container.
This book as a whole looks at the building blocks and security boundaries commonly used in container-based systems and how they’re constructed in the Linux operating system. In the featured chapter, "Container Isolation," you’ll learn how namespaces limit the set of files and directories that particular container processes can see, functionally isolating them from other operations.
Learn how a container is actually a Linux process with a restricted view of the machine it’s running onExplore the different namespaces typically used to create Linux containersExamine how containerized processes are isolated from the host and other containerized processes        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Container+Security-EB9781492056690_4.html#idm46206281910264)
    1. [Examples](https://ebookreading.net/view/book/Container+Security-EB9781492056690_4.html#idm46206280727224)
1. [1. Control Groups](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#ch_control_groups)
    1. [Cgroup hierarchies](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206282101368)
    1. [Creating cgroups](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206277519848)
    1. [Setting resource limits](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206278902344)
    1. [Assigning a process to a cgroup](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206281286360)
    1. [Docker using cgroups](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206277148504)
    1. [Cgroups v2](https://ebookreading.net/view/book/Container+Security-EB9781492056690_5.html#idm46206277005320)
1. [2. Container Isolation](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#ch_container_isolat)
    1. [Linux namespaces](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276959848)
    1. [Isolating the hostname](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276959256)
    1. [Isolating process IDs](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#s_process_ids)
    1. [Changing the root directory](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276819848)
    1. [Combine namespaces and changing the root](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276327544)
    1. [Mount namespace](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276117384)
    1. [Network namespace](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206276096040)
    1. [User namespace](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275940776)
        1. [User namespace restrictions](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275556776)
    1. [Inter-process communications namespace](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275745656)
    1. [Cgroup namespace](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275424872)
    1. [Container processes from the host perspective](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275416056)
    1. [Conclusions](https://ebookreading.net/view/book/Container+Security-EB9781492056690_6.html#idm46206275415464)
1. [3. Virtual machines](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#ch_virtual_machines)
    1. [Booting up a machine](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275294344)
    1. [Enter the VMM](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275237016)
        1. [Type 1 VMM, or Hypervisors](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275232280)
        1. [Type 2 VMM](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275220552)
        1. [Kernel-based Virtual Machines](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275210984)
    1. [Trap-and-emulate](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275204568)
    1. [Handling non-virtualizable instructions](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275198792)
    1. [Process isolation](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275189864)
    1. [Disadvantages of virtual machines](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275177528)
    1. [Container isolation compared to VM isolation](https://ebookreading.net/view/book/Container+Security-EB9781492056690_7.html#idm46206275169064)
1. [Index](https://ebookreading.net/view/book/Container+Security-EB9781492056690_8.html#idm46206275298904)
