# Benjrm-Documentation

## User centered design documentation

### Product Vision
We aim to develop a GDPR-compliant quiz platform for schools, universities, and other educational institutions that
combines data sovereignty with modern digital learning. As a self-hosted alternative to conventional cloud-based
solutions, our platform enables educators to easily create, manage, and analyze quizzes and learning activities while
maintaining full control over their data.

For learners, the platform provides an engaging and interactive learning experience through gamification elements,
increasing motivation and supporting long-term learning success. By focusing on security, privacy, and ease of use, our
solution offers a reliable and user-friendly environment for digital education.

### User Research
#### Target Audience
For a detailed target audience analysis, see the supporting document:
[Target Audience Analysis - Google Docs](https://docs.google.com/document/d/1iM4d8lcry5CjvrjBjCj3R3suOkrYikzaBQUz1QgHUF8/edit?tab=t.hrlw56sjmmy)

#### Personas
To better understand the needs, motivations, and pain points of our target users, we developed three representative personas reflecting the key user groups of the platform:
students, digitally experienced teachers, and less technically confident teachers.
For a detailed visual representation of the personas, refer to the supporting document:
[Personas - PowerPoint](https://mnithmde-my.sharepoint.com/:p:/g/personal/noel_hoppe_mni_thm_de/IQB63Zu6y18eQLmnmgqJevkKAQIMhytJQI-UkuQJQ91kALo?e=GieEHD)

### Competitive Analysis
To better understand the current market landscape for digital quiz and e-learning platforms, we analyzed several established competitors in the field of
gamified learning and online assessment tools. The selected competitors include Kahoot!, QuizAcademy, TriviaMaker and Particify.
To get a further understanding of the competitive landscape, we created criteria for comparison and evaluated each competitor based on these criteria.
The results of this analysis are summarized in the following Miro board:
[Miro Board Link](https://miro.com/welcomeonboard/Ymhrb2IvdjdHUXNEcXhmZ1J0OGNqVk1IS2d4eXFwaXN4ODIrMStVOHYyZ0huZzREQ2FiVTcxOHFQQ0J4RzlvUDhZM01iUmJ6MjhmNjF2RHcrUk9qcmlEY0dBKzUxWk1kNWQrMzIxS0RPWnJOVGNGQ2tmNDhiSXBGcDBKcDVmRnhnbHpza3F6REdEcmNpNEFOMmJXWXBBPT0hdjE=?share_link_id=192512292421)

### Requirements Engineering and User Story Mapping
Based on the above research and analysis, we have defined a set of user stories and requirements, which are documented and prioritized in the following Miro board:
[Miro Board Link](https://miro.com/welcomeonboard/Ymhrb2IvdjdHUXNEcXhmZ1J0OGNqVk1IS2d4eXFwaXN4ODIrMStVOHYyZ0huZzREQ2FiVTcxOHFQQ0J4RzlvUDhZM01iUmJ6MjhmNjF2RHcrUk9qcmlEY0dBKzUxWk1kNWQrMzIxS0RPWnJOVGNGQ2tmNDhiSXBGcDBKcDVmRnhnbHpza3F6REdEcmNpNEFOMmJXWXBBPT0hdjE=?share_link_id=192512292421)

### Visual Design
We are using Figma to design the visual component of the platform.
This includes creating a mood board, user flows, mockups and prototypes.
Figma serves as our central tool for collaboratively defining the user interface and overall user experience of the applicaation.
The complete design wotk can be accessed here: [Figma Design Link](https://www.figma.com/design/C9VVUgbENsonybgmeKInTY/User-Interface?node-id=0-1&m=dev)

### Agile Development with Scrum

#### Definition of Ready (DoR)
The Definition of Ready (DoR) ensures that a user story is sufficiently prepared before moving from product backlog to sprint backlog.
[DoR Document - Google Docs](https://docs.google.com/document/d/1iM4d8lcry5CjvrjBjCj3R3suOkrYikzaBQUz1QgHUF8/edit?tab=t.8a39jk9ykjze)

#### Definition of Done (DoD)
The Definition of Done (DoD) ensures that a user story is considered complete and meets the agreed-upon criteria before it can be marked as done.
[DoD Document - Google Docs](https://docs.google.com/document/d/1iM4d8lcry5CjvrjBjCj3R3suOkrYikzaBQUz1QgHUF8/edit?tab=t.c15s8ljnwhhb)

#### Sprint Planning and Backlog Management
The detailed sprint planning and backlog management process is managed in YouTrack.
> The YouTrack project is accessible only in THM network. Please use a VPN connection to access it from outside the THM network.

[YouTrack Project Overview](https://youtrack.mni.thm.de/projects/SERSOSE26G1)

[YouTrack Agile Development Board](https://youtrack.mni.thm.de/projects/SERSOSE26G1/agiles/122-557/current)

[YouTrack Project Managemmet Board](https://youtrack.mni.thm.de/projects/SERSOSE26G1/agiles/122-558/current)


## Team Organization, Culture & Learnings

This section documents how our team was organized over the course of the project, which tools we used, and the lessons learned we're taking away from the project. This is meant to make our workflow and how it evolved over the sprints understandable.

### Team Organization

| Role                 | Responsible                  |
|----------------------|------------------------------|
| Product Owner        | Everyone                     |
| Scrum Master         | Mike                         |
| Ticket Reviewer      | Erik, Noel                   |
| Frontend Development | Everyone (mainly Mike, Erik) |
| Backend Development  | Mainly Julian, Bela          |
| CI/CD                | Mainly Noel, Robin           |

In practice, everyone pitched in across different areas, but the rough division of work shaped up as described above: Noel and Robin mainly handled CI/CD, Julian and Bela the backend, and Mike and Erik the frontend, though everyone else also contributed regularly here as well.

### Meeting Cadence

In the beginning, we only met once a week. After the second sprint, it became clear that this didn't work for two-week deadlines, too much time passed between syncs, so problems only surfaced late. We then switched to meeting every 2–3 days, which worked considerably better.

### Learnings

- **One sprint meeting per week is not enough for two-week deadlines.** A cadence of at least every two days works much better, since problems get caught and fixed earlier.
- **Shorter meeting intervals encourage productivity.** Instead of one big weekly goal, you constantly have smaller, clearly achievable goals in front of you, which makes motivation and progress more tangible.
- **Feature-based branching is organizationally much better than technology-based branching.** At the start, we had two separate branches off main, one for frontend, one for backend. This made it hard to integrate changes from both sides with each other. A dedicated branch per feature, only merged into main once frontend and backend are integrated, turned out to be far more practical.
- **Putting real effort into mockups saves time in code reviews.** When you put real care into the mockup, design is barely a discussion point in the review afterward.
- **Estimating time for tasks is hard.** The estimated time for tickets often didn't match the actual effort required in practice, something we kept having to recalibrate across sprints.