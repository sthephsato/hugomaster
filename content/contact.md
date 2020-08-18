---
title: 'Contact Us'
date: 2018-02-22T17:01:34+07:00
layout: contact
menu: 'main'
---

<h2>Contact Us or Ask us a Question</h2>
<form name="contact" method="POST" data-netlify="true">
  <div class="form-group">
    <label for="nameInput">Name</label>
    <input type="text" name="name" class="form-control" id="nameInput" placeholder="Enter name">
  </div>
  <div class="form-group">
    <label for="inputEmail1">Email </label>
    <input type="email" name="email"  class="form-control" id="inputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="messageInput">Your Message or Question:</label>
    <textarea class="form-control" id="messageInput" rows="3" name = "message"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
