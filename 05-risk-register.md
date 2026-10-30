# 5. Risk Register

**Scoring:** Probability (1 to 5) x Impact (1 to 5) = Score. 1-6 Low, 7-14 Medium, 15-25 High.
**Review cadence:** weekly inside stand-up; full review at each sprint planning.
**Owner:** Project Manager (risk owners are named per risk).

| ID | Risk | Category | P | I | Score | Response | Mitigation / contingency | Owner | Status |
|---|---|---|---|---|---|---|---|---|---|
| R1 | Difficulty reaching enough hearing-impaired students and teachers for research and testing | Stakeholder | 4 | 5 | 20 | Mitigate | Secure partner school or teacher in Sprint 1; book sessions early; recruit extra participants; fallback to teachers and special-education students' representatives | PM, BA | Open |
| R2 | Misunderstanding user needs because the team lacks sign-language fluency | Requirements | 3 | 5 | 15 | Mitigate | Use a qualified interpreter in interviews and tests; validate wireframes with users early; BA documents findings in writing | BA | Open |
| R3 | Poor quality or inaccurate captions and sign-language content | Quality | 3 | 4 | 12 | Mitigate | Interpreter review step; teacher approval before publishing; caption quality check in the Definition of Done | QA | Open |
| R4 | Scope creep from new feature ideas (live classes, AI sign recognition) | Scope | 4 | 4 | 16 | Avoid | Out-of-scope list in charter; all requests go through backlog; change control with supervisor | PM | Open |
| R5 | Video storage, streaming and bandwidth limits on free hosting | Technical | 3 | 4 | 12 | Mitigate | Compress video; use adaptive resolution; spike in Sprint 1; fallback to external video hosting | Lead Developer | Open |
| R6 | Team members unavailable due to exams or other commitments | Resource | 3 | 4 | 12 | Mitigate | Plan capacity with calendars; cross-train on key areas; pair on critical stories | PM | Open |
| R7 | Accessibility defects found late | Quality | 3 | 4 | 12 | Mitigate | Accessibility acceptance criteria on every story; audit in Sprint 2; automated checks in CI | QA | Open |
| R8 | UX hand-off delays block developers | Dependency | 3 | 3 | 9 | Mitigate | Designer works one sprint ahead; design reviews mid-sprint | UX, PM | Open |
| R9 | Communication gaps in a mixed-ability setting | Communication | 2 | 4 | 8 | Mitigate | Written-first communication standard; live captions; shared notes | PM | Open |
| R10 | Ethical and consent issues when testing with minors | Compliance | 2 | 5 | 10 | Avoid | Parental consent forms; supervisor ethics approval; anonymised data; no recording without consent | PM | Open |
| R11 | Security or privacy issue with student data | Technical | 2 | 5 | 10 | Mitigate | Role-based access, hashed passwords, minimal personal data, security review before release | Lead Developer | Open |
| R12 | Integration issues late in the project (video player, quiz, dashboard) | Technical | 3 | 3 | 9 | Mitigate | Continuous integration; integrate every sprint; demo working software at each review | Developers | Open |
| R13 | Estimation inaccuracy leading to missed sprint goals | Planning | 4 | 3 | 12 | Mitigate | Planning poker, buffer of about 10 to 15 percent, velocity-based planning from Sprint 2, scope flex plan | PM | Open |
| R14 | Key team member becomes unavailable | Resource | 2 | 4 | 8 | Mitigate | Knowledge sharing, documented setup, code reviews by at least two developers | PM | Open |

## Top 5 Risks Heat Map (by score)

| Rank | Risk | Score |
|---|---|---|
| 1 | R1 Access to users | 20 |
| 2 | R4 Scope creep | 16 |
| 3 | R2 Understanding user needs | 15 |
| 4 | R3 Content quality | 12 |
| 4 | R5 Video hosting | 12 |

## Risk-Driven Backlog Actions

| Risk | Backlog action |
|---|---|
| R1 | Recruitment and scheduling tasks in Sprint 1 (part of HM-001) |
| R2 | Interpreter booked for HM-001, HM-007, HM-021 |
| R5 | Technical spike on video storage inside HM-004 |
| R7 | Accessibility audit HM-013 in Sprint 2 |

## Issues and Decisions Log (template)

| ID | Date | Issue / decision | Raised by | Action | Owner | Due | Status |
|---|---|---|---|---|---|---|---|
| I1 | | | | | | | |
