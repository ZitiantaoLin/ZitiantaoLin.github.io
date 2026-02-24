---
layout: about
title: about
permalink: /
subtitle: Master of Science in Information Systems · Northeastern University
profile: false
nav: false
---

<div style="display:flex; gap:32px; align-items:flex-start; flex-wrap:wrap;">

  <!-- Left: image carousel -->
  <div style="width:260px;">
    <div style="position:relative; width:260px; height:260px; overflow:hidden; border-radius:16px;">
      <img id="carousel-img"
           src="/assets/img/ewfe(1).jpg"
           style="width:100%; height:100%; object-fit:cover; display:block;" />
      <button type="button" onclick="prevImg()"
              style="position:absolute; left:10px; top:50%; transform:translateY(-50%);
                     border:none; width:34px; height:34px; border-radius:50%;
                     background:rgba(0,0,0,0.45); color:white; font-size:18px; cursor:pointer;">
        ‹
      </button>
      <button type="button" onclick="nextImg()"
              style="position:absolute; right:10px; top:50%; transform:translateY(-50%);
                     border:none; width:34px; height:34px; border-radius:50%;
                     background:rgba(0,0,0,0.45); color:white; font-size:18px; cursor:pointer;">
        ›
      </button>
    </div>

    <!-- dots -->
    <div style="display:flex; justify-content:center; gap:10px; margin-top:10px;">
      <span id="dot-0" onclick="goImg(0)" style="width:8px; height:8px; border-radius:50%; background:#666; cursor:pointer;"></span>
      <span id="dot-1" onclick="goImg(1)" style="width:8px; height:8px; border-radius:50%; background:#bbb; cursor:pointer;"></span>
    </div>
  </div>

  <!-- Right: text -->
  <div style="flex:1; min-width:260px;">
    <h1 style="margin-top:0;">Zitiantao Lin</h1>
    <p>
      I am a Master's student in Information Systems at Northeastern University.
      My research focuses on <strong>human-robot interaction, gaze-guided manipulation, mixed reality</strong>, and <strong>tactile learning</strong>.
    </p>
    <p>
      I aim to pursue a PhD in Robotics and Intelligent Systems.
    </p>

    <h2>Research Interests</h2>
    <ul>
      <li>Gaze-guided robot manipulation & mixed reality</li>
      <li>Human-robot interaction (HRI)</li>
      <li>Multimodal learning and policy adaptation</li>
      <li>Tactile sensing and closed-loop control</li>
    </ul>
  </div>

</div>

<script>
  const imgs = [
    "/assets/img/ewfe(1).jpg",
    "/assets/img/PhD2.jpg"
  ];
  let idx = 0;

  function render() {
    const el = document.getElementById("carousel-img");
    if (!el) return;
    el.src = imgs[idx];
    for (let i = 0; i < imgs.length; i++) {
      const dot = document.getElementById("dot-" + i);
      if (dot) dot.style.background = (i === idx) ? "#666" : "#bbb";
    }
  }

  function prevImg() {
    idx = (idx - 1 + imgs.length) % imgs.length;
    render();
  }

  function nextImg() {
    idx = (idx + 1) % imgs.length;
    render();
  }

  function goImg(i) {
    idx = i;
    render();
  }

  render();
</script>
