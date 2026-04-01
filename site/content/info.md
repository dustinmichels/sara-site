---
title: "ABOUT ME"
---

<div class="info-columns">
  <div class="info-bio">
    <p>I am Postdoctoral Scientist in Douglas Rasher's Lab at the Bigelow Laboratory for Ocean Sciences.
    I use concepts from community ecology to understand how coral reef organisms, from microbes to fish, are shaped by their ever-changing environments. I strive to conduct research that helps inform marine conservation and restoration.</p>
  </div>
  <div class="info-contact">
    <p><strong>CONTACT ME</strong></p>
    <p>
      email: <button id="email-btn" onclick="revealEmail()" class="reveal-btn">[show]</button><span id="email-display"></span><br>
      twitter: <a href="https://twitter.com/SaraSwaminathan">@SaraSwaminathan</a><br>
      github: <a href="https://github.com/saraswaminathan">saraswaminathan</a>
    </p>
  </div>
</div>

<script>
function revealEmail() {
  const email = atob("c3N3YW1pbmF0aGFuQGJpZ2Vsb3cub3Jn");
  const el = document.getElementById('email-display');
  el.innerHTML = '<a href="mailto:' + email + '">' + email + '</a>';
  document.getElementById('email-btn').style.display = 'none';
}
</script>

{{< gallery >}}
<img src="/images/sara_boat.jpeg" alt="">
<img src="/images/sara_science.png" alt="">
<img src="/images/sara_dive2.JPG" alt="">
<img src="/images/sara_beach.jpg" alt="">
<img src="/images/sara_boat2.jpeg" alt="">
<img src="/images/sara_bug.jpeg" alt="">
<img src="/images/sara_event.jpeg" alt="">
<img src="/images/sara_dive.jpg" alt="">
<img src="/images/sara_present.jpeg" alt="">
<img src="/images/sara_mermaid.jpg" alt="">
<img src="/images/sara_sea.JPG" alt="">
<img src="/images/sara_coral.JPG" alt="">
{{< /gallery >}}
