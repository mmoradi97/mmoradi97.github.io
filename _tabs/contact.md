---
title: Contact
icon: fas fa-envelope
order: 3
layout: page
---

[mmoradi97@icloud.com](mailto:mmoradi97@icloud.com)

<style>
  /* Minimal styling for the embedded Formspree form (works even without any CSS framework). */
  .contact-form {
    max-width: 520px;
  }
  .contact-form .field {
    margin: 0 0 1rem 0;
  }
  .contact-form label {
    display: block;
    font-weight: 600;
    margin: 0 0 0.35rem 0;
  }
  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 0.75rem 0.9rem;
    border-radius: 0.5rem;
    border: 1px solid rgba(255, 255, 255, 0.18);
    background: rgba(255, 255, 255, 0.04);
    color: inherit;
    outline: none;
  }
  .contact-form input:focus,
  .contact-form textarea:focus {
    border-color: rgba(255, 255, 255, 0.35);
  }
  .contact-form button {
    padding: 0.65rem 1.0rem;
    border-radius: 0.55rem;
    border: 1px solid rgba(255, 255, 255, 0.25);
    background: rgba(255, 255, 255, 0.08);
    color: inherit;
    font-weight: 600;
    cursor: pointer;
  }
  .contact-form button:hover {
    background: rgba(255, 255, 255, 0.12);
  }
</style>

<form class="contact-form" action="https://formspree.io/f/mreagwkd" method="POST">
  <div class="field">
    <label for="name">Name</label>
    <input id="name" name="name" type="text" autocomplete="name" required>
  </div>

  <div class="field">
    <label for="email">Email</label>
    <input id="email" name="email" type="email" autocomplete="email" required>
  </div>

  <div class="field">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="6" required></textarea>
  </div>

  <button type="submit">Send</button>
</form>
