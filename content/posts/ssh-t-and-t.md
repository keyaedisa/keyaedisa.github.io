---
title: "Ssh Tips and Tricks"
date: 2023-06-07T19:28:05-04:00
draft: false
---

# SSH Tips and Tricks!

Hi! I was inspired to make a post about SSH that could be used as a somewhat quick reference for some basic SSH commands and tips and tricks regarding proper usage practices.
Below you will find summaries of a few articles I found to have useful information. This way I felt would be better both for me writing this blog quickly and also for allowing you the reader to quickly read and decide what reference you actually need.
Where possible, you should definitely use SSH authentication. Not only because it's more secure, but also because it's a really good way to speed up your workflow especially if you live in the terminal like me! I know that many of you have workflows that aren't terminal centric and if they work for you then great! I will however advocate that you do learn how to live in a terminal as it can significantly speed up your work flow! No need to traverse ui's and bounce around apps when you can do most if not all of it in the terminal ya know? Anyways, below you can find some good refs and their summaries!

In today's digital age, securing remote access to servers is crucial for businesses and individuals alike. One way to achieve this is by using Secure Shell (SSH) keys instead of passwords.

First, let's start with Red Hat's guide on "Managing Multiple SSH Key Pairs" https://www.redhat.com/sysadmin/manage-multiple-ssh-key-pairs. Here, we learn how to generate new SSH keys and add them to our authorized_keys file on the target system. We also see examples of how to remove and rename SSH key files without disrupting existing connections. By utilizing multiple SSH key pairs, we can segregate access control and reduce the risk of compromise.

Next, TechTarget provides us with insights into "Proper SSH Key Management" https://www.techtarget.com/searchsecurity/tip/How-does-proper-SSH-key-management-protect-your-network. They explain how poor SSH key management can expose organizations to security risks such as unauthorized access and data breaches. Proper key rotation, regular auditing, and strict permission settings are essential steps towards ensuring robust protection.

BeyondTrust takes us through a comprehensive "Overview of SSH Key Management Best Practices" https://www.beyondtrust.com/blog/entry/ssh-key-management-overview-6-best-practices. These include generating strong keys, securely distributing them via encrypted channels, and tracking usage throughout the entire lifecycle. Adopting these best practices helps ensure that only authorized personnel have access to sensitive systems and networks.

Finally, Atlassian guides us through "Git and SSH Tutorial" https://www.atlassian.com/git/tutorials/git-ssh/, explaining how Git uses SSH for authenticating local and remote users. Their tutorial demonstrates step-by-step procedures for setting up and configuring Git with SSH, making it easier for developers to collaborate and work remotely.


