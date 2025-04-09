---
title: "AT&T National Outage - Lessons learned"
date: 2024-02-28T23:02:30-05:00
draft: False
---

One of the things that made national news a little while ago now is the national outage of the AT&T mobile network. You can read about it from a journalists/editor's perspective here: [AT&T National Outage on AP News](https://apnews.com/article/cellular-att-verizon-tmobile-outage-02d8dfd93019e79e5e2edbeed08ee450)

## My First Guess

My first guess when it came to the outage, was some sort of ransomware attack for three main reasons:

1. How suddenly the outage started happening and how slowly it propagated through the network.
2. The company seemed to not say what caused it or even their suspicions earlier on in the news run.
3. Ransomware attacks seem to be happening more and more these days.

It seems that I was wrong as of now, because AT&T is now reporting in the media that it was due to someone running an incorrect operation during a network expansion programming.

## What does that mean?

So if AT&T had new towers setup hardware-wise, then sometimes scripts or programs have to be run to hook them into the network on a programmatic level. And running proper script and/or program would have been the 'correct' operation.

Now imagine that in the same folder of those scripts or programs, there's an option to run one which deactivates existing towers on the network instead of signing in new ones. That would be an 'incorrect' operation.

## Hardening against it in the future

In the future, infrastructure can be hardened to keep such a mistake from happening. Which will likely be one or a combination of the following:

1. A sandbox environment - It is typically bad form to deploy new code in a production environment. Many companies deploy new programs or changes in a sandbox or development environment, so it doesn't take down their production environment, which is what customers actually use.
2. Isolating the processes from each other - It's common sense to me that conflicting processes shouldn't be in the same place. Hopefully there is a way to further isolate said processes from each other.
3. Employee accountability and safety standards - If the issue happened due to an employee being too tired to run the right process or something, some safeguards can be placed to advise employees not to run potentially network-altering operations unless they're well rested and in the right mind to do so.

Now with this being said, it will be hard to tell if AT&T actually implements any of these controls. Except for internal reports by employees or going another 25 years without a similar event, AT&T is free to keep any potential future mitigations secret. Unless our government calls for a hearing to force them to divulge said information.