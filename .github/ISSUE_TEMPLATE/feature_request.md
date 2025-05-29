name: 💡 Feature Request
description: Suggest a new feature or improvement
title: "[Feature]: "
labels: [enhancement]
body:
  - type: input
    id: summary
    attributes:
      label: Brief Description
      placeholder: e.g. "Add favorites feature"
    validations:
      required: true

  - type: textarea
    id: motivation
    attributes:
      label: Why is this feature useful?
      placeholder: Describe the use case or problem it solves.
    validations:
      required: true

  - type: textarea
    id: implementation
    attributes:
      label: Possible Implementation (optional)
      placeholder: Any ideas or suggestions on how to implement it?
