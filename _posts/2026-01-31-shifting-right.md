---
title: Why shifting right is important
layout: post
post-image: /assets/images/testers-breaking-things.png
description: Article about why shifting right is important
tags: Quality
---

## Intro
This post was inspired by xxx on his post about shift right. This post will talk about the why shift right is important, what you can test in shift right and why it is key to a mature quality engineering culture.

## So, what is shift Right?
So, shift right is 'testing' that is done after the software has been delivered. Now I am using the word testing loosely here. I don't mean it is the type of testing where a tester tests a system via automation or manually, I mean it is observing the behaviour of the system after it has been released and is in the users’ hands. 

## Why is it important?
Ultimately only the customer can say whether the software they are using is of good quality or not. Now testers and quality engineers may have good idea, but ultimately, they cannot say 100% that the software is of high enough quality for the end user’s needs. 

When teams are working on software they can do things, such as:

- Speak to users to understand things such as how they use the system and what problem the software is trying to solve. This is great we have a window into the end user, this will help us with development and testing.
 - Make sure that our test environment matches the production set-up so that we know we are testing on similar hardware. This is great as we now we have a test environment like production, so we should get a realistic view of the software’s performance on that hardware. 
 - Load datasets that replicate the data that is in production. Again great, we now can see how the system performs and looks with Prod like data.

Now all of this is great but often this doesn't happen. Deadlines need to be hit; customers may not have the time to speak to you and getting real world data can take some time. Now, you may get some of these kinds of things, but you will  rarely get everything. And even if you did, who’s to say that you won’t get an issue in production that you thought you had mitigated through testing and having all these things set-up.

Also, quality is so much more than testing. Quality is not just about making sure the software doesn't break its about helping our users complete the task they need to with the least amount of friction as possible. Its no-good having software that works but frustrates the users so much that they stop using it. If we don't shift right, we may not know or be able to foresee in enough time, when the quality is degrading and our users are unhappy. 

Shift right is important because ideally it enables you to fix issues prior to them being discovered by the user, as well as pivoting if the team needs to work on other areas or stop working on a feature at all. 

## What can you test in 'shift Right'?
There are quite a few things you can do when you 'Shift Right'. I will go through a few of these and explain what they are and how they can lead to creating a quality software product.

### Monitor what the user does
With tools such as Pendo and you can track how a user uses the software. You can track things such as:

 - What pages they have visited
 - What path are they taking though the software
 - What features they are using the most. 

Now these things are so important to monitor and track. By understanding how the user is using the software you can tell how well your hypothesis worked on a new feature or an update to an existing feature. Let’s say your product team did a bunch of research into a new feature. Your team then release that feature, and you find out that it is hardly being used. Yes, this is disappointing and proves that whatever hypothesis you had was wrong. However, you have learnt a valuable lesson and one that you can take with you moving forward. Now imagine you get someone suggest a similar feature at a later date. You can use that information from the experience of monitoring to push back and say that this kind of thing has not been successful in the past so let’s not do it. By doing this you can focus on another piece of work that will potentially get used and add value rather than working on something that will probably fail. You can also use Pendo to see what the user flows are and can make changes to the application based on this information. For example, you could remove buttons that are not being used to make the interface look more modern and contemporary

By having these pieces of information, you can focus the team’s effort on places to drive change that add value to your users and no waste time on areas that are not used. Also with tools like Pendo you can ask through surveys how the users feel about your software which can provide valuable information and insight into your users which can drive positive change. This can also feed you data and insights about what the user likes and what things could be improved.

### Monitor performance
Performance can often slowly degrade over time, and it can be hard to notice if you don't monitor it. With tools such as Datadog you can monitor hardware performance, such as CPU usage and also things like how long API calls are taking. You can set up dashboards and alert thresholds to make sure you know exactly what is going on and get alerted when thresholds are exceeded. Now how can this improve the quality of the software? Well over time, if you see the performance degrading you can investigate it and resolve. This will mean that the user may never get to a stage where they raised a bug because the software is slowing down. From their perspective the software is always responsive and performant. In this scenario you have improved the quality of the application without the user even knowing. They key thing for monitoring performance is knowing what your thresholds are so you know when you need to start thinking about improving it.

### Monitor logs for Issues
Sometimes the application that a user is interacting with can have issues that do not manifest itself in a way that a user will notice. As users we have all encountered situations where you’re using an application or website, and you do something and all of a sudden an error dialogue appears telling you that something has gone wrong. Now these types of errors are obvious and there is a chance that the user will raise an issue, especially if they lose some work or the issue impacts their day-to-day work significantly. Now imagine an event occurs but there is not dialogue box. The user will just carry on, totally unaware of the issue that has just occurred. Monitoring log files is a way to get alerts when these exceptions occur, potentially in scenarios when the user is oblivious. Again, like monitoring performance, you are improving the quality of the software but fixing issues before the user even knows about them. Tools such as Azure Monitor are great for doing this.

Now the monitoring performance and monitor logs are both proactive approaches to shift right. They are taking the initiative and fixing things before the user raises an issue and you must fix it through a support ticket. 

## What do you need to do?
Now all of what I have mentioned are great but a key thing to make them work and be successful is to think about them as early as you can in the software development lifecycle. So, in the below holistic testing model, this would be on the left-hand side.  

![Holistic Testing Model](/assets/images/holistic-testing-model.png)

When it comes to shifting right, you need to be asking questions in the shifting left side, like:

 - What does success look like from a user’s perspective? How will we monitor that?
 - What do you want to monitor?
 - How are we going to monitor?
 - Why do we want to monitor?
 - Who will monitor?
 - Will we manually monitor or will we get automated alerts
 - What trends are we looking for
 - What thresholds will tell us we need to do something?					 	

These need to be asked as early as possible, so that any work that needs to be planned in to enable the monitoring, can be done. 

 ## Why is it key to a mature quality engineering culture?

 Shifting right is key to a mature quality engineering culture. Shifting right with monitoring and observability is about being proactive and mature processes are proactive. Reacting to issues creates stress, interrupts teams flow if they have moved onto other pieces of work and most importantly, can tarnish a company’s reputation if user find lots of bugs and issues. With a little forethought a team can improve the quality of features that have developed as well as fix any bugs that may have gotten through.
