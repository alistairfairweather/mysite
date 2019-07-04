---
layout: page
title: Contact Alistair
permalink: /contact/
---

<form name="contact" method="POST" netlify-honeypot="beep-borp" data-netlify="true">
  <p>
    <label>Your name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your email address: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your phone number: <input type="phone" name="phone" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p class="hidden">
    <label>Don’t fill this out if you're an organic life form: <input name="beep-borp" /></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>