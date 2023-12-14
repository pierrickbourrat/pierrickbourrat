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
  - block: portfolio
    id: research
    content:
      title: Research
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      #default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle:
      page_type: publication
      count: 1
      filters:
        folders:
          - publication
        featured_only: true
      order: desc
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      #subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
     # email: p.bourrat@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Macquarie University
        city: North Ryde
        region: NSW
        postcode: '2109'
        country: Australia
        country_code: AU
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours: 'By appointment'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '-33.77453'
        longitude: '151.11111'  
      contact_links:
        - icon: at
          icon_pack: fas
          name: Email me
          link: 'mailto:p.bourrat@gmail.com'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
     # autolink: true
      # Email form provider
     # form:
     #   provider: netlify
     #   formspree:
     #     id:
     #   netlify:
          # Enable CAPTCHA challenge to reduce spam?
     #     captcha: false
    design:
      columns: '2'
---