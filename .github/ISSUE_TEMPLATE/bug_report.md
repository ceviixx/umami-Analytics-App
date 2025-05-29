name: 🐞 Bug Report
description: Report a bug or unexpected behavior in the app
title: "[Bug]: "
labels: [bug]
body:
  - type: input
    id: version
    attributes:
      label: App Version
      placeholder: e.g. 1.2.3
    validations:
      required: true

  - type: input
    id: device
    attributes:
      label: Device and iOS Version
      placeholder: e.g. iPhone 13 Pro, iOS 17.4
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: |
        1. Open the app
        2. Navigate to ...
        3. Tap on ...
        4. Bug occurs
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      placeholder: What did you expect to happen?

  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots or screen recordings (optional)
      placeholder: Drag a file here or paste it

  - type: textarea
    id: logs
    attributes:
      label: Crash logs or console output (optional)
