# Agile Practices & Leadership

## Software Collaboration in Practice

[Slides for this session](https://docs.google.com/presentation/d/1GV_PSrTRRKlXE1IKp9NXRHbgipyK1nmdk34i8n_UobQ/edit?usp=sharing)

### Session Structure

Timing: 2 hours

* Opening: why/reflection discussion, objectives, deliverable (5 mins)
* Waterfall vs. Agile Lecture (40 mins)
   * Lecture (30 mins)
   * Group Discussion (5 mins)
   * Whole Group share-out (5 mins)
* Pomodoro (5 mins) 
* Agile in Practice (20 mins)
   * Lecture (5 mins)
   * Story Practice (10 mins)
   * Share out (5 mins)
* Project Management Tools & Resources (5 mins)
* How Teams Work Together (17 mins)
   * Whole Group Introduction (2 mins)
   * EQ & Leadership Domains Discussion (5 mins)
   * Reflection (5 mins)
   * Tuckman's Group Life Cycle Discussion (5 mins)
* Project Group DTR (20 mins)
* Debrief/Takeaways (5 mins)
* Closing: Next Steps (3 mins)

### Objectives
* Describe the general concept of the "waterfall" model
* Explain how "agile" differs from waterfall
* Explain the idea of a sprint
* Write a story following a template
* Describe how you use your strengths and leadership skills in teams
* Describe how you might adapt your strengths according to team dynamics
* Discuss how to leverage each others' strengths to work even more effectively in your project

### Deliverable
Submit a reflection on using agile and participating in retro feedback using [this template](https://github.com/turingschool/career-development-curriculum/blob/master/module_one/agile_feedback_reflection_guidelines.md) in survey provided by 9am on Friday of Week 5

### Connections: The Why 
To build great software we need to be intentional about the **process**. Whether working solo or in groups, your process is a more significant determiner of your project's success than your technical skill. And refining your process helps you establish your place in the industry as an emerging developer. 

In this session we'll take a quick overview of "Waterfall," "Agile," how to begin better managing your projects at Turing, and how to build even better teams. 

**Whole Group Discussion:** How would you describe your process in last week's paired project? 

### Waterfall vs. Agile 
These two approaches to software development use the same steps but in different ways:

![Agile vs. Waterfall](https://github.com/turingschool/career-development-curriculum/blob/master/files/agileandwaterfall.gif)

#### Waterfall
Waterfall follows these steps in a one-off activity:
1. Requirements: The clients, market researchers, and project managers develop a book of features
2. Technical Design: Software architects design what the app should look like
3. Implementation: Developers follow the spec to the letter to build out the application
4. Verification: QA tests the app according to the spec
5. Deployment & Maintenance: The app is launched; Interns troubleshoot bugs
 
#### Strengths of Waterfall
* This works well in scenarios in which testing is:
  * Infeasible 
  * Expensive
  * Dangerous
* Easy to stagger teams, have one hand off to the next each phase

#### Weaknesses of Waterfall
* Writing requirements is impossible
* Each phase takes months/years = quickly outdated
* No chance to "listen to the code"
* No user feedback until complete
* No potential for revenue until complete

#### Agile
Same steps as Waterfall, executed in iterative rounds, except that there is one additional step: *feedback!*
1. Requirements
2. Design
3. Implementation
4. Verification
5. Feedback & Approval
6. Go back to 1

#### Strengths of Agile

* Responsive to the user / product owner
  * Use of MVPs
* "Discover" the better solutions along the way
* Can grow organically
* Easier to stop early
* Possible to generate revenue along the way

#### Weaknesses of Agile

* No real estimate of the total cost
* People won't shut up about it
* Need to have cross-functional teams and strong teamwork in order to execute
* A whole lot of conversation (see above)
  * "I've never seen a project fail because of technical reasons."
  
#### Turn & Talk
Within your projects teams, discuss:

* How could you adapt the agile process of developing software in this project? What could that look like in practice? 
* Who else could you solicit feedback from during your development process besides instructors? How will that fit into your timeline?

1-2 groups share out their takeaways. 

#### Agile in the Real World

* GitHub's story
* Netflix
  * Advancaed and consistent in software processes
  * Deploys 30-150 times a day
* Digg.com's downfall
  * Google tried to buy them for $200M in 2008
  * After a failed launch of their new web site in 2010 (with little/no feedback loop), by the time 2012 rolled around:
  * LinkedIn bought some of their patents for about $4M
  * Washinton Post paid about $12M to hire the entire Digg team of employees
  * The digg.com domain name, code and data, was sold to BetaWorks for $500,000
* Eric Ries' "The Lean Startup"
* [Agile Manifesto](http://agilemanifesto.org/), written in 2001 and has its merits and its flaws; was part of the beginning of agile

### Agile in Practice
There are all kinds of strategies, frameworks, and buzzwords around agile development. But everything revolves around *stories* and *sprints*.

#### The Sprint

A sprint is the time box that our work fits into.

* Typical sprint is 2 weeks
* Starts with planning (aka requirements)
* It always takes longer than planned
* Cut scope or extend time?
* Always cut scope (half, not half-assed)
* Features are delivered in production
* Solicit user feedback
* Ends with review/retrospective

Ways to structure a sprint:
* Scrum: 
  * [Video](https://www.scrumalliance.org/why-scrum)
  * [More Info](https://www.scrum.org/Resources/What-is-Scrum)

#### A Story

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

In this example, you've prototyped a small to-do list app. It just allows the user to create to-dos. And it only supports a single user.

As a group, draft one story for *each* of the following:

*   Checking the box for a to-do moves it to the completed list
*   The top of the todo list has a count of the number to todos which updates when I add a new one
*   Clicking trash on a to-do pops up a confirm/cancel dialog

3 different groups share out for each example.

### Where to Go From Here: Project Management Tools
* Start using a project management tool
* Turn your requirements into stories following the above template
* Prioritize stories and schedule sprints (even just 2-3 days)
* Deploy to production, maybe solicit feedback from "users"
* Cutting scope is ok, cutting quality isn't

Check out these resources:
* [Git Workflow for Teams](https://github.com/turingschool/career-development-curriculum/blob/master/module_one/git_workflow_for_teams.md)
* [GitHub Projects](https://help.github.com/en/articles/about-project-boards)
* [Trello](https://trello.com/)
* [Pivotal Tracker](https://www.pivotaltracker.com/)
* [JIRA](https://www.atlassian.com/software/jira)
* [Asana](https://asana.com/)

### How Teams Work Together
Now let's talk now about how teams work together.

#### Introduction
Doing agile vs. Being agile = what's the difference?

* Doing Agile = putting the tools into place
  * These are the *practices*
* Being Agile = building relationships & collaboration, communication, continuous learning
  * This is the team's *mindset*

#### Emotional Intelligence in Teams
Emotional Intelligence or EQ is the ability to:
 * Recognize, understand and manage our own emotions
 * Recognize, understand and influence the emotions of others

Developing EQ:
 * Gaining awareness that emotions drive our behavior and impact people
 * Learning to manage those emotions — both our own and others — especially when we are under pressure

#### Pairin: Leadership Domains
Let's consider how our strengths play a part in the types of roles we take on in our project groups. 

[Four Domains of Leadership](https://docs.google.com/document/d/1N449kYbcOhu22vbORfjUOfjFOIfPoka5w00q_fklipU/edit?usp=sharing):
  * **Executing:** Team members who have a dominant strength in Executing are those you turn to time and again to implement a solution. These people work tirelessly to get something done. People who are strong in the Executing domain have an ability to take an idea and transform it into a reality within the organization they lead
  * **Influencing:** People who are innately good at influencing are always selling the team’s ideas inside and outside the organization. When you need someone to take charge, speak up, and make sure your group is heard, look to someone with Influence.
  * **Relationship Building:** Relationship Builders are the glue that holds a team together. Strengths associated with bringing people together -- whether it is by keeping distractions at bay or keeping the collective energy high -- transform a group of individuals into a team capable of carrying out complex projects and goals.
  * **Strategic Thinking:** Those who are able to keep people focused on “what they could” be are constantly pulling a team and its members into the future. They continually absorb and analyze information and help the team make better decisions. 

Using the handout above, reflect on the following questions in your journal:

* How would you describe your Emotional Intelligence (EQ) competency?
* How does this make you an effective leader?
* What does this tell you about how you operate on teams?

#### Bringing These Styles Together: Tuckman's Group Life Cycle
Now that you understand these leadership styles look like, let's discuss how these styles can come together to work well. Psychologist Bruce Tuckman developed the "Tuckman's Group Life Cycle," which consists of 4 phases:

* Forming
* Storming
* Norming
* Performing
* Adjourning
* [Reference this handout](https://salvos.org.au/scribe/sites/2020/files/Resources/Transitions/HANDOUT_-_Tuckmans_Team_Development_Model.pdf)
* [Optional Video for more Information](https://www.youtube.com/watch?v=OhSI6oBQmQA&list=PLbu6naAjG_K93h0wjyn1b1EHQl1Q2pH_y)

**Whole Group Discussion:**
* Why are each of these phases important? How do each of these phases build on each other?
* How can a team move past the storming phase into the norming phase?
* How does this cycle relate to agile systems?

#### Project Team DTR
Begin your DTR by discussing:

* Leadership:
  * What kind of leader could each of you be in this group?
  * How will all of you come together to exemplify leadership in the group?
* Conflict: 
  * Where could it occur on our team?
  * How will you resolve conflict if it occurs?
* Gaps in our EQ?
  * What domains are not covered in your team? 
  * How does that affect your team’s performance?
* Tuckman’s: Forming, storming, norming, performing, adjourning
  * How can you move through Tuckman's stages as a team?
 
Continue your DTR:

* Reference the [DTR guidelines and memo questions here](https://github.com/turingschool/career-development-curriculum/blob/master/module_one/dtr_guidelines_memo.md)
* Then, look at the spec:
  * How will you break up the iterations of the project into user stories?
  * What project management tool will you use?
  * When are you soliciting feedback?
  * When will you retro?
    * We’ll have our first retro on Wednesday!
    
#### Share Takeaways
3 groups share:

* What are your team’s strengths?
* How do you plan to navigate Tuckman’s stages?
* How are you approaching agile in your team?

### Closing: Next Steps
* Be prepared to revisit Tuckman’s stages and complete a group retro on Wednesday
* Your deliverable:
  * Submit a reflection on using agile and participating in retro feedback in survey provided by 9am on Friday of Week 5
