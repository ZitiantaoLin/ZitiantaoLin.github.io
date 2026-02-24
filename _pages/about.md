---
layout: about
title: about
permalink: /
subtitle: Master of Science in Information Systems · Northeastern University
profile: false
nav: false
---

<div style="display:flex; gap:48px; align-items:flex-start; flex-wrap:wrap;">

  <!-- ================= LEFT SIDEBAR ================= -->
  <div style="width:280px;">

    <!-- Image Carousel -->
    <div style="position:relative; width:280px; height:280px; overflow:hidden; border-radius:16px;">
      <img id="carousel-img"
           src="/assets/img/ewfe(1).jpg"
           style="width:100%; height:100%; object-fit:cover; display:block;" />

      <button type="button" onclick="prevImg()"
              style="position:absolute; left:12px; top:50%; transform:translateY(-50%);
                     border:none; width:36px; height:36px; border-radius:50%;
                     background:rgba(0,0,0,0.45); color:white; font-size:18px; cursor:pointer;">
        ‹
      </button>

      <button type="button" onclick="nextImg()"
              style="position:absolute; right:12px; top:50%; transform:translateY(-50%);
                     border:none; width:36px; height:36px; border-radius:50%;
                     background:rgba(0,0,0,0.45); color:white; font-size:18px; cursor:pointer;">
        ›
      </button>
    </div>

    <!-- Dots -->
    <div style="display:flex; justify-content:center; gap:10px; margin-top:12px;">
      <span id="dot-0" onclick="goImg(0)" style="width:8px; height:8px; border-radius:50%; background:#666; cursor:pointer;"></span>
      <span id="dot-1" onclick="goImg(1)" style="width:8px; height:8px; border-radius:50%; background:#bbb; cursor:pointer;"></span>
    </div>

    <!-- Profile Info -->
    <div style="margin-top:28px; font-size:15px; line-height:1.9;">
      <p style="font-weight:600; font-size:18px; margin-bottom:4px;">
        Zitiantao Lin
      </p>

      <p style="margin:0; color:#666;">
        Master at Northeastern University
      </p>

      <div style="margin-top:18px;">

        <p style="margin:6px 0;">
          📍 Boston, Massachusetts
        </p>

        <p style="margin:6px 0;">
          🏛 Northeastern University
        </p>

        <p style="margin:6px 0;">
          ✉ <a href="mailto:lin.ziti@northeastern.edu">lin.ziti@northeastern.edu</a>
        </p>

        <p style="margin:6px 0;">
          🔗 <a href="[https://www.linkedin.com/in/zitiantao-lin/]" target="_blank">LinkedIn</a>
        </p>

        <p style="margin:6px 0;">
          🎓 <a href="https://scholar.google.com/" target="_blank">Google Scholar</a>
        </p>

      </div>
    </div>

  </div>

  <!-- ================= RIGHT CONTENT ================= -->
  <div style="flex:1; min-width:280px;">

    <h1 style="margin-top:0;">Zitiantao Lin</h1>

    <p>
      I am a Master's student in Information Systems at Northeastern University.
      My research focuses on <strong>human-robot interaction, gaze-guided manipulation, mixed reality systems, and tactile learning</strong>.
    </p>

    <p>
      Currently, I work on gaze-driven robotic grasping systems integrating eye-tracking,
      YOLO-based object detection, and robotic manipulation.
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
    "/assets/img/profile1.jpg",
    "/assets/img/profile2.jpg"
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
