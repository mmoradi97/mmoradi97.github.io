---
title: Contact
icon: fas fa-envelope
order: 3
layout: page
---

<div class="contact-block">
  <div class="contact-section">
    <div class="contact-section-title">Email:</div>
    <div class="contact-email">
      <a href="mailto:mmoradi97@icloud.com">mmoradi97@icloud.com</a>
    </div>
  </div>

  <div class="contact-section">
    <div class="contact-section-title">Form:</div>

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
  </div>
</div>

<style>
  /* Contact form styling (explicitly supports Chirpy's light/dark toggle). */
  :root {
    --cf-bg: rgba(255, 255, 255, 0.92);
    --cf-border: rgba(0, 0, 0, 0.18);
    --cf-border-focus: rgba(0, 0, 0, 0.32);
    --cf-btn-bg: rgba(0, 0, 0, 0.05);
    --cf-btn-bg-hover: rgba(0, 0, 0, 0.08);
    --cf-btn-border: rgba(0, 0, 0, 0.18);
    --cf-label: rgba(0, 0, 0, 0.70);
    --cf-section: rgba(0, 0, 0, 0.80);
  }

  /* If Chirpy forces a mode, respect it (this avoids the “system dark overrides forced light” bug). */
  html[data-mode='light'] {
    --cf-bg: rgba(255, 255, 255, 0.92);
    --cf-border: rgba(0, 0, 0, 0.18);
    --cf-border-focus: rgba(0, 0, 0, 0.32);
    --cf-btn-bg: rgba(0, 0, 0, 0.05);
    --cf-btn-bg-hover: rgba(0, 0, 0, 0.08);
    --cf-btn-border: rgba(0, 0, 0, 0.18);
    --cf-label: rgba(0, 0, 0, 0.70);
    --cf-section: rgba(0, 0, 0, 0.80);
  }

  html[data-mode='dark'] {
    --cf-bg: rgba(255, 255, 255, 0.04);
    --cf-border: rgba(255, 255, 255, 0.18);
    --cf-border-focus: rgba(255, 255, 255, 0.35);
    --cf-btn-bg: rgba(255, 255, 255, 0.08);
    --cf-btn-bg-hover: rgba(255, 255, 255, 0.12);
    --cf-btn-border: rgba(255, 255, 255, 0.25);
    --cf-label: rgba(255, 255, 255, 0.72);
    --cf-section: rgba(255, 255, 255, 0.82);
  }

  /* Fallback: if no explicit data-mode is present, follow system preference. */
  @media (prefers-color-scheme: dark) {
    html:not([data-mode]) {
      --cf-bg: rgba(255, 255, 255, 0.04);
      --cf-border: rgba(255, 255, 255, 0.18);
      --cf-border-focus: rgba(255, 255, 255, 0.35);
      --cf-btn-bg: rgba(255, 255, 255, 0.08);
      --cf-btn-bg-hover: rgba(255, 255, 255, 0.12);
      --cf-btn-border: rgba(255, 255, 255, 0.25);
      --cf-label: rgba(255, 255, 255, 0.72);
      --cf-section: rgba(255, 255, 255, 0.82);
    }
  }

  .contact-block {
    max-width: 560px;
  }

  .contact-section {
    margin: 0 0 1.25rem 0;
  }

  .contact-section-title {
    font-weight: 700;
    font-size: 1.05rem;
    margin: 0 0 0.5rem 0;
    color: var(--cf-section);
  }

  .contact-email a {
    font-size: 1.02rem;
  }

  .contact-form .field {
    margin: 0 0 1rem 0;
  }

  .contact-form label {
    display: block;
    font-weight: 600;
    font-size: 0.92rem;
    margin: 0 0 0.4rem 0;
    color: var(--cf-label);
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
    padding: 0.65rem 1.05rem;
    border-radius: 0.6rem;
    border: 1px solid var(--cf-btn-border);
    background: var(--cf-btn-bg);
    color: inherit;
    font-weight: 700;
    cursor: pointer;
  }

  .contact-form button:hover {
    background: var(--cf-btn-bg-hover);
  }
</style>
