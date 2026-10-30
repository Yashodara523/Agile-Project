# 3. Product Backlog

**Product Owner proxy:** Business Analyst  **Backlog manager:** Project Manager (with BA)
**Estimation:** Story points (Fibonacci), planning poker with the full team
**Prioritisation:** MoSCoW
**Status values:** To Do, In Progress, In Review, Testing, Done

## 3.1 Epics

| ID | Epic | Goal |
|---|---|---|
| E1 | Research and accessible design foundation | Understand users and set an accessible design baseline |
| E2 | Accounts and roles | Secure sign-in for students, teachers and admins |
| E3 | Visual-first lesson delivery | Lessons that need no audio: captions, sign-language video, illustrated text |
| E4 | Assessments and visual feedback | Quizzes with clear non-audio feedback |
| E5 | Progress and teacher insight | Students and teachers can see learning progress |
| E6 | Communication | Text-based questions and answers |
| E7 | Validation and release | Usability testing, quality, deployment, documentation |

## 3.2 Product Backlog

| ID | Epic | User story | Priority | Points | Sprint |
|---|---|---|---|---|---|
| HM-001 | E1 | As a BA, I want to interview students and teachers so that requirements reflect real needs | Must | 5 | 1 |
| HM-002 | E1 | As a team, we want personas and accessibility requirements so that design decisions are evidence-based | Must | 3 | 1 |
| HM-003 | E1 | As a student, I want a high-contrast, consistent interface so that I can read and navigate easily | Must | 5 | 1 |
| HM-004 | E1 | As a developer, I want the architecture, repository and CI pipeline set up so that the team can ship safely | Must | 5 | 1 |
| HM-005 | E2 | As a user, I want to register and log in so that my learning is saved | Must | 5 | 1 |
| HM-006 | E2 | As an admin, I want role-based access (Student, Teacher, Admin) so that each user sees the right features | Must | 3 | 1 |
| HM-007 | E1 | As a student, I want wireframes of lesson screens validated early so that we avoid rework | Must | 5 | 1 |
| HM-008 | E3 | As a student, I want to browse a lesson catalogue by subject so that I can find what to learn | Must | 5 | 2 |
| HM-009 | E3 | As a student, I want lesson videos with accurate captions so that I can follow without audio | Must | 8 | 2 |
| HM-010 | E3 | As a student, I want a sign-language video next to the lesson so that I can learn in my first language | Must | 8 | 2 |
| HM-011 | E3 | As a student, I want illustrated step-by-step text lessons so that I can learn visually at my own pace | Should | 5 | 2 |
| HM-012 | E3 | As a teacher, I want to upload and organise lessons with captions and sign-language video so that I can publish content easily | Must | 8 | 2 |
| HM-013 | E7 | As a QA engineer, I want a first accessibility audit so that issues are found early | Must | 3 | 2 |
| HM-014 | E4 | As a teacher, I want to create quizzes so that I can check understanding | Must | 8 | 3 |
| HM-015 | E4 | As a student, I want visual feedback (colour, icons, animation) after each answer so that I know how I did without sound | Must | 3 | 3 |
| HM-016 | E5 | As a student, I want to see my progress so that I stay motivated | Should | 5 | 3 |
| HM-017 | E5 | As a teacher, I want a dashboard of student progress and quiz results so that I can support learners | Should | 8 | 3 |
| HM-018 | E6 | As a student, I want to ask questions in text and receive answers so that I can get help | Should | 8 | 3 |
| HM-019 | E6 | As a user, I want visual notifications (badges, banners, vibration-free) instead of sound alerts so that I never miss updates | Should | 3 | 3 |
| HM-020 | E7 | As a QA engineer, I want an automated regression suite so that new changes do not break old features | Must | 5 | 3 |
| HM-021 | E7 | As a UX designer, I want to run usability tests with students and teachers so that we validate the design | Must | 5 | 4 |
| HM-022 | E7 | As a team, we want to fix issues found in testing so that quality is acceptable at release | Must | 8 | 4 |
| HM-023 | E7 | As a student on a weak connection, I want pages and video to load quickly so that I can learn in low-bandwidth areas | Should | 5 | 4 |
| HM-024 | E7 | As a developer, I want a hosted release with deployment notes so that the prototype can be demonstrated | Must | 5 | 4 |
| HM-025 | E7 | As a supervisor, I want a final report and demo so that research findings are documented | Must | 5 | 4 |
| HM-026 | E7 | As a teacher, I want a visual user manual so that I can use the platform independently | Should | 3 | 4 |

**Total planned:** 139 story points (Must = 107, Should = 32). Won't-have for this release: live classes, native apps, certificates, AI sign recognition.

## 3.3 Acceptance Criteria (key stories)

Acceptance criteria use Given / When / Then. **Every learner-facing story also inherits the accessibility criteria in the Definition of Done.**

**HM-005 Register and log in**
- Given a new user, when they submit valid details, then an account is created and they are signed in.
- Given invalid or duplicate details, when they submit, then a clear visual error message explains the problem.
- Passwords are stored hashed; sessions expire after inactivity.

**HM-009 Captioned lesson video**
- Given a lesson with video, when the student plays it, then captions are shown by default and can be resized.
- Captions are synchronised within 0.5 seconds of speech.
- No information in the lesson is available only through audio.

**HM-010 Sign-language video**
- Given a lesson, when the student opens it, then a sign-language video is shown beside or below the main content and can be enlarged.
- The student can pause, replay and slow down the sign-language video.

**HM-012 Teacher upload**
- Given a logged-in teacher, when they upload a video with a caption file and optional sign-language video, then the lesson appears in the catalogue after preview and publish.
- Uploads without captions cannot be published and the teacher sees why.

**HM-015 Visual feedback**
- Correct and incorrect answers are indicated by colour, icon and text together (never colour alone).
- No sound is required to understand a result.

**HM-017 Teacher dashboard**
- Given a teacher with assigned students, when they open the dashboard, then they see per-student completion and quiz scores for their lessons.
- A teacher cannot see other teachers' students.

**HM-021 Usability testing**
- At least 8 participants take part, with an interpreter present where needed.
- Each participant attempts the same 5 core tasks; success, time and difficulty are recorded.

## 3.4 Backlog Management Rules

1. The BA writes stories; the team sizes them; the PM protects sprint scope.
2. A story must meet the **Definition of Ready** before entering a sprint.
3. New requests go to the backlog, are sized and prioritised, and replace lower-priority work if capacity is full.
4. Backlog is refined mid-sprint so the next sprint is always ready.
5. Change requests that affect scope or dates are raised to the supervisor.
