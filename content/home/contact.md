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
  email: samuel.hurault@ens.fr
  address:
    street: 45 Rue d'Ulm
    city: Paris
    postcode: '75005'
    country: France
    country_code: FR
  directions: Centre Sciences des Données (CSD)

design:
  columns: '2'
---
