---
layout: single
title: " "
classes: wide
author_profile: false
---

<style>
/* --- Simple academic layout (Miguel-like) --- */
.acad{
  display:grid;
  grid-template-columns: 2.2fr 1fr;
  gap: 3rem;
  align-items:start;
  margin-top: 1.6rem;
}

/* Left column */
.name{
  font-size: 2.6rem;
  font-weight: 800;
  letter-spacing: 0.12em;
  margin: 0 0 0.4rem 0;
}

.sub{
  font-size: 1.05rem;
  font-style: italic;
  line-height: 1.55;
  margin: 0.1rem 0;
  color: #111827;
}

.photo{
  margin-top: 1.1rem;
  width: 260px;
  border: 1px solid #e5e7eb;
}

.roleblock{
  margin-top: 1.3rem;
  font-size: 1.05rem;
  line-height: 1.7;
}

.roleblock a{
  text-decoration: underline;
}

/* Right column */
.right h3{
  font-size: 1.1rem;
  margin: 0 0 0.6rem 0;
  font-weight: 800;
}

.right p{
  margin: 0.15rem 0;
  line-height: 1.6;
}

.links{
  margin-top: 1.1rem;
}

.links h3{
  margin-top: 1.3rem;
}

.links a{
  font-weight: 700;
  margin-right: 0.7rem;
  text-decoration: none;
}

/* Responsive */
@media (max-width: 1000px){
  .acad{
    grid-template-columns: 1fr;
    gap: 1.6rem;
  }
  .photo{
    width: 220px;
  }
  .name{
    font-size: 2.1rem;
    letter-spacing: 0.08em;
  }
}
</style>

<div class="acad">

  <!-- LEFT -->
  <div>
    <div class="name">NAVEED EJAZ</div>

    <div class="sub">Lecturer in Computer Science (Ulster University Belfast, Northern Ireland, UK)</div>
    <div class="sub">Applied Multimodal AI · Computer Vision · NLP/LLMs · Responsible AI</div>

    <img class="photo" src="{{ '/assets/images/naveed.jpg' | relative_url }}" alt="Dr Naveed Ejaz">

    <div class="roleblock">
      Lecturer<br/>
      <a href="https://www.ulster.ac.uk/" target="_blank" rel="noopener">Ulster University</a> (Belfast)
    </div>
  </div>

  <!-- RIGHT -->
  <div class="right">
    <h3>Contact Information</h3>
    <p>School of Computing</p>
    <p>Ulster University Belfast</p>
    <p>Belfast, Northern Ireland (UK)</p>
    <p>Email: <a href="mailto:n.ejaz@ulster.ac.uk">n.ejaz@ulster.ac.uk</a></p>

    <div class="links">
      <h3>Related links</h3>
      <a href="https://scholar.google.ca/citations?user=EWORmh8AAAAJ&hl=en" target="_blank" rel="noopener">Scholar</a>
      <a href="https://www.linkedin.com/in/naveed-ejaz/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/naveed-ejaz" target="_blank" rel="noopener">GitHub</a>
      <a href="/contact/">Contact page</a>
    </div>
  </div>

</div>
