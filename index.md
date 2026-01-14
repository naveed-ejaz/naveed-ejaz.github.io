---
layout: single
title: " "
classes: wide
author_profile: false
---

<style>
/* Simple academic layout (photo left, info right) */
.simple-home{
  display:flex;
  gap: 2.2rem;
  align-items:flex-start;
  margin-top: 1.2rem;
}

/* Photo block */
.simple-photo{
  width: 260px;
  flex: 0 0 260px;
}
.simple-photo img{
  width: 100%;
  height: auto;
  border-radius: 6px;
  border: 1px solid #e5e7eb;
}

/* Right content */
.simple-content{
  flex: 1;
  min-width: 280px;
}
.name{
  font-size: 2.0rem;
  font-weight: 800;
  margin: 0 0 0.35rem 0;
}
.tagline{
  font-size: 1.05rem;
  color: #334155;
  margin: 0 0 1rem 0;
  line-height: 1.5;
}
.role{
  font-size: 1.05rem;
  margin: 0.3rem 0 0.6rem 0;
}
.links a{
  margin-right: 0.8rem;
  font-weight: 600;
  text-decoration: none;
}
.panel{
  margin-top: 1.1rem;
  padding-top: 0.9rem;
  border-top: 1px solid #e5e7eb;
}
.panel h3{
  margin: 0 0 0.5rem 0;
  font-size: 1.05rem;
}
.panel ul{
  margin: 0.2rem 0 0 1.1rem;
}
.panel li{
  margin: 0.35rem 0;
}

/* Mobile */
@media (max-width: 900px){
  .simple-home{
    flex-direction: column;
    gap: 1.2rem;
  }
  .simple-photo{
    width: 220px;
    flex: 0 0 auto;
  }
  .name{
    font-size: 1.7rem;
  }
}
</style>

<div class="simple-home">

  <div class="simple-photo">
    <img src="{{ '/assets/images/naveed.jpg' | relative_url }}" alt="Dr Naveed Ejaz">
  </div>

  <div class="simple-content">
    <div class="name">Dr Naveed Ejaz</div>

    <div class="role">
      <strong>Lecturer in Computer Science</strong><br/>
      Ulster University Belfast, Northern Ireland (UK)
    </div>

    <p class="tagline">
      My research focuses on <strong>applied multimodal artificial intelligence</strong> for intelligent decision-making in
      <strong>healthcare</strong>, <strong>infrastructure</strong>, and <strong>societal systems</strong>, with emphasis on
      <strong>real-world deployment</strong>, <strong>ethics</strong>, and <strong>impact</strong>.
    </p>

    <div class="links">
      <a href="mailto:n.ejaz@ulster.ac.uk">Email</a>
      <a href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/naveed-ejaz" target="_blank" rel="noopener">GitHub</a>
      <a href="/contact/">Contact Page</a>
    </div>

    <div class="panel">
      <h3>Research themes</h3>
      <ul>
        <li><strong>AI for Health & Wellbeing</strong> — clinical decision support, privacy-aware AI</li>
        <li><strong>AI for Smart Infrastructure & Planning</strong> — drone imagery, monitoring</li>
        <li><strong>Responsible AI for Safety & Society</strong> — online harms, explainable AI</li>
        <li><strong>Multimodal & Generative AI Systems</strong> — vision–language, RAG, edge/cloud</li>
      </ul>
    </div>

    <div class="panel">
      <h3>Prospective students</h3>
      <ul>
        <li>PhD / MSc supervision in applied AI (CV, NLP/LLMs, multimodal AI, responsible AI)</li>
        <li>Email me with your CV + a short description of interests</li>
      </ul>
    </div>

  </div>
</div>
