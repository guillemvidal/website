---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: ""
      background:
        color: white
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research sits at the intersection of political economy and public policy. I focus on producing **actionable research to inform governments and institutions**, especially on inequality, welfare, and socioeconomic policy.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of social structures in shaping political behavior and policy outcomes.
    design:
      columns: '1'
      css_class: 'research-section'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: card
      columns: 1
---
