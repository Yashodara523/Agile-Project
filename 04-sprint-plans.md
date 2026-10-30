# 4. Sprint Plans

Each sprint is **2 weeks**. The same cadence was used throughout:

| Day | Event |
|---|---|
| Day 1 (Monday) | Sprint planning (90 min) |
| Daily | Stand-up (15 min) |
| Day 6 (mid-sprint) | Backlog refinement (60 min) |
| Day 9 | Code freeze for sprint scope, final testing |
| Day 10 (Friday) | Sprint review (60 min), then retrospective (45 min) |

**Capacity assumption (planning):** 3 developers, 1 designer, 1 BA, 1 QA, working part-time alongside studies. Commitment is set by the team after planning poker, using the previous sprint's velocity from Sprint 2 onwards.

> "Planned" values are what was committed at planning. Record actuals in `metrics/sprint-metrics.csv`.

---

## Sprint 1 (Weeks 1-2): Discover and Foundation

**Sprint goal:** Understand the users, baseline the requirements, and set up the technical and design foundation so that development can start in Sprint 2.

| Story | Points |
|---|---|
| HM-001 User interviews | 5 |
| HM-002 Personas and accessibility requirements | 3 |
| HM-003 Accessible design system | 5 |
| HM-004 Architecture, repo and CI | 5 |
| HM-005 Register and log in | 5 |
| HM-006 Role-based access | 3 |
| HM-007 Wireframes validated with users | 5 |
| **Planned total** | **31** |

**Key activities (PM):** kick-off meeting, charter approval, working agreements, tool setup, stakeholder register, risk register baseline, interview scheduling with partner teachers.
**Definition of success:** requirements baseline signed off; clickable prototype reviewed by at least 2 teachers; login working in the test environment.
**Review demo:** persona board, design system, clickable prototype, working login.

---

## Sprint 2 (Weeks 3-4): Core Learning Experience

**Sprint goal:** A student can open a lesson with captions and sign-language video, and a teacher can upload and publish that lesson. Alpha release at the end of the sprint.

| Story | Points |
|---|---|
| HM-008 Lesson catalogue | 5 |
| HM-009 Captioned video player | 8 |
| HM-010 Sign-language video | 8 |
| HM-011 Illustrated text lessons | 5 |
| HM-012 Teacher upload and publish | 8 |
| HM-013 First accessibility audit | 3 |
| **Planned total** | **37** |

**Key activities (PM):** capacity check against Sprint 1 velocity, dependency tracking (design hand-off to developers), interpreter review of sign-language content, risk review for video storage and bandwidth.
**Definition of success:** alpha demo with real lesson content; interpreter confirms sign-language video quality.

---

## Sprint 3 (Weeks 5-6): Assess and Engage

**Sprint goal:** Students can take quizzes with clear visual feedback and see their progress; teachers can monitor results and answer questions. Beta release (feature complete) at the end of the sprint.

| Story | Points |
|---|---|
| HM-014 Quiz creation | 8 |
| HM-015 Visual feedback | 3 |
| HM-016 Student progress | 5 |
| HM-017 Teacher dashboard | 8 |
| HM-018 Text Q&A | 8 |
| HM-019 Visual notifications | 3 |
| HM-020 Regression suite | 5 |
| **Planned total** | **40** |

**Key activities (PM):** scope check at mid-sprint (Should-have stories HM-017 and HM-018 are the first to move if velocity is lower than planned), usability test planning, consent forms and participant recruitment, scope freeze after review.
**Definition of success:** all Must stories Done; beta deployed to a test server; usability sessions scheduled.

---

## Sprint 4 (Weeks 7-8): Validate and Release

**Sprint goal:** Validate the platform with real users, fix the highest-impact issues, release a stable prototype, and deliver the final report and demo.

| Story | Points |
|---|---|
| HM-021 Usability testing | 5 |
| HM-022 Fix issues from testing | 8 |
| HM-023 Performance and low bandwidth | 5 |
| HM-024 Hosted release and deployment notes | 5 |
| HM-025 Final report and demo | 5 |
| HM-026 Visual user manual | 3 |
| **Planned total** | **31** |

**Key activities (PM):** testing logistics, triage of test findings (severity and effort), release go/no-go checklist, project closure report, lessons learned workshop, handover of artifacts.
**Definition of success:** no open critical or high defects; task success of at least 85%; final report accepted by supervisor.

---

## Planned Burn-Up Summary

| After sprint | Planned cumulative points | % of 139 |
|---|---|---|
| Sprint 1 | 31 | 22% |
| Sprint 2 | 68 | 49% |
| Sprint 3 | 108 | 78% |
| Sprint 4 | 139 | 100% |

## Scope Flex Plan

If velocity falls short, drop in this order: HM-019, HM-016, HM-011, HM-018, HM-017. Must-have stories are never traded away without supervisor approval.
