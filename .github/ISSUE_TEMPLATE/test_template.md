---
name: Test template, please ignore
about: Testing form
title: '[IMPROVEMENT]: Test template, please ignore'
labels: 'enhancement, maintenance'
assignees: ''
body:
- type: input
  id: test-id
  attributes:
    label: Custom name
    description: "Define custom name property"
    placeholder: "some-name"
  validations:
    required: true

---

## Description
<library-name> should be updated from <current-version> to <target-version>

## Objectives
<library-name> should have version <target-version>

## Strategy/Requirements
Update dependencies, and verify functionality.

<library-name> should be updated from <current-version> to <target-version>.
The changelog should be checked for any backward compatibility issues and breaking changes.


## Tasks

- [ ] Check changelog
- [ ] Update <library-name> library {test-id} | {{test-id}}
- [ ] Update Unit tests if needed
- [ ] Remove PRs created automatically by Dependabot (if any are left)

## Acceptance Criteria

- Dependencies are updated
- Functionality still works
- Unit tests run successfully

## Future Considerations
n/a

## Notes
_Extra notes: e.g. Changes should be checked carefully for both iOS and Android platforms._
