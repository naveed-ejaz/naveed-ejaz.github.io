---
layout: single
title: " "
classes: wide
author_profile: false
---

<style>
/* --- HERO LAYOUT: wider + more balanced --- */
.hero-wrap{
  width: 100%;
}

.hero-grid{
  display:grid;
  grid-template-columns: 1.55fr 1fr;   /* makes left column noticeably wider */
  gap:1.1rem;
  align-items: stretch;
  margin: 0.7rem 0 1.1rem 0;
}

.hero-left{
  padding:1.35rem 1.4rem;
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
  margin:0 0 0.35rem 0;
}

.hero-title{
  font-size:1.65rem;
  font-weight:780;
  margin:0 0 0.55rem 0;
  color:#0f172a;
}

.hero-subtitle{
  font-size:0.98rem;
  line-height:1.65;
  color:#334155;
  margin:0.2rem 0 1.05rem 0;
  max-width: 80ch; /* allow the text to fill space */
}

.hero-meta{
  display:flex;
  gap:0.75rem;
  flex-wrap:wrap;
  margin:0.9rem 0 1.05rem 0;
}

.meta-item{
  background:white;
  padding:0.65rem 0.85rem;
  border-radius:14px;
  border:1px solid #e5e7eb;
  min-width: 240px;
  flex: 1 1 240px;
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

/* Buttons */
.hero-links{
  display:flex;
  gap:0.55rem;
  flex-wrap:wrap;
}

.btn-primary,.btn-ghost{
  padding:0.5rem 0.95rem;
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

/* --- RIGHT SIDE: split into 2 smaller cards so it’s less “cluttered” --- */
.hero-right{
  display:grid;
  grid-template-rows: auto auto;
  gap:1.1rem;
}

.card{
  background:white;
  border-radius:16px;
  padding:1.05rem 1.1rem;
  border:1px solid #e5e7eb;
  box-shadow: 0 10px 24px rgba(0,0,0,0.05);
}

.card h3{
  margin:0 0 0.55rem 0;
  font-size:1.05rem;
}

.card ul{
  padding-left:1.05rem;
  margin:0;
}

.card li{
  margin: 0.35rem 0;
  font-size:0.94rem;
  line-height:1.45;
}

/* --- FULL WIDTH BAND to “fill” the page --- */
.band{
  background: linear-gradient(135deg, rgba(79,70,229,0.08), rgba(14,165,233,0.06));
  border:1px solid rgba(148,163,184,0.35);
  border-radius:18px;
  padding:1.1rem 1.15rem;
  margin: 0.9rem 0 1.25rem 0;
}

.band-grid{
  display:grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap:0.85rem;
}

.band-card{
  background: rgba(255,255,255,0.7);
  border:1px solid rgba(226,232,240,0.9);
  border-radius:16px;
  padding:0.9rem 1rem;
}

.band-card h4{
  margin:0 0 0.35rem 0;
  font-size:1.0rem;
}

.band-card p{
  margin:0;
  font-size:0.94rem;
  line-height:1.5;
  color:#334155;
}

.soft-rule{
  height:1px;
  border:none;
  background:#e5e7eb;
  margin:1.5rem 0;
}

/* Responsive */
@media(max-width: 980px){
  .hero-grid{ grid-template-columns: 1fr; }
  .band-grid{ grid-template-columns: 1fr; }
}
</style>

<div class="hero-wrap">

  <div class="hero-grid">

    <div class="hero-left">
      <div class="hero-kicker">Lecturer in Computer Science</div>
      <div class="hero-title">Dr Naveed Ejaz · Ulster University Belfast</div>

      <p class="hero-subtitle">
        I am a Lecturer in Computer Science at <strong>Ulster University Belfast</strong>.
        My research focuses on <strong>applied multimodal artificial intelligence</strong> for
        intelligent decision-making in <strong>healthcare</strong>, <strong>infrastructure</strong>,
        and <strong>societal systems</strong>, with emphasis on <strong>real-world deployment</strong>,
        <strong>ethics</strong>, and <strong>impact</strong>.
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
        <a class="btn-ghost" href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
        <a class="btn-ghost" href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank" rel="noopener">LinkedIn</a>
        <a class="btn-ghost" href="https://github.com/naveed-ejaz" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>

    <div class="hero-right">
      <div class="card">
        <h3>Research themes</h3>
        <ul>
          <li><strong>AI for Health & Wellbeing</strong> — clinical decision support and privacy-aware AI</li>
          <li><strong>AI for Smart Infrastructure & Planning</strong> — drone imagery and road monitoring</li>
          <li><strong>Responsible AI for Safety & Society</strong> — online harms and explainable AI</li>
          <li><strong>Multimodal & Generative AI Systems</strong> — vision–language models, RAG, edge/cloud AI</li>
        </ul>
      </div>

      <div class="card">
        <h3>Prospective students</h3>
        <ul>
          <li>PhD / MSc supervision in multimodal AI, computer vision, NLP/LLMs, and responsible AI</li>
          <li>Interdisciplinary projects with healthcare, engineering, and public-sector partners</li>
          <li>Email me with your CV + 2–3 lines on your interests</li>
        </ul>
      </div>
    </div>

  </div>

  <div class="band">
    <div class="band-grid">
      <div class="band-card">
        <h4>Impact & deployment</h4>
        <p>Applied AI systems deployed for healthcare workflows, infrastructure monitoring, and decision support.</p>
      </div>
      <div class="band-card">
        <h4>Funding & collaboration</h4>
        <p>Open to UK/Northern Ireland partnerships with healthcare, local government, and industry.</p>
      </div>
      <div class="band-card">
        <h4>Research direction</h4>
        <p>Applied multimodal AI to support evidence-based decisions in high-impact public services.</p>
      </div>
    </div>
  </div>

</div>

<hr class="soft-rule"/>

## Supervision & Collaboration

I welcome enquiries from prospective **PhD and MSc students** interested in applied,
impact-driven AI research aligned with the themes above.

Please email me with a brief description of your background and research interests.
