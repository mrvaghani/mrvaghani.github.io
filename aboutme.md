---
layout: page
title: About me
subtitle: Some things about me that I think you should know
---

### Objective:

My goal is to obtain a position in automation and DevSecOps. I am also interested in penetration testing in Red and Blue teams.

# About me:

I am currently pursuing masters in CyberSecurity at [NJIT](http://njit.edu/) with an anticipated graduation date of May 2021. I have also worked as Software Developer, DevOps and automation engineer during my time at ADP.

### Professional Experience

- Python and bash to for writing custom automation tools
- DevOps/Code pipeline using Docker/Kubernetes/Jenkins
- Microservices using Python Flask REST APIs with JWT for security
- Implemented secure configuration audit solution for ADP's global voice infrastructure. This helped reduce the recovery time of outages that were caused by bad configuration and helped prevent these outages in the future
- Responsible for writing Technical Documentation and runbooks
- Excellent communication and presentation skills
- Convert technical information into business requirements


### Things I learned by working on projects
Along with my job and pursuing full time masters, I also like to spend my free time tinkering and learning new things. 
Here are some of the things I learned from my projects:

- #### FreeNAS storage server (Physical)

  - This was my first time hands on experience with FreeBSD. I started by learning the package manager and by understanding how the disks are mounted
  
  - Properly designing my system meant I had to understand zfs, [storage pools](https://www.ixsystems.com/documentation/freenas/11.3-U3.2/storage.html#pools) and many new things regarding data redundancy
  - Setting up network shared services required me to learn [FreeBSD jails](https://www.freebsd.org/doc/handbook/jails.html)
  
  - Sharing storage over network meant learning TCP/IP, DHCP, NFSv4, iSCSI. This made it easy for me to backup all of my devices to FreeNAS server over the network, even OSX Time Machine!

- #### Hypervisor - VMWare ESXi (Physical)

  - After having too many VMs created on my desktop using VMWare Workstation, it was time to migrate to a dedicated ESX server
  - I learned how to compile a driver for my High IOPS PCI-E SSD for ESXi because it was only available for Redhat
  - Since I had no local storage for VMs, it was time to learn NFS and iSCSI to compare performance. Block storage was better if I were planning on using VMotion and other features offered by ESX. And since I only had 1 ESX, I choose to go with NFS data stores for VMs
  - After upgrading from version 5.5, vSphere Web Client became a necessasity and so I added it 
  
- #### Networking - Managed 10Gb Fiber Switch (Physical)
  - This was my first hands on experience with fiber and SFP+ cables
  - I also resized my DHCP pool in order to free up some IPs to be assigned statically
  - Added most used IPs in my HOSTS file for convinience
  - Setup all IPMI on a separate management VLANs
  - Setup Link Aggregation for my Synology NAS to support dual ethernet ports
  - All the servers were connected via this switch over 10Gb Fiber
  
- #### Firewall - Pfsense (Physical)
  - After getting tired of the limitations of the router provided by ISP, I decided to change it for a physical Pfsense box
  - Pfsense provided better security while having the ability to add more packages for extra functionality
  - Using Squid proxy for caching Windows Updates was very helpful when I had to update entire homelab VMs
  - I also tried to block Ads and other Malware by using pfBlockerNG but ended up using my Raspberry-Pie and [Pi-Hole](https://pi-hole.net/) by creating a DNS sinkhole
  
- #### Kubernetes sandbox - Ubuntu 18.04 LTS (virtual)

  - In order to have a place to host and manage docker containers, I decided to have 3 Docker host and managed it using Docker Compose
  - After having too many containers to manually manage, I decided to deploy using Ansible
  - Writing Ansible playbooks was very time consuming so I decided to setup Kubernetes cluster and starting using it to manage my containers
  
- #### Metasploit Unleashed Lab - (virtual)
  - In order to practice Metasploit, I setup a vulnerable Linux VM provided by Offensive Security called Metasploitable
  
- #### Kali Linux - (virtual)
  - Setup a VM with Kali to practice for online courses as well as participating in CTF events. Last CTF I attended was [All-Army CyberStakes](https://cyberstakes.acictf.com/)
  
- #### Windows XP - (virtual)
  - In order to practice Buffer Overflow in some known vulnerable applications that were only available for XP
  
- #### Windows 10 - (virtual)
  - Reverse Engineering Malware using ghidra. Unfortunately my university did not have student discounts available for IDA Pro
  
- #### Ubuntu 18.04 LTS - (virtual)
  - Test Sandbox used for testing out new packages and scripts without breaking other machines
  
- #### Windows Server 2016 - (virtual)
  - Practicing DHCP, DNS, AD and IIS roles
  
- #### Game Servers - (virtual)
  - Counter Strike: Source 128-tick server
  - Minecraft 1.15 Server

# Contact

You can get in touch by using one of the methods listed at the bottom of this page.
