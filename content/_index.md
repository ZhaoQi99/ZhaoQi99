---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    id: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: DevOps Developer Engineer
          company: JD Technology
          company_url: 'https://www.jdcloud.com/'
          company_logo: org-jdt
          location: Beijing,China
          date_start: '2020-07-01'
          date_end: ''
          description: |2-
              * PaaS management platform
              * AIOps platform
        - title: DevOps Developer Intern
          company: JD Technology
          company_url: 'https://www.jdcloud.com/'
          company_logo: org-jdt
          location: Beijing,China
          date_start: '2019-07-01'
          date_end: '2020-01-01'
          description: 'AIOps'
        - title: Backend Developer Intern
          company: Chaitin Tech
          company_url: 'https://www.chaitin.cn/'
          company_logo: org-chaitin
          location: Beijing,China
          date_start: '2019-02-01'
          date_end: '2019-04-01'
          description: 'X-Ray'
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credly.com/badges/ecba1792-07d3-4753-8750-198bad00ed42/linked_in_profile
          date_end: '2028-06-14'
          date_start: '2025-06-14'
          description: 'Passing the GitHub Foundations certification exam validates subject matter expertise by measuring entry-level skills with GitHub basics like repositories, commits, branching, markdowns, and project management.'
          icon: github-foundations
          organization: Github
          organization_url: https://github.com
          title: GitHub Foundations
          url: 'https://examregistration.github.com/certification/GHF'

    design:
      columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: collection
  #   content:
  #     title: Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       # exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: zhaoqi99 [at] outlook [dot] com
      contact_links:
        - icon: github
          icon_pack: fab
          name: Follow Me
          link: 'https://github.com/ZhaoQi99'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
---
