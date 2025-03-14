---
layout: post
title: ARCHER2 Weekly Newsletter
date: 2023-04-26 11:00:00
author: ARCHER2 Service
tags: [newsletters] 
categories: [news]
---

- [Service Desk Holiday]({{ page.url }}#service-desk-holiday---monday-1st-may-2023)  : Monday 1st May 2023
- [Delayed - Major software upgrade]({{ page.url }}#delayed-major-software-upgrade) - expected start date now 19th May
- [RDFaaS maintenance]({{ page.url }}#rdfaas-maintenance-29-31-may--2023) 29-31 May  2023
- [Call for Nominations - SIAM Activity Group on Supercomputing (SIAG/SC) Prizes]({{ page.url }}#call-for-nominations---siam-activity-group-on-supercomputing-siagsc-prizes)
- [The 10th ARCHER2 eCSE software development call and Early Career eCSE Panel Observers call]({{ page.url }}#the-10th-archer2-ecse-software-development-call-and-early-career-ecse-panel-observers-call)
	- [The 10th ARCHER2 eCSE call]({{ page.url }}#the-10th-archer2-ecse-call)
	- [ARCHER2 Early Career eCSE Panel Observers call]({{ page.url }}#archer2-early-career-ecse-panel-observers-call)
	- [eCSE and observers call dates]({{ page.url }}#ecse-and-observers-call-dates)
- [Access to HPC Call open]({{ page.url }}#access-to-hpc-call-open)
- [GPU programming with CUDA and HIP training course]({{ page.url }}#gpu-programming-with-cuda-and-hip-training-course)
- [Recently added known issues]({{ page.url }}#recently-added-known-issues)
- [Upcoming ARCHER2 training]({{ page.url }}#upcoming-archer2-training)

<!--more-->
 

## Service Desk Holiday  : Monday 1st May 2023

The ARCHER2 service desk will be closed on  Monday 1st May 2023, reopening at 8:00am on Tuesday 2nd May.


## Delayed Major software upgrade

New Upgrade Date: <b>Expected to start 19th May 2023</b><br/>
Previously scheduled: Fri 14th April - w/b Mon 8th May

The delay to the upgrade is due to HPE planning an additional system software release within the next couple of weeks and they recommend that we upgrade to this latest version rather than the one originally planned.

As soon as the software is released we will be able to formulate a timetable and will notify users of the revised upgrade dates. We expect the upgrade to start 19th May.

Despite, the ARCHER2 team making good progress completing final technical work and preparation ahead of the originally planned upgrade, this further update will require some additional testing and so we expect the start of the upgrade on the main system to be delayed by a few weeks, with the exact timescale depending on the release and install schedule for the new versions of the system software.

This essential upgrade will ensure access to security updates; improvements to interconnect reliability and performance; improvements to upgradeability, maintainability and monitoring; and access to more recent compilers, software libraries and tools. Unfortunately, the major software upgrade will cause a long outage, but we have endeavoured to minimise the outage.

During the upgrade, users will be unable to connect to ARCHER2 via the login nodes, jobs will not run on the compute nodes and users will not be able to access any data on the system which include the /home, /work, NVMe and RDFaaS (/epsrc and /general) file systems.

Following the upgrade, we would advise users to recompile and test your codes as the new software will be based on a new operating system and new versions of compilers and libraries. The ARCHER2 CSE team will be recompiling and testing all centrally installed software. There will be no Python 2 installation available as part of supported software following the upgrade. Python 3 will continue to be fully supported.

We will include weekly reminders of the software upgrade in the ARCHER2 weekly newsletter and a further notification will be sent to all users once the final upgrade start date is confirmed. We are also planning a user forum which will provide an opportunity to ask any questions to HPE and EPCC staff and learn about new features and changes to the user environment following the upgrade.

We have created a [webpage ](https://docs.archer2.ac.uk/faq/upgrade-2023/) with further details of the upgrade which will be updated throughout the upgrade process. As always, please [contact the service desk ](mailto:support@archer2.ac.uk) if you have any questions.

We apologise for any inconvenience which may have been caused by the delay and will provide any further updates as soon as they become available.


## RDFaaS maintenance 29-31 May  2023


RDFaaS will be undergoing maintenance and so will be unavailable to users.

This means that the filesystems ```/epsrc``` and ```/general``` will not be available.

It will be made unavailable to users from 14:00 on Monday 29th May.

It should be fully restored by 18:00 on Wednesday 31st May though we hope most services will be restored before this.

Further information will be available on the [Status page]({{base_url}}/support-access/status)


## Call for Nominations - SIAM Activity Group on Supercomputing (SIAG/SC) Prizes


The [SIAM Activity Group on Supercomputing (SIAG/SC)](https://siag-sc.org/) is looking for nominations for the following prizes:

- [SIAG/SC Early Career Prize](https://www.siam.org/prizes-recognition/activity-group-prizes/detail/siag-sc-early-career-prize): Awarded every two years to one individual in their early career for outstanding research contributions in the field of algorithms research and development for parallel scientific and engineering computing in the three calendar years prior to the award year"

- [SIAG/SC Best Paper Prize](https://www.siam.org/prizes-recognition/activity-group-prizes/detail/siag-sc-best-paper-prize): Awarded every two years to the author(s) of the most outstanding paper, as determined by the selection committee, in the field of parallel scientific and engineering computing published within the four calendar years preceding the award year

- [SIAG/SC Career Prize](https://www.siam.org/prizes-recognition/activity-group-prizes/detail/siag-sc-career-prize): Awarded every two years to one outstanding senior researcher who has made broad and distinguished contributions to the field of algorithms research and development for parallel scientific and engineering computing

The Deadline for nominations is July 31, 2023.

Please consider nominating suitable candidates.

We are especially looking for a diverse set of candidates for the Early Career Prize.




## The 10th ARCHER2 eCSE software development call and Early Career eCSE Panel Observers call 

### The 10th ARCHER2 eCSE call

We are very pleased to announce that the 10th ARCHER2 eCSE call (ARCHER2-eCSE010) is now open for proposals. The deadline for submitting documents for technical evaluation is 16:00 on 23 May 2023, with the final deadline for proposal submission being 16:00 on 13 Jun 2023. The early career eCSE Panel Observers opened alongside the eCSE call and the deadline for applications for this call is 16:00 on 23 May 2023.

Embedded CSE (eCSE) support provides funding for RSEs (Research Software Engineers, PDRAs or equivalent) to carry out software development of codes to be run on the ARCHER2 system. Projects can be requested for up to 18 person months of effort per Project. There is flexibility in the way the effort is requested. For example, a project may have more than one person working on it or the effort could be spread over a greater number of calendar months, i.e. a staff member could work on the project at less than 100% alongside other commitments or it could be worked on by a staff member who doesn't work full time. Please just get in contact with the ARCHER2 Service Desk if you wish to discuss possible scenarios.

The code(s) may already be running on ARCHER2, where the aim is to improve performance or scalability, to add functionality or to improve the usability and maintainability, or the code(s) may be running elsewhere (e.g. on a Tier-2 system) and the proposal could be to bring the software up to a level where it would perform well on ARCHER2.

For this call, software which results in research which is within the remit of EPSRC is eligible. Funding can be requested for staff located at the institution of the PI, third parties, or can include staff from the centralised CSE support team or a mixture of the above.

More details of how to apply are available by following the link to the [eCSE calls page ](https://www.archer2.ac.uk/ecse/)

together with details of the application and review process, assessment criteria eligibility, etc. A [recent webinar](https://www.archer2.ac.uk/training/courses/220428-ecse-webinar/) includes a walk through of the submission of a proposal.

### ARCHER2 Early Career eCSE Panel Observers call 

The eCSE Panel Meeting is the meeting where eCSE proposals are reviewed and decisions are made on which proposals to fund. As part of our commitment to encouraging and developing Early Career Researchers, we are offering a small number of places to such researchers to attend the eCSE panel meeting as Early Career Observers. The aim is to give Early Career Researchers a better insight into this competitive selection process, to assist them in the preparation of future funding proposals.

The deadline for applying to attend the panel meeting as an observer is 16:00 on 23 May 2023.  [Details of the call](https://www.archer2.ac.uk/ecse/observers/)
 
[An insight into the experience from one of our recent Early Career Panel Observers](https://www.archer2.ac.uk/news/2023/01/18/ecse-ec-obs.html)


### eCSE and observers call dates

- Deadline for submitting ARCHER2-eCSE10 documents for technical evaluation: 16:00 on Tuesday 23 May 2023
- Deadline for final ARCHER2-eCSE10 submission: 16:00 on Tuesday 13 Jun 2023
- Deadline for Early Career eCSE Panel Observers call: 23 May 2023

A [recent webinar](https://www.archer2.ac.uk/training/courses/220428-ecse-webinar/) which includes a walk through of the submission of an eCSE proposal.



## Access to HPC Call open

Access to HPC Call (EPSRC remit only) opened 27th March 2023
ARCHER2 or Tier-2 computing resource 

- <b>Feasibility stream</b>
    + Maximum request of £1,000 notional value (for example, 5,000 CU, 33,000 CPUh or 1,000 GPUh).
    + Projects can be up to six months in length.
- <b>Main stream</b>
    + Projects can be up to 12 months in length.
- <b>Pioneer stream</b> (ARCHER2 only)
    + Projects can be up to 2 years in length.
    + Minimum request of 165,000 CU per year.
	
<b>TA Deadline</b> - 12 May 2023 at 4:00pm UK time<br/>
<b>Submit Deadline</b> - 26 May 2023 at 4:00pm UK time

[More details and application forms]( https://www.archer2.ac.uk/support-access/access#calls-for-archer2-time-only)




## GPU programming with CUDA and HIP training course

This Cirrus training course may also be of interest to some ARCHER2 users.

3rd - 4th May 2023 in [Edinburgh](https://www.cirrus.ac.uk/training/locations/epcc)

[Further information and registration]( https://www.cirrus.ac.uk/training/courses/230503-cirrus-gpu/)

This short course will provide an introduction to GPU computing with CUDA aimed at scientific application programmers wishing to develop their own software.

     
## Recently added known issues
 
The "[Known Issues](https://docs.archer2.ac.uk/known-issues/)" page of the ARCHER2 Documentation
<https://docs.archer2.ac.uk/known-issues/>
lists all current open known issues including a description of the issue, its symptoms and any work-arounds.

- No recent issues


## Upcoming ARCHER2 Training

- [Message-passing Programming with MPI](https://www.archer2.ac.uk/training/courses/210000-mpi-self-service/), Online, always-open self-service course
- [Shared Memory Programming with OpenMP](https://www.archer2.ac.uk/training/courses/210000-openmp-self-service/), Online, always-open self-service course
- [QM/MM with GROMACS + CP2K](https://www.archer2.ac.uk/training/courses/220000-gromacs-self-service/), Online, Always open - self-service course <br><br>
- [Cirrus - GPU programming with CUDA and HIP](https://www.cirrus.ac.uk/training/courses/230503-cirrus-gpu/), 	[Edinburgh](https://www.cirrus.ac.uk/training/locations/epcc), 3rd - 4th May 2023 9:30-17:00, 9:00-16:00 

[Further details of upcoming training](https://www.archer2.ac.uk/training/#upcoming-training)

We always welcome researchers wishing to present their work in a webinar - please contact the [Service Desk](https://www.archer2.ac.uk/support-access/servicedesk.html) if you would be interested in presenting your work.

[Twitter](https://twitter.com/ARCHER2_HPC)

[Recordings of past courses](https://www.archer2.ac.uk/training/materials/)

[Recordings of past virtual tutorials](https://www.archer2.ac.uk/training/materials/webinars)
