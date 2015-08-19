---
layout: page
title: Contact Us
permalink: /contact-us/
---

<div class="mere-row">
  <div class="mere-col  mere-col-half">
    <p>Please contact us for a <em>no obligation quote</em><br> using one of these methods:</p>
    <p>Phone: <a href="tel:{{ site.phoneint }}">{{ site.phone }}</a></p>
    <p>Mobile: <a href="tel:{{ site.mobileint }}">{{ site.mobile }}</a></p>
    <p>Email: <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
  </div>
  <div class="mere-col  mere-col-half">
    <form action="//formspree.io/ben@meredevelopment.co.uk" method="POST">  
      <input type="hidden" name="_next" value="{{ "thanks" | prepend: site.baseurl | prepend: site.url }}" />
      <input type="hidden" name="_subject" value="Contact Form - A P Cleaning Services" />
      <input type="hidden" name="_cc" value="ben@meredevelopment.co.uk" />
      <input type="text" name="Name" placeholder="Your Name"><br>
      <input type="email" name="_replyto" placeholder="Your Email Address"><br>
      <textarea name="message" placeholder="Your Message"></textarea>
      <input type="submit" value="Send">
    </form>
  </div>
</div>
<hr>
<div class="mere-row">
  <div class="mere-col  mere-col-half">
    <h3>Bristol Office</h3>
    Ashley Walsh<br>
    31 Blenheim Drive<br>
    Filton<br>
    Bristol<br>
    BS34 7AX<br>
  </div>
  <div class="mere-col  mere-col-half">
    <h3>Port Talbot Office</h3>
    Ashley Walsh<br>
    21 Graig-Y-Tewgoed<br>
    Cwmafan<br>
    Port Talbot<br>
    SA12 9YE
  </div>
</div>
<hr>
