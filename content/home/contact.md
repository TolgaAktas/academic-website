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
      captcha: true

  # Contact details (edit or remove options as required)
  email: tolga.f.aktas@gmail.com
  phone: XXX XXX XX XX
  address:
    street: 54 Lomb Memorial Dr  
    city: Rochester
    region: NY
    postcode: '14623'
    country: United States
    country_code: US
  coordinates:
    latitude: '43.08614739832001'
    longitude: '-77.6776696504515'
  directions: Find parking in Parking Lot F and walk to the building behind the bus stop.
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/tfaktas'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://rit.zoom.us/j/3870504347'

design:
  columns: '2'
---
