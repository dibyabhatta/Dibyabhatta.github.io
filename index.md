---
layout: default
title: Home
---

<header>
    <img src="profile.jpg" alt="Dibya Bhatta">
    <h1>Dibya Bhatta</h1>
    <p>PhD Candidate | Solomon Lab, Australian National University</p>
</header>

<!-- Tabs -->
<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Home')">Home</button>
  <button class="tablinks" onclick="openTab(event, 'Research')">Research</button>
  <button class="tablinks" onclick="openTab(event, 'Publications')">Publications</button>
  <button class="tablinks" onclick="openTab(event, 'CV')">CV</button>
  <button class="tablinks" onclick="openTab(event, 'Contact')">Contact</button>
  <button class="tablinks" onclick="openTab(event, 'ScholarshipHub')">Scholarship Hub</button>
</div>

<div id="Home" class="tabcontent" style="display:block;">
  <h2>About Me</h2>
  <p>I am a PhD candidate at Solomon Lab, The Australian National University. My PhD research focuses on the mechanistic basis of the interaction between <em>Zymoseptoria tritici</em> and wheat.</p>
  <p>YouTube series: <strong>"Candid with Candidates"</strong> with PhD friends globally: <a href="https://www.youtube.com/@Agri_dibu" target="_blank"><i class="fa-brands fa-youtube"></i> youtube.com/agri_dibu</a></p>
</div>

<div id="Research" class="tabcontent">
  <h2>Research Interests</h2>
  <ul>
    <li>Zymoseptoria–wheat Interaction</li>
    <li>Plant Stress Physiology</li>
    <li>Plant–Microbe Interaction</li>
    <li>Bioremediation of heavy metals using PGPR</li>
  </ul>
</div>

<div id="Publications" class="tabcontent">
  <h2>Publications</h2>
  <p>Bhatta et al., 2023, "Hormones and the antioxidant transduction pathway..."  
    <a href="https://doi.org/10.1016/j.ecoenv.2023.115377" target="_blank">View DOI</a></p>
  <p>More papers: <a href="https://scholar.google.com/citations?hl=ko&user=c-z-tTIAAAAJ" target="_blank"><i class="fa-brands fa-google"></i> Google Scholar</a></p>
</div>

<div id="CV" class="tabcontent">
  <h2>CV</h2>
  <img src="profile.jpg" alt="Dibya Bhatta" class="cv-photo">

  <!-- Education, Work Experience, Skills, Languages, Scholarships same as your previous content -->
  {% include cv_content.html %}
</div>

<div id="Contact" class="tabcontent">
  <h2>Contact</h2>
  <p><i class="fa-solid fa-envelope"></i> Email: <a href="mailto:dibya.bhatta@anu.edu.au">dibya.bhatta@anu.edu.au</a></p>
  <p><i class="fa-brands fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/agridibu/" target="_blank">Profile</a></p>
  <p><i class="fa-brands fa-twitter"></i> Twitter: <a href="https://X.com/agri_dibu" target="_blank">@agri_dibu</a></p>
</div>

<div id="ScholarshipHub" class="tabcontent">
  <h2>Scholarship Hub</h2>
  <p>Daily scholarship opportunities from around the world, curated for students and researchers. You can update this section regularly using posts in `_posts/` if you convert this to full Jekyll blog later.</p>
</div>
