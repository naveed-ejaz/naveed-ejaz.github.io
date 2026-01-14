---
layout: home
author_profile: false
title: ""
classes: wide
---

<style>
/* Tweak overall typography for a cleaner look */
.page__content{
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
}

/* Hide theme-generated page title area (some themes show it even on home) */
.page__title, .page__hero--overlay, .page__hero, header.page__title{
  display: none !important;
}

.hero-card{
  display:grid;
  grid-template-columns: 1.2fr 0.9fr;
  gap:1.1rem;
  padding:1.25rem;
  border-radius:18px;
  background: linear-gradient(135deg, #f0f7ff, #f5f3ff);
  border:1px solid #e5e7eb;
  box-shadow: 0 12px 28px rgba(0,0,0,0.07);
  margin: 0.5rem 0 1.5rem 0;
}

.hero-kicker{
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size:0.72rem;
  color:#475569;
  margin:0 0 0.25rem 0;
}

.hero-title{
  font-size:1.7rem;
  font-weight:750;
  margin:0 0 0.45rem 0;
  color:#0f172a;
}

.hero-subtitle{
  font-size:0.98rem;
  line-height:1.6;
  color:#334155;
  margin:0.2rem 0 0.9rem 0;
  max-width: 64ch;
}

.hero-meta{
  display:flex;
  gap:0.75rem;
  flex-wrap:wrap;
  margin:0.85rem 0 1rem 0;
}

.meta-item{
  background:white;
  padding:0.6rem 0.8rem;
  border-radius:14px;
  border:1px solid #e5e7eb;
  min-width:240px;
}

.meta-label{
  display:block;
  font-size:0.72rem;
  color:#64748b;
  margin-bottom: 0.1rem;
}

.meta-value{
  font-weight:650;
  color:#0f172a;
}

.hero-links{
  display:flex;
  gap:0.55rem;
  flex-wrap:wrap;
}

.btn-primary,.btn-ghost{
  padding:0.5rem 0.9rem;
  border-radius:999px;
  font-weight:650;
  font-size:0.92rem;
  text-decoration:none !important;
  border:1px solid #c7d2fe;
}

.btn-primary{
  background:#4f46e5;
  color:white !important;
  border-color:#4f46e5;
}

.btn-ghost{
  background:white;
  color:#1e293b !important;
}

.hero-panel{
  background:white;
  border-radius:16px;
  padding:1rem 1.05rem;
  border:1px solid #e5e7eb;
}

.hero-panel h3{
  margin:0 0 0.55rem 0;
  font-size:1.05rem;
}

.hero-panel ul{
  padding-left:1.05rem;
  margin:0;
}

.hero-panel li{
  margin: 0.35rem 0;
  font-size:0.95rem;
  line-height:1.45;
}

.soft-rule{
  height:1px;
  border:none;
  background:#e5e7eb;
  margin:1.5rem 0;
}

.section-title{
  font-size:1.25rem;
  margin: 0 0 0.6rem 0;
}

.section-text{
  font-size:0.98rem;
  line-height:1.65;
}

@media(max-width:900px){
  .hero-card{ grid-template-columns:1fr; }
  .meta-item{ min-width:100%; }
}
</style>

<div class="hero-card">

  <div>
    <div class="hero-kicker">Lecturer in Computer Science</div>
    <div class="hero-title">Dr Naveed Ejaz</div>

    <p class="hero-subtitle">
      I am a <strong>Lecturer in Computer Science at Ulster University Belfast</strong>.
      My research focuses on <strong>applied multimodal artificial intelligence</strong> for
      intelligent decision-making in <strong>healthcare</strong>, <strong>infrastructure</strong>,
      and <strong>societal systems</strong>, with emphasis on <strong>real-world deployment</strong>,
      <strong>ethics</strong>, and <strong>impact</strong>.
    </p>

    <div class="hero-meta">
      <div class="meta-item">
        <span class="meta-label">Affiliation</span>
        <span class="meta-value">Ulster University Belfast</span>
      </div>
      <div class="meta-item">
        <span class="meta-label">Email</span>
        <span class="meta-value">
          <a href="mailto:n.ejaz@ulster.ac.uk">n.ejaz@ulster.ac.uk</a>
        </span>
      </div>
    </div>

    <div class="hero-links">
      <a class="btn-primary" href="/contact/">Contact</a>
      <a class="btn-ghost" href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
      <a class="btn-ghost" href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank" rel="noopener">LinkedIn</a>
      <a class="btn-ghost" href="https://github.com/naveed-ejaz" target="_blank" rel="noopener">GitHub</a>
    </div>
  </div>

  <div class="hero-panel">
    <h3>Resear
