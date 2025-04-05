---
layout: default.njk
title: Contact
permalink: /contact/index.html
---

<div class="contact-container">
  <div class="contact-info">
    <div class="info-item">
      <p><a href="mailto:khushmanbhullar@example.com">khushmanbhullar@example.com</a></p>
    </div>
  </div>

  <section class="contact-form-section">
    <h2>Send a Message</h2>
    <form action="#" method="POST" class="contact-form">
      <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" name="name" id="name" required placeholder="Your Name">
      </div>
      <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" name="email" id="email" required placeholder="Your Email">
      </div>
      <div class="form-group">
        <label for="message">Message:</label>
        <textarea name="message" id="message" required placeholder="Your Message"></textarea>
      </div>
      <button type="submit" class="submit-button">Send Message</button>
    </form>
  </section>
</div>
