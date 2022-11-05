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
  email: kalongboniface97@gmail.com
  phone: +233 50 616 2161
  address:
    street: 450 Offinso-Ahenkro
    city: Kumasi
    region: AF
    postcode: '00233'
    country: Ghana
    country_code: GH
  coordinates:
    latitude: '7.349'
    longitude: '-2.342'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday to Sunday 24/7'
  appointment_url: 'https://calendly.com/kalongboniface'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/boniface_kalong'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
