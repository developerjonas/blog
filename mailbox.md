---
layout: page
title: Mailbox
permalink: /mailbox/
---

<style>
  .terminal-wrapper {
    background-color: #000;
    color: #00ff00;
    font-family: 'Courier New', Courier, monospace;
    padding: 2rem;
    max-width: 600px;
    margin: 2rem auto;
    border: 2px solid #00ff00;
    border-radius: 8px;
  }

  .terminal-label {
    margin-top: 1rem;
    margin-bottom: 0.5rem;
    display: block;
    font-weight: bold;
  }

  .terminal-input {
    background: transparent;
    border: none;
    border-bottom: 2px solid #00ff00;
    color: #00ff00;
    font-family: inherit;
    font-size: 1.1rem;
    width: 100%;
    outline: none;
    caret-color: #00ff00;
    padding: 0.2rem 0;
  }

  .submit-line {
    margin-top: 2rem;
    font-weight: bold;
    text-decoration: underline;
    cursor: pointer;
    display: inline-block;
    transition: color 0.3s;
  }

  .submit-line:hover {
    color: #00cc00;
  }

  .terminal-message {
    margin-top: 2rem;
    font-style: italic;
    color: #00ff99;
  }
</style>

<div class="terminal-wrapper">
  <p>// Subscribe to <strong>Lab-Notes Mailbox</strong></p>
  <p>// Get updates when new notes are published</p>

  <form id="mailbox-form" action="https://formspree.io/f/your-form-id" method="POST">
    <label class="terminal-label">Email:</label>
    <input class="terminal-input" type="email" name="email" placeholder="__________" required />

    <span class="submit-line" onclick="document.getElementById('mailbox-form').submit();">
      ↳ send to mailbox
    </span>
  </form>

  <div class="terminal-message">
    *Your email stays safe. No spam. No noise.
  </div>
</div>
