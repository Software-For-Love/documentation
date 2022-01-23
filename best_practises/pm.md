---
title: Project Manager
parent: Best Practices
nav_order: 2
---

# Best Practices: Project Manager

Leading a team of developers and designers can be nerve-wracking, but it's a rewarding experience! As the person at the helm, you have to take on the most responsibility and that can cause a great deal of stress. This guide to project management should help relieve some of it!

## Agile Methodology

Here at SFL, we believe in the [Agile Manifesto](https://assets.uits.iu.edu/pdf/Agile-Manifesto.pdf). It defines 4 values and 12 principles that are essential for project management.

Here's a diagram that highlights Agile Development:

![Agile Development](https://content.altexsoft.com/media/2016/04/2-agile-wp-1024x484.png)

Agile development holds iterative design at its core. The idea is to prepare a backlog of software requirements a.k.a the **Product Backlog**. It represents the tasks that have yet to be _assigned_. It is encouraged to breakdown tasks as much as possible. For example, when implementing a contact us form, you can break it down into:

1. the title,
2. inputs,
3. styling,
4. form validation (checking emails/phone numbers),
5. form submission
6. testing.

New tasks can be added at any point of a project.

## Scrum Boards

Scrum boards are the best way to organize sprints. You can use tools like [Trello](www.trello.com), [Github](https://docs.github.com/en/github/managing-your-work-on-github/managing-project-boards/about-project-boards).

Github is strongly recommended for software projects with implementation. You can connect issues and pull requests to tasks and organization is a breeze.

Additionally, some teams are experimenting with [Jira](https://www.atlassian.com/software/jira) as well. Please notify the CTO if you would like to use Jira, as it may have costs associated with it.

## User Stories
The creation of a software solution is broken down into large bodies of work known as **epics**. These epics contain a collection of smaller requirements known as **user stories.** User stories are an explanation of a feature request that are written from the perspective of a stakeholder. The purpose of a user story is to convey how the specific feature intends to provide value to stakeholders. This is the approach that Software For Love uses to break down the work required to complete our projects.

The format of a user story would be: "As a \[stakeholder\], I want to \[...\], so that \[...\]."

Here, the **stakeholder** represents who we are building this feature for. For example, if you were to implement a feature on the Software For Love website, the stakeholder could be a new volunteer, or a new client. Following that, we would describe what they want to achieve. For example, a new volunteer would want to view the previous projects that Software For Love has worked on. Finally, we describe what the anticipated value is from what they want to do. If a new volunteer wants to view the previous projects Software For Love has worked on, it would be so that they could gain a better understanding of the work we do to help our community.

If you combine it all together, you will get this user story: **"As a new volunteer, I want to view the previous projects that Software For Love has worked on, so that I can gain a better understanding of the work they do to help our community."**

This statement easily conveys what the end functionality we would like to see is, as well as the benefit it will have. [Please view this resource for additional information regarding user stories.](https://www.atlassian.com/agile/project-management/user-stories)

However, this should be appended with **acceptance criteria** in order to better clarify the expectations of users. Acceptance criteria should also be written from the perspective of a stakeholder, and should be as specific as possible. Use the following template when writing acceptance criteria:

"Given \[context\], when \[action\], then \[result\]."

An example for the previously mentioned user story could be: "**Given** that I do not have any prior knowledge regarding Software For Love's previous endeavors, **when** I am visiting the projects page **then** I shall be presented with descriptions of all of the previous projects SFL has worked on."

More informaiton on writing acceptance criteria can be found [here.](https://zepel.io/agile/acceptance-criteria-for-user-stories/)

Additionally, it is also important to indicate the importance or priority of an issue when adding it to the product backlog. This will help your team be able to determine which issues they should pick up in sprint planning sessions (ie. More important stories should be completed as soon as possible, and less important stories can possibly be pushed to a later sprint.)

## Sprint Planning
**Sprints** are a time period determined by the team where select tasks from the product backlog are worked on and completed. Tackling a project in sprints helps reduce the "intimidation" factor. It's like saying you're going to bike across Canada. Anyone would be intimidated by that, but if you say you're going to bike 20 km a day, that becomes a lot easier.

At SFL, we recommend that sprints should be 2 weeks long. It is important to dedicate time to **Sprint planning** prior to starting a sprint, so that you and your team decide what tasks they can complete for the sprint. During Sprint Planning meetings, you should assign tasks to your team members, and also include an estimate regarding the time and difficulty that a task may take. 

It is crucial that you discuss the time required to complete a task, as that ensures that you and the assignee are on the same page regarding this task. It is important that you let your developers/designers determine what they feel they can complete during the sprint, rather than you telling them what they should do. This helps bring them confidence in what they do. This information must also be logged in the User Story. Tasks that will get completed within a sprint get assigned to a **Sprint Backlog**.

## Work log

As we transition to charging clients using billable hours, it is important that we keep track of the work being done by our developers and designers. **You should be strict with this and it is your responsibility that these hours get logged**.

You can use this sample [Google sheet](https://docs.google.com/spreadsheets/d/1FzZ8p6jcDI5qdJmZVgxLlgHIqx9nV8Jg39T9jLmOnEc/edit?usp=sharing) to track work hours, or better yet, make use of the Scrum boards to track hours.

## Stand-Up Meetings

Communication is very crucial during sprints. This is an especially hard task to accomplish in a remote working environment, with teams of volunteers that may be very busy. Therefore, it is strongly recommended to have **in-chat standup meetings** about 2x a week. These stand-up meetings should be used to discuss progress on tasks, what your team members are planning to work on, and any challenges that have popped up. To accomplish, you could use Slackbot to send a message like the following:

"Hey team! :wave:

This is a reminder to post your stand-up in the  channel!  

Please include:
-What you worked on since the last stand-up (last Wednesday) 
-What you plan to work on until the next stand-up (next Wednesday) 
-Any challenges you are facing!"

## Sprint Review
Once a sprint has completed, a Sprint Review is designed to inspect the outcome of the past sprint. Here, it is important that you review the progress that your team has made. Some interesting points to look at may be the amount of time spent working, the number of issues closed, or the time it required to close a pull request. These metrics could showcase success or uncover some issues. Furthermore, use this time to analyze what has been completed, what has not been completed, and the impact that this may have on your project timeline. It is crucial that you flag any important issues that you uncover at this point, and address them with the CTO.

## Sprint Retrospective

As a project manager, it is extremely important to receive feedback from your team members whenever possible. As such, we strongly recommend that you conduct **Sprint Retrospectives.** These are team exercises to reflect on how the last sprint went. It could be with regards to anything that concerned them, from interactions, to tools, to processes that you have implemented. Software For Love members have used [this tool](https://metroretro.io/) in the past to conduct retrospectives, and we strongly encourage the usage of it.

To conduct a retrospective, set up a board with 4 sections: What was good, what was bad, what your team should start doing, and what your team should stop doing. Set a timer for 4 minutes per section, to encourage your team to think about the section and try to come up with as many points as they can. It is perfectly fine if some points are mentioned repeatedly! That showcases that more than one team member is on the same page regarding it.

Once your 16 minutes are up, review the board with your team. Encourage teammates to talk and elaborate about the points that they've written, and take notes regarding their feedback. It is extremely crucial for you to be receptive to feedback and be open to making change, as this will increase morale within your team.

Please mention all findings from your Sprint Retrospective in the tech team meeting, so that other project managers and SFL execs can also learn about your findings!

## Client Meetings
As the project manager, it will be very important for you to lead client meetings with the client representative on a regular basis. During the initial stages of your project, you will use this time to elicit project requirements from the client representative, which you then formulate into Epics and User Stories. You should also use these meetings to validate prototypes, as well as to showcase the progress you have made with respect to implementation.

Client feedback is especially crucial for your project. The software solution that your team generates might seem like a good solution to you and your team, but it would ultimately be pointless unless it fulfills the client's wishes. Therefore, you must ensure that feedback from the client is elicited on a regular basis, and that their feedback is implemented within the solution.

Clients may sometimes present you with large or unusual requests for your project. It is important for you to use your discretion, and advise the client whether you think their ideas are feasible or practical. If you are not sure, or need time to think about it, then you should inform the client as such, and discuss with the team or the CTO. **Do not make blind promises!** You will disappoint the client if you cannot deliver at a later point.

## Tech Team Meetings
Software For Love has bi-weekly team meetings, where team's project manager discuss the work that their team has accomplished, their action items for the next 2 weeks, as well as any challenges that they're facing. Every team's project manager will be expected to include a slide in the presentation deck outlining the points they will be discussing. Please contact the CTO if you have any questions about these meetings.

## Incident Management
In rare occasions, we have had issues with team members who have not met our required expectations at Software For Love. If you feel that the conduct of a team member violates Software For Love's [Code of Conduct](https://software-for-love.github.io/documentation/code-of-conduct/sfl_code_of_conduct.html), or does not meet the standards outlined in [SFL Volunteer Responsibilities](https://software-for-love.github.io/documentation/code-of-conduct/SFL_Volunteer_Responsibilities.html), then **please notify the CTO immediately.**

## Conclusion
If you have any further questions, feel free to message the CTO (Dharitri Dixit) or CEO (Soorya Saravanapavan) and we would be happy to answer any questions that you may have!