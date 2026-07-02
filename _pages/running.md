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
  --runner-orange: #FDBA74;
  --runner-purple: #C084FC;
  --runner-muted: var(--global-text-color-light);
}

.running-hero {
  position: relative;
  overflow: hidden;
  border: 1px solid var(--global-divider-color);
  border-radius: 18px;
  padding: 1.4rem 1.5rem 1.2rem;
  margin-bottom: 1.7rem;
  background:
    linear-gradient(180deg, rgba(96, 165, 250, 0.12), rgba(134, 239, 172, 0.08)),
    var(--global-card-bg-color);
}

.running-hero h2 {
  margin-top: 0;
  margin-bottom: 0.4rem;
  font-weight: 700;
}

.running-hero p {
  margin-bottom: 0;
  color: var(--runner-muted);
}

.running-scene {
  position: relative;
  height: 95px;
  margin-top: 1.1rem;
}

.sun {
  position: absolute;
  top: 8px;
  right: 28px;
  width: 34px;
  height: 34px;
  border-radius: 50%;
  background: var(--runner-orange);
  box-shadow: 0 0 24px rgba(253, 186, 116, 0.6);
  animation: sunPulse 2.8s ease-in-out infinite;
}

.mountain {
  position: absolute;
  bottom: 18px;
  width: 0;
  height: 0;
  border-left: 85px solid transparent;
  border-right: 85px solid transparent;
  border-bottom: 70px solid rgba(134, 239, 172, 0.35);
}

.mountain.one {
  left: 5%;
}

.mountain.two {
  left: 28%;
  transform: scale(0.8);
  border-bottom-color: rgba(192, 132, 252, 0.25);
}

.mountain.three {
  right: 7%;
  transform: scale(0.9);
  border-bottom-color: rgba(96, 165, 250, 0.24);
}

.running-track {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 8px;
  height: 4px;
  border-radius: 999px;
  background: linear-gradient(90deg, var(--runner-blue), var(--runner-green), var(--runner-orange));
}

.runner {
  position: absolute;
  bottom: 18px;
  left: 0;
  font-size: 2rem;
  animation: runAcross 7s linear infinite;
}

@keyframes runAcross {
  0% {
    transform: translateX(-10%) translateY(0);
  }
  25% {
    transform: translateX(25vw) translateY(-3px);
  }
  50% {
    transform: translateX(50vw) translateY(0);
  }
  75% {
    transform: translateX(70vw) translateY(-3px);
  }
  100% {
    transform: translateX(100vw) translateY(0);
  }
}

@keyframes sunPulse {
  0%, 100% {
    transform: scale(1);
    opacity: 0.85;
  }
  50% {
    transform: scale(1.08);
    opacity: 1;
  }
}

.record-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 0.9rem;
  margin: 1.4rem 0 2rem;
}

.record-card {
  border: 1px solid var(--global-divider-color);
  border-radius: 14px;
  padding: 1rem;
  background: var(--global-card-bg-color);
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

.record-card .event {
  font-size: 0.82rem;
  color: var(--runner-muted);
  margin-top: 0.35rem;
}

.badge-road {
  display: inline-block;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: rgba(96, 165, 250, 0.16);
  color: var(--runner-blue);
  font-size: 0.8rem;
  font-weight: 600;
}

.badge-trail {
  display: inline-block;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: rgba(134, 239, 172, 0.16);
  color: var(--runner-green);
  font-size: 0.8rem;
  font-weight: 600;
}
</style>

<div class="running-page">

<div class="running-hero">
  <h2>Running Records</h2>
  <p>Personal bests from road running, marathon, and trail running.</p>

  <div class="running-scene">
    <div class="sun"></div>
    <div class="mountain one"></div>
    <div class="mountain two"></div>
    <div class="mountain three"></div>
    <div class="runner">🏃</div>
    <div class="running-track"></div>
  </div>
</div>

## Personal Bests

<div class="record-grid">
  <div class="record-card">
    <div class="label">5K</div>
    <div class="value">22:41</div>
    <div class="event">Local Race · 2026-06-07</div>
  </div>

  <div class="record-card">
    <div class="label">10K</div>
    <div class="value">47:37</div>
    <div class="event">2025 Seoul Earth Marathon · 2025-09-21</div>
  </div>

  <div class="record-card">
    <div class="label">Half Marathon</div>
    <div class="value">1:41:08</div>
    <div class="event">2026 Seoul Half Marathon · 2026-04-26</div>
  </div>

  <div class="record-card">
    <div class="label">Marathon</div>
    <div class="value">4:06:35</div>
    <div class="event">2026 Seoul Marathon · 2026-03-15</div>
  </div>
</div>

### <span class="badge-road">Road Running</span>

| Distance | Record | Event | Date |
|---|---:|---|---|
| 5K | 22:41 | Local Race | 2026-06-07 |
| 10K | 47:37 | 2025 Seoul Earth Marathon | 2025-09-21 |
| Half Marathon | 1:41:08 | 2026 Seoul Half Marathon | 2026-04-26 |
| Marathon | 4:06:35 | 2026 Seoul Marathon | 2026-03-15 |

### <span class="badge-trail">Trail Running</span>

| Distance | Record | Elevation Gain | Event | Date |
|---|---:|---:|---|---|
| 20K Trail | 4:04:18 | 1,058 m | 2026 Jangsu Trail Race 20.1km | 2026-04-04 |
| 50K Trail | 7:16:13 | 1,910 m | 2026 Untangodo Skyrace 42.2km | 2026-06-14 |

</div>
