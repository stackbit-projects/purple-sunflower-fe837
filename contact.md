---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Um mit uns in Kontakt zu treten bitte folgende Felder ausfüllen.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Dein Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: E enieD
        is_required: true
      - input_type: select
        name: Thema
        label: Thema
        default_value: Bitte auswählen
        options:
          - Fehler auf der Seite
          - Idee / Vorschlag
          - Sonstiges
          - Sponsoring
      - input_type: textarea
        name: Nachricht
        label: Nachricht
        default_value: Deine Nachricht
      - input_type: checkbox
        name: consent
        label: >-
          Ich bestätige, dass diese Seite meine Informationen zum Kontakt
          speichern darf.
    submit_label: Senden
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
