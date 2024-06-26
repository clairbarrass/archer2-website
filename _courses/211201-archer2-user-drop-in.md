---
layout: course
title: ARCHER2 user drop-in session
banner: web_banners_05.jpg
human_dates: Wednesday 1st December 2021  14:00 - 16:00 
start_date: 2021-12-01 14:00:00
end_date: 2021-12-01 16:00:00
trainers: Julien Sindt, Juan Rodriguez Herrera
course_type: vt
registration_status: 
registration_url:
location: Online
location_url:
prace_course: false
---

We ran a webinar last week to introduce the [ARCHER2 full system](https://www.archer2.ac.uk/training/courses/211117-archer2-full-system/) and the recording and slides from that webinar are available. 

Now that users have access to the ARCHER2 full service, we will be running a drop-in session on Wednesday 1st December from 14:00-16:00, where members of the ARCHER2 support team will be on hand to answer questions about the ARCHER2 full system and transferring data from the 4-cabinet system to the full system. 

We're aware that switching to a new system can be complicated, and we will be on-hand throughout this webinar to answer questions, provide advice, and hear feedback from the ARCHER2 community about this process.

Drop in at any point during the session - it is not expected to attend the full two hours.

This online session is open to all. It will use the Blackboard Collaborate platform.


## Summary of the Questions asked and Answers given

Q. I have an issue using `module restore PrgEnv-gnu`

A.  On the full system you should use `module load PrgEnv-gnu` instead

More info: <https://docs.archer2.ac.uk/user-guide/sw-environment/>

---

Q.  How do I run on the full system while it is uncharged - my budget was all used on the 4-cab

A.  Ask the PI for enough extra CUs to give your budget a positive balance and then you can run on the full system during the uncharged period using your usual account code.

More info: <https://docs.archer2.ac.uk/archer2-migration/account-migration/#how-much-resource-will-my-project-have-on-archer2-full-system>

---

Q.  I have an issue using the PETSc version I compiled on the 4-cab - I have copied it to the /home directory on the full system

A.  You must have it on your /work directory as only the /work directory is visible to the compute nodes.  
You may need to recompile on the full system.
If possible, use the centrally installed version `module load petsc`

More info: <https://docs.archer2.ac.uk/software-libraries/petsc/>
	
---

Q.  My code used to take just a few minutes to write the output on ARCHER.  It takes several hours on ARCHER2 - why is file-per-process IO so much slower, and how can I fix this?

A. ARCHER2 nodes are much bigger than on ARCHER1 so file-per-process will generate a *lot* of files very quickly

This, in turn, can overload the filesystem

It would be difficult to diagnose this without seeing the code. If the problem persists, I would recommend submitting a query to support@archer2.ac.uk to ask one of the support team to have a look at your code.

More info: <https://docs.archer2.ac.uk/user-guide/io/>

---

Q.  Is it possible to obtain a greater quota on /work for some large runs

A.  Email the service desk explaining why you need the extra quota, how much you need, and for how long, and we will do our best to accommodate you.

Contact the desk: [support@archer2.ac.uk](mailto: support@archer2.ac.uk)

---

Thanks to all who took part in the session



<!--

<section id="service">

  <div class="row ">	

      <div class="col-xs-6 col-sm-4">
        <a class="ar2_linkbox ar2_linkbox-teal" 
          href="https://eu.bbcollab.com/guest/7242f53cebc04ee1b5554c88b2ab235f">
          <strong>Join Session</strong><br/>
          Join this online session in your browser
        </a>
      </div>

      <div class="col-xs-6 col-sm-4">
        <a class="ar2_linkbox ar2_linkbox-green" href="courses/"
           href="myevents.ics">
          <strong>Add to Calendar</strong><br/>
          Download ICS file to add this event to your calendar complete with join link
        </a>
      </div>

											
    </div>

-->


<!--
<h2><a name="video">Video</a></h2>

<div>

<iframe title="Video"  width="560" height="315" src="https://www.youtube.com/embed/XXXXXXXXXXX" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>

-->

<!--

<section id="service">
  <div class="container">
    <div class="row ">	



      <div class="col-xs-6 col-sm-4">
        <a class="ar2_linkbox ar2_linkbox-teal" href="  ">
          <strong>Transcript</strong><br/>
          Download a transcript of the video audio
        </a>
      </div>



      <div class="col-xs-6 col-sm-4">
        <a class="ar2_linkbox ar2_linkbox-green" href="courses/"
           href="ARCHER2_Training_VT.pdf">
          <strong>Slides</strong><br/>
          Download pdf of the presentation.
        </a>
      </div>
										
    </div>
  </div>
</section>
-->
