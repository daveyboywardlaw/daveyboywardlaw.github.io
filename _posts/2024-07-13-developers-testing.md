---
title: Why Developers Testing Works
layout: post
post-image: /assets/images/developers-testing.png
description: 
tags:
- Testing
- Software Development
- Quality
---

## Introduction

In this post I am going to talk about the advantages of having developers doing the testing over dedicated testers. 

## A bit of background

Recently I have changed role from a test manager to a quality lead. Now it may not sound like much of a shift, but it is in many ways. The company that I am working for have the concept of a quality assistance model which was developed by Atlassian. More details about this can be found here:

 [Developing quality assistance skills](https://www.atlassian.com/inside-atlassian/software-QA-skills)

Now in this model there are no testers, and the developers do the testing - both 'manual' and automated. Now having the developers do the testing was something that I knew about. In my previous role developers did a good share of the testing but there was still a tester on hand to do testing if required. I remember hearing the idea of no testers a few years ago by Alan Page and Brent Jensen on the AB testing podcast. Now when I first heard it I was a tester and I remember totally disagreeing with them as I listened to one of their podcasts on my drive home from work. I remember swearing a little when I heard it as I was a tester and if testers were not required then I may not have a particularly long career in testing. But being curious (like most testers are) I kept listening to the podcast and as time went by and through trying some things out at work I started to agree with what they were saying. 

Now the role of a quality lead is to build a quality first culture by being a voice for quality in all stages of the product lifecycle. Now if this works then the team get all the help they need from a testing and quality perspective without a dedicated tester and they learn new skills along the way. Having been in my role for a few weeks and seen how it works with no testers, I feel it is the way forward for testing and quality. Now I did think this before but there was always a slight hesitancy as I worked in an environment where there were still a few testers so maybe that was like a comfort blanket to me. However, in a role where there are no testers, and the developers do the testing it has become clear to me that it is the best way to test and help improve the quality of what is produced. By having the developers doing the testing, releases can be quick, and quality can be equal - if not better than if you have dedicated testers. 

### What do the developers do?

Now in my current role the developers from a testing perspective, do the following:

 * Write automated tests for the task they are working on
 * Manually test the change (against acceptance criteria and other less edge case scenarios) and add this test evidence to the ticket
 * After their testing, they pair with another developer and that developer tests the changes (with more of a focus on edge cases). So basically, pair testing.

Prior to making a change they are also involved in refinement and discussions with the product and design teams to about how the specific feature will work etc...

So the developers do have a good understanding of what they are building and why. 

### Advantages

So what are the advantages of this?

* **It provides faster feedback** - When 2 developers are testing the feedback is quicker. If there are any tests that need adding they can be added during the testing session. If code changes are needed, they can be made and the testing developer can redeploy locally and retest the change there and then. If there is a technical discussion to have they can have it there and then. This short feedback loop really helps get changes done quickly and the value out to the customer quicker. 
    

* **They understand what’s under the hood** - They know the code and, in my view, knowing the code makes developers very good testers. As they know the code they know where there could be issues, for example, issues with how the code integrates with other parts of the system. This can aide them in thinking of test scenarios and potential issues to look out for that a tester may not be aware of. Also, by testing with another developer additional knowledge about the code may be bought to the testing which again can help improve the testing that is done. 

* **It helps developers learn testing skills** - As there is no dedicated tester then the developers hone their testing skills. Now sometimes you hear the phrase "Developers don’t have a testing mindset". I don’t agree but let’s say that they don’t. What’s the best way for them to get one? By testing of course!!!! Now trying to test without much experience can be hard and difficult to learn. But if they have access to someone like a quality lead to help and guide them, that learning can be accelerated. And like all learning those lessons can then be used in future testing sessions. Now the quality lead (or whatever you want to call it) can mentor and coach the developers as a when they need it. To start with it may be that they ask for a lot of help but as the time goes by, they stop asking as it isn't required so much as they have built the skills. The testing skills that they learn can be utilized both in manual testing sessions as well as in the automated tests that they write in the future.

* **It helps developer understand the application at a higher level** - Not all developers know the UI well, so by having developers pair testing manually they get exposure to the UI and understand more about how it works. This in turn gives the team additional input into the UI which may result in changes and updates to improve it. 

### Summary

Developers testing is a great way to improve quality and add value to customers quicker through faster feedback loops. Its not about getting rid of testers. The testers would just move into a different role, for example quality lead. And even then, if you have a quality lead the ultimate aim for the quality lead is to work themselves out of a job. After all once the teams have become great testers, deliver quality software and constantly look to refine and develop their testing and quality skills as a team, they don't need a quality lead. And that is not a bad thing, the quality lead can then move to another role which uses their skills in a way that helps the business. Remember, testing is just something that needs to be done and it really doesn’t matter who does it. If the developers do it you can shop quality software quickly without losing anything that a dedicated tester can add. 

Now before people say you need testers and you can’t have developers do all the testing, there are things that need to be in place to make this work. You can’t just get developers to test and that’s it. I will write about this in a future post. These things that you need are not rocket science or anything that cannot be done with some time and thought.
