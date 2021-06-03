---
layout: layouts/standard.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 3
---

<h2 class="mt-4">Send Me a Message</h2>
<form class="mb-4 p-2 border" name="contact" method="POST" netlify-honeypot="bot-field" data-netlify="true" >
  <p class="d-none">
    <label>Don’t fill this out if you’re human: <input name="bot-field" /></label>
  </p>
  <p class="mb-3">
    <label class="form-label d-block">Your Name: <input type="text" name="name" class="form-control d-block" required="required" maxlength="50"/></label>   
  </p>
  <p class="mb-3">
    <label class="form-label d-block">Your Email: <input type="email" name="email" class="form-control d-block" required="required"/></label>
  </p>
  <p class="mb-3">
    <label class="form-label">Your Role: <select name="role[]" multiple class="form-control" required="required">
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p class="mb-3 d-block">
    <label class="form-label d-block">Message: <textarea name="message" class="form-control" required="required" maxlength="1000"></textarea></label>
  </p>
  <p class="mb-3">
    <button type="submit" class="btn btn-primary mx-auto d-block">Send</button>
  </p>
</form>