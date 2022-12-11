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
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: jxa421@case.edu
  phone: 234-281-5565
  address:
    street: 10900 Euclid Avenue (WG Bldg Room 82D)
    city: Cleveland
    region: OH
    postcode: '44106'
    country: United States
    country_code: US
  coordinates:
    latitude: '41.504576531767384'
    longitude: '-81.6041538314905'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/jay_tvm'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://cwru.zoom.us/my/jayakrishnanajayakumar'

design:
  columns: '2'
---
