---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

active: false

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
  email: tianzhengmiao@foxmail.com
  phone: +86 15515093857
  #address:
    #street: 450 Serra Mall
    #city: Singapore
    #region: CA
    #postcode: '94305'
    #country: Singapore
    #country_code: SGP
  #coordinates:
    #latitude: '37.4275'
    #longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
    #- 'Monday 10:00 to 13:00'
    #- 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/MiaoTianzheng'
    #- icon: video
     # icon_pack: fas
      #name: Zoom Me
      #link: 'https://zoom.com'

design:
  columns: '2'
---
