---
title: "Contact"
description: "Contact me"
ShowBreadCrumbs: false
---

# Contact Me
You wanna talk to me?
![*blushes*](https://pub.jshmnrd.ca/w/img/0002-Blush260.jpg)

You can contact me via email, <a href="#" onClick="alert('no spam please!')">hello[at]jshmnrd.ca</a>.<br>Also be sure to sign my guestbook to leave your mark!

## Guestbook

<!-- Guestbook Script -->
<script async src="https://guestbooks.meadow.cafe/resources/js/embed_script/6265/script.js"></script>
<style>
.guestbooks___input-container {
  border: 1px solid var(--border);
  background: var(--entry);
  margin: 0px 0px 10px 10px;
  padding: 2px 5px 2px 5px;
  color: red;
}
</style>
<!-- Guestbook Form -->
<div id="guestbooks___guestbook-form-container">
  <form id="guestbooks___guestbook-form" 
        action="https://guestbooks.meadow.cafe/guestbook/6265/submit" 
        method="post">
    <div class="guestbooks___input-container">
      <input type="text" 
             id="name" 
             name="name" 
             placeholder="Your Name" 
             required>
    </div>
    <div class="guestbooks___input-container">
      <input type="url" 
             id="website" 
             name="website" 
             placeholder="Website (optional)">
    </div>
    <div id="guestbooks___challenge-answer-container"></div>
    <div class="guestbooks___input-container">
      <textarea id="text" 
                name="text" 
                placeholder="Leave your message here..." 
                rows="4"
                style="width: 100%; box-sizing: border-box; resize: vertical;"
                required></textarea>
    </div>
    <div id="guestbooks___pow-status"></div>
    <button class="button" type="submit">Sign Guestbook</button>
    <div id="guestbooks___error-message"></div>
  </form>
</div>
<!-- Attribution (optional but appreciated!) -->
<div id="guestbooks___guestbook-made-with" style="text-align: right; margin-top: 10px;">
  <small>Powered by <a href="https://guestbooks.meadow.cafe" target="_blank">Guestbooks</a></small>
</div>
<!-- Messages Section -->
<hr style="margin: 2em 0;"/>
<h3 id="guestbooks___guestbook-messages-header">Messages</h3>
<div id="guestbooks___guestbook-messages-container"></div>