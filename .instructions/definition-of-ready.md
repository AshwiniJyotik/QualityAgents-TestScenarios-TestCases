# Definition of Ready (DoR)

Applies to: all standard projects in this repository. Use this checklist to
confirm whether a backlog item (user story, bug, task, or spike) is ready for
estimation and inclusion in sprint planning.

How to use:
- Run this checklist during refinement. A story should meet all **mandatory**
  items or have a documented plan (spike or dependency) before estimation.

Mandatory DoR checklist:
- Title and short description present and understandable.
- Business value / goal clearly stated (why this matters).
- Actor / persona clarified (who benefits).
- Acceptance criteria defined (Given/When/Then or clear bullets).
- Dependencies identified (APIs, teams, data, infra) and owners listed.
- UX or API mockups attached when UI/API changes are required.
- Performance/security/regulatory constraints noted if applicable.
- Definition of Done (DoD) relevant to this story referenced or linked.
- Story is small enough to be completed within a single sprint or has been
  logically split.
- Estimateable: team can size it (story points or hours) or a spike is
  scheduled to enable estimation.

Recommended (but optional) items:
- Linked to a parent Epic or Initiative.
- Success metrics or acceptance signals (e.g., increased conversion by X%).
- Test data or test account details included if needed.

Handling missing mandatory items:
- If a mandatory item is missing, mark the story as NOT DoR-ready and either
  a) create a small spike to resolve it, or b) capture the missing info as a
  task with an owner and a deadline before planning.

Sprint pull-in policy:
- A story may only be pulled into a sprint when all **Mandatory DoR** items
  are satisfied. If any mandatory item is missing, the story cannot be
  planned into the sprint until remediation is completed or a compliant
  alternate (split story or spike) exists.

Responsibility:
- The Product Owner (with the team's agreement) is responsible for
  confirming DoR status before the story is included in a sprint.

Validation notes for agents:
- This file is written as a plain Markdown checklist. Parsers should accept
  bulleted lists and common headings. If a backlog item fails any mandatory
  line, return the missing items and remediation steps.

Examples:
- Minimal DoR-ready story: Title, As a <who>, I want <what> so that <why>,
  3 acceptance criteria, dependencies listed, estimate assigned.
