---
title: "Contact"
date: 2022-05-14T20:11:40-05:00
draft: false
---
<br>
<div>
  <div class="flex-contact">
    <div>
      <a href="tel:+1 (832)933-1111">
        <i class="fa-solid fa-phone fa-5x" style="color:green;"></i>
        <p>Call Me</p>
      </a>
    </div>
    <div>
      <a href="sms:+1 (832)933-1111">
        <i class="fa-solid fa-comment-sms fa-5x" style="color:blue;"></i>
        <p>Text Me</p>
      </a>
    </div>
    <div>
      <a href="mailto:ryan@rarhomeinspections.com">
        <i class="fa-solid fa-at fa-5x" style="color:white"></i>
        <p>Email Me</p>
      </a>
    </div>
    <div>
      <a href="/rarhomeinspections.vcf">
        <i class="fa-solid fa-address-card fa-5x" style="color:grey"></i>
        <p>Add Me</p>
      </a>
    </div>
  </div>
</div>


<h2 class="flex-inner">SEND A MESSAGE</h2>
<div class="container">
    <form action="https://formsubmit.co/ryan@rarhomeinspections.com" method="POST">
      <ul class="flex-outer">
        <li>
          <label for="name">Name</label>
          <input type="text" id="name" name="Name" placeholder="Enter your name here">
        </li>
        <li>
          <label for="email">Email</label>
          <input type="email" id="email" name="Email" placeholder="Enter your email here">
        </li>
        <li>
          <label for="phone">Phone</label>
          <input type="tel" id="phone" name="Phone" placeholder="Enter your phone here">
        </li>
        <li>
          <label for="message">Message</label>
          <textarea rows="6" id="message" name="Message" placeholder="Enter your message here"></textarea>
        </li>
        <li>
          <label for="prefferd">Prefferd Contact Method:</label>
          <select name="Prefferd" id="prefferd">
          <option value="any">Any</option>
          <option value="call">Call</option>
          <option value="text">Text</option>
          <option value="email">Email</option>
        </li>
  </select>
        <li>
          <button type="submit">Submit</button>
        </li>
      </ul>
    </form>
</div> 