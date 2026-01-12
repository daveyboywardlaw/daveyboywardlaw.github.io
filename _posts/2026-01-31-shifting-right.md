---
title: Why shifting right is important
layout: post
post-image: /assets/images/testers-breaking-things.png
description: Article about why shifting right is important
tags: Quality
---


## Intro
This post was inspired by xxx on his post about shift right. This post will talk about the why shift right is important, what you can test in shift right and why it is key to a mature quality
engineering culture.

### So, what is shift Right?
So shift right is 'testing' that is done after the software has been delivered. Now I am using the word testing loosely here. I don't mean it is the type of testing where a tester tests a system via automation or manually, I mean it is observing the behaviour of the system after it has been released and is in the users hands.

### why is it important?
Ultimately only the customer can say whether the software they are using is of good quality or not. Now testers and quality engineers may have good idea but ultimately they cannot say 100% that the software is of high enough quality for the end users needs. 

Now when we are working on the software our team can do things such as:

- Testers and quality engineers can speak to users to understand things such as how they use the system and what problem the software is trying to solve. Now this is great we have a window onto the end user which will help us with our testing. 
 - Make sure that our test environment matches the production set-up so that we know we are testing on similar hardware. This is great as we now we have a test environment like production, so we should get a realistic view of the softwares performance on that hardware. 
 - Load datasets that replicate the data that is in production. Again great, we now can see how the system performs with Prod like data.

Now all of this is great but lets be honest, how often does this actually happen? You may get some of these kind of things but you will very rarely get everything. And even if you did,  whose to say that you wont get an issue in production that you thought you had mitigated through testing and having all of these things set-up.

Also quality is so much more than testing. Quality is not just about making sure the software doesn't break its about helping our users complete the task they need to with the least mount of friction as possible. However, if we don't shift right we may not know or be able to foresee in enough time when the quality is degrading and our users are unhappy. 

SHift right is important because it enables you to fix issues prior to them being discovered by the user as well as pivoting if the team needs to work on other areas or stop working on a feature at all. 

## What can you test in 'shift Right'?
There are quite a few things you can do when you 'shift Right'. I will go through a few of these and explain what they are and how they can lead to creating a greater quality software product.


### Monitor what the user does
With tools such as Pendo and you are able to track how a user uses the software. You can track things such as:

 - What pages they have visited
 - What path are they taking though the software
 - What 'features' they are using the most. 

Now these things are so important to monitor and track. By understanding how the user is using the software you are able to tell how well your hypothesis worked on a new feature or an update to an existing feature. Lets say your product team did a bunch of research into a new feature. Your team then release that feature and you find out that it is hardly being used. Yes this is disappointing and proves that whatever hypothesis you had was wrong. However, you have leant a valuable lesson and one that you can take with you moving forward. Now imagine you get someone suggest a similar feature at a later date. You can use that information of experience of the monitoring to push back and say that the this kind of thing has not been successful in the past so lets not do it. By doing this you can focus on another piece of work that will potentially get used and add value. You can also use Pendo to see what the user flows are and can make changes to the application based on this information. 

By having these pieces of information you can focus the teams effort in places to drive change that add value to your users and no waste time on areas that are not used. Also with tools like Pendo you can ask through surveys how the war feels about your software which can provide valuable information and insight into your users which can drive positive change. This can also feed you data and insights about what the user likes and what things could be improved.

### Monitor performance
Performance can often slowly degrade over time and it can be hard to notice, if you don't monitor performance. With tools such as data dog you can monitor hardware performance, such as CPU usage and also things like how long api calls are taking.  You can set up dashboards and alert thresholds to make sure you know exactly What is going on and get alerted when thresholds are met. Now how can this improve the quality of the software? Well over time, if you see the performance degrading you can investigate it and resolve it before the user raises a performance issue. This will mean that the user may never get to a stage where they ran a bug because the software is slowing down. From their perspective the software is always responsive and performant. In this scenario you have improved the quality of the application without the user even knowing.They key thing for monitoring performance is knowing what your thresholds are so you know when you need to start thinking about improving it.

### Monitor logs for Issues
Sometimes the application that a user is interacting with can have issues that do not manifest itself in a way that a user will notice. As users we have all encountered situations where your using an application or website and you do something and all of a sudden an error dialogue appears telling you that something has gone wrong. Now there are obvious and there is a chance that the user will raise an issue, especially if they loose some work or the issue impacts their day to day work significantly. Now imagine an ever occurs but there is not dialogue box. The user will just carry on, totally unaware of the issue that has Just occurred. Monitoring log files is a way to get alerts when these exceptions occur and potentially when the user is not aware. This type of monitoring can help you spot issues and fix them before a user knows there is a problem. Tools such as Azure Monitor are great for for doing this. Now monitoring logs like this  can help improve the quality by fixing issues that could potentially impact the user in a negate way


Now the monitoring performance and monitor logs are both proactive approaches to shift right. They are taking the initiative and fixing things before the user does.

## What do you need to do?
Now all of what I have mentioned are great but a key thing to make them work and be successful is to think about them as early as you can in the sale.. So when you are in the left hand 
side of the Sdk



Figire 8


you need to be asking the following types of questions.

 - What does success look like from a users perspective?
 - What do you want to monitor?
 - How are we going to monitor?
 - Why do we want to monitor?
 - who will monitor?
 - where will we monitor?


 ## Why is it key to a mature quality engineering culture?

 Shifting right is key to a mature quality engineering culture. Shifting right wih monitoring and observability is being proactive and mature processes are proactive. Reacting to issues creates stress, interepts teams flow if they have moved onto other peices of work and most importantly can tarnish a companies reputation if user find lots of bugs and issues.  