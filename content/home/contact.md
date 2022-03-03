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
  phone: 234 281 55 65
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
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
