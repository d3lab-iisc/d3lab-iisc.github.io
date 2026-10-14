---
title: Code
summary: Open-source code released by the D3 Lab, IISc Bengaluru.
date: 2026-10-14
type: landing

# Every page inside content/code/ is shown as a code card below.
# To add a new code: copy the `hetero-euclid` folder, rename it, and edit its index.md
# (or run `hugo new content code/<repo-name>`). Newest first (by `date`).
cascade:
  - _target:
      kind: page
    type: project

sections:
  - block: markdown
    content:
      title: Code
      text: |-
        Open-source implementations of our methods. All code is available on the [D3 Lab GitHub](https://github.com/d3lab-iisc/). If you use any of it in your work, please cite the corresponding paper.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '0', '0']

  - block: portfolio
    content:
      title:
      filters:
        folders:
          - code
      sort_by: Date
      sort_ascending: false
    design:
      columns: '1'
      view: masonry
      spacing:
        padding: ['20px', '0', '60px', '0']
---
