---
title: "#NoHobbyists - Cybersecurity Cannot Depend on Hobbyists"
date: 2022-11-06
subtitle:    ""
layout:      post 
description: "We have a talent and knowledge deficit with cybersecurity. The pace of technical innovation is ever increasing as is the need to constantly upskill.  Often, the most successful and sought after talent spend many many hours on their own to keep pace; this is not sustainable."
author: Tracy Bannon
image:       "img/BlogImages/jasmin-schreiber-JE4iHJE-knI-unsplash.jpg"
tags:        ["CyberSecurity", "Training", "Developers"]
categories:  ["Blog" ]
---
When it comes to cybersecurity , we have a talent and knowledge deficit right now.  The truth is that organizations have not budgeted or planned for the consistent upskilling need.  The pace of technical innovation is ever increasing as is the need to constantly upskill.  Often, the most successful and sought after talent spend many many hours on their own to keep pace.   

Being honest, I have to admit I really love tech!  It’s my passion, my hobby, and my career.  That having been said, keeping pace takes extra dedication, cycles, and hours. In my role as a chief architect and in my engineering role, I am constantly parachuted into different organizations across a broad spectrum of sizes; regardless as to the size or domain, I have observed a growing dependency on folks keeping current and upskilling in their own time. 
<img src="/img/BlogImages/NoHobbyistsHashTag.jpg"  width=75% height=75% ALT="#NoHobbyists" >


There should be **#NoHobbyists** when it comes to Cyber Security!  We cannot allow our people and our teams to be completely self-taught in their free time!   The goal is to step back from assuming people can and will invest on their own.  So what do we do?

First, we need to agree that software security is a shared sport. There is no one in the organization that is exempt or excluded. Organizations need to have leading software delivery policies and standards as well as basic business policies. The [NIST Cybersecurity framework (CSF)](https://www.nist.gov/cyberframework/getting-started) is a great, inclusive framework for thinking through broad risks and beginning to address the basics.  

Next, we need to recognize the shortage of cyber talent. In the October 2022 [(ISC)<sup>2</sup> Cybersecurity Workforce Study](https://www.isc2.org/Research/Workforce-Study) , the global shortage is 3.4 million workers with over 700,000 positions unfilled in the US alone.  With this deficit, organizations are making do with their current talent, asking them to take on more responsibility and placing tremendous faith in automated pipelines.In addition to designing/implementing mission logic and the tests to visibly  demonstrate quality, developers are front and center in cyber-security. 

Here’s a wrinkle:  most upskilling and innovative tools are not developer focused.   Earlier in 2022, Synopsys called out a “critical gap in developer security training puts applications at risk”.  

As an industry, what are we to do?  Take a look at these suggestions:

 ### Structured Education 
 Put structure around developer education - Most security training for developers lacks depth and examples.  Focus on the 70:20:10 model with 70% on the job experience and challenges, 20% informal like mentoring and 10% formal training.  

I'm doing this now with stream-aligned teams and avoiding heavy upfront training.  This doesn’t mean no formal training; it means focus on applying what has been learned.  I’m finding more and more groups are taking on this informed and practical approach.   It’s much like apprenticing.  You need to learn, practice, and demonstrate. 
<img src="/img/BlogImages/70-20-10.jpg"  width=50% height=50% ALT="70:20:10 Education Training Model" >

Training and upskilling efforts are following this approach and we’re seeing growth in industry away from formal-only course work. Often, it is taking the form of a more “lean than Six Sigma'' belt approach.   For example,  [Gary Gruver's](https://www.linkedin.com/in/garygruver/) Engineering Digital Transformation (EDT) course uses a white-green-blackbelt approach.   A white belt has formal training, green belt is demonstrating mastery of the course content in a real world setting and finally, a black belt has successfully executed and is now helping others on their white and green belt journeys. 

<u>Bottom line - *training cannot be limited to the classroom and must rapidly become experiential*.</u>

 ### Relevant Training
Make sure the training is relevant - This may appear to be common sense though case studies and examples provided do not match the technology or platforms delivery teams are using.  This can be a real dilemma.  Established languages like Java or Python have a dramatically larger catalog of available security training than newer languages and tools. You may need to chat with your chief architect or lead engineer to understand relevant design patterns and the underlying architecture to better tailor training.  

There can be tremendous opportunity to build a shared culture when security folks and developers work through the technology stack together making sure the delivery team understands leading design and delivery practices and that those who are more focused on cybersecurity reviews, audits, and operational know the tech stack and languages used as well.  Also keep in mind that individuals may need additional training on complementary tools.  For example, cyber security professionals often use Python given its readability and flexibility for tasks such as attach simulation, port scanning, or even intrusion detection. 

 ### Break Things Mindset
Teach developers to think about breaking things - Sounds counterintuitive? Nope!  Developer mental maps are to create new and build.  Include "how to break it" dialog in training, visioning, peer reviews and paired walkthroughs.  I advocate a short tour-of-duty with the operations folks who support applications and solutions.  They are  frontline in daily debugging.  We all know that developers are generally NOT supporting operations daily.  That is a fallacy of modern #DevOps and why we are seeing the rise of SRE and other “oops, what about production” conversations. It can be quite a mental model shift to think about how each line of code you are writing could be broken though once that shift takes place, software engineers and developers write more secure code by design. 

 ### Budget for Upskilling
Plan time and funding for upskilling and education - Perhaps the biggest challenge to reducing hobbyists is to commit funding and plan time for cornerstone learning. The education and learning company, Security Journey/Hacked_EDU also places emphasis on hands-on learning moving away from lecture or slide-driven education to immersive experience.   The US Air Force has invested in immersive learning with their [Digital University](https://digitalu.af.mil/) founded with the help of an industry consortium. It’s so effective that other US Services are looking to use this capability as well.  

Many training organizations and groups focused on improving cybersecurity knowledge are also recommending changes. Synopsys calls out that the lack of developer training in particular on secuirty topics is a risk to all [application security (appsec)](https://www.synopsys.com/blogs/software-security/security-training-developers/).

 ### Give time for play
Give the entire delivery team time to play!  Give teams dedicated time to play with different training projects.  One particularly popular training project that is used in universities and high schools is the OWASP training project [WebGoat](https://owasp.org/www-project-webgoat/).  Their playful motto speaks volumes:  “Learn to Hack, Stop the attack.”   Keeping with the theme of not forcing our delivery teams to be cyber security hobbyists, it is important to both team building and to learning to provide dedicated time to learn through play. 

Gamification tools are also helpful for learning.  CISA (the US Cybersecurity and Infrastructure Security Agency) has partnered with Pacific Northwest National Labs to create cybersecurity learning games for mobile devices.   The first to be released is “Defend the Crown”.  MITRE, a federally funded research and development corporation (FFRDC) has also created a gamification engine specifically for cyber security learning.  The [MITRE Cyber Academy](https://mitrecyberacademy.org/) gives options to learn and compete with other students. They’ve extended the offering to include embedded software cyber techniques as well. 

 ### Team Threat Modeling
Treat threat modeling as a team sport - Build a shared culture by threat modeling together.  It may sound elusive though the concept is simple:  use your existing backlog of user stories to pull together a cohesive team even: business, cyber, testing, designers, developers, users/product owner.   Using “ye ole mad lib language” for a user story, extend it to add two new items:  the critical asset and possible threat!   Cyber thought leader, Alyssa Miller helped me frame this out when we met at RSAC!  

<img src="/img/BlogImages/MadLib.jpg"  width=50% height=50% ALT="Cybersecurity User Story MadLib" >

Bear in mind there are many types and levels of threat modeling; it is not the intent that organizations would rely on MadLib threat modeling as their sole approach. The team MadLibis intended to provide exposure to different ways of thinking and different humans involved.   

Developers learn how cyber professionals think; Cyber focused folks learn how testing engineers evaluate and process.Everyone learns how the end user or product owner thinks and their fears and needs. 
<img src="/img/BlogImages/MadLibFilledIn.jpg"  width=50% height=50% ALT="Cybersecurity User Story MadLib Example" >

 ### Know Dependencies
You must know your dependencies!   It never ceases to amaze me how many organizations don’t know or manage dependencies actively. It can be overwhelming.  POM, BOM, SBOM, hierarchies and lineage, open source and package managers.  The key is to get started.  There is no OSFA (one size fits all) approach.  Work with your product teams directly to understand how they are approaching dependency management.  Note the tools and techniques.  Together, identify opportunities to share what works and improve where there are gaps.  Look for automations and ability to directly tie and trigger to your CI/CD pipeline. 

For those that work in the government space, there is the added complexity of achieving supply chain goals of the [White House Executive order from May 2021](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/).

 ### Encourage Experimentation
Always encourage experimentation - This is the basis for all modern software engineering!  With experimentation will come outcomes. Whether you label them success or failure, learn fast and iterate, celebrating each new outcome.  It can often be difficult in a long established organization to begin adoption of an experimental mindset. Let’s face it, executing experiments means the organization will see some ideas absolutely flourish while many others will fail. 

Dr. Ron Westrum’s organizational culture model can give a few insights on the difficulties.Westrum’s research identified three types of organizational culture: pathological (power oriented), bureaucratic (rule oriented) and generative (performance oriented).  Failure is viewed exceptionally differently for each: pathological organizations address failure with scapegoating, bureaucratic organizations seek justice for failures,.  It is only the highly cooperative, shared risk mental model of a generative organization that sees failure as an opportunity for inquiry and learning.

### Shared Responsibility & Grace
Embrace Shared Responsibility And Give Grace - Cybersecurity is truly a shared responsibility.  It takes patience, intentionality, and psychological safety to usher this new shared mindset forward.  My friend,  [Lisa Plaggemier](https://www.linkedin.com/in/lisaplaggemier/),wrote 

>“Cybersecurity is all about shared responsibility, communication and collaboration. Yet, for decades the fear of retribution from bad actors has precluded businesses from actively and openly engaging with their customers with regard to cybersecurity.”


If you take away a single thought, it is that we **cannot lob more responsibility onto developers without arming them and the organization**!  Security is not for self-taught hobbyists.  Learning, experimentation, and psychological safety MUST be cornerstone elements as we move forward with secure software. 


*Photo by Jasmin Schreiber on Unsplash* 