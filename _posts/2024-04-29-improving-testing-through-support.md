---
title: Improving Testing through support
layout: post
post-image: /assets/images/improving-testing-through-support.png
description: 
tags:
- Testing
- Support
- Quality
---

There are many ways in which you can improve a teams testing. One way is the learnings discovered through sprint retrospectives whilst other ways are for testers to go on courses or learn from testing communities. All of these are excellent mechanisms for helping a team to improve their testing. But how about being able to improve testing through talking to the support team? It may feel that 
support are in their own little world, dealing with customers queries as well as fixing any issues that are raised. However, taking a step back, the support team are the one team that probably have 
more interaction with the end users that most other people. As well as that interaction they may have a massive wealth of information about how the users use the system through any bugs that have been raised. 

So how can the support team help us improve testing?

## Share how users use the system

In support calls that are raised there will be steps to reproduce. Now these steps will be written from the users perspective and this will provide insight into how they are using the system. It may give information such as:

* How users navigate through the system
* Do users use keyboard shortcuts?
* Examples of real life data that users enter
* The order in which users perform certain tasks

Now this information is very useful from a testing perspective. When testing, testers will typically do things a certain way. For example a tester may use the mouse to copy and paste data into the system. But what if through looking at support tickets  a lot of users use keyboard shortcuts? Yes you are testing the copy and paste functionality but you are not using the system like users are. So there is potentially a gap where the testing being done is not representative of how a user uses the system. Now you are never going to test exactly like a user uses the system but if you can cover some of what they do it will help to make sure that the users are satisfied when they use the system.

So how can this be documented? Well it may just be something simple like Sharepoint site that the support team create that documents some key behaviours about the users. The development teams can then use this to help guide how they test. Now the information may change as time goes on (so it should be updated) and it will be a useful resource for anyone who tests the system. 

## Learn testing (and quality) Lessons

Bugs will always get through. Your users may never find the bugs but they will always exist. When a bug is found the best outcome is that it is fixed and deployed as quickly as possible and lessons are learnt. A great way to learn lessons is to look at support tickets that have been raised and understand how various elements (including testing) could have been done better to stop the issue happening again.

Now when issues get raised, each issue will involve interaction with the users around things such as:

* What is the error
* What steps were performed prior to the error occurring
* What data was used
* How it impacts the user

Now the support team will have hopefully understood the issue and managed to fix it. By doing this they have in depth knowledge of the issue and what caused it. Now combining this with the input of a testing/quality professional you can now try and understand why the issue happened and what could have been done to prevent it. This maybe some addition testing that could be done in the future for a similar change or even a documentation update. Getting buy in from the support team should be easy as the aim here is to stop bugs getting raised, and support teams can get behind this as less bugs means more time working on other things that they may want to work on. How you liase with the support team and document the testing lessons is up to you, it may be monthly meetings or it could be done some other way. The important thing is that that information is shared and documented in such a way that it can easily be found by other teams and can be updated when needed. 

Now in my experience issues raised to the support team will typically cover the following kinds of things:

* System questions
* Technical questions
* Behavioural Questions
* Software faults

Now each of these provides an opportunity to not only improve testing but also the quality of other aspects of the system, for example documentation.

Lets look at these things.......

### System Questions

These will typically be questions about what the system can do. Not from a functional perspective but more from a features perspective.

For example, Can I call the api to upadate a users email address.

### Technical Questions

This will be questions about a technical aspect of the system. This will typically be asked by a clients infrastructure team or if the software has apis or is configurable, could be questions from a client development team.

For Example, Will the system work on the latest version of Windows Server?

### Behaviour Question

These will be about how the system will behave in certain circumstances. This could be from a functional perspective or even from an integration perspective.  

For example, Why does the system not mandate a date of birth?

### Software Fault

These will be what you would traditionally call bugs. Issues with the software where the functionality is incorrect or there is an error.

For example, The system doesn't ask for a DOB on a system where age drives additional behaviour or when a user adds a record there is an unhandled exception. 
  
### Documentation

For all of these 4 areas above you can document what needs to be improved however you see best. Here are some examples:

 * Update existing documentation so that the issue raised does not get raised again. For example for a technical question you update technical documentation. 
 * Create a hints and tips document for when you have workshops with potential clients to mitigate the risk of requirements being misunderstood. 
 * Add testing scenarios that should be run for similar changes
  
 Whatever you do the key thing is to mitigate those types of issues being raised again. 
 
## Wrap Up

Support is a key source of information that can be used to improve the quality of your product. Tapping into this will give great insights into users and how they use the system as well as showing you where things can be improved. 
Remember the quality of a system is not just the 'program' that the user sees, its all of the other artifacts around it. If these are not good quality the impact on your product and company could 
be significant. 
