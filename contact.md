---
layout: page
title: Contact Alistair
permalink: /contact/
---

<style>
#cunning {
visibility: hidden;
}
</style>

<form name="contact" method="POST" netlify-honeypot="beep-borp" data-netlify="true">
  <p>
    <label>Your name: <input type="text" name="name" required /></label>   
  </p>
  <p>
    <label>Your email address: <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Your phone number: <input type="number" name="phone" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p id="cunning">
    <label>Don’t fill this out if you're an organic life form: <input name="beep-borp" /></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>