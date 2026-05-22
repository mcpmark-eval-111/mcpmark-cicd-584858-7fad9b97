---
name: Maintenance report
about: Track maintenance, refactoring, or housekeeping work
title: 'Maintenance: <short description of the task>'
labels: maintenance, needs-triage
assignees: ''
---

## Maintenance Type

What kind of maintenance is this? (Check all that apply)

- [ ] Code refactoring / cleanup
- [ ] Dependency upgrade
- [ ] Security patch
- [ ] Documentation update
- [ ] Test coverage / tooling improvement
- [ ] Build / CI infrastructure
- [ ] Other (describe below)

## Description

Describe the maintenance task in detail. What is the current state and what
should it look like once the work is complete?

## Motivation

Why is this maintenance needed now? Examples: outdated dependency, flaky
tests, technical debt, security advisory, performance regression, etc.

## Affected Areas

List the files, modules, or systems this maintenance will touch.

- `src/...`
- `tests/...`
- `package.json`

## Proposed Approach

Describe the planned approach. Include any commands, scripts, or migration
steps that will be required.

## Risks / Impact

- Potential breaking changes:
- Backwards compatibility concerns:
- Rollout / rollback plan:

## Acceptance Criteria

- [ ] Code passes linting and formatting checks
- [ ] All existing tests still pass
- [ ] New tests added where appropriate
- [ ] Documentation updated

## Additional Context

Add any other context, references, or links to relevant discussions. Mention
"low", "medium", "high", or "critical" to influence the priority label
applied by the automation workflow.
