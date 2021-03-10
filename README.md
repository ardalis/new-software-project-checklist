[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![HitCount](http://hits.dwyl.io/ardalis/new-software-project-checklist.svg)](http://hits.dwyl.io/ardalis/new-software-project-checklist)
[![Sparkline](https://stars.medv.io/ardalis/new-software-project-checklist.svg)](https://stars.medv.io/ardalis/new-software-project-checklist)

# Ultimate New Software Project Decision Checklist

When starting a new software project, there are many decisions that need to be made. Every decision can be phrased as a question. The following checklist outlines the questions that should be asked, and answered, as early in the life of a new software project as possible.

## Give a Star! :star:

If you like this list or found it helpful, please give it a star. Thanks!

And now, the list!

## Who

- Who is on the team (and what are their roles)?
- Who is ultimately responsible for the project (management owner)?
- Who is the project being built to support? Who will its users be?
- Who does the team coordinate with downstream (for QA, deployments, support, etc. if any)?
- Who does the team coordinate with upstream (for requirements, direction, prioritization, etc.)?

## Communication

- How will/does the team communicate?
  - Is there an email alias for the team?
  - Is there a list of team members and their contact information available?
  - Is there a real-time chat tool configured (Teams, Slack, Discord, etc.)?
- Does the team have any regular standing meetings?
  - Daily standup or sync meeting?
  - Periodic demo to customer/management?
  - Iteration/sprint-related meetings?

## What

- What is the ultimate goal of the app? What problem does it solve?
- What kind of app is the team building? What hardware will it run on (web, mobile, desktop, etc.)?
- What kind of methodology will the team use to collaborate (Kanban, Scrum, XP, etc.)?
- What framework(s) will the app be built with/on?
- What architectural pattern(s) will the app leverage?
- What programming language(s) will the app be written in?
- What code formatting standards has the team adopted?
- What persistence store(s) will the app use?
- What kinds of tests will the app require?
  - Unit tests
  - Integration tests
  - Functional tests
  - UI tests
  - Load tests
- What will the initial source control structure look like?
  - Where does code go?
  - Where do tests go?
  - Where do docs go?
  - Where do build scripts go?
- What is the branching strategy used?
  - What is the main branch called?
  - What is the dev branch (if any) called?
  - Are there other long-lived branches (per release, per feature, etc)?
- What process is envisioned for accepting commits?
  - Pull requests?
  - Approvals required?
  - Automated build/test pass required?
  - What team members have admin access?
- What build/deploy automation tools does the app use?

## Where

- Where is the team located, physically?
- If remote, what remote collaboration tools will be used?
- Where will the project's artifacts (code, work items, builds, etc) be located?

## When

- When is the project due?
- When is the first milestone due?
- When is the first proof-of-concept demo planned for?

## Why

- Why is the company building this app?
  - Why is the company building **this** app?
  - Why is the company **building** this app?
  - Why is **the company** building this app?
- Why were the decisions made on this last chosen vs. their alternatives?
  - Consider recording [Architecture Decision Records](https://ardalis.com/getting-started-with-architecture-decision-records/)

## How

- How do different parts of the app communicate with one another?
  - In process library method calls
  - Out of process API calls
  - Out of process async messages
- How does the system communicate with its persistence store?
  - Direct SQL calls
  - OR/M
- How does the system communicate with other dependencies?
  - HTTP client
  - FTP
  - Shared database
  - Carrier pigeon
- How will the app handle cross-cutting concerns?
  - Logging
  - Security/Auth
  - Auditing
  - Monitoring and Health Checks

