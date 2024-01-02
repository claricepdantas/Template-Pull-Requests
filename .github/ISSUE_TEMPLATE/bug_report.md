---
name: Bug report
about: Create a report to Bug
title: ''
labels: ''
assignees: claricepdantas

---

name: Bug report
about: Create a report to Bug
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: ["bug", "triage"]
projects: ["nome do projeto"]
assignees:
  - nome do usuário
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: what-happened
    attributes:
      label: What is the scope of this change (e.g. component or file name):
      description: Write a short, imperative tense description of the change.
      placeholder: Are there any breaking changes?
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: Does this change affect any open issues?
