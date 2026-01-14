---
layout: single
title: " "
classes: wide
author_profile: false
---

<style>
/* 🔑 THIS IS THE KEY FIX: remove theme width constraint */
.initial-content{
  max-width: 100% !important;
}

/* Center content nicely after widening */
.page__content{
  max-width: 1400px;
  margin: 0 auto;
}

/* --- HERO LAYOUT --- */
.hero-grid{
  display:grid;
  grid-template-columns: 1.6fr 1fr;
  gap:1.3rem;
  margin: 1rem 0 1.4rem 0;
}

/* Left main card */
.hero-left{
  padding:1.5rem 1.6rem;
  border-radius:18px;
  background: linear-gradient(135deg, #f0f7ff, #f5f3ff);
  border:1px solid #e5e7eb;
  box-shadow: 0 12px 28px rgba(0,0,0,0.07);
}

.hero-kicker{
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size:0.72rem;
  color:#475569;
  margin-bottom:0.4rem;
}

.hero-title{
  font-size:1.7rem;
  font-weight:800;
  margin:0 0 0.6rem 0;
  color:#0f172a;
}

.hero-subtitle{
  font-size:1rem;
  line-height:1.65;
  color:#334155;
  max-width: 90ch;
}

/* Meta row */
.hero-meta{
  display:flex;
  gap:0.9rem;
  flex-wrap:wrap;
  margin:1rem 0 1.1rem 0;
}

.meta-item{
  background:white;
  padding:0.7rem 0.9rem;
  border-radius:14px;
  border:1px solid #e5e7eb;
  flex:1 1 260px;
}

.meta-label{
  display:block;
  font-size:0.72rem;
  color:#64748b;
}

.meta-value{
  font-weight:650;
  color:#0f172a;
}

/* Buttons */
.hero-links{
  display:flex;
  gap:0.6rem;
  flex-wrap:wrap;
}

.btn-primary,.btn-ghost{
  padding:0.55rem 1rem;
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

/* Right side */
.hero-right{
  display:grid;
  gap:1.1rem;
}

.card{
  background:white;
  border-radius:16px;
  padding:1.2rem 1.3rem;
  border:1px solid #e5e7eb;
  box-shadow: 0 10px 24px rgba(0,0,0,0.05);
}

.card h3{
  margin-top:0;
  font-size:1.1rem;
}

.card li{
  margin:0.4rem 0;
  font-size:0.95rem;
}

/* Responsive */
@media(max-width: 1000px){
  .hero-grid{ grid-template-columns: 1fr; }
}
</style>

<div class="hero-grid">

  <div class="hero-left">
    <div class="hero-kicker">Lecturer in Computer Science</div>
    <div class="hero-title">Dr Naveed Ejaz · Ulster University Belfast</div>

    <p class="hero-subtitle">
      I am a Lecturer in Computer Science at <strong>Ulster University Belfast</strong>.
      My research focuses on <strong>applied multimodal artificial intelligence</strong> for
      intelligent decision-making in <strong>healthcare</strong>, <strong>infrastructure</strong>,
      and <strong>societal systems</strong>, with emphasis on
      <strong>real-world deployment</strong>, <strong>ethics</strong>, and <strong>impact</strong>.
    </p>

    <div class="hero-meta">
      <div class="meta-item">
        <span class="meta-label">Email</span>
        <span class="meta-value"><a href="mailto:n.ejaz@ulster.ac.uk">n.ejaz@ulster.ac.uk</a></span>
      </div>
      <div class="meta-item">
        <span class="meta-label">Location</span>
        <span class="meta-value">Belfast, Northern Ireland (UK)</span>
      </div>
    </div>

    <div class="hero-links">
      <a class="btn-primary" href="/contact/">Contact</a>
      <a class="btn-ghost" href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank">Google Scholar</a>
      <a class="btn-ghost" href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank">LinkedIn</a>
      <a class="btn-ghost" href="https://github.com/naveed-ejaz" target="_blank">GitHub</a>
    </div>
  </div>

  <div class="hero-right">
    <div class="card">
      <h3>Research themes</h3>
      <ul>
        <li><strong>AI for Health & Wellbeing</strong> — clinical decision support</li>
        <li><strong>AI for Smart Infrastructure & Planning</strong> — drone imagery</li>
        <li><strong>Responsible AI for Safety & Society</strong> — online harms</li>
        <li><strong>Multimodal & Generative AI Systems</strong> — vision–language, RAG</li>
      </ul>
    </div>

    <div class="card">
      <h3>Prospective students</h3>
      <ul>
        <li>PhD / MSc supervision in applied AI</li>
        <li>Interdisciplinary & industry-linked projects</li>
        <li>Email me with CV + interests</li>
      </ul>
    </div>
  </div>

</div>

## Supervision & Collaboration

I welcome enquiries from prospective **PhD and MSc students** interested in applied,
impact-driven AI research aligned with my research themes.
