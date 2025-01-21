---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!--
<div style="text-align: justify;">
    <ul>
        <li>I am currently an Assistant Professor in the Department of Computing at the Hong Kong Polytechnic University (PolyU).</li>
        <li>I received my Ph.D. degree in Computer Engineering from Stony Brook University, where I had the privilege of working under the guidance of Prof. <a href="http://www.ece.sunysb.edu/~yang/">Yuanyuan Yang</a>. Prior to that, I earned a Bachelor's degree in Telecommunications Engineering from Xidian University, Xi'an, China.</li>
        <li>My research interests include edge computing and networks, edge AI, LEO satellite networks, and distributed quantum computing.</li>
    </ul>
</div>


<br />


News
=====
<div style="text-align: justify;">
    <ul>
        <li><strong>[12/2024]</strong> I am actively recruiting highly motivated Ph.D. students. If you are interested in joining my research group, please send your CV and academic transcripts to my email: <a href="mailto:yu-y.liu@polyu.edu.hk">yu-y.liu@polyu.edu.hk</a>.</li>
    </ul>
</div>
-->



<div style="margin-top: 2rem; display: flex; flex-direction: column; gap: 2rem;">
  <div style="display: flex; gap: 2rem; align-items: flex-start;">
    <img
      src="images/yuliu3.jpg"
      alt="Yu Liu"
      style="object-fit: cover; border-radius: 0.5rem; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); height: auto;"
      id="profile-image"
    />
    
    <div style="color: #4B5563; display: flex; flex-direction: column; gap: 1.5rem;" id="position-section">
      <div>
        <h3 style="font-weight: bold; color: #1F2937; margin-bottom: 0.5rem;">Position</h3>
        <p>Assistant Professor</p>
        <p>Department of Computing</p>
        <p>Hong Kong Polytechnic University</p>
      </div>

      <div>
        <h3 style="font-weight: bold; color: #1F2937; margin-bottom: 0.5rem;">Email</h3>
        <a href="mailto:yu-y.liu@polyu.edu.hk" 
           style="color: #2563EB; text-decoration: none; display: flex; align-items: center; gap: 0.5rem;"
           onmouseover="this.style.color='#1D4ED8';" 
           onmouseout="this.style.color='#2563EB';">
          <svg style="width: 1rem; height: 1rem;" viewBox="0 0 24 24"></svg>
          yu-y.liu@polyu.edu.hk
        </a>
      </div>
    </div>
  </div>
</div>

<script>
  // JavaScript to dynamically set the image height to match the "Position" section
  window.addEventListener('load', () => {
    const image = document.getElementById('profile-image');
    const positionSection = document.getElementById('position-section');
    image.style.height = `${positionSection.offsetHeight}px`;
  });

  window.addEventListener('resize', () => {
    const image = document.getElementById('profile-image');
    const positionSection = document.getElementById('position-section');
    image.style.height = `${positionSection.offsetHeight}px`;
  });
</script>

