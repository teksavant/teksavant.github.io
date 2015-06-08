---
layout: default
title: Contact Amarjeet
---

<div id="contact">
  <h1 class="pageTitle">Contact Me</h1>
  <div class="contactContent">
    <p class="intro">If you like my work and would like to work with me or have any questions, then don't hesitate to contact me.</p>
    <p>Please only use phone contact for urgent inquiries. Otherwise, Twitter and email are best ways to reach me.</p>
    <p><ul style="list-style-type: none;">
          <li>call: <a href="tel:+91-99713762229">+91-9971376229</a></li>
          <li>twitter: <a href="http://twitter.com/intent/tweet?screen_name=amarjeetsingh53">@amarjeetsingh53</a></li>
    </ul></p>
  </div>
  <form action="http://formspree.io/{{ site.social.email }}" method="POST">
    <label for="name">Name</label>    
    <input type="text" id="name" name="name" class="full-width"><br>
    <label for="email">Email Address</label>
    <input type="email" id="email" name="_replyto" class="full-width"><br>
    <label for="message">Message</label>
    <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Send" class="button">
  </form>
</div>