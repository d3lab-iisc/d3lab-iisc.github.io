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
          # - Former Members
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
        | 2025 | [Gulshan Baghel](https://www.linkedin.com/in/gulshan-baghel-a94a3a2a4) | MTech |
        | 2025 | [Padmani Shivam B](https://www.linkedin.com/in/shivampadmani/) | MTech |
        {{< /spoiler >}}

        {{< spoiler text="Research Associates" >}}
        | Name | Lab Affiliation |
        | :--- | :--- | 
        | [Balaram Aitipamula](https://www.linkedin.com/in/balaram-aitipamula-a79058207/) | Research Associate |
        | [Vedant Singh Bedi](https://www.linkedin.com/in/vedant-singh-bedi-22194527b) | Intern |
        | [Rajdeep Lahiri](https://www.linkedin.com/in/rajdeep-lahiri-b86593243) | Intern |
        | [Kaustuv Devmishra](https://www.linkedin.com/in/kaustuv-devmishra-372868253) | Intern |
        | [Saurav Dutta](https://www.linkedin.com/in/saurav-dutta-7aa931195/) | Research Associate |
        | [Mamkesh Gautam](https://www.linkedin.com/in/mamkeshgautam/) | Research Associate |
        | [Srivageesh K Srinidhi](https://www.linkedin.com/in/srivageesh-k-srinidhi-645547228/) | Intern |
        {{< /spoiler >}}
    design:
      columns: '1'
---