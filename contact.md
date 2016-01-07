---
layout: page
title: Contact
permalink: /contact/
feature-img: "img/color.png"
---

<form action="https://getsimpleform.com/messages?form_api_token=352aab0a053514dbcdcf7d2d0b69857d" method="post">
  <input type='hidden' name='redirect_to' value='http://cobunny.com/thank-you' />
  <input type='text' name='name' placeholder='Your Full Name'  onblur="javascript:validateInline function(input.value) {
  if(input.value.trim().length == 0) return false;
  }"/>
  <input type='email' name='email' placeholder='Your E-mail Address' />
  <textarea name='message' placeholder='Write your message ...' onblur="javascript:validateInline function(input.value) {
  if(input.value.trim().length == 0 || input.value.trim().length > 30) return false;
  }"></textarea>
  <input type='submit' value='Send Message'/>
</form>