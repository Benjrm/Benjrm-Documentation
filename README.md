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
Figma serves as our central tool for collaboratively defining the user interface and overall user experience of the application.
The complete design work can be accessed here: [Figma Design Link](https://www.figma.com/design/C9VVUgbENsonybgmeKInTY/User-Interface?node-id=0-1&m=dev)

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

[YouTrack Project Management Board](https://youtrack.mni.thm.de/projects/SERSOSE26G1/agiles/122-558/current)


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

### Sprint Tables

#### Sprint 1 – Status as of 21.05.2026

Sprint 1 was largely focused on setting up the foundations of our development environment — including GitHub workflows, CI/CD pipelines, and other developer tooling that, while not directly visible to the end user, are essential for sustainable and efficient development going forward. This groundwork took a significant portion of the sprint's capacity.

At the same time, the team was still settling in: estimating task effort and coordinating our workflows was a learning process, which meant that some items took longer than planned. We also identified areas for improvement in our branching strategy, which lacked clear conventions early on. Both of these aspects were addressed and refined as we moved into further Sprints.

In terms of deliverables, the team completed the full user management flow — including registration, login, password reset, and email verification via Keycloak — as well as the basic application structure with a working backend, landing page, and database integration. The continuous integration pipeline was fully set up, and the Git workflow including branching conventions and PR standards was established. Quiz management was very close to completion, with all API endpoints, UI pages, and backend tests finished; only the API tests remained in progress at the end of the sprint.

| Ticket              | Zusammenfassung                                                       | Typ            | Status 07.05.2026 |
| ------------------- | --------------------------------------------------------------------- | -------------- | ----------------- |
| SERSOSE26G1-132     | CI/CD                                                                 | Epic           | Offen             |
| ↳ SERSOSE26G1-99    | Continous Integration                                                 | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-108 | Notify                                                                | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-103 | Filesystem Scan                                                       | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-102 | Static-Application-Security Scan                                      | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-101 | Linting Backendcode                                                   | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-104 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-100 | Linting Frontendcode                                                  | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-126   | Continous Delivery / Deployment                                       | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-134 | Anwendung deployen                                                    | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-135 | Container pushen                                                      | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-133 | Container bauen                                                       | Aufgabe        | Offen             |
| SERSOSE26G1-21      | Quizverwaltung                                                        | Epic           | Offen             |
| ↳ SERSOSE26G1-30    | Quizliste einsehen                                                    | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-156 | Integrationstests Backend                                             | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-167 | API Tests                                                             | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-147 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-56  | UI - Seite erstellen                                                  | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-57  | API endpoint                                                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-59    | Quiz bearbeiten                                                       | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-159 | Integrationstests Backend                                             | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-76  | UI anpassen                                                           | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-168 | API Tests                                                             | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-139 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-60  | API endpoint                                                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-23    | Quiz einsehen                                                         | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-91  | UI erstellen                                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-157 | Integrationstests Backend                                             | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-87  | API endpoint                                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-164 | API Tests                                                             | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-144 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-22    | Quiz erstellen                                                        | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-172 | Add error handling                                                    | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-160 | Integrationstests Backend                                             | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-140 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-46  | Ui anpassen                                                           | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-151 | Repository Layer inklusive Datenbankschema                            | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-166 | API Tests                                                             | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-44  | API endpoint                                                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-25    | Quiz löschen                                                          | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-155 | Integrationstests Backend                                             | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-141 | Unittests Backend                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-54  | API endpoint                                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-55  | UI anpassen                                                           | Aufgabe        | Zu verifizieren.  |
|   ↳ SERSOSE26G1-163 | API Tests                                                             | Aufgabe        | In Bearbeitung    |
| SERSOSE26G1-26      | Fragenverwaltung                                                      | Epic           | Offen             |
| ↳ SERSOSE26G1-28    | Fragen löschen                                                        | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-161 | Integrationstests Backend                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-169 | API Tests                                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-145 | Unittests Backend                                                     | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-62  | API endpoint                                                          | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-88  | UI Fragen löschen                                                     | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-29    | Frage bearbeiten                                                      | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-162 | Integrationstests Backend                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-170 | API Tests                                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-90  | UI anpassen                                                           | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-143 | Unittests Backend                                                     | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-148 | API endpoint                                                          | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-27    | Fragen anlegen                                                        | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-158 | Integrationstests Backend                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-150 | Repository Layer inklusive Datenbankschema                            | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-165 | API Tests                                                             | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-146 | Unittests Backend                                                     | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-47  | API endpoint                                                          | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-89  | UI Fragen Erstellen                                                   | Aufgabe        | Offen             |
| SERSOSE26G1-31      | Legal                                                                 | Epic           | Offen             |
| ↳ SERSOSE26G1-32    | Impressum                                                             | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-68  | Impressum Downloadbar machen                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-66  | Impressum an Frontend ausliefern                                      | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-65  | Impressum Dokument schreiben                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-67  | Impressum im Frontend Rendern                                         | Aufgabe        | Erledigt          |
| SERSOSE26G1-5       | Benutzerverwaltung                                                    | Epic           | Offen             |
| ↳ SERSOSE26G1-6     | Registrierung                                                         | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-15  | Compose für Keycloak erstellen                                        | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-18  | Keycloak einrichten                                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-38    | Passwort zurücksetzen                                                 | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-131 | Konfiguration in Realm von Keycloack setzen                           | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-7     | Anmeldung                                                             | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-16  | Keycloak als identity provider einbinden                              | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-17  | Startseite mit Referenz zu Keycloak                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-37    | Accountverifizierung via E-Mail-Addresse                              | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-129 | Mailserver in Keycloak einbinden                                      | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-130 | Konfiguration in Realm setzen                                         | Aufgabe        | Erledigt          |
| SERSOSE26G1-94      | Basics                                                                | Epic           | Erledigt          |
| ↳ SERSOSE26G1-95    | Website                                                               | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-78  | Backend Grundgerüst erstellen                                         | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-83  | Schema Ordnerstrucktur Festlegen                                      | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-82  | Landing Page erstellen                                                | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-93    | Daten persistieren                                                    | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-77  | Compose für Datenbank anlegen                                         | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-80  | Datenbank in Backend einbinden                                        | Aufgabe        | Erledigt          |
| SERSOSE26G1-96      | Management                                                            | Epic           | Offen             |
| ↳ SERSOSE26G1-138   | Sprint Retrospektive                                                  | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-137   | Sprint Review                                                         | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-152   | (Daily) Scrum                                                         | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-97    | Sprint Planning                                                       | Aufgabe        | Offen             |
| SERSOSE26G1-98      | Engineering Productivity                                              | Epic           | Offen             |
| ↳ SERSOSE26G1-120   | YouTrack - GitHub Integration                                         | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-171 | YouTrack integration konfigurieren                                    | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-109   | Containerize                                                          | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-127 | Debug-Compose erstellen                                               | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-112 | Debug-Container für Frontend                                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-111 | Debug-Container für Backend                                           | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-118 | Release compose                                                       | Aufgabe        | In Bearbeitung    |
| ↳ SERSOSE26G1-121   | Git Workflow & PR Standards                                           | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-125 | Branch protection                                                     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-123 | Pull Request Template definieren                                      | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-122 | Branching Strategie inkl. Naming Convention definieren und einrichten | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-124 | GitHub Organisation und Repository erstellen                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-154   | API Dokumentation                                                     | Aufgabe        | Zu verifizieren.  |
| SERSOSE26G1-128     | YouTrack                                                              | Aufgabe        | Offen             |

##### Sprint 2 – Status as of 02.06.2026

The primary goal of Sprint 2 was to complete the quiz management and question management features. While significant progress was made — particularly in question management, where creating, viewing, editing, and deleting questions were largely implemented at the backend level — neither epic reached full completion by the end of the sprint. Additionally, the team began work on the "Quiz Spielen" feature, including initial UI and API work for the game lobby and question flow.

The team continued to face challenges carried over from Sprint 1. The branching strategy still caused friction and had not yet been fully resolved, leading to integration issues during the sprint. Furthermore, the team did not meet frequently enough, which made it harder to catch blockers early and coordinate effectively across workstreams. Both points were taken as clear action items going into Sprint 3.

| Ticket              | Zusammenfassung                            | Typ            | Status 02.06.2026 |
| ------------------- | ------------------------------------------ | -------------- | ----------------- |
| SERSOSE26G1-132     | CI/CD                                      | Epic           | Offen             |
| ↳ SERSOSE26G1-126   | Continous Delivery / Deployment            | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-135 | Container pushen                           | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-133 | Container bauen                            | Aufgabe        | Offen             |
| SERSOSE26G1-175     | Quiz Spielen                               | Epic           | Offen             |
| ↳ SERSOSE26G1-176   | Quiz lobby starten                         | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-185 | API Endpoint                               | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-196 | UI anpassen                                | Aufgabe        | In Bearbeitung    |
| ↳ SERSOSE26G1-177   | Quiz lobby beitreten                       | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-186 | API Endpoint                               | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-195 | UI                                         | Aufgabe        | In Bearbeitung    |
| ↳ SERSOSE26G1-179   | Fragen beantworten                         | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-188 | API Endpoint                               | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-194 | UI erstellen                               | Aufgabe        | In Bearbeitung    |
| ↳ SERSOSE26G1-205   | Leaderboard                                | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-206 | API                                        | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-207 | UI                                         | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-182   | Avatar (bzw. Emoji) für Spieler            | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-190 | API Endpoint                               | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-198 | UI anpassen                                | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-178   | Quiz starten                               | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-187 | API Endpoint                               | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-197 | UI anpassen                                | Aufgabe        | Zu verifizieren.  |
| ↳ SERSOSE26G1-181   | Spieler Name generieren                    | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-189 | API Endpoint                               | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-193 | UI erstellen                               | Aufgabe        | Zu verifizieren.  |
| SERSOSE26G1-21      | Quizverwaltung                             | Epic           | Offen             |
| SERSOSE26G1-226     | Zielgruppen Analyse                        | Epic           | Offen             |
| SERSOSE26G1-227     | Mockups                                    | Epic           | Offen             |
| SERSOSE26G1-26      | Fragenverwaltung                           | Epic           | Offen             |
| ↳ SERSOSE26G1-209   | Fragen einsehen                            | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-214 | Integrationstests Backend                  | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-213 | API Tests                                  | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-212 | UI                                         | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-210 | API endpoint                               | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-211 | Unittests Backend                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-28    | Fragen löschen                             | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-161 | Integrationstests Backend                  | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-169 | API Tests                                  | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-145 | Unittests Backend                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-62  | API endpoint                               | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-88  | UI Fragen löschen                          | Aufgabe        | In Bearbeitung    |
| ↳ SERSOSE26G1-149   | Infoslide unterstützen                     | Benutzer-Story | Offen             |
| ↳ SERSOSE26G1-52    | Numerische Schätzfragen unterstützen       | Benutzer-Story | Offen             |
| ↳ SERSOSE26G1-29    | Frage bearbeiten                           | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-162 | Integrationstests Backend                  | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-170 | API Tests                                  | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-90  | UI anpassen                                | Aufgabe        | In Bearbeitung    |
|   ↳ SERSOSE26G1-143 | Unittests Backend                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-204 | Markdown Parser                            | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-148 | API endpoint                               | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-51    | Multiple-Choice-Fragen unterstützen        | Benutzer-Story | Offen             |
| ↳ SERSOSE26G1-27    | Fragen anlegen                             | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-158 | Integrationstests Backend                  | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-150 | Repository Layer inklusive Datenbankschema | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-165 | API Tests                                  | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-146 | Unittests Backend                          | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-47  | API endpoint                               | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-89  | UI Fragen Erstellen                        | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-50    | Single-Choice-Fragen unterstützen          | Benutzer-Story | Offen             |
| ↳ SERSOSE26G1-53    | Reihenfolge fragen unterstützen            | Benutzer-Story | Offen             |
| SERSOSE26G1-96      | Management                                 | Epic           | Offen             |
| ↳ SERSOSE26G1-202   | Sprint Retrospective - Sprint 2            | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-203   | Sprint Review - Sprint 2                   | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-200   | YouTrack - Sprint 2                        | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-201   | (Daily) Scrum - Sprint 2                   | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-199   | Sprint Planning - Sprint 3                 | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-97    | Sprint Planning                            | Aufgabe        | Offen             |
| SERSOSE26G1-109     | Containerize                               | Benutzer-Story | Erledigt          |
| ↳ SERSOSE26G1-111   | Debug-Container für Backend                | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-118   | Release compose                            | Aufgabe        | Erledigt          |
| SERSOSE26G1-128     | YouTrack                                   | Aufgabe        | Offen             |
| SERSOSE26G1-174     | Backend Healtcheck                         | Benutzer-Story | Erledigt          |
| ↳ SERSOSE26G1-192   | Dockerfile anpassen                        | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-191   | API Endpoint                               | Aufgabe        | Erledigt          |

#### Sprint 3 – Status as of 18.06.2026

Sprint 3 marked a noticeable improvement in team dynamics. The branching strategy was refined and consistently applied, reducing integration friction that had been a recurring issue in the previous sprints. The team also made a conscious effort to meet more regularly, which proved to have a significant positive impact: blockers were identified earlier, communication improved, and the overall pace of the sprint felt more coordinated and predictable.

In terms of deliverables, both sprint goals were met. The core "Quiz Spielen" feature was successfully implemented — players can now start and join a lobby, answer questions, and view the leaderboard. On the question management side, the remaining bugs and open API tests from Sprint 2 were resolved, bringing the full create, view, edit, and delete workflow to completion. Additionally, the privacy policy was fully implemented and the quiz management API tests were wrapped up, closing out several long-standing open items.

| Ticket              | Zusammenfassung                             | Typ            | Status 18.06.2026 |
| ------------------- | ------------------------------------------- | -------------- | ----------------- |
| SERSOSE26G1-132     | CI/CD                                       | Epic           | Offen             |
| ↳ SERSOSE26G1-126   | Continous Delivery / Deployment             | Benutzer-Story | In Bearbeitung    |
|   ↳ SERSOSE26G1-135 | Container pushen                            | Aufgabe        | Zu verifizieren.  |
|   ↳ SERSOSE26G1-133 | Container bauen                             | Aufgabe        | Zu verifizieren.  |
| SERSOSE26G1-175     | Quiz Spielen                                | Epic           | Offen             |
| ↳ SERSOSE26G1-176   | Quiz lobby starten                          | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-185 | API Endpoint                                | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-196 | UI anpassen                                 | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-177   | Quiz lobby beitreten                        | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-186 | API Endpoint                                | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-195 | UI                                          | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-179   | Fragen beantworten                          | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-188 | API Endpoint                                | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-194 | UI erstellen                                | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-205   | Leaderboard                                 | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-206 | API                                         | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-182   | Avatar (bzw. Emoji) für Spieler             | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-238 | UI                                          | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-178   | Quiz starten                                | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-187 | API Endpoint                                | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-197 | UI anpassen                                 | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-181   | Spieler Name generieren                     | Benutzer-Story | In Bearbeitung    |
|   ↳ SERSOSE26G1-189 | API Endpoint                                | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-193 | UI erstellen                                | Aufgabe        | Zu verifizieren.  |
| SERSOSE26G1-21      | Quizverwaltung                              | Epic           | Offen             |
| ↳ SERSOSE26G1-30    | Quizliste einsehen                          | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-167 | API Tests                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-59    | Quiz bearbeiten                             | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-168 | API Tests                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-183   | Quiz importieren und exportieren            | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-231 | UI                                          | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-232 | Api Endpunkt                                | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-22    | Quiz erstellen                              | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-166 | API Tests                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-25    | Quiz löschen                                | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-163 | API Tests                                   | Aufgabe        | Erledigt          |
| SERSOSE26G1-26      | Fragenverwaltung                            | Epic           | Offen             |
| ↳ SERSOSE26G1-209   | Fragen einsehen                             | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-213 | API Tests                                   | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-28    | Fragen löschen                              | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-169 | API Tests                                   | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-88  | UI Fragen löschen                           | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-52    | Numerische Schätzfragen unterstützen        | Benutzer-Story | Offen             |
|   ↳ SERSOSE26G1-233 | UI                                          | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-234 | Api Endpunkt                                | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-29    | Frage bearbeiten                            | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-170 | API Tests                                   | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-90  | UI anpassen                                 | Aufgabe        | Erledigt          |
| ↳ SERSOSE26G1-27    | Fragen anlegen                              | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-165 | API Tests                                   | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-89  | UI Fragen Erstellen                         | Aufgabe        | Erledigt          |
| SERSOSE26G1-31      | Legal                                       | Epic           | Erledigt          |
| ↳ SERSOSE26G1-69    | Datenschutzerklärung                        | Benutzer-Story | Erledigt          |
|   ↳ SERSOSE26G1-71  | Datenschutzerklärung Downloadbar machen     | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-72  | Datenschutzerklärung an Frontend ausliefern | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-73  | Datenschutzerklärung im Frontend Rendern    | Aufgabe        | Erledigt          |
|   ↳ SERSOSE26G1-70  | Datenschutzerklärung Dokument schreiben     | Aufgabe        | Erledigt          |
| SERSOSE26G1-5       | Benutzerverwaltung                          | Epic           | Offen             |
| ↳ SERSOSE26G1-40    | Konto bearbeiten                            | Benutzer-Story | In Bearbeitung    |
|   ↳ SERSOSE26G1-236 | Api Endpunkt                                | Aufgabe        | Offen             |
|   ↳ SERSOSE26G1-235 | UI                                          | Aufgabe        | In Bearbeitung    |
| SERSOSE26G1-96      | Management                                  | Epic           | Offen             |
| ↳ SERSOSE26G1-199   | Sprint Planning - Sprint 3                  | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-224   | YouTrack - Sprint 3                         | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-222   | Sprint Review - Sprint 3                    | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-221   | Sprint Retrospective - Sprint 3             | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-219   | Sprint Planning - Sprint 4                  | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-200   | YouTrack - Sprint 2                         | Aufgabe        | Offen             |
| ↳ SERSOSE26G1-223   | (Daily) Scrum - Sprint 3                    | Aufgabe        | Offen             |
| SERSOSE26G1-173     | Übersetzungen                               | Benutzer-Story | In Bearbeitung    |
| ↳ SERSOSE26G1-237   | i18n Übersetzungen                          | Aufgabe        | In Bearbeitung    |
