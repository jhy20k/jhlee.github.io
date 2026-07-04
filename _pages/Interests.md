---
layout: page
title: "🏃"
permalink: /running/
description: Marathon and trail running records
nav: true
nav_order: 3
---

<style>
.running-page {
  --runner-blue: #60A5FA;
  --runner-green: #86EFAC;
  --runner-muted: var(--global-text-color-light);
}

.running-section-card {
  border: 1px solid var(--global-divider-color);
  border-radius: 18px;
  padding: 1.2rem 1.3rem;
  margin-bottom: 1.5rem;
  background: var(--global-card-bg-color);
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
  border: 1px solid var(--global-divider-color);
  border-radius: 14px;
  padding: 1rem;
  background: var(--global-bg-color);
}

.record-card .label {
  font-size: 0.85rem;
  color: var(--runner-muted);
  margin-bottom: 0.25rem;
}

.record-card .value {
  font-size: 1.25rem;
  font-weight: 700;
}

.record-card .event,
.record-card .meta {
  font-size: 0.82rem;
  color: var(--runner-muted);
  margin-top: 0.35rem;
}

.badge-road,
.badge-trail {
  display: inline-block;
  padding: 0.22rem 0.65rem;
  border-radius: 999px;
  font-size: 0.85rem;
  font-weight: 600;
}

.badge-road {
  background: rgba(96, 165, 250, 0.16);
  color: var(--runner-blue);
}

.badge-trail {
  background: rgba(134, 239, 172, 0.16);
  color: var(--runner-green);
}
</style>

<div class="running-page">

<div class="running-section-card">
  <div class="section-title">
    <span class="badge-road">Road Running</span>
  </div>

  <div class="record-grid">
    <div class="record-card">
      <div class="label">5K</div>
      <div class="value">22:41</div>
      <div class="event">Local Race </div> 2026-06-07</div>
    </div>

    <div class="record-card">
      <div class="label">10K</div>
      <div class="value">47:37</div>
      <div class="event">2025 Seoul Earth Marathon </div> 2025-09-21</div>
    </div>

    <div class="record-card">
      <div class="label">Half Marathon</div>
      <div class="value">1:41:08</div>
      <div class="event">2026 Seoul Half Marathon </div> 2026-04-26</div>
    </div>

    <div class="record-card">
      <div class="label">Marathon</div>
      <div class="value">4:06:35</div>
      <div class="event">2026 Seoul Marathon </div> 2026-03-15</div>
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
      <div class="event">2026 Jangsu Trail Race 20.1km · 2026-04-04</div>
      <div class="meta">Elevation Gain: 1,058 m</div>
    </div>

    <div class="record-card">
      <div class="label">50K Trail</div>
      <div class="value">7:16:13</div>
      <div class="event">2026 Untangodo Skyrace 42.2km · 2026-06-14</div>
      <div class="meta">Elevation Gain: 1,910 m</div>
    </div>
  </div>
</div>

</div>
