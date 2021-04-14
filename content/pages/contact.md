---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Ada sesuatu yang mau kamu sampaikan, isi saja formulir ini atau kamu juga
      bisa kirim email ke cuanku.official@gmail.com
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Tulis nama kamu ya
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Alamat email yang bisa dihubungi balik juga ya
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Website Error
          - Sponsorship
          - Partnership
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
