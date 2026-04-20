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
        {{< spoiler text="MTech/MTech(Res)" >}}
        |  Graduation Year | Name | Degree |
        | :---: | :--- | :---: |
        | 2025 | Gulshan Baghel | MTech |
        | 2025 | Padmani Shivam B | MTech |
        {{< /spoiler >}}

        {{< spoiler text="Research Associates" >}}
        | Name | Lab Affiliation |
        | :---: | :--- | 
        | Balaram Aitipamula | Research Associate |
        | Vedant Singh Bedi | Intern |
        | Rajdeep Lahiri| Intern |
        | Kaustuv Devmishra| Intern |
        | Saurav Dutta | Research Associate |
        | Mamkesh Gautam| Research Associate |
        | Srivageesh K Srinidhi | Intern |
        {{< /spoiler >}}
    design:
      columns: '1'
---