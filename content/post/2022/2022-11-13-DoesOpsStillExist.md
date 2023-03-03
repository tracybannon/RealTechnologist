---
title: "Does Ops Still Exist??"
date: 2022-11-13
subtitle:    ""
layout:      post 
description: "Does Ops Still Exist?  What has happened to Operations folks?  The rise of the term SRE (site reliability engineer) seems to indicate Ops has somehow gone away.  DevOps did not diminish the need for Operations and neither will SRE."
author: Tracy Bannon
image:       "img/BlogImages/colin-watts-oaiESTTyAu0-unsplash_smaller.jpg"
tags:        ["Operations", "SRE", "DevOps", "DevSecOps"]
categories:  ["Blog" ]
---
??? Does Ops still exist ???  This is an honest question.  I’ve spent my career knee-deep in software architecture, design, engineering, and delivery. Never once in my adoption of DevOps principles and practices did I think that Ops had gone away OR that Ops had suddenly started to build software products.    
 
Y’all probably know my story by now that I am truly Dev married to Ops.  My hubby and I started our “Dev + Ops” journey over two decades ago when we both worked for AccuWeather in good ol’ State College PA.   Recently, on one of our long evening walks together, I posed the question:  “Does Ops still exist?”   
 
Our initial unison voice was “of course!”; then we started to decompose and compare what has changed over time.   What was Ops when we started our journey and how has it changed?
 
+ 𝐎𝐩𝐬 𝐰𝐚𝐬 𝐜𝐡𝐚𝐫𝐠𝐞𝐝 𝐰𝐢𝐭𝐡 𝐭𝐡𝐞 𝐬𝐭𝐚𝐛𝐢𝐥𝐢𝐭𝐲 𝐨𝐟 𝐩𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧.   They were very protective, rightly so, of any access and any changes. Ops was the moat.   Ops was also the builder of the outer defenses and implementers of our DMZs.  As part of software engineering, I was awestruck and enamored with Ops knowledge of any and all hardware, all compute, all networking, all storage.  They spoke of  NIC cards, jumpers, and dip switches. . 
 
+ 𝐎𝐩𝐬 𝐡𝐚𝐝 𝐞𝐥𝐞𝐯𝐚𝐭𝐞𝐝 𝐩𝐫𝐢𝐯𝐢𝐥𝐞𝐠𝐞𝐬 𝐢𝐧 𝐩𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧.  This was done to ensure stability by reducing the roster  of those who could make changes.  It also reduced possible security leaks and helped avoid data policy incursions should someone access a translation log, event log, or datastore. It was not foolproof!  I can attest to conducting many environment drift evaluations to understand configuration changes.  Enter CMDB, ITIL and … well, let’s not go down that path right now. 
 
+ 𝐎𝐩𝐬 𝐰𝐞𝐫𝐞 𝐭𝐡𝐞 𝐟𝐢𝐫𝐬𝐭 𝐫𝐞𝐬𝐩𝐨𝐧𝐝𝐞𝐫𝐬 𝐭𝐨 𝐞𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭 𝐢𝐬𝐬𝐮𝐞𝐬, especially production.  (For  this, they had my undying gratitude.) While our product teams (called dev teams back in the day) worked hours more aligned with the business, Ops ran shifts around the clock. Ops had permanent pagers while software engineers took turns at being “on call” .  We begrudgingly took the “Level 3 pager” on Friday afternoon for the coming weekend and hoped we would not be interrupted.   
 
+ 𝐎𝐫𝐢𝐠𝐢𝐧𝐚𝐥𝐥𝐲, 𝐝𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭𝐬 𝐰𝐞𝐫𝐞 𝐚𝐧 𝐚𝐜𝐭𝐮𝐚𝐥 𝐜𝐨𝐥𝐥𝐚𝐛𝐨𝐫𝐚𝐭𝐢𝐨𝐧 between Development and Operations with deployment checklist reviews and the need to improve the deployment checklist based on inputs from Ops.  As we got smarter and better and as technologies improved, automating deployment steps was shared across the team.  Anyone was welcome to write the DCL, PowerShell, and eventually bosh scripts.  (Caveat: no matter what, only the DBA could ever, ever, ever, touch the database; the deployment team always had at least one DBA, often seemingly frustrated with the possible risk and the lack of rollback forethought.)
 
Keeping in mind that collaboration takes time and that Ops was focused on stability.  Also keep in mind that I was not always a patient architect or engineer. In my adoption of more and more techniques that eventually became known as CI/CD and DevOps, I began to “automate away the need to collaborate”  whenever and wherever possible. 
 
𝐓𝐇𝐄𝐑𝐄!  I said it aloud.  Most won’t admit this and perhaps I am alone in my honesty.  I knew that I could ask “my Ops guy” for advice even when we no longer worked for the same company so why did I need to work as closely on deployment with the operations group? 
 
To continue that vein, I believe that DevOps is mostly about rapid design and development of quality software.   DevOps and DevSecOps are both highly focused on pre-production/ operations and the subsequent desire to remove the barriers to moving more capabilities to the end user.   
 
I saw a need to make the software as maintainable and debug-able as possible without me. I applied my understanding of Ops having served a few tours in the shared service gang and living with Ops. 
 
Reducing my Ops dependency happened incrementally starting by automating deployments to remove the need for Ops help.  We would execute the deployment and when the automated test and safety net or manual smoke tests passed, we declared our work done and left it to Ops to monitor.  As cloud adoption and infrastructure as code (IAC) improved and expanded,  we included IaC as part of the deployment.  
 
In retrospect, could this have been a way to include Ops thinking without including Ops as part of the team?
 
+ 𝐎𝐩𝐬 𝐝𝐢𝐝 𝐧𝐨𝐭 𝐨𝐟𝐭𝐞𝐧 𝐡𝐚𝐯𝐞 𝐭𝐡𝐞 𝐥𝐮𝐱𝐮𝐫𝐲 𝐨𝐟 𝐟𝐨𝐜𝐮𝐬𝐢𝐧𝐠 𝐨𝐧 𝐢𝐦𝐩𝐫𝐨𝐯𝐞𝐦𝐞𝐧𝐭𝐬.  Why?  Often because they were firefighting latent issues arising from changes to an environment.  While Ops has often been forced into first responder mode, it does not mean they could not and did not identify and desire improvements!  In one agency, Ops had different teams based on continuous monitoring and production stability and others focused on implementing improvements and automations. Wnyone who tells me that SREs are suddenly a new and different breed will find me hard to convince. 
 
Does Ops still exist?  🆈🅴🆂!  Has it changed? 🆈🅴🆂!
 
𝐎𝐩𝐬 𝐚𝐧𝐝 𝐒𝐑𝐄 𝐚𝐫𝐞 𝐫𝐞𝐥𝐚𝐭𝐞𝐝, perhaps even “kissing cousins. I am sure we will begin to use them interchangeably over time.   Ops has always been focused on stability,  reliability, and resiliency of production. So why the rise of SRE and the conversations about the death of Ops?  Because the tools and techniques have changed!   I remember the joy when we could ghost image and build new servers without having to use ISO images!  Step by step we have created grand and wonderful tools to automate away the manual and the monotonous. Everything as code means our Ops folks need to learn development techniques and our Dev folks are learning about infrastructure, networking and protocols, and such.  
 
Now development teams are called product teams or platform teams.  Some build end user software and others build the pipelines needed to apply automations needed for modern software delivery. If they build a pipeline, they may be called DevOps teams.   If they are worth their salt, they are cognizant of the impacts of software architecture and engineering decisions on production operations (though this is not new!!)
 
Now risk, audit, compliance, and security have a place at the table helping the DevSecOps teams add the automations and policy as code.  
 
Now Ops teams are often called SRE teams (though not all.)  We still have hardware and we still have data centers and we still have those that do not yet have the luxury of an SRE error budget, though I am confident the concept of inverting reliability focus to realizing that five nines is a goal that affords a mire 5 minutes and 35 seconds of downtime and disruption. 
 
Bryan Finster, James Brookbank and I have been chatting about this recently on the DevHops podcast... I realized how much has changed and how massively different our individual  journeys are though how similar the intent. 
 
Is Ops dead?  🅽🅾!.  It is being refreshed with new tools, new measurements, new processes, new techniques, and in some corporations, new names. 
 

*Photo by Colin Watts on Unsplash* 