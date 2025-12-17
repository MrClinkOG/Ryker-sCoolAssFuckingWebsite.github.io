---
layout: default
---

<section class="hero hero-shell" id="home">
  <div class="hero-frame" aria-hidden="true">
    <div class="hero-frame__inner">
      <span class="hero-frame__bar bar-top"></span>
      <span class="hero-frame__bar bar-bottom"></span>
      <span class="hero-frame__bar bar-left"></span>
      <span class="hero-frame__bar bar-right"></span>
    </div>
  </div>
  <div class="hero__canvas" aria-hidden="true">
    <canvas id="heroCanvas"></canvas>
  </div>
  <div class="hero__content">
    <p class="hero__eyebrow">Autonomy · Multi-agent systems · CAD</p>
    <h1>Ryker Kollmyer</h1>
    <p class="hero__lede">
      Mechatronics and distributed-systems student researcher focused on robust hardware and software systems.
    </p>
  </div>
</section>

<section class="content-split" id="portfolio" aria-label="Portfolio layout">
  <aside class="profile-panel" id="about" aria-labelledby="profileHeading">
    <div class="profile-panel__card">
      <div class="profile-panel__image">
        <img src="{{ 'Screenshot 2025-11-11 at 3.26.22 PM.jpg' | relative_url }}" alt="Kevin Liu portrait">
      </div>
      <div class="profile-panel__meta">
        <p class="profile-panel__eyebrow">Kevin Liu</p>
        <h2 id="profileHeading">Researcher Student</h2>
        <p class="profile-panel__summary">
          Hello! I'm Kevin Liu, I enjoy coding, 
          pets/animals, riding around town on my scooter, 
          swimming, violin, music, and stocks(I know it's alot)!
        </p>
      </div>
      <dl class="profile-panel__stats">
        <div>
          <dt>Focus</dt>
          <dd>Genomics, Engineering</dd>
        </div>
        <div>
          <dt>Current</dt>
          <dd>Albany High School CA '26</dd>
        </div>
      </dl>
      <div class="profile-panel__actions">
        <a href="{{ site.github.owner_url }}" class="pill-link" target="_blank" rel="noopener" data-cursor-target>GitHub</a>
        <a href="https://www.linkedin.com/in/rykerkollmyer/" class="pill-link pill-link--ghost" target="_blank" rel="noopener" data-cursor-target data-proofer-ignore>LinkedIn</a>
      </div>
    </div>
  </aside>

  <div class="portfolio-column">
    <header class="portfolio-header">
      <p class="portfolio-kicker">"What if?" started everything in my</p>
      <h2>General Portfolio</h2>
      <p>
        Software systems, hackathons, antkeeping, and music. Click any card to see an expanded view of the projects,
      </p>
    </header>
    <div class="project-stack" id="portfolioGrid">
      <!-- Cards injected by portfolio.js -->
    </div>
  </div>
</section>

<footer class="site-footer" id="contact">
  <div>
    <h3>Let's connect!</h3>
    <p>Kevinliu20080620@gmail.com · @_anearlybirb</p>
  </div>
  <p>© 2025 Kevin Liu. All rights reserved.</p>
</footer>
