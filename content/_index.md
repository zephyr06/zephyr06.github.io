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

  # - block: skills
  #   content:
  #     title: Skills
  #     text: 'aa'
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '2'

  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'

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


  - block: collection
    id: Publications
    content:
      title: <h>Selected Publications</h> 
      text: See the *latest* full list of the publication at [Google Scholar](https://scholar.google.com/citations?user=axGVXwcAAAAJ&hl=en).<p></p><p></p>
      folders:
        - publication
      count: 3
    design:
      columns: '2'
      view: citation
      

  # - block: collection
  #   # id: projects
  #   content:
  #     title: Featured Publications
  #     folders:
  #       - publication
  #   design:
  #     columns: '2'
  #     view: card

  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Awards'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       # - certificate_url: https://www.coursera.org
  #       #   date_end: ''
  #       #   date_start: '2021-01-25'
  #       #   description: ''
  #       #   icon: coursera
  #       #   organization: Coursera
  #       #   organization_url: https://www.coursera.org
  #       #   title: Neural Networks and Deep Learning
  #       #   url: ''
  #       - date_start: '2020-12-01'
  #         title: IROS Best Entertainment and Amusement Paper Award Finalist
  #       - date_start: '2024-03-08'
  #         title: Pratt Fellowship Award
  #   design:
  #     columns: '2'

  - block: markdown
    id: awards
    content:
      title: Awards
      subtitle: 
      text: 
        <u1><li>2020 IROS Best Entertainment and Amusement Paper Award Finalist</li></u1>
        <u1><li>Pratt Fellowship Award</li></u1>
    design:
      columns: '2'

  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'

  - block: markdown
    id: services
    content:
      title: Services
      subtitle: 
      text: <p>Reviewer for the following journals and conferences:</p>
        <u1><li>International Conference on Robotics and Automation (ICRA)</li></u1>
        <u1><li>Journal of System Architecture</li></u1>
        <u1><li>ACM Transactions on Embedded Computing Systems</li></u1>
        <u1><li>The Journal of Supercomputing</li></u1>
        <u1><li>Workshop on OPtimization for Embedded and ReAl-time systems (OPERA) co-located with the 45th IEEE Real-Time Systems Symposium (RTSS)</li></u1>
    design:
      columns: '2'


  - block: markdown
    id: Teaching
    content:
      title: Teaching
      subtitle: 
      text: <p>Graduate Teaching Assitant for the following courses:</p>
        <u1><li>CS6476 Intro to Computer Vision (Georgia Tech)</li></u1>
        <u1><li>ECE5494 Innovation Pathways in Artificial Intelligence and Machine Learning (Virginia Tech)</li></u1>
        <u1><li>ECE5554 Computer Vision (Virginia Tech)</li></u1>
        <u1><li>ECE3714 Intro to Control Systems (Virginia Tech)</li></u1>
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sen.zephyr.wang@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
