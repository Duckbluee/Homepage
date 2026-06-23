---
title: ''
summary: ''
date: 2026-06-16
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: sm
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: papers
    content:
      title: Publications
      count: 8
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
---
