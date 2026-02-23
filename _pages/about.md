---
layout: about
title: about
permalink: /
subtitle: Master of Science in Information Systems · Northeastern University
profile: false
---

<div style="display:flex; gap:32px; align-items:flex-start; flex-wrap:wrap;">

  <!-- Left: image carousel -->
  <div style="width:260px;">
    <div style="position:relative; width:260px; height:260px; overflow:hidden; border-radius:16px;">
      <img id="carousel-img"
           src="/assets/img/ewfe(1).jpg"
           style="width:100%; height:100%; object-fit:cover; display:block;" />
      <button onclick="prevImg()"
              style="position:absolute; left:10px; top:50%; transform:translateY(-50%);
                     border:none; width:34px; height:34px; border-radius:50%;
                     background:rgba(0,0,0,0.45); color:white; font-size:18px; cursor:pointer;">
        ‹
      </button>
      <button onclick="nextImg()"
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
      My research focuses on human-robot interaction, gaze-guided manipulation, mixed reality, and tactile learning.
    </p>
    <p>
      I aim to pursue a PhD in Robotics and Intelligent Systems.
    </p>
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

  // optional auto-play (uncomment if you want)
  // setInterval(nextImg, 5000);

  render();
</script>




selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Master's student in Information Systems at Northeastern University. 
My research focuses on **human-robot interaction, gaze-guided manipulation, mixed reality systems, and tactile learning**.

Currently, I work on gaze-driven robotic grasping systems that integrate eye-tracking, YOLO object detection, and robotic manipulation. 
I am also interested in equivariant learning and multimodal policy adaptation under perturbations.

My long-term goal is to develop intelligent robotic systems that bridge perception, interaction, and physical reasoning.



Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
