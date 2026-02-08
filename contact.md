---
layout: default
title: Contact
permalink: /contact/
---

## Get in touch

Use the form below to send me a message. I'll get back to you as soon as I can.

<form action="https://formspree.io/f/mreagwkd" method="POST" class="contact-form">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-group">
    <label for="email">Your email</label>
    <input type="email" id="email" name="_replyto" required>
  </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="6" required></textarea>
  </div>

  <button type="submit" class="btn-submit">Send message</button>
</form>

<style>
.contact-form{ max-width: 600px; margin-top: 24px; }
.form-group{ margin-bottom: 18px; }
.contact-form label{ display: block; margin-bottom: 6px; font-weight: 600; }
.contact-form input, .contact-form textarea{ width: 100%; padding: 10px 12px; border: 1px solid rgba(255,255,255,0.2); border-radius: 8px; background: rgba(255,255,255,0.05); color: #fff; font-size: 16px; font-family: inherit; }
.contact-form input:focus, .contact-form textarea:focus{ outline: none; border-color: rgba(255,255,255,0.4); background: rgba(255,255,255,0.08); }
.btn-submit{ background: #2aa8ff; color: #071018; padding: 12px 24px; border: none; border-radius: 10px; font-weight: 700; font-size: 16px; cursor: pointer; }
.btn-submit:hover{ filter: brightness(1.1); }
</style>
