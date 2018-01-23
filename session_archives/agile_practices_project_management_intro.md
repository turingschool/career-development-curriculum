---
title: Agile Project Management
layout: page
---

## Why

To build great software we need to be intentional about the **process**. Whether working solo or in groups, your process is a more significant determiner of your project's success than your technical skill.

In this session we'll take a quick overview of "Waterfall", "Agile", and how to begin managing your projects at Turing.

### Learning Goals

* Students can describe the general concept of the "waterfall" model
* Students can explain how "agile" differs from waterfall
* Students can explain the idea of a sprint
* Students can write a story following a template

## Big Picture

### Waterfall Development

1. Requirements - the big book of features
2. Technical Design - "architects"
3. Implementation - "code monkeys"
4. Verification - handoff to Q/A
5. Maintenance - let interns fix the bugs

#### Strengths of Waterfall

* Once requirements are set, you can estimate how long it'll take to build. But...you're wrong.
* Easy to stagger teams, have one hand off to the next each phase
* Spend a long time in 1 & 2 billing clients and you don't have to build anything
* When the project fails you blame the requirements and those people are long gone

#### Problems of Waterfall

* Writing requirements is impossible
* Each phase takes months/years -- quickly outdated
* No chance to "listen to the code"
* No user feedback until complete
* No potential for revenue until complete
* It just doesn't work

### Agile

1. Requirements
2. Design
3. Implementation
4. Verification
5. Feedback & Approval
6. Goto 1

#### Problems with Agile

* No real estimate of the total cost
* Like veganism, crossfit, people won't shut up about it
* Need to have cross-functional teams
* A whole lot of conversation ("I've never seen a project fail...")

#### Strengths of Agile

* Responsive to the user / product owner
* "Discover" the better solutions along the way
* Can grow organically
* Easier to stop early
* Possible to generate revenue along the way

#### Agile in the Real World

* GitHub's story
* Eric Ries' "The Lean Startup"

## Agile in Baby Steps

There are all kinds of strategies, frameworks, and buzzwords around agile development. But everything revolves around *stories* and *sprints*.

### The Sprint

A sprint is the time box that our work fits into.

* Typical sprint is 2 weeks
* Starts with planning (aka requirements)
* It always takes longer than planned
* Cut scope or extend time?
* Always cut scope (half, not half-assed)
* Features are delivered in production
* Solicit user feedback
* Ends with review/retrospective

### A Story

"How to Write (Good) Stories" is a 90-minute lesson unto itself. But let's do the express version. A good story:

* Exhibits a tiny chunk of business value
* Is written in a common format
* Can be clearly demonstrated/verified
* Represents half a work day of labor, or less!

#### A Template for Stories

```plain
As a(n) [user type]
In order to [extract business value]
When I [take some action]
  (and [take some other action])
Then I [observe an outcome]
  (and I [observe another outcome])
```

#### Quick Story Writing Practice

Let's start with some ideas that translate well to single stories.

*Imagine* we've prototyped a small to-do list app. It just allows the user to create to-dos. And it only supports a single user.

Start on your own and draft one story for *each* of the following:

*   Checking the box for a to-do moves it to the completed list
*   The top of the todo list has a count of the number to todos which updates when I add a new one
*   Clicking trash on a to-do pops up a confirm/cancel dialog

Then we'll turn to a pair and compare our results.

#### Where You Go From Here

* Start using a project management tool, like Waffle
* Turn your requirements into stories following this template
* Prioritize stories and schedule sprints (even just 2-3 days)
* Deploy to production, maybe solicit feedback from "users"
* Cutting scope is ok, cutting quality isn't

## Addendum

Want more? Here are some additional resources you can check out:

* The [Waterfall model](http://www.agilenutshell.com/agile_vs_waterfall)
* The [Agile Manifesto](http://agilemanifesto.org/principles.html)
* Scrum:
  * [Video](https://www.scrumalliance.org/why-scrum)
  * [More Info](https://www.scrum.org/Resources/What-is-Scrum) 	
* Tuckman's Stages of Team Development:
  * [Video](https://www.youtube.com/watch?v=OhSI6oBQmQA&list=PLbu6naAjG_K93h0wjyn1b1EHQl1Q2pH_y)
  * [More Info](https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
* [XP aka Extreme Programming](http://www.extremeprogramming.org/)
* [Git Workflow for Teams](https://github.com/turingschool/professional_skills/blob/master/module_two/git_workflow_for_teams.md)
* [Waffle.io](https://waffle.io/)
* [What is Agile?](https://www.agilealliance.org/agile101/)
* [10 Key Principles of Agile](http://www.allaboutagile.com/what-is-agile-10-key-principles/)
* [Agile Programming Best Practices](https://www.versionone.com/agile-101/agile-software-programming-best-practices/)
