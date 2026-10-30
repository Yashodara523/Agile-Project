# 7. Definition of Ready, Definition of Done and Quality Plan

## 7.1 Definition of Ready (story can enter a sprint)

- [ ] Written as a user story with a clear business value
- [ ] Acceptance criteria in Given / When / Then format
- [ ] Sized by the team (story points)
- [ ] Dependencies identified and unblocked
- [ ] Design or wireframe available (for UI stories)
- [ ] Accessibility criteria identified
- [ ] Small enough to finish within one sprint

## 7.2 Definition of Done (story is complete)

**Code and build**
- [ ] Code reviewed and approved by at least one other developer
- [ ] Merged to main through a pull request with passing CI
- [ ] No known critical or high defects

**Testing**
- [ ] Acceptance criteria verified by QA
- [ ] Unit tests written for new logic
- [ ] Regression suite passes
- [ ] Tested on at least two browsers and one mobile screen size

**Accessibility (applies to every learner-facing story)**
- [ ] All information available without audio
- [ ] Video has accurate captions
- [ ] Colour is never the only indicator; icons and text are also used
- [ ] Text contrast meets WCAG 2.1 AA (4.5:1 for normal text)
- [ ] Fully usable by keyboard
- [ ] Clear, simple language and consistent layout
- [ ] No time limits that cannot be extended

**Delivery**
- [ ] Deployed to the test environment
- [ ] Demonstrated at sprint review
- [ ] Documentation or release note updated
- [ ] Product Owner proxy (BA) accepts the story

## 7.3 Quality Plan

| Area | Approach | Owner | Tooling (examples) |
|---|---|---|---|
| Functional testing | Test cases linked to stories and acceptance criteria | QA | Spreadsheet or test management tool |
| Regression testing | Automated suite run on every merge | QA, Developers | CI pipeline |
| Accessibility testing | Automated scan plus manual checklist plus testing with users | QA, UX | Axe / Lighthouse, screen-based checklist |
| Usability testing | 5 core tasks with at least 8 participants | UX, BA | Task script, observation sheet |
| Code quality | Peer review, linting, branch protection | Developers | GitHub |
| Performance | Page-load and video start-up checks on throttled network | Developers, QA | Browser developer tools |
| Security | Role checks, input validation, password hashing, review before release | Lead Developer | Checklist |

## 7.4 Severity Definitions

| Severity | Definition | Fix target |
|---|---|---|
| Critical | System unusable, data loss, security issue, or content inaccessible to deaf users | Immediately |
| High | Main feature broken, no workaround | Within the sprint |
| Medium | Feature impaired, workaround exists | Within next sprint |
| Low | Cosmetic or minor | Backlog |

## 7.5 Release Readiness Checklist (Sprint 4)

- [ ] All Must stories Done
- [ ] No open critical or high defects
- [ ] Usability task success at least 85%
- [ ] Accessibility checklist passed
- [ ] Deployment tested and rollback plan available
- [ ] User manual and release notes ready
- [ ] Supervisor go decision recorded

## 7.6 Usability Test Core Tasks

1. Register and log in
2. Find and open a lesson in a chosen subject
3. Watch a lesson using captions and the sign-language video
4. Complete a quiz and understand the result
5. Ask a question to the teacher and find the answer

**Measures:** task success (yes/partial/no), time on task, errors, satisfaction rating (1 to 5), observer notes.
