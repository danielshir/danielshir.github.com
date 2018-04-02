---
layout: post
title: "The Team Asymmetry Fallacy"
date: '2018-04-02 12:47:00 +0300'
categories: software management
crosspost_to_medium: false
---

Teams need to work with each other to get work done, there’s no question about that. When it comes to a large scale software project, usually multiple teams are involved and team cooperation is key to getting the product out of the door. In every organization there are bound to be several types of teams. Some teams are considered quite adept and strong, while others may be simply balanced, but some teams (and this is true for every organization I’ve seen) are deemed weak and less effective than most. This blog post however isn’t about that fact, but rather how it is often dealt with.

Imagine yourself as the head of an R&D department in Software Co. You have a total of four teams under you, two are considered strong and two are considered weak.

![R&D chart]({{ "/img/assets/team-asymmetry-fallacy/image1.png" | absolute_url }})

For all intents and purposes, I’m assuming that we must accept the current team situation as a given. Obviously, as the head of R&D, it’s up to you to make sure that all teams are professional and capable within your organization. 

First, let’s go over what characterizes a team as either strong or weak. Here are some basic identifying characteristics:


|Category|Strong Team|Weak Team|
|-------|--------|---------|
|Division of labor|Efficient|Inefficient|
|Scheduling|Tight, precise|Lacking organization|
|Handling of arising problems|Effective|Ineffective, throws team into mayhem|
Work rate|Productive|Mediocre|
|Scope changes|Adept at making changes|Changes require a lot of synchronization from all team members|
|Supervision|Autonomous|Constant hand holding|


Now, let’s also imagine that we need to work on two projects, which we’ll appropriately call Project A and Project B. Both projects have a similar workload, an identical level of importance, and each requires two teams’ worth of full time attention. How should work be split across all four teams?

The initial reaction most people would have to this question would be to split the work symmetrically across the R&D department. That is, to have each strong team pair with a weak team to tackle a single project. Here’s the equivalent diagram - 

![Division of labor]({{ "/img/assets/team-asymmetry-fallacy/image2.png" | absolute_url }})

Since both Project A and B have a similar priority with a similar workload, the initial reaction to symmetrically divide up the work is understandable. Most companies I’ve worked with use this exact system. The real interesting question here is, what’s going to happen when a strong team has to interact with the weak team and vice versa?

Let’s explore this team dynamic point by point:

It’s clear from the table above that both the division of labor and scheduling will suffer. Strong teams are able to divide labor up efficiently, but having to work with a weak team means that the other team hasn’t been able to do the same. This means that sprints are usually not lined up and features aren’t ready at approximately the same time, causing delays in integration. “Why is feature X not ready? Well Brandon isn’t here this week and we have no idea what’s going on in there. He’ll do it when he gets back”. I’m sure this is familiar to most.

Arising technical problems will cause issues as weak teams are usually thrown into disarray when a serious technical problem comes up. In a weak-strong project dynamic, this usually means that whatever problem comes up, it’ll be up to the strong team to take charge and solve it on their end. I’m pretty sure all software developers have witnessed this kind of thing unravel within the codebase. Wondered what’s that weird formatting logic doing on the backend and not on the client side? Well, that’s because of some client-side technical slack being picked up by the backend team.

Strong teams usually don’t require a lot of supervision, and of course by contrast weak teams need a lot of check-ins, sync meetings and administration. As with other facets of the weak-strong dynamic, the concessions will almost always be made by the strong side of the equation. What this means is that you’ll have your stronger developers wrapped up in meetings, stand-ups and sync meetings rather than buckling down and tackling your company’s greatest tech challenges. It’s a simple misallocation of resources.

The strong-weak dynamic is something to be avoided. Projects that use it, are almost always guaranteed to be on track with the weak team’s pace, leaving the strong team frustrated and unmotivated. Speed of execution is the product of of all working factors for a given project. Throwing a weak team into the mix is a real speed killer.

Of course there’s no obvious solution for this type of situation. Steps should be taken in order to ensure that the organization’s team are strong rather than weak. However, this isn’t always a possibility, at least in the short term. Referring to the earlier example, the solution I’d like to offer is a bit controversial. 

What if we organized our teams like this:

![New division of labor]({{ "/img/assets/team-asymmetry-fallacy/image3.png" | absolute_url }})

In our new scenario, we have two dynamics - strong-strong and weak-weak. In my opinion, this ends up being a lot more efficient than the previous configuration. The strong teams can be left to their own devices, developing Project A quietly and peacefully. As for the teams working on Project B, much of management’s attention can be focused on both weaker teams in order to make sure things go as smoothly as possible. 

Instead of “paying the management tax” twice, we’re just going to “pay” it once. In addition, it’s a lot easier to manage risk when it’s focused around a single area of development rather than dispersing it across several projects. It’s actually the opposite of say, portfolio diversification in an investment analogy.

This isn’t to say that this is a miracle solution for this issue. Project B will have to be very carefully developed and monitored to make sure that development is done correctly and efficiently. There are no silver bullets, and the best thing would be to avoid this situation altogether - hire carefully!

If you ever find yourself in this type of situation, just try to explore this type of work configuration. I bet you’d be surprised at how much smoother the workflow can be when we choose team strength symmetry over asymmetry. 
