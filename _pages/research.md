---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-intro {
  margin-bottom: 2.5rem;
  color: #666;
  font-size: 0.95em;
  line-height: 1.65;
}

.research-header {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 2rem 0 1.3rem;
}

.research-header span {
  color: #999;
  font-size: 0.72em;
  font-weight: 600;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  white-space: nowrap;
}

.research-header::after {
  content: "";
  flex: 1;
  height: 1px;
  background: #e5e5e5;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.4rem;
}

.research-card {
  overflow: hidden;
  background: #fff;
  border: 1px solid #e5e5e5;
  border-radius: 5px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.research-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
}

.research-image {
  width: 100%;
  height: 210px;
  overflow: hidden;
  background: #f8f8f8;
}

.research-image img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  display: block;
}

.research-content {
  padding: 1.2rem 1.25rem 1.35rem;
}

.research-topic {
  margin-bottom: 0.45rem;
  color: #999;
  font-size: 0.67em;
  font-weight: 600;
  letter-spacing: 0.09em;
  text-transform: uppercase;
}

.research-title {
  margin: 0 0 0.7rem;
  font-size: 1.07em;
  font-weight: 600;
  line-height: 1.35;
}

.research-description {
  margin: 0;
  color: #666;
  font-size: 0.84em;
  line-height: 1.6;
}

@media (max-width: 700px) {
  .research-grid {
    grid-template-columns: 1fr;
  }

  .research-image {
    height: auto;
  }
}
</style>

<p class="research-intro">
My research focuses on wireless communication and sensing systems,
with particular emphasis on Integrated Sensing and Communication (ISAC),
aerial networks, software-defined radio, and adaptive wireless systems.
</p>

<div class="research-header">
  <span>Current Research</span>
</div>

<div class="research-grid">

  <!-- Research 1 -->

  <article class="research-card">

    <div class="research-image">
      <img src="{{ '/images/Resim1.png' | relative_url }}"
           alt="Multi-Static ISAC for Low-Altitude Networks">
    </div>

    <div class="research-content">

      <div class="research-topic">
        ISAC · Aerial Networks
      </div>

      <h2 class="research-title">
        Multi-Static ISAC for Low-Altitude Networks
      </h2>

      <p class="research-description">
        Multi-static Integrated Sensing and Communication architectures
        for low-altitude networks, focusing on distributed sensing,
        dynamic resource allocation, node role management, and UAV-aware
        communication and sensing.
      </p>

    </div>

  </article>


  <!-- Research 2 -->

  <article class="research-card">

    <div class="research-image">
      <img src="{{ '/images/Resim2.png' | relative_url }}"
           alt="ISAC-Assisted Dynamic Indoor Wi-Fi Coverage">
    </div>

    <div class="research-content">

      <div class="research-topic">
        ISAC · Wi-Fi
      </div>

      <h2 class="research-title">
        ISAC-Assisted Dynamic Indoor Wi-Fi Coverage
      </h2>

      <p class="research-description">
        ISAC-based environmental awareness for adaptive indoor wireless
        networks, enabling real-time sensing of user and environmental
        dynamics to support coverage optimization and seamless connectivity.
      </p>

    </div>

  </article>


  <!-- Research 3 -->

  <article class="research-card">

    <div class="research-image">
      <img src="{{ '/images/Resim3.png' | relative_url }}"
           alt="Flight-Dynamics-Aware Aerial Communications">
    </div>

    <div class="research-content">

      <div class="research-topic">
        UAV · Aerial Communications
      </div>

      <h2 class="research-title">
        Flight-Dynamics-Aware Aerial Communications
      </h2>

      <p class="research-description">
        Adaptive wireless communication for UAV networks considering
        flight dynamics, mobility, channel variability, and real-time
        link conditions to enable reliable aerial connectivity.
      </p>

    </div>

  </article>

</div>
