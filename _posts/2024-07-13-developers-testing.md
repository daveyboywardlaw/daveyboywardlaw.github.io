---
title: Developers Testing
layout: post
post-image: /assets/images/improving-testing-through-support.png
description: 
tags:
- Testing
- Software Development
- Quality
---

# Why developers testing works

## Introduction

In this post I am going to talk about the advantages of having developers doing the testing over a dedicated tester. 

## A bit of background

Recently I have changed role from a test manager to a quality lead. Now it may not sound like much of a shift but is actually is. Now the company that I am working for have the concept of a quality assistance model which was developed by Atlalasain.

Now in this model there are no testers and the developers do the testing. Now this was something that I heard of and in my precious role developers did a good share of the testing but there was still a tester on hand to do testing. I remember hearing this idea a few years ago by Alan Page and Brent XXXX on the AB testing podcast and their modern testing principles. Now when I first heard it I was a tester and I remember totally disagreeing with them as I listened to one of their podcasts on my drive home from work. But being curious I kept listening to the podcast and as time went time and through trying some things out at work I started to agree with what they were saying. 

Having been in my role for a few weeks and seen how it works with no testers, I feel it is the way forward for testing and quality. Releases can be quick and quality is just as good - if not better than if you have dedicated testers. Now the role of a quality lead is to build a quality first culture by being a voice for quality in all stages of the product lifecycle. Now if this works then the team get all the help they need from a testing and quality perspective, with the ultimate aim of the quality lead working themselves out of a job.

### What do the developers do?

Now in my current role the developers from a testing perspective do the following:

 * Write automated tests for the task they are working on
 * Manually test the change (against acceptance criteria and other less edge case scenarios) and add test evidence to the ticket
 * Pair with another developer and that developer tests the changes (with more of a focus on edge cases) with the developer who made the changes present. Basically pair testing.

### Advantages

So what are the advantages of this?

 * Faster feedback

    When 2 developers are testing the feedback is quicker. If there are any tests that need adding they can be added during the testing session. If coode changes are needed they can be made and the testing developer can redeploy locally and retest the change.


 * Know the code

    They know the code. People often say that devs cant test because they know the code. In my view knowing the code makes developErs very good testers. They know eher there could be issues as they know for example how the code integrates with other parts of the system. A tester does not know that therefore there is a greater risk that an issue may not be picked it 


 * Helps developer learn testing skills

    As there is no dedicated tester then the develoeprs hone theor testing skills. Now sometimes you hear the phrase "Developers don’t have a testing mindset" . I don’t agree but lets say that they don’t. Whats the best way for them to get one? By testing and getting the input of a quality lead to help and gide them. By doing this the testing skills can be learn and they can be utailised in manual testing sessions as well as in the automsted tests that they write. 
         

 * Helps developer understand the application

    Not all developers know the UI well so by having developers pair testing manually they get exposure to the UI and understand more about how it works.  


Testing is just something atht needs to be done and ot ereally doesn’t matter who does it. If the developers do it you can shop quality software quicky without losing anything that a dedicated tester can add. 

### Summary

There are some things that you need to have in place in order for this to work. But there is no reason why they cannot be.

Devs are also involved in refinement

 write automated tests as well as what we call FlexiQA
