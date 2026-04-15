name: Bug Report
description: Report a bug with required details
title: "[ISSUE-ID] Short Summary of the Bug"
labels: ["bug"]

body:

  - type: input
    id: issue_id
    attributes:
      label: Issue ID
      description: Unique identifier for the issue
      placeholder: ISSUE-123
    validations:
      required: true

  - type: input
    id: summary
    attributes:
      label: Short Summary of the Bug
      placeholder: Brief description of the issue
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Provide detailed description of the issue
      placeholder: Explain what happened, expected vs actual behavior
    validations:
      required: true

  - type: textarea
    id: evidence
    attributes:
      label: Evidence & Links
      description: Add logs, URLs, references, or any supporting evidence
      placeholder: Logs, links, dashboards, etc.

  - type: textarea
    id: attachments
    attributes:
      label: Attachments
      description: Upload screenshots, logs, or screen recordings (drag & drop supported in GitHub)
      placeholder: Drag and drop files here or paste images/logs
