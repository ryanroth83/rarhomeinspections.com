---
title: "Contact"
date: 2022-05-14T20:11:40-05:00
draft: false
---
<br>
<div>
  <div class="flex-contact">
    <div class="icon-contact icon-call">
      <a href="tel:+1 (832)933-1111">
        <i class="fa-solid fa-square-phone fa-4x"></i>
        <p>Call Me</p>
      </a>
    </div>
    <div class="icon-contact icon-sms">
      <a href="sms:+1 (832)933-1111">
        <i class="fa-regular fa-square-comment fa-4x"></i>
        <p>Text Me</p>
      </a>
    </div>
    <div class="icon-contact icon-whatsapp">
      <a href="https://wa.me/18329331111">
        <i class="fa-brands fa-whatsapp fa-4x"></i>
        <p>Whats App</p>
      </a>
    </div>
    <div class="icon-contact icon-email">
      <a href="mailto:ryan@rarhomeinspections.com">
        <i class="fa-regular fa-square-envelope fa-4x"></i>
        <p>Email Me</p>
      </a>
    </div>
    <div class="icon-contact icon-addme">
      <a href="/rarhomeinspections.vcf">
        <i class="fa-solid fa-address-card fa-4x"></i>
        <p>Add Me</p>
      </a>
    </div>
  </div>
</div>
<div class="container">
    <form action="https://formsubmit.co/ryan@rarhomeinspections.com" method="POST">
      <input type="hidden" name="_subject" value="Message from contact page.">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_template" value="box">
      <ul class="flex-outer">
        <h2 class="contact_text">Send Me A Message</h2>
        <li>
          <label for="name">Name</label>
          <input type="text" id="name" name="Name" placeholder="Enter your name here" required>
        </li>
        <li>
          <label for="email">Email</label>
          <input type="email" id="email" name="Email" placeholder="Enter your email here" required>
        </li>
        <li>
          <label for="phone">Phone</label>
          <input type="tel" id="phone" name="Phone" placeholder="Enter your phone here" required>
        </li>
        <li>
          <label for="message">Message</label>
          <textarea rows="6" id="message" name="Message" placeholder="Enter your message here" required></textarea>
        </li>
        <li>
          <label for="response">Response</label>
          <select name="response" style="cursor:pointer;" id="response" required>
          <option value="any">Any</option>
          <option value="call">Call</option>
          <option value="text">Text</option>
          <option value="email">Email</option>
          <option value="none">None</option>
        </li>
  </select>
        <li>
          <button style="cursor:pointer;" type="submit">Submit</button>
        </li>
      </ul>
    </form>
</div> 
<div>
  <a href="mailto:ryan@rarhomeinspections.com">
    <h4 class="contact_text">Email: ryan@rarhomeinspections.com</h4>
  </a>
  <a href="tel:+1 (832)933-1111">
    <h4 class="contact_text">Phone (Call/Text): 832-933-1111</h4>
  </a>
</div>