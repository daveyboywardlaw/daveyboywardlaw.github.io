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

Testing prior to release is the testing tat most software folks are familiar with. This will typically involve:

 * A developer testing their changes by writing unit, integration and maybe UI tests. 
 * A tester running tests (typically again the UI) or maybe testing things like APIs using tools like postman.

## Testing in production

Testing in production is when the activities of the user are monitored and observed. Typically this will involved:

 * Looking to see how the user interacts with the software
 * Raising alerts when an exception occurs in the logs

## What does successful testing look like in each
SO what does successful testing look like in each of these areas

### Release testing
So successful release testing will look good when:

 * The changes that are tested match what is described is something like a functional specification
 * The developers unit tests pass
 * The developers integration tests pass
 * The developer/testers automated UI tests pass

### Testing in production
SUccessful testing in production will look good when:

 * There are no exceptions in the log files
 * Users are using all elements of the new feature

## Successful release testing != successful testing in production (and visa versa)
So why does successful testing prior to release not mean that testing in production wil be successful?

Well imagine you have testing a new featire prior to release and all looks good. You have done explaoratory testing and have tested a bunch of edge cases and looking at the user story (or maybe even a functional specification) everything looks good. You think that the customer will be happy as everything works as it should. 





