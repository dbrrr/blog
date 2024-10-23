---
layout: post
title:  "Ships in the Darkness (Greenhouse Noise part 2)"
date:   2024-10-23 13:54:18 +0200
categories: organizations 
---

Read [part 1]("/organizations/2024/10/05/greenhouse-noise.html") here.

When reflecting on greenhouse noise, I've begun thinking about daily work in naval terms. I'm sure LinkedIn would love the analogy. A team is a boat. Its members are the sailors. The organization is a fleet. 

But what I find interesting about the analogy is that _navigation_ is a central topic in sailing, not only for an individual team/ship but for the cohesion of the fleet. Will the ships collide? Are they going in the same direction? Are they executing maneuvers in in coordination? 

Before GPS, naval navigation used various instruments in a process called "dead reckoning". Wikipedia gives the following definition:

> [...] dead reckoning is the process of calculating the current position of a moving object by using a previously determined position, or fix, and incorporating estimates of speed, heading (or direction or course), and elapsed time.

Estimation, speed, calculations -- tweak a few words, and it sounds like a book on agile methodologies!

<div align="center" style="text-align: center; margin-bottom: 10px;">
   <img src="/assets/celestial_navigation.jpg" width="350px" style="padding:10px;" alt="Scrum masters"/>
   <div style="color: #4D4D4F; font-size: 0.7em;"> Scrum masters estimating burndown</div>
</div>

The notorious problem with dead reckoning is _compounding error_ -- accuracy is a function over previous measurements *and their errors*, and without recalibration against "known good" measurements it can become highly inaccurate over larger distances. Regular recalibration is essential for success; again, not unlike agile. GPS obviates this completely, because position (and subsequently bearing) are continuously measured with high accuracy. 

Unfortunately, organizational alignment isn't as well-defined a problem as positioning on the globe. We can't simply recalibrate by sighting a few landmarks. Even with excellent and responsive metrics and fast feedback cycles, you'll never know your exact "position" -- you can only reduce the range of error and reduce the cost of mistakes. Furthermore, by analogy, positioning is an *operational* problem for each individual ship/team. But an organization is a fleet -- good positional accuracy within each team is a necessary but not sufficient condition for alignment. **Even if the ships know exactly where they are, they still need to know their bearings** (i.e. where they're going). They also need the bearings of _the other ships_ in order to coordinate.

How does this relate to noise? Well, I think noise which comes as *a result of* organizational friction can be compared to difficulty in finding your position and/or bearings *as a result of* moving together with a fleet. 

<div align="center" style="text-align: center; margin-bottom: 10px;">
   <img src="/assets/sailing_in_the_dark.webp" width="350px" style="padding:10px;" alt="This message has been brought to you by AI"/>
   <div style="color: #4D4D4F; font-size: 0.7em;"> Rowboat-driven development</div>
</div>

I recently had a discussion with a coworker where I used the analogy of seeing a rowboat come out of the darkness to deliver some information. But -- the mere existance of a rowboat in the open ocean suggested the presence of a larger ship nearby. Which ship? Are they a part of the fleet? Do they know where I'm going? Do I know where they're going? Should I go talk to that ship? Why did they send a rowboat?

I think this idea captures some of the factors which I believe contribute to noise:

  - Knowledge silos create <a href="https://en.wikipedia.org/wiki/Fog_of_war" target="_blank">fog of war</a>. Fog of war gets in the way of transparent communication. Assumptions are made. Miscommunications occur. On a clear, sunny day, multiple ships can coordinate in unison. 
  
  - Fog of war fosters inefficient alignment. Small rowboats float between teams, crowdsourcing operational visibility. We're ignoring the existence of radios, here 😉.

  - Misalignment creates uncertainty. Ships get in the way of each other. To avoid collisions, they move more cautiously. Sails are reefed and the crew await new orders.

Coming back to navigation, I think how successfully you can re-calibrate your team/ship's position compounds _all of this_ since the fleet can't decide on a new course without a good understanding of where it is. In the worst case you're still in the realm of dead-reckoning (slow, inefficient, high-risk, with compounding "drift"), and in the absolute worst case you're dead-reckoning as a fleet using disparate navigational instruments scattered between various ships and reaching consensus using row-boats. In such an environment, communication becomes focused more on where the fleet _is_ instead of where it's going. The fleet itself becomes an obstacle to navigation. And when those ships leave for vacation, you realize it's open water and how much time you spend dodging rowboats 🚣.
