---
template: ContactPage
slug: contact
title: Contact Page
featuredImage: 'https://ucarecdn.com/e22a858a-b420-47af-99f6-ed54b6860333/'
subtitle: This is the contact page subtitle.
address: '404 James St, Burleigh Heads QLD 4220'
phone: 0987 123 456
email: example@example.com
locations:
  - lat: '55.7897714'
    lng: '12.5059623'
    mapLink: >-
      https://www.google.com/maps/place/Borrebakken+Park/@55.7897714,12.5059623,17z/data=!4m12!1m6!3m5!1s0x46524e6023e44b69:0xca65501ebacb9603!2sBorrebakken+Park!8m2!3d55.7897684!4d12.5081562!3m4!1s0x46524e6023e44b69:0xca65501ebacb9603!8m2!3d55.7897684!4d12.5081562
meta:
  description: This is a meta description.
  title: Contact Page
---

# Example contact form

This form is setup to use Netlify's form handling:

- the form action is set to the current absolute url: `action: '/contact/'`
- a name attribute is sent with the form's data `'form-name': 'Contact'`
- netlify data attributes are added to the form `data-netlify data-netlify-honeypot`

Find out more in the [Netlify Docs](https://www.netlify.com/docs/form-handling/).
