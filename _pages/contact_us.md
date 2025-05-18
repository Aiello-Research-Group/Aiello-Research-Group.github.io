---
layout: page
permalink: /contact_us/
title: Contact Us
nav: true
nav_order: 9
---

<section class="contact-us">
  <div class="container">
    <h1>Get in Touch</h1>
    <p>We'd love to hear from you! Please fill out the form below, and we'll get back to you as soon as possible.</p>

    <!-- Contact Form -->
    <div class="form-container">
      <form action="https://formspree.io/f/mbldyzkb" method="POST" onsubmit="window.location.href='/thank_you'; return true;">
        <div class="form-group">
          <label for="name">Your Name</label>
          <input type="text" id="name" name="name" placeholder="Enter your name" required>
        </div>

        <div class="form-group">
          <label for="email">Your Email</label>
          <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>

        <div class="form-group">
          <label for="organization">Organization</label>
          <input type="text" id="organization" name="organization" placeholder="Enter your organization" required>
        </div>

        <div class="form-group">
          <label for="reason">Reason for Contact</label>
          <select id="reason" name="reason" required>
            <option value="Data Request">Data Request</option>
            <option value="Career">Career</option>
            <option value="Other">Other</option>
          </select>
        </div>

        <div class="form-group">
          <label for="message">Your Message</label>
          <textarea id="message" name="message" placeholder="Write your message" rows="5" required></textarea>
        </div>

        <button type="submit" class="submit-button">Send Message</button>
      </form>
    </div>

  </div>
</section>