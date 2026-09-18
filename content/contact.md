---
title: "Contact us"
layout: "contact"
description: "Contact the Call Detective team about creating a citizen science verification website."
hero:
  subtitle: "Let’s talk about your ecoacoustics project."
  image: "/hero-image-1920w.webp"
  alt: "Landscape photograph of the Australian outback plains with a lone tree in the foreground and mountains in the distance"
  sources:
    - src: "/hero-image-1280w.webp"
      width: "1280w"
    - src: "/hero-image-1920w.webp"
      width: "1920w"
    - src: "/hero-image-2560w.webp"
      width: "2560w"
    - src: "/hero-image-3840w.webp"
      width: "3840w"
home_link:
  url: "/"
  label: "← Call Detective"
intro:
  eyebrow: "Get in touch"
  heading: "Start a conversation"
form:
  name: "contact"
  method: "POST"
  action: "/"
  honeypot:
    name: "bot-field"
    label: "Don’t fill this out if you’re human:"
  fields:
    - id: "contact-name"
      name: "name"
      label: "Name"
      type: "text"
      autocomplete: "name"
      required: true
    - id: "contact-email"
      name: "email"
      label: "Email"
      type: "email"
      autocomplete: "email"
      required: true
    - id: "contact-organisation"
      name: "organisation"
      label: "Organisation"
      hint: "(optional)"
      type: "text"
      autocomplete: "organization"
    - id: "contact-message"
      name: "message"
      label: "How can we help? Tell us about your call detective project idea"
      element: "textarea"
      rows: 7
      required: true
  submit_label: "Send message"
  submitting_label: "Sending…"
  alerts:
    success: "Message received. We’ll get back to you soon."
    failure: "There was a problem sending your message. Please try again."
---

Interested in creating a Call Detective website, or have a question about an
existing project? Send us a message and our team will get back to you.
