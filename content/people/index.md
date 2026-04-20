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
      title: Alumni
      text: |-
        {{< spoiler text="Show Former Members" >}}

        | Name | Position in Lab | Years | Current Affiliation |
        | :--- | :--- | :---: | :--- |
        | Dr. A. Kumar | PhD Student | 2020–2025 | Assistant Professor, XYZ University |
        | B. Rao | Masters Student | 2022–2024 | PhD Student, IIT Bombay |
        | C. Sharma | Research Associate | 2021–2023 | ABC Technologies |

        {{< /spoiler >}}
    design:
      columns: '1'
---