---
title:       "Faux Script Kiddie!"
subtitle:    "Why is it so easly to learn to hack?"
description: ""
date:        2021-06-03
author: "Tracy Bannon"
categories:  ["Blog" ]
image:       "img/BlogImages/ScriptKiddie.jpg"
tags:        ["CyberSecurity", "DevOps", "DevSecOps", "Tech Reflections"]
---
A few weeks ago I dusted off my dog-eared copy of ”The Web Application Hacker’s Handbook” by Studdard and Pinto (Yes,I still prefer printed books though I now spring for a second e-version for when I’m traveling.). 

I’ve installed the most recent version of Burp Suite community edition and OWASP’s ZAP and  decided to freshen up my ethical hacking/cyber-student skills.   Of course, I am not probing public sites, but rather, using the ethical learning sites:

DVMA- (https://dvwa.co.uk/) 
OWASP’s Mutillidae II  (https://github.com/webpwnized/mutillidae) 
WebGoat (https://owasp.org/www-project-webgoat/)

To be clear, I am not actively pen-testing live sites and wasting valuable corporate and government resources thwarting my explorations.  That is left to the script kiddie who has little parental oversight, time on their hands, and the same tools and learning available to me.  They actively attempt to hack live sites and targets.   I’m focused on legitimate sites created just for learning and testing.   Script kiddies often waste many resources of corporate America and the government because we have to pay attention even to the beginner hacker.

I could claim to be a bit of a faux script kiddie, or be a bit more honest that I am a software architect and engineer that must keep my skills current. Guiding teams, sponsors, clients, and communities on software design and the use of DevSecOps capabilities means staying current is an imperative or perhaps better stated, 

*No alt text provided for this image*
As I have been sampling curriculum available through academia as well as industry, I’m struck by the focus on cyber pros and penetration testers.  While this is a very necessary group of folks, are we as an industry, investing the time and effort to arm our developers, testers, engineers, and architects on cyber practices and application security? 

AppSec, as my buddy Joe Stagner likes to call application security, still does not have the momentum and focus needed.  Security is everyone’s responsibility. Security is not only the role of the scanning pro or pen-tester.  

The learning aides and tools are available and often are free to get started.  A simple docker pull command and your teams are ready to learn.   

![DockerPull](/img/BlogImages/DockerPull.png)

So we have tools and job aides. Next we need dedicated time; not extracurricular or personal evenings spent because we are passionate. Building a culture of shared security responsibility requires organizations to include time in our estimates and value stream delivery roadmaps for learning and for keeping skills honed and for keeping our people engaged, armed, and motivated.   

Studdard and Pinto include an entire chapter, ch 21, on hacking methodology. If plausible,  everyone can benefit if we factor in additional time for each software product for a hack-a-thon executed by those who are designing, coding, and testing?  Everyone learns or sharpens skills and with some elbow grease, new gaps are potentially identified.   Granted, this book and methodology are focused on web enabled applications though the concepts are a rock-solid foundation for AppSec.  There are many other resources available as well.  Working hand in hand with our cyber-pros can only provide better coverage.

There is a growing reliance on software factories and DevSecOps pipelines to provide the cyber foundations.  While I am an advocate of jumpstart tools, frameworks, and even platforms, we need to beware the growing trend to outsource DevSecOps pipelines away from the operators, away from the testers, and away from the developers.  

The software industry needs to have a mix of specialists, generalists, and athletes that are as deeply knowledgeable about how the assembly lines/software conveyor belt works as they are about the software products flowing across them.  DevSecOps is not something you acquire; it is not something you buy.  

![SecurityTree](/img/BlogImages/SecurityTree.png)
Figure 1: One of many available AppSec hacking / analysis frameworks for software pros to explore.[1]  

OWASP and BURP both provide excellent frameworks for systematically searching for and uncovering vulnerabilities.  As a software engineer or developer, my future code can be greatly improved from the learning experience of having hacked my own products. Identifying and scanning for vulnerabilities, penetration testing, runtime testing and even code review should be a part of our normal software intensive system lifecycle.

[1]Stuttard, Dafydd, and Marcus Pinto. The Web Application Hacker’s Handbook: Finding and Exploiting Security Flaws. 2nd ed., Wiley, 2011.

Feature Image from https://www.cybervista.net/threat-actor-profiles-script-kiddies/