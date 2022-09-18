![Cover image for Get started with Ansible](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781491965191.jpg)

[Get started with Ansible](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_1.html "Get started with Ansible")
====================================================================================================================

Author : [Lorin Hochstein](https://ebookreading.net/search/author/Lorin+Hochstein)

Release Date : 2016/08/01

ISBN : 9781491965191

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 Ansible is a great tool for handling deployment as well as configuration management, providing a lot more functionality than shell scripts. It doesn't require that one learn a new set of abstractions to hide the differences between operating systems. That makes its surface area smaller; there's less you need to know before you get started.
Why is it important?
We're all slowly turning into system engineers. Using a single tool for both configuration management and deployment makes life simpler for the folks responsible for operations. Project goals include a consistent, secure, highly reliable tool that's minimal in nature and has a low learning curve.
What you'll learn—and how you can apply it
Covers the basic concepts of Ansible at a high level, including how it communicates with remote servers and how it differs from other configuration-management tools. You'll learn how to use the Ansible command-line tool to perform simple tasks on a single host
This lesson is for you because…
You're a developer deploying your code to productionYou're a systems administrator looking for a better way to automateYou need a quick introduction to leveraging an idempotent resource model for immutable infrastructurePrerequisites
Be familiar with at least one Linux distribution (e.g., Ubuntu, RHEL/CentOS, SUSE)Be familiar with basic Linux system administration tasks, e.g., know how to:Connect to a remote machine using SSHInteract with the bash command-line shell (pipes and redirection)Install packagesUse the sudo commandCheck and set file permissionsStart and stop servicesSet environment variablesWrite scripts (any language)Learn some YAML and Jinja2Materials or downloads needed in advance
Have a Linux server with which to practiceThis Lesson is taken from Ansible: Up and Running by Lorin Hochstein.
        Show and hide more                
Table of Contents
-----------------

1. [Get started with Ansible](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#introduction)
    1. [A Note About Versions](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775026467504)
    1. [Ansible: What Is It Good For?](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775026574560)
    1. [How Ansible Works](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775026450800)
    1. [What’s So Great About Ansible?](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775026450128)
        1. [Easy-to-Read Syntax](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775024749792)
        1. [Nothing to Install on the Remote Hosts](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775024219680)
        1. [Push-Based](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023264656)
        1. [Ansible Scales Down](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775025452224)
        1. [Built-in Modules](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775026747120)
        1. [Very Thin Layer of Abstraction](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023172688)
    1. [Is Ansible Too Simple?](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023157760)
    1. [What Do I Need to Know?](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023148752)
    1. [What Isn’t Covered](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023135024)
    1. [Installing Ansible](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023123568)
    1. [Setting Up a Server for Testing](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023122944)
        1. [Using Vagrant to Set Up a Test Server](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023072608)
        1. [Telling Ansible About Your Test Server](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775022987264)
        1. [Simplifying with the ansible.cfg File](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023019744)
    1. [Summary](https://ebookreading.net/view/book/Get+started+with+Ansible-EB9781491965191_3.html#idm139775023015120)
