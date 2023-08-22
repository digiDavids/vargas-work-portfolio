---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills Rating
      items:
        - name: Troubleshooting
          description: 95%
          icon: sistrix
          icon_pack: fab
        - name: Cloud Computing
          description: 90%
          icon: cloud
          icon_pack: fas        
        - name: Project Management
          description: 75%
          icon: chart-bar
          icon_pack: fas
        - name: Collaboration
          description: 90%
          icon: people-group
          icon_pack: fas
        - name: Web Creation
          description: 90%
          icon: globe
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lifelong Learner
          company: Online Learning 
          company_url: 'https://admin.vargaspctech.com/tech-training-resources'
          company_logo: leanpub
          location: Arkansas
          date_start: '2021-09-01'
          date_end: ''
          description: Educating myself with Online Training and Upskilling Certifications. 
        - title: Data Center Operations Analyst III / Sr Systems Administrator
          company: Tokyo Electron US
          company_url: 'http://www.tel.com/'
          company_logo: building-regular
          location: Austin, TX
          date_start: '1998-06-01'
          date_end: '2021-09-01'
          description: |2-
              Responsibilities include:

              * Managed a robust Microsoft O365/M365 and Hybrid On-Premise environment for 3000+ users.
              * Migrated on-premise mailboxes to Exchange Online.
              * Developed Powershell scripts to automate tasks.
              * Reported on Office 365 Infrastructure.
              * Managed Data Center servers.
              * Worked with other departments to identify technology solutions.
              * Managed support cases using Microsoft Dynamics CRM Helpdesk.
              * Monitor and maintain enterprise email system
              * Perform hardware, software, and network upgrades
              * Implement and maintain system security
              * Support enterprise VMware environments
              * Implement backup strategy
              * Assist coworkers and provide daily tech support
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://learn.microsoft.com/en-us/users/dbvargas/credentials/bf5a58d5c951d57f
          date_end: '2024-07-07'
          date_start: '2023-07-06'
          description: '  Skills measured 
                          Manage Azure identities and governance
                          Implement and manage storage
                          Deploy and manage Azure compute resources
                          Implement and manage virtual networking
                          Monitor and maintain Azure resources'
          organization: Microsoft
          organization_url: https://www.microsoft.com
          title: Azure Administrator Associate
          url: 'https://learn.microsoft.com/en-us/certifications/azure-administrator/'
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
       folders:
       - project
       # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
       default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
       buttons:
        - name: All
          tag: '*'
        - name: ai
          tag: learning
        - name: Other
          tag: Azure
  #   design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
       columns: '1'
       view: showcase
      # For Showcase view, flip alternate rows?
       flip_alt_rows: false
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to reach out, I am actively seeking remote work from the State of Arkansas!
      # Contact (add or remove contact options as necessary)
      email: dbvargas@gmail.com
      phone: +1‪(512) 761-6273‬
      address:
        street: 
        city: 
        region: Arkansas
        postcode: '72687'
        country: United States
        country_code: US
      directions: 
      office_hours:
        - 'Weekdays 10:00am to 5:00pm'
      contact_links:
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'https://join.skype.com/invite/a42lRG0OGpAv'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.us'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
