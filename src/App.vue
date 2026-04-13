<template>
  <div class="page">
    <a class="skipLink" href="#main">Skip to content</a>

    <header class="topbar">
      <div class="container topbarInner">
        <div class="brand">
          <div class="mark" aria-hidden="true">GD</div>
          <div class="brandText">
            <div class="brandName">GoDev Studio</div>
            <div class="brandTag">Web • Mobile • Automation</div>
          </div>
        </div>

        <nav class="nav" aria-label="Primary">
          <a href="#services">Services</a>
          <a href="#work">Work</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <main id="main" class="container">
      <section class="hero" aria-label="Intro">
        <div class="heroCard">
          <div class="avatar" aria-hidden="true">M</div>
          <div class="heroMeta">
            <h1 class="headline">Mitch Developer</h1>
            <p class="subhead">I build fast, modern websites that convert. Let’s ship something clean and reliable.</p>

            <ul class="quickFacts" aria-label="Highlights">
              <li>Vue 3 + Vite</li>
              <li>Responsive + accessible</li>
              <li>SEO-ready</li>
            </ul>

            <div class="ctaRow">
              <a class="btn primary" href="#contact">Get a quote</a>
              <a class="btn" href="#work">See work</a>
            </div>

            <div class="contactRow" aria-label="Contact links">
              <a class="chip" href="mailto:hello@example.com">hello@example.com</a>
              <a class="chip" href="tel:+10000000000">+1 (000) 000-0000</a>
              <a class="chip" href="https://github.com/" target="_blank" rel="noreferrer">GitHub</a>
              <a class="chip" href="https://www.linkedin.com/" target="_blank" rel="noreferrer">LinkedIn</a>
            </div>
          </div>
        </div>
      </section>

      <section id="services" class="section">
        <div class="sectionHead">
          <h2>Services</h2>
          <p>Simple packages that help you look professional and get leads.</p>
        </div>
        <div class="grid3" role="list">
          <article class="card" role="listitem">
            <h3>Landing pages</h3>
            <p>High-converting single-page sites with strong messaging and clear calls-to-action.</p>
          </article>
          <article class="card" role="listitem">
            <h3>Business websites</h3>
            <p>Multi-section sites with performance, accessibility, and SEO baked in.</p>
          </article>
          <article class="card" role="listitem">
            <h3>Site refresh</h3>
            <p>Modernize your existing site: layout polish, speed improvements, and mobile fixes.</p>
          </article>
        </div>
      </section>

      <section id="work" class="section">
        <div class="sectionHead">
          <h2>Work</h2>
          <p>A few example “tiles” you can replace with real projects.</p>
        </div>
        <div class="grid2" role="list">
          <article class="card" role="listitem">
            <h3>Local service site</h3>
            <p>Clean hero, pricing, testimonials, contact section. Optimized for mobile.</p>
            <div class="meta">Stack: Vue • Vite • Static</div>
          </article>
          <article class="card" role="listitem">
            <h3>Product teaser</h3>
            <p>Fast, lightweight marketing page with crisp typography and clear CTA.</p>
            <div class="meta">Stack: Vue • Vite • Static</div>
          </article>
        </div>
      </section>

      <section id="contact" class="section">
        <div class="sectionHead">
          <h2>Contact</h2>
          <p>Prefer email? Tap the button — no backend required.</p>
        </div>
        <div class="contactCard">
          <div>
            <div class="label">Email</div>
            <div class="value"><a href="mailto:hello@example.com">hello@example.com</a></div>
          </div>
          <div>
            <div class="label">Phone</div>
            <div class="value"><a href="tel:+10000000000">+1 (000) 000-0000</a></div>
          </div>
          <div class="contactActions">
            <a class="btn primary" href="mailto:hello@example.com?subject=Project%20inquiry">Email me</a>
            <a class="btn" href="#top" @click.prevent="() => window.scrollTo({ top: 0, behavior: 'smooth' })">Back to top</a>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="container footerInner">
        <div>© {{ new Date().getFullYear() }} GoDev Studio</div>
        <div class="footerLinks">
          <a href="#services">Services</a>
          <a href="#work">Work</a>
          <a href="#contact">Contact</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
// intentionally empty for now (static marketing site)
</script>
