---
title: Testing prior to release and testing in production
layout: post
post-image: /assets/images/tester-to-quality-coach-help.png
description:
tags:
- Testing
---

Testing prior to release is testing to see if the feature behaves as you expect. Testing in production is testing to see if it adds value. Successful testing in one does not guarantee successful testing in the other. In this post I will go into a little more detail and explain what I mean.

## Testing prior to release

Testing prior to release is the testing that most software folks are familiar with. This will typically involve:

 * A developer testing their changes by writing unit, integration and maybe UI tests. 
 * A tester running tests (typically again the UI) or maybe testing things like APIs using tools like postman.

## Testing in production

Testing in production is when the activities of the user are monitored and observed. Typically this will involve things like:

 * Looking to see how the user interacts with the software
 * Raising alerts when an exception occurs in the logs

## What does successful testing look like in each
So what does successful testing look like in each of these areas

### Release testing
So successful release testing will look good when:

 * The changes that are tested match what is described is something like a functional specification
 * The developers unit tests pass
 * The developers integration tests pass
 * The developer/testers automated UI tests pass

### Testing in production
Successful testing in production will look good when:

 * There are no exceptions in the log files
 * Users are using the new feature or elements of it

## Successful release testing != successful testing in production (and visa versa)
So why does successful testing prior to release not mean that testing in production wil be successful?

Imagine this: you've thoroughly tested a new feature before release. You've done exploratory testing, covered a wide range of test scenarios via automation and reviewed everything against the user story or even a detailed functional specification. Everything checks out, and you feel confident that the feature will make customers happy because there is a low likehood of bugs. So, you go ahead and release it.

A few days pass. You start monitoring usage and quickly realize something's off — no one is using the feature. Then, a call comes in from someone high up in the company:
“This new feature hasn’t driven the increase in paid subscriptions we were expecting.”
The team gets a stern talking-to, and you're left confused. There were no bugs at release. Testing went well. But despite successful pre-release testing, the real-world outcome didn’t match what management were expecting.

Now flip that situation. The feature was rushed and testing was minimal due to tight deadlines. You release it nervously, expecting a flood of bug reports. But surprisingly, only a few minor issues pop up. Monitoring shows heavy usage of the new feature. Soon, you get another call from a higher-up — and this time, it’s praise: “This new feature exceeded our expectations have paid subscriptions have gone up ten fold.” The team is congratulated and even given the rest of the day off.

Sure, it could have gone the other way. If the lack of testing had resulted in severe bugs, the feature likely wouldn’t have driven much value because of the bugs.

The takeaway? Just because a release passes all your tests doesn’t mean it will succeed in the real world. Testing in staging or QA environments isn’t the same as testing in production — and success in one doesn’t guarantee success in the other. Yes testing in production is partly looking for issues in the logs like exceptions, but it is also about testing to see if the feature is actually being used. Its no good having a app with no bugs that nobody uses. If it is being used then it is adding value to the users and if it add values users will continue to use it as well as pay to use it. 
