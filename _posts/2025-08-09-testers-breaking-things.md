---
title: The problem with people saying testers break things
layout: post
post-image: /assets/images/testing-prior-release-testing-production.png
description: Article about how saying testers break things can be bad
tags: Testing
---

## Overview

This blog will talk about why saying "Testers break things" can be harmful to testers and can lead to a perception that testers and the skill of testing are not as respected as they should be. 

## Frustration

 One phrase that infuriates me in the testing and quality world is "Testers just break things". It may may take others forms such as: 

 - "You're a tester, your job is to break things"

 - "All you testers do is break things"

 - "Try and do your best to break It"

It may sometimes seem a little jokey or said in jest but ultimately is can have negative connotations to the tester, testers and testing as a whole. Just the word break elicits negative things. As a child you would have got told off if you broke something. I know I did!!!

Also, even now I feel testing in some quarters is still looked down upon like it was a few years ago and saying testers only break things doesn’t help. Testing has in the past been seen (In my opinion) as something that requires less skill and is something that always brings bad news to a project or product. As a tester you will be the one saying, "I've found a critical bug!!" or asking questions that could mean a change is required. Testers don’t actually produce anything that is tangible to help deliver a project or product. A developer writes code that ultimately brings a design and product idea to life. The designer will have designs that will have been reviewed and implemented and a product person will come up with the idea and have research about why the idea will make the company money or benefit the customer. All of these are positive things for a piece of software. However that positivity can be tempered by a tester finding a critical issue a few days before go-live or asking a question about the software that could highlight that re-work is needed. 

### What do I mean by a break?

What I mean by break is an outcome where the software exhibits unintended behaviour that has a negative impact on the users experience of that software. 

### You broke it!!! No I didn't

If this language is used someone looking in from the outside may assume that testers break the software. They may think that they intentionally do something to make the software behave in the incorrect way. Now we all know that this is incorrect. What a tester does is execute (manually or through automation) steps that could result in them observing the software behaving in the incorrect way. Now this incorrect way could be obvious, for example something like an unhandled exception. But it could also be something more subtle like accessability issues or a user flow that could frustrate end users. 

A tester cannot break the software as it is already broken. What a tester does is uncover that break.

### Software is different

Software is different, it is always going to be broken. Somewhere in the process, whether it be in incorrect logic, incomplete requirements or poor unit testing, an issue has crept into the software which could impact the users. There will always be some part of the system that has an issue that has not been found yet. It may be obvious but it may not be. The issues can be very subtle and very hard replicate but in all software there will be issues. So when someone says a tester just break things they are wrong, the software is already broken. What the tester does is use their skill and experience to uncover where the software is broken and in what scenarios. 

## Testers Skills

The key skill of a tester is knowing where to look for these breaks and understand how best to test the software in order to uncover them. Its a skill that requires years of practice to hone and develop. Those years can be spent learning a vast array of tools or becoming an expert in an area of testing such as exploratory testing or security testing. Through years of practice and uncovering issues across potentially many companies and industries testers know what signs to look for and will have some great heuristics that will help them uncover these broken bits of the software. 

 By saying "oh testers just break things" diminishes the skills good testers have and ignore the value work that they contribute to a successful product or project. 

## Changing the narrative

So how can we change the narrative? There are a couple of things you can say and do as a tester to illustrate that as a tester you don't "Just break things"

 - Show the results of what you do 
    
    When you find an issue and you bring it to the team show how you found the bug and your thought process behind what you did to find it. By explaining this to the team they will over time gain an understanding of the skill that it takes to find certain bugs as well as how a testers mind works in various testing scenarios and contexts. 
    
- Pair with developers to test

    This links to the first point. Sit with the developer and pair test. By them watching you in action they can see how you work and how you go about finding bugs in certain scenarios, That will help them understand how you work and they can also ask the why so that they know why you are doing it and can learn so they can test better themselves. 

-  Run a session on Heuristics and Oracles

	To show others in the team some useful heuristics and oracles will help them understand some beneficial rules of thumb as well as how you know as a tester, that something passes a specific test. This will highlight to them the knowledge and skills that you have that you use everyday to help you in your role. They can then use that to help them so that when they test they may potentially capture issues they previously may not have. 

