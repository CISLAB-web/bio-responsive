---
title: Research
date: 2025-08-25
type: landing

sections:
  - block: hero
    content:
      title: Research Areas
      text: |
        The **Computational Interactive System (CIS) Laboratory** at Dankook University conducts cutting-edge research in accessible AI technologies—covering **assistive robotics**, **sign language generation**, **computer vision**, and **generative models**—to enhance human–computer interaction and improve accessibility for people with disabilities.
      image:
        filename: /research/research.png
    design:
      background:
        color: '#000000'
        text_color_light: true   # ✅ 让文字变成白色
      image:
        placement: right
        size: contain   # 或 cover****

  - block: markdown
    content:
      title: Our Focus
      text: |
        <!--
          Images below use the public path /media/research/...
          Put your files in `/static/media/research/`:
            assistive_robotics.jpg
            sign_language_generation.jpg
            computer_vision.jpg
            generative_models.jpg
            accessible_ai.jpg
        -->

        <div class="container-xxl">

          <!-- Assistive Robotics -->
          <div class="row align-items-center g-4 my-5">
            <div class="col-md-5">
              <img src="assistive.jpg" class="img-fluid rounded shadow-sm" alt="Assistive Robotics">
            </div>
            <div class="col-md-7">
              <h3 class="mb-2">Assistive Robotics</h3>
              <p class="lead mb-2">Intelligent robots that support people with disabilities in daily life.</p>
              <ul class="mb-2">
                <li>Human–robot interaction and intent inference</li>
                <li>Adaptive control and safe physical assistance</li>
                <li>On-device perception and personalization</li>
              </ul>
              <p class="mb-0"><em>Goal:</em> deliver reliable, privacy-aware assistance in homes, clinics, and public spaces.</p>
            </div>
          </div>

          <!-- Sign Language Generation (alternate layout) -->
          <div class="row align-items-center g-4 my-5 flex-md-row-reverse">
            <div class="col-md-5">
              <img src="assistive.jpg" class="img-fluid rounded shadow-sm" alt="Sign Language Generation">
            </div>
            <div class="col-md-7">
              <h3 class="mb-2">Sign Language Generation</h3>
              <p class="lead mb-2">Text/speech-to-sign pipelines with diffusion and VQ-based models.</p>
              <ul class="mb-2">
                <li>NLP ↔ CV bridging, gloss-to-pose generation</li>
                <li>3D hand/body models (e.g., MANO) and kinematic constraints</li>
                <li>Real-time rendering and evaluation with Deaf/HoH user studies</li>
              </ul>
              <p class="mb-0"><em>Goal:</em> inclusive, low-latency communication tools.</p>
            </div>
          </div>

          <!-- Computer Vision -->
          <div class="row align-items-center g-4 my-5">
            <div class="col-md-5">
              <img src="assistive.jpg" class="img-fluid rounded shadow-sm" alt="Computer Vision">
            </div>
            <div class="col-md-7">
              <h3 class="mb-2">Computer Vision</h3>
              <p class="lead mb-2">Human-centered perception under real-world constraints.</p>
              <ul class="mb-2">
                <li>Facial skin analysis and structure-aware segmentation</li>
                <li>3D hand/pose reconstruction, multi-view fusion</li>
                <li>Robustness, uncertainty, and fairness in deployment</li>
              </ul>
              <p class="mb-0"><em>Goal:</em> dependable perception for interactive systems.</p>
            </div>
          </div>

          <!-- Generative Models (alternate layout) -->
          <div class="row align-items-center g-4 my-5 flex-md-row-reverse">
            <div class="col-md-5">
              <img src="assistive.jpg" class="img-fluid rounded shadow-sm" alt="Generative Models">
            </div>
            <div class="col-md-7">
              <h3 class="mb-2">Generative Models</h3>
              <p class="lead mb-2">Diffusion, GAN, and autoregressive modeling for controllable synthesis.</p>
              <ul class="mb-2">
                <li>Controllable sign-pose generation and animation</li>
                <li>Structure-aware medical/skin imaging and augmentation</li>
                <li>Personalized content with safety/consent mechanisms</li>
              </ul>
              <p class="mb-0"><em>Goal:</em> creation tools that respect constraints and user intent.</p>
            </div>
          </div>

          <!-- Accessible AI & HCI -->
          <div class="row align-items-center g-4 my-5">
            <div class="col-md-5">
              <img src="assistive.jpg" class="img-fluid rounded shadow-sm" alt="Accessible AI & HCI">
            </div>
            <div class="col-md-7">
              <h3 class="mb-2">Accessible AI & HCI</h3>
              <p class="lead mb-2">Designing end-to-end accessible systems with user-centered evaluation.</p>
              <ul class="mb-2">
                <li>Task-oriented dialog, multi-agent orchestration</li>
                <li>Privacy, security, and ethical guidelines in-the-loop</li>
                <li>Longitudinal studies with diverse user groups</li>
              </ul>
              <p class="mb-0"><em>Goal:</em> measurable improvements in accessibility and quality of life.</p>
            </div>
          </div>

        </div>

    design:
      columns: '1'
---
