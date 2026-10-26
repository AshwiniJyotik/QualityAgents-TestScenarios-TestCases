# Definition of Done (DoD)

Applies to: all standard projects in this repository. Use this checklist to
confirm that implemented work is complete, releasable, and meets quality
expectations.

How to use:
- Apply this checklist before marking a story/task as done. For release
  readiness, ensure all relevant DoD items are satisfied across teams.

Mandatory DoD checklist:
- Code implemented and follows repository style and linting rules.
- Unit tests added/updated with satisfactory coverage for changed logic.
- Integration and/or API contract tests added where applicable.
- Automated tests pass in CI and local checks pass (lint, build).
- Peer-reviewed: PR created and at least one approving review from a
  responsible reviewer.
- Documentation updated: README, API docs, user docs, or release notes as
  applicable.
- Feature toggles or rollout plans defined if needed for gradual release.
- No known critical bugs; remaining issues are tracked and prioritized.
- Security checks completed for sensitive changes (dependency scans,
  secrets, vulnerability reports) or a mitigation plan exists.
- Deployment artifacts are built and validated in staging (or a plan exists
  to do so before release).

Recommended (but optional):
- Performance tests executed if change affects latency or throughput.
- UX review completed and accessibility checks passed for UI changes.

Validation notes for agents:
- This file is written as a plain Markdown checklist. Validators should mark
  items present or missing and report any CI/build failures or missing tests.

Post-implementation validation:
- When validating completed work, the agent should list unmet DoD items and
  include explicit remediation steps (e.g., add unit tests, re-run CI,
  request security scan clearance).

Closure authority:
- A story may be considered closed only when all **Mandatory DoD** items are
  satisfied.
- Closure must be confirmed jointly by the Product Owner and the testing
  team; the Product Owner verifies business acceptance while the testing
  team verifies quality and test completion.

Responsibility and handover:
- The implementing team should raise the PR and signal when work is ready
  for verification. The testing team performs verification and reports
  results. The Product Owner performs the final acceptance and closes the
  story when satisfied.
