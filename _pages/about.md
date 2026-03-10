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
           src="/assets/img/PhD1.jpg"
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
          🔗 <a href="https://www.linkedin.com/in/zitiantao-lin/" target="_blank">LinkedIn</a>
        </p>

        <p style="margin:6px 0;">
          🎓 <a href="https://scholar.google.com/citations?user=IqmXvv8AAAAJ" target="_blank">Google Scholar</a>
        </p>

      </div>
    </div>

  </div>

  <!-- ================= RIGHT CONTENT ================= -->
  <div style="flex:1; min-width:280px;">

    <!-- ===== Intro / Contact ===== -->
    <h1 style="margin-top:0;"></h1>

    <p>
      I am currently pursuing a Master of Science in Information Systems at Northeastern University, where I serve as a Graduate Research Assistant in the CRAFT Lab under the supervision of Prof. Gilbert Yang Ye.

      My research focuses on the intersection of Human–Computer Interaction (HCI), contactless human interaction sensing, eye tracking, and Computer Vision. I am particularly interested in AI-driven context-aware interaction, integrating eye-gaze tracking and dynamic motion tracking to enable more intuitive and natural collaboration between humans and robotic systems.

      Recently, my research has centered on incorporating human intention signals, obtained through eye-gaze input, into robotic manipulation policies. My work on MR-enabled eye-gaze interaction, RaycastGrasp, received the Best Paper Award at ICIR 2025.
    </p>

    <p style="margin-top:12px;">
      <a href="mailto:lin.ziti@northeastern.edu">Email</a>
      &nbsp;/&nbsp;
      <a href="https://www.linkedin.com/in/zitiantao-lin/" target="_blank">LinkedIn</a>
      &nbsp;/&nbsp;
      <a href="https://scholar.google.com/citations?user=IqmXvv8AAAAJ" target="_blank">Google Scholar</a>
      &nbsp;/&nbsp;
      <a href="https://github.com/ZitiantaoLin" target="_blank">GitHub</a>
    </p>

    <!-- ===== Research Interests ===== -->
    <h2 style="margin-top:28px;">Research Interests</h2>
    <hr style="margin:10px 0 14px 0; opacity:0.25;">
    <ul>
      <li><strong>Human-Robot Interaction (HRI):</strong> Developing intuitive interaction paradigms for assistive robotics and embodied agents using multimodal inputs.</li>
      <li><strong>Eye-Gaze & Situated Interaction:</strong> Leveraging wearable eye-tracking and mixed reality (MR) to model human intention and enhance spatial awareness.</li>
      <li><strong>Embodied AI & Perception:</strong> Integrating Computer Vision and Transformer-based models for calibration-free depth generation and semantic understanding.</li>
      <li><strong>Intelligent Interactive Systems:</strong> Designing robust, end-to-end systems that bridge human-centric sensing with real-time robotic control and planning.</li>
    </ul>

    <!-- ===== News ===== -->
    <h2 style="margin-top:28px;">News</h2>
    <hr style="margin:10px 0 14px 0; opacity:0.25;">
    <div>

    </div>

    <!-- ===== Selected Publications ===== -->
    <h2 style="margin-top:28px;">Selected Publications</h2>
    <hr style="margin:10px 0 14px 0; opacity:0.25;">

    <div style="display:flex; flex-direction:column; gap:22px;">

      <div style="display:flex; gap:18px; align-items:flex-start; flex-wrap:wrap; margin-bottom: 30px;">
        <div style="flex:1; min-width:280px;">
          <div style="font-weight:700; font-size:18px; line-height:1.25;">
            GGC-Trans: Gaze-Guided Cross-View Transformer for Calibration-Free Depth Generation
          </div>
          
          <div style="margin-top:8px; opacity:0.9;">
            <strong>Zitiantao Lin</strong>, Handan Liu, Yang Ye
          </div>
          
          <div style="margin-top:6px; opacity:0.75; font-style:italic;">
            Under Review, 2026
          </div>

          <div style="margin-top:10px; display:flex; gap:10px; flex-wrap:wrap;">
            <span style="display:inline-block; padding:4px 10px; border-radius:6px; 
                         background:rgba(0,123,255,0.1); color:#007bff; font-size:13px; font-weight:600; border:1px solid rgba(0,123,255,0.2);">
              Independent First Author
            </span>
          </div>
          
          <div style="margin-top:12px; font-size:14.5px; line-height:1.5; opacity:0.85;">
            Developing a Transformer-based architecture that bridges egocentric semantic features with exocentric spatial coordinates. 
            The system leverages cross-attention and gaze heatmaps as attentional priors to enable calibration-free depth generation and object localization in cluttered scenes.
          </div>
        </div>

        <div style="width:240px; flex:0 0 240px;">
          <img src="/assets/img/pubs/ggctrans_preview.png" 
               alt=""
               style="width:240px; height:150px; object-fit:cover; border-radius:10px;
                      border:1px solid rgba(0,0,0,0.18);" />
        </div>
      </div>

      <!-- Pub Item 1 -->
      <div style="display:flex; gap:18px; align-items:flex-start; flex-wrap:wrap;">
        <div style="flex:1; min-width:280px;">
          <div style="font-weight:700; font-size:18px; line-height:1.25;">
            BEAR: Benchmarking and Enhancing Multimodal Language Models for Atomic Embodied Capabilities
          </div>
          
          <div style="margin-top:8px; opacity:0.9;">
            Yu Qi, Haibo Zhao, Ziyu Guo, Siyuan Ma, Ziyan Chen, Yaokun Han, Renrui Zhang, <strong>Zitiantao Lin</strong>, Shiji Xin, Yijian Huang, Kai Cheng, Peiheng Wang, Jiazheng Liu, Jiayi Zhang, Yizhe Zhu, Wenqing Wang, Yiran Qin, Xupeng Zhu, Haojie Huang, Lawson L.S. Wong
          </div>
          
          <div style="margin-top:6px; opacity:0.75; font-style:italic;">
            Under Review, 2026
          </div>

          <div style="margin-top:10px; display:flex; gap:10px; flex-wrap:wrap;">
            <a href="https://bear-official66.github.io/" target="_blank"
               style="display:inline-block; padding:6px 12px; border-radius:8px;
                      background:rgba(255,255,255,0.15); border:1px solid rgba(0,0,0,0.25);
                      text-decoration:none;">
              Project
            </a>
            <a href="https://arxiv.org/pdf/2510.08759" target="_blank"
               style="display:inline-block; padding:6px 12px; border-radius:8px;
                      background:rgba(255,255,255,0.15); border:1px solid rgba(0,0,0,0.25);
                      text-decoration:none;">
              PDF
            </a>
          </div>
        </div>

        <div style="width:240px; flex:0 0 240px;">
          <a href="https://bear-official66.github.io/" target="_blank" style="text-decoration:none;">
            <img src="/assets/img/BEAR.png" 
                 alt="BEAR Project Preview"
                 style="width:240px; height:150px; object-fit:cover; border-radius:10px;
                        border:1px solid rgba(0,0,0,0.18);" />
          </a>
        </div>
      </div>

      <!-- Pub Item 2 -->
      <div style="display:flex; gap:18px; align-items:flex-start; flex-wrap:wrap;">
        <div style="flex:1; min-width:280px;">
          <div style="font-weight:700; font-size:18px; line-height:1.25;">
            GazeCastGrasp: MR-Enabled Eye-Gaze Interaction for Assistive Robotic Manipulation
          </div>
          
          <div style="margin-top:8px; opacity:0.9;">
            <strong>Zitiantao Lin*</strong>, Yongpeng Sang*, Xiao Hu, Yang Ye†
          </div>
          
          <div style="margin-top:6px; opacity:0.75; font-style:italic;">
            Under Review, 2025
          </div>

          <div style="margin-top:10px; display:flex; gap:10px; flex-wrap:wrap;">
            <a href="#" target="_blank"
               style="display:inline-block; padding:6px 12px; border-radius:8px;
                      background:rgba(255,255,255,0.15); border:1px solid rgba(0,0,0,0.25);
                      text-decoration:none;">
              Demo Video
            </a>
          </div>
        </div>

        <div style="width:240px; flex:0 0 240px;">
          <img src="/assets/img/pubs/gazecastgrasp_preview.png" 
               alt="GazeCastGrasp System Interface"
               style="width:240px; height:150px; object-fit:cover; border-radius:10px;
                      border:1px solid rgba(0,0,0,0.18);" />
        </div>
      </div>

      <!-- Pub Item 3 -->
      <div style="display:flex; gap:18px; align-items:flex-start; flex-wrap:wrap;">
        <div style="flex:1; min-width:280px;">
          <div style="font-weight:700; font-size:18px; line-height:1.25;">
            RaycastGrasp: Eye-Gaze Interaction with Wearable Devices for Robotic Manipulation
          </div>
          
          <div style="margin-top:8px;">
            <span style="background: rgba(255, 215, 0, 0.2); color: #b8860b; padding: 3px 8px; border-radius: 6px; font-size: 13px; font-weight: 700; border: 1px solid rgba(184, 134, 11, 0.3);">
              🏆 Best Paper Award
            </span>
          </div>

          <div style="margin-top:8px; opacity:0.9;">
            <strong>Zitiantao Lin*</strong>, Yongpeng Sang*, Yang Ye
          </div>
          <div style="margin-top:6px; opacity:0.75; font-style:italic;">
            IEEE 4th International Conference on Intelligent Reality (ICIR), 2025
          </div>

          <div style="margin-top:10px; display:flex; gap:10px; flex-wrap:wrap;">
            <a href="https://github.com/ZitiantaoLin/RaycastGrasp-Eye-Gaze-Interaction-with-Wearable-Devices-for-Robotic-Manipulation" target="_blank"
               style="display:inline-block; padding:6px 12px; border-radius:8px;
                      background:rgba(255,255,255,0.15); border:1px solid rgba(0,0,0,0.25);
                      text-decoration:none;">
              Project / Code
            </a>
            <a href="https://arxiv.org/abs/2510.22113" target="_blank"
               style="display:inline-block; padding:6px 12px; border-radius:8px;
                      background:rgba(255,255,255,0.15); border:1px solid rgba(0,0,0,0.25);
                      text-decoration:none;">
              PDF
            </a>
          </div>
        </div>

        <div style="width:240px; flex:0 0 240px;">
          <a href="https://github.com/ZitiantaoLin/RaycastGrasp-Eye-Gaze-Interaction-with-Wearable-Devices-for-Robotic-Manipulation" target="_blank" style="text-decoration:none;">
            <img src="/assets/img/pubs/paper3.gif" 
                 alt="RaycastGrasp System Demo"
                 style="width:240px; height:150px; object-fit:cover; border-radius:10px;
                        border:1px solid rgba(0,0,0,0.18);" />
          </a>
        </div>
      </div>

        <div style="width:240px; flex:0 0 240px;">
          <a href="https://arxiv.org/abs/2510.22113" target="_blank" style="text-decoration:none;">
            <img src="/assets/img/pubs/paper3.gif" 
                 alt="RaycastGrasp System Demo"
                 style="width:240px; height:150px; object-fit:cover; border-radius:10px;
                        border:1px solid rgba(0,0,0,0.18);" />
          </a>
        </div>
      </div>

    </div>

  </div>

</div>

<script>
  const imgs = [
    "/assets/img/PhD1.jpg",
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
