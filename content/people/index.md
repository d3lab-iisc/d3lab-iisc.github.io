---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - PhD Students
          - Masters Students
          - Research Associates
          - Former Members
      sort_by: Params.first_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: markdown
    content:
      title: Former Members
      text: |-
        | Name | Degree/Role | Current Position |
        | :--- | :---: | ---: |
        | A. Kumar | PhD Student | Assistant Professor |
        | B. Rao | Masters Student | PhD, IIT Bombay |
        | C. Sharma | Research Associate | Industry |

    design:
      columns: '1'
---