---
title: Contact
icon: fas fa-envelope
order: 3
layout: page
---

**Email:**

[mmoradi97@icloud.com](mailto:mmoradi97@icloud.com)

**Form:**

<style>
  /* Contact form styling that works in both light & dark mode. */
  :root {
    --cf-bg: rgba(255, 255, 255, 0.85);
    --cf-border: rgba(0, 0, 0, 0.14);
    --cf-border-focus: rgba(0, 0, 0, 0.28);
    --cf-btn-bg: rgba(0, 0, 0, 0.04);
    --cf-btn-bg-hover: rgba(0, 0, 0, 0.07);
    --cf-btn-border: rgba(0, 0, 0, 0.18);
  }

  /* Chirpy typically sets html[data-mode]. If it doesn't, the media query below still helps. */
  html[data-mode='dark'] {
    --cf-bg: rgba(255, 255, 255, 0.04);
    --cf-border: rgba(255, 255, 255, 0.18);
    --cf-border-focus: rgba(255, 255, 255, 0.35);
    --cf-btn-bg: rgba(255, 255, 255, 0.08);
    --cf-btn-bg-hover: rgba(255, 255, 255, 0.12);
    --cf-btn-border: rgba(255, 255, 255, 0.25);
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --cf-bg: rgba(255, 255, 255, 0.04);
      --cf-border: rgba(255, 255, 255, 0.18);
      --cf-border-focus: rgba(255, 255, 255, 0.35);
      --cf-btn-bg: rgba(255, 255, 255, 0.08);
      --cf-btn-bg-hover: rgba(255, 255, 255, 0.12);
      --cf-btn-border: rgba(255, 255, 255, 0.25);
    }
  }

  .contact-form {
    max-width: 520px;
    margin-top: 0.75rem;
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
    border-radius: 0.6rem;
    border: 1px solid var(--cf-border);
    background: var(--cf-bg);
    color: inherit;
    outline: none;
  }

  .contact-form input:focus,
  .contact-form textarea:focus {
    border-color: var(--cf-border-focus);
  }

  .contact-form button {
    padding: 0.65rem 1.0rem;
    border-radius: 0.6rem;
    border: 1px solid var(--cf-btn-border);
    background: var(--cf-btn-bg);
    color: inherit;
    font-weight: 600;
    cursor: pointer;
  }

  .contact-form button:hover {
    background: var(--cf-btn-bg-hover);
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
