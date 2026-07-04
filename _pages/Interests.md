---
layout: page
title: "🏃"
permalink: /running/
nav: true
nav_order: 3
---

<style>
/* Hide the page title only on this page.
   Navbar title still remains as 🏃. */
.post-header {
  display: none;
}

/* Keep the site header/navbar background unchanged.
   Apply the blue background only to the running content area. */
.interests-page {
  --runner-blue: #60A5FA;
  --runner-green: #86EFAC;
  --runner-muted: #EAF6FF;
  --card-bg: rgba(255, 255, 255, 0.94);
  --card-border: rgba(255, 255, 255, 0.35);

  background-color: #0164B8;
  color: #ffffff;
  padding: 2rem 1.4rem;
  border-radius: 18px;
  margin-top: 0.5rem;
  margin-bottom: 2rem;
}

.interests-hero {
  text-align: center;
  margin-bottom: 2rem;
}

.interests-hero h2 {
  color: #ffffff;
  font-weight: 700;
  margin-bottom: 0.25rem;
}

.interests-hero p {
  color: var(--runner-muted);
  margin-bottom: 1rem;
}

.interests-hero img {
  width: 170px;
  height: 170px;
  object-fit: contain;
  image-rendering: pixelated;
  border-radius: 18px;
  margin-top: 0.3rem;
}

.running-section-card {
  border: 1px solid var(--card-border);
  border-radius: 18px;
  padding: 1.2rem 1.3rem;
  margin-bottom: 1.5rem;
  background: rgba(255, 255, 255, 0.14);
  backdrop-filter: blur(6px);
}

.section-title {
  margin-bottom: 1rem;
}

.record-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 0.9rem;
}

.record-card {
  border: 1px solid rgba(255, 255, 255, 0.45);
  border-radius: 14px;
  padding: 1rem;
  background: var(--card-bg);
  color: #1f2937;
}

.record-card .label {
  font-size: 0.85rem;
  color: #64748b;
  margin-bottom: 0.25rem;
}

.record-card .value {
  font-size: 1.25rem;
  font-weight: 700;
  color: #111827;
}

.record-card .event,
.record-card .meta {
  font-size: 0.82rem;
  color: #64748b;
  margin-top: 0.35rem;
}

.badge-road,
.badge-trail {
  display: inline-block;
  padding: 0.22rem 0.65rem;
  border-radius: 999px;
  font-size: 0.85rem;
  font-weight: 700;
}

.badge-road {
  background: rgba(255, 255, 255, 0.9);
  color: #2563eb;
}

.badge-trail {
  background: rgba(255, 255, 255, 0.9);
  color: #059669;
}
</style>

<div class="interests-page">

<div class="interests-hero">
  <img src="{{ '/assets/img/runner.gif' | relative_url }}" alt="Running pixel animation">
  <h2>Running Records</h2>
  <p>Road running, and trail running personal bests.</p>
</div>

<div class="running-section-card">
  <div class="section-title">
    <span class="badge-road">Road Running</span>
  </div>

  <div class="record-grid">
    <div class="record-card">
      <div class="label">5K</div>
      <div class="value">22:41</div>
      <div class="event">Local Race</div>
      <div class="meta">2026-06-07</div>
    </div>

    <div class="record-card">
      <div class="label">10K</div>
      <div class="value">47:37</div>
      <div class="event">2025 Seoul Earth Marathon</div>
      <div class="meta">2025-09-21</div>
    </div>

    <div class="record-card">
      <div class="label">Half Marathon</div>
      <div class="value">1:41:08</div>
      <div class="event">2026 Seoul Half Marathon</div>
      <div class="meta">2026-04-26</div>
    </div>

    <div class="record-card">
      <div class="label">Marathon</div>
      <div class="value">4:06:35</div>
      <div class="event">2026 Seoul Marathon</div>
      <div class="meta">2026-03-15</div>
    </div>
  </div>
</div>

<div class="running-section-card">
  <div class="section-title">
    <span class="badge-trail">Trail Running</span>
  </div>

  <div class="record-grid">
    <div class="record-card">
      <div class="label">20K Trail</div>
      <div class="value">4:04:18</div>
      <div class="event">2026 Jangsu Trail Race 20.1km</div>
      <div class="meta">2026-04-04</div>
      <div class="meta">Elevation Gain: 1,058 m</div>
    </div>

    <div class="record-card">
      <div class="label">50K Trail</div>
      <div class="value">7:16:13</div>
      <div class="event">2026 Untangodo Skyrace 42.2km</div>
      <div class="meta">2026-06-14</div>
      <div class="meta">Elevation Gain: 1,910 m</div>
    </div>
  </div>
</div>

</div>
