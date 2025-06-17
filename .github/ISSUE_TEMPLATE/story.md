---
name: Story
about: User Story - Definition of a feature within an Epic from the user's perspective
title: "<story title>"
labels: 
  - enhancement
type: story
assignees: ''
estimate: 1
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this story template!
  - type: dropdown
    id: story-type
    attributes:
      label: Story Type
      options:
        - Feature
        - Enhancement
        - Technical
      required: true
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      options:
        - High
        - Medium
        - Low
      required: true
  - type: dropdown
    id: story-points
    attributes:
      label: Story Points
      options:
        - 1
        - 2
        - 3
        - 5
        - 8
        - 13
      required: true
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Provide a detailed description of the story
      placeholder: Enter story description here...
      required: true
  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria
      description: List the criteria that must be met for this story to be considered complete
      placeholder: |
        - [ ] Criterion 1
        - [ ] Criterion 2
      required: true
---

**IN ORDER TO:**  
<!-- Goal this story supports -->

**AS A:**  
<!-- User role -->

**I WANT:**  
<!-- Feature or capability desired -->

**DESCRIPTION:**  
<!-- Short summary of the feature -->

**ACCEPTANCE CRITERIA:**  
<!-- List rules and examples that need to pass -->
- [ ]
- [ ]