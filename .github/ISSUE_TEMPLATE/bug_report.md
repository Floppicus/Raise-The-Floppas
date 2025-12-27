---
name: Bug report
about: Create a report to help us improve
title: Game issue [BUG]
labels: bug
assignees: Floppicus
body:
- type: markdown
  attributes:
    value: "## Welcome!"
- type: markdown
  attributes:
    value: |
      Thanks for taking the time to fill out this bug! If you need real-time help, join us on Discord.
- type: input
  id: prevalence
  attributes:
    label: Bug prevalence
    description: "How often do you or others encounter this bug?"
    placeholder: "Whenever I visit the user account page (1-2 times a week)"
  validations:
    required: true
- type: textarea
  id: repro
  attributes:
    label: Reproduction steps
    description: "How do you trigger this bug? Please walk us through it step by step."
    value: |
      1.
      2.
      3.
      ...
    render: bash
  validations:
    required: true
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
  
---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Do '....'
4. See error

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]

**Smartphone (please complete the following information):**
 - Device: [e.g. iPhone6]
 - OS: [e.g. iOS8.1]


**Additional context**
Add any other context about the problem here.
