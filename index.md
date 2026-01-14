---
layout: single
title: " "
classes: wide
author_profile: false
---

<style>
/* ===== HERO LAYOUT ===== */
.hero{
  display:grid;
  grid-template-columns: 0.55fr 1.35fr 1fr;
  gap:1.2rem;
  align-items: stretch;
  margin: 1rem 0 1.5rem 0;
}

/* ===== PHOTO CARD ===== */
.photo-card{
  background:white;
  border:1px solid #e5e7eb;
  border-radius:18px;
  padding:0.9rem;
  box-shadow: 0 10px 24px rgba(0,0,0,0.05);
  display:flex;
  align-items:center;
}

.photo-card img{
  width:100%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius:14px;
  border:1px solid #e5e7eb;
}

/* ===== MAIN CONTENT CARD ===== */
.main-card{
  padding:1.4rem 1.6rem;
  border-radius:18px;
  background: linear-gradient(135deg, #f0f7ff, #f5f3ff);
  border:1px solid #e5e7eb;
  box-shadow: 0 12px 28px rgba(0,0,0,0.07);
}

.kicker{
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size:0.72rem;
  color:#475569;
  margin-bottom:0.4rem;
}

.title{
  font-size:1.6rem;
  font-weight:800;
  margin:0 0 0.6rem 0;
  color:#0f172a;
}

.subtitle{
  font-size:0.98rem;
  line-height:1.65;
  color:#334155;
  margin:0.2rem 0 1rem 0;
  max-width: 90ch;
}

/* ===== META ===== */
.meta{
  display:flex;
  gap:0.8rem;
  flex-wrap:wrap;
  margin:0.9rem 0 1.1rem 0;
}

.pill{
  background:white;
  padding:0.65rem 0.85rem;
  border-radius:14px;
  border:1px solid #e5e7eb;
  flex:1 1 240px;
}

.pill small{
  display:block;
  font-size:0.72rem;
  color:#64748b;
}

.pill strong{
  display:block;
  font-weight:700;
  color:#0f172a;
}

/* ===== LINKS ===== */
.links{
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

/* ===== RIGHT CARD ===== */
.side-card{
  background:white;
  border-radius:18px;
  padding:1.25rem 1.35rem;
  border:1px solid #e5e7eb;
  box-shadow: 0 10px 24px rgba(0,0,0,0.05);
}

.side-card h3{
  margin-top:0;
  font-size:1.1rem;
}

.side-card li{
  margin:0.4rem 0;
  font-size:0.95rem;
  line-height:1.45;
}

/* ===== RESPONSIVE ===== */
@media(max-width: 1100px){
  .hero{ grid-template-columns: 1fr; }
  .photo-card img{ aspect-ratio: 4 / 3; }
}
</style>

<div class="hero">

  <!-- PHOTO -->
  <div class="photo-card">
    <img src="/assets/images/naveed.jpg" alt="Dr Naveed Ejaz">
  </div>

  <!-- MAIN CONTENT -->
  <div class="main-card">
    <div class="kicker">Lecturer in Computer Science</div>
    <div class="title">Dr Naveed Ejaz · Ulster University Belfast</div>

    <p class="subtitle">
      I am a Lecturer in Computer Science at <strong>Ulster University Belfast</strong>.
      My research focuses on <strong>applied multimodal artificial intelligence</strong> for intelligent
      decision-making in <strong>healthcare</strong>, <strong>infrastructure</strong>, and
      <strong>societal systems</strong>, with emphasis on
      <strong>real-world deployment</strong>, <strong>ethics</strong>, and <strong>impact</strong>.
    </p>

    <div class="meta">
      <div class="pill">
        <small>Email</small>
        <strong><a href="mailto:n.ejaz@ulster.ac.uk">n.ejaz@ulster.ac.uk</a></strong>
      </div>
      <div class="pill">
        <small>Location</small>
        <strong>Belfast, Northern Ireland (UK)</strong>
      </div>
    </div>

    <div class="links">
      <a class="btn-primary" href="/contact/">Contact</a>
      <a class="btn-ghost" href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank">Google Scholar</a>
      <a class="btn-ghost" href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank">LinkedIn</a>
      <a class="btn-ghost" href="https://github.com/naveed-ejaz" target="_blank">GitHub</a>
    </div>
  </div>

  <!-- RIGHT PANEL -->
  <div class="side-card">
    <h3>Research themes</h3>
    <ul>
      <li><strong>AI for Health & Wellbeing</strong> — clinical decision support</li>
      <li><strong>AI for Smart Infrastructure & Planning</strong> — drone imagery & monitoring</li>
      <li><strong>Responsible AI for Safety & Society</strong> — online harms & explainable AI</li>
      <li><strong>Multimodal & Generative AI Systems</strong> — vision–language, RAG, edge/cloud</li>
    </ul>

    <h3 style="margin-top:1.1rem;">Prospective students</h3>
    <ul>
      <li>PhD / MSc supervision in applied AI</li>
      <li>Interdisciplinary & industry-linked projects</li>
      <li>Email me with your CV + interests</li>
    </ul>
  </div>

</div>

## Supervision & Collaboration

I welcome enquiries from prospective **PhD and MSc students** interested in applied,
impact-driven AI research aligned with my research themes.
