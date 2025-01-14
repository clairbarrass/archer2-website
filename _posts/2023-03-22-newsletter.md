---
layout: post
title: ARCHER2 Weekly Newsletter
date: 2023-03-22 11:00:00
author: ARCHER2 Service
tags: [newsletters] 
categories: [news]
---

- [The Science Behind the Image Competition]({{ page.url }}#the-science-behind-the-image-competition) webinar - today 2pm
- [RDFaaS maintenance]({{ page.url }}#rdfaas-maintenance-3rd---5th-april-2023)  3rd - 5th April 2023
- [Efficient use of the HPE Cray EX Supercomputer ARCHER2]({{ page.url }}#efficient-use-of-the-hpe-cray-ex-supercomputer-archer2), online, 28 - 30 March 2023 09:00 - 17:00 GMT
- [ARM Forge tools (DDT and MAP) license "boost"]({{ page.url }}#arm-forge-tools-ddt-and-map-license-boost) w/b 20th March
- [Major software Upgrade]({{ page.url }}#major-software-upgrade-fri-14th-april---wb-mon-8th-may): Fri 14th April - w/b Mon 8th May
- [Recently added Known Issues]({{ page.url }}#recently-added-known-issues)
- [Upcoming ARCHER2 training]({{ page.url }}#upcoming-archer2-training)

<!--more-->
 


## The Science Behind the Image Competition

Wednesday 22nd March 2023 14:00 - 15:00   and
Wednesday 5th April 2023 14:00 - 15:00

In these webinars we invite entrants from the 2022 ARCHER2 Image and Video Competition to talk about their work, and the science behind their stunning images and videos.

[Join link]( https://eu.bbcollab.com/guest/28a7a30423e7469a91a2b1d2f931964e)

This online session is open to all. It will use the Blackboard Collaborate platform.




## RDFaaS maintenance 3rd - 5th April 2023

RDFaaS will be undergoing maintenance and so will be unavailable to users.

This means that the filesystems `/epsrc` and `/general` will not be available.

It will be made unavailable to users from 14:00 on Monday 3rd April.

It should be fully restored by 18:00 on Wednesday 5th April though we hope most services will be restored before this. 

Further information will be available on the[ Status page]( https://www.archer2.ac.uk/support-access/status.html)



## Efficient use of the HPE Cray EX Supercomputer ARCHER2

28 - 30 March 2023 09:00 - 17:00 GMT - Rescheduled to avoid strike days

This three day workshop will provide attendees with the knowledge required to understand the most optimal way to port, execute and optimize applications for ARCHER2. The workshop is a mixture of lectures and practical hands-on sessions. Example exercises will be provided but attendees are encouraged to bring their own applications.

Specific topics that will be covered include:

- Cray EX System Architecture
- Compiling and running applications ( Programming Environment, compilers, libraries, Slurm )
- Debugging tools
- Application profiling
- Optimization of applications for serial performance, parallel execution and efficient use of I/O

This is an opportunity to learn about the system hardware and software architecture, direct from HPE Cray Centre of Excellence experts, and we do not expect to be able to repeat this opportunity in the near future. No recordings will be provided so we encourage you to sign up now to ensure your place.

[Full details and registration](https://www.archer2.ac.uk/training/courses/230321-hpe-cray-ex/)


## ARM Forge tools (DDT and MAP) license "boost" 

Week beginning  20th March (this week)
 
We have arranged that the license for ARM/Forge (debugging via ddt and profiling via MAP) be increased from the existing 64 nodes to
256 nodes. This is for a limited period only: 7 days from Monday 20th March (after which the license reverts to 64 nodes).
We encourage developers and users to try out the tools, or try out larger problems. [Instructions](https://docs.archer2.ac.uk/data-tools/arm-forge/).


Note that ARM Forge was recently acquired by a new owner, Linaro; we still refer to "ARM Forge" for the time being to avoid confusion.



## Major software Upgrade: Fri 14th April - w/b Mon 8th May


A reminder that there will be a major software upgrade on ARCHER2 from Friday 14th April - week beginning 8th May. This major software upgrade includes the base operating system, the Slingshot interconnect system software, the HPE Cray Programming Environment and the HPE Cray Management Software.

This essential upgrade will ensure access to security updates; improvements to interconnect reliability and performance; improvements to upgradeability, maintainability and monitoring; and access to more recent compilers, software libraries and tools. Unfortunately, the major software upgrade will cause a long outage but we have endeavoured to minimise the outage as well as give as much notice to users as possible so that you can plan accordingly.

During the upgrade, users will be unable to connect to ARCHER2 via the login nodes, jobs will not run on the compute nodes and users will not be able to access any data on the system which include the /home, /work, NVMe and RDFaaS (/epsrc and /general) file systems.

Following the upgrade, we would advise users to recompile and test your codes as the new software will be based on a new operating system and new versions of compilers and libraries. The ARCHER2 CSE team will be recompiling and testing all centrally installed software. There will be no Python 2 installation available as part of supported software following the upgrade. Python 3 will continue to be fully-supported.  

We will include weekly reminders of the software upgrade in the ARCHER2 weekly newsletter and a further notification will be sent to all users two weeks prior to the upgrade. We are also planning a user forum which will provide an opportunity to ask any questions to HPE and EPCC staff and learn about new features and changes to the user environment following the upgrade.

We have created a [webpage with further details of the upgrade](https://docs.archer2.ac.uk/faq/upgrade-2023/) which will be updated throughout the upgrade process:  

Please [contact the service desk](mailto:support@archer2.ac.uk) if you have any concerns regarding the upgrade. 

     
## Recently added Known Issues
 
The "[Known Issues](https://docs.archer2.ac.uk/known-issues/)" page of the ARCHER2 Documentation
<https://docs.archer2.ac.uk/known-issues/>
lists all current open known issues including a description of the issue, its symptoms and any work-arounds.

- No recent issues


## Upcoming ARCHER2 Training

- [Message-passing Programming with MPI](https://www.archer2.ac.uk/training/courses/210000-mpi-self-service/), Online, always-open self-service course
- [Shared Memory Programming with OpenMP](https://www.archer2.ac.uk/training/courses/210000-openmp-self-service/), Online, always-open self-service course
- [QM/MM with GROMACS + CP2K](https://www.archer2.ac.uk/training/courses/220000-gromacs-self-service/), Online, Always open - self-service course <br><br>
- [Efficient use of the HPE Cray EX Supercomputer ARCHER2](https://www.archer2.ac.uk/training/courses/230321-hpe-cray-ex), Online, 28 - 30 March 2023 09:00 - 17:00 GMT 	
- [Data Analysis and Visualisation in Python](https://www.archer2.ac.uk/training/courses/230330-data-analysis-python/), Online, 30 - 31 March 2023 09:30 - 17:00 BST 
- [ARCHER2 for Data Scientists](https://www.archer2.ac.uk/training/courses/230411-data-scientists/), Online, 11 April 2023 10:00 - 17:30 BST 
- [HPC Carpentry](https://www.archer2.ac.uk/training/courses/230411-hpc-carpentry/), Edinburgh, 11 - 12 April 2023 09:30 - 16:00 BST 
- [Modern C++ for Computational Scientists](https://www.archer2.ac.uk/training/courses/230417-modern-c/), 17-20 April 2023, 09:30 - 12:30 BST
- [ Modern C++ for Computational Scientists](https://www.archer2.ac.uk/training/courses/230424-modern-c/), Online, 24 - 27 April 2023 13:00 - 16:00 BST 
- [Data Carpentry](https://www.archer2.ac.uk/training/courses/230424-data-carpentry/), Online, 24th - 27th April 2023 09:30 - 13:00 BST

[Further details of upcoming training](https://www.archer2.ac.uk/training/#upcoming-training)

[Twitter](https://twitter.com/ARCHER2_HPC)

[Recordings of past courses](https://www.archer2.ac.uk/training/materials/)

[Recordings of past virtual tutorials](https://www.archer2.ac.uk/training/materials/webinars)