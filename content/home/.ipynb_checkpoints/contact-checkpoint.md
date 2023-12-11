---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  # form:
  #  provider: netlify
  # formspree:
  #   id:
  # netlify:
  #  # Enable CAPTCHA challenge to reduce spam?
  #    captcha: false
  contact_links:
      - icon: at
        name: email me
        icon_pack: fas
        link: mailto:p.bourrat@gmail.com 

  # Contact details (edit or remove options as required)

  address:
    street: Macquarie University
    city: North Ryde
    region: NSW
    postcode: '2109'
    country: Australia
    country_code: AU
  coordinates:
    latitude: '-33.77453'
    longitude: '151.11111'
    office_hours: by appointment
  

design:
  columns: '2'
---
