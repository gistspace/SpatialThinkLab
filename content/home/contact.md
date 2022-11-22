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
  email: mairead.deroiste@vuw.ac.nz
  phone: +64 4 463 6431
  address:
    street: Co215, Cotton Building, Kelburn Parade
    city: Wellington
    postcode: '6012'
    country: New Zealand
    country_code: NZ
  coordinates:
    latitude: '-41.2901' #updated
    longitude: '174.7685' #updated
  directions: Second floor of the Cotton Building room 215
  office_hours:
    - 'Email for an appointment'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/SpatialThinkLab'


design:
  columns: '2'
---
