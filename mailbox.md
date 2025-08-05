---
layout: page
title: Mailbox
permalink: /mailbox/
---

# Mailbox

Subscribe to **Lab Notes**  
Get quiet updates when new thoughts drop.  
No spam. No noise. Just notes.

<form id="mailbox-form" action="https://formspree.io/f/your-form-id" method="POST">
  <label class="form-line">
    Email : <input type="email" name="email" placeholder="__________" required />
  </label>

  <div class="submit-line" onclick="document.getElementById('mailbox-form').submit();">
    ↳ send to mailbox
  </div>
</form>

_Your email stays safe. Encrypted in mindspace._

<style>
  :root {
    --bg: transparent;
    --fg-light: #000000;
    --fg-dark: #ffffff;
    --border-light: #000000;
    --border-dark: #ffffff;
    --hover-light: #333333;
    --hover-dark: #cccccc;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --fg: var(--fg-dark);
      --border: var(--border-dark);
      --hover: var(--hover-dark);
    }
  }

  @media (prefers-color-scheme: light) {
    :root {
      --fg: var(--fg-light);
      --border: var(--border-light);
      --hover: var(--hover-light);
    }
  }

  form {
    max-width: 600px;
    margin: 2rem auto;
    font-family: inherit;
    color: var(--fg);
    background-color: var(--bg);
    padding: 1rem;
  }

  .form-line {
    display: flex;
    align-items: center;
    font-weight: bold;
    font-size: 1.2rem;
    color: var(--fg);
  }

  input[type="email"] {
    background: transparent;
    border: none;
    border-bottom: 2px dotted var(--border);
    color: var(--fg);
    font-size: 1.2rem;
    padding: 0.2rem;
    width: 100%;
    margin-left: 0.5rem;
    font-family: inherit;
    outline: none;
    caret-color: var(--fg);
  }

  .submit-line {
    margin-top: 2rem;
    font-weight: bold;
    text-decoration: underline;
    color: var(--fg);
    cursor: pointer;
    display: inline-block;
    transition: color 0.3s ease;
  }

  .submit-line:hover {
    color: var(--hover);
  }
</style>
