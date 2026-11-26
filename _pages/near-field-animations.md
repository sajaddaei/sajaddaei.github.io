---
layout: page
title: Near-field animations
permalink: /near-field-animations/
description: Animated demonstrations of metric-dependent near/far-field transition boundaries.
nav: false
---

<style>
.sd-animations{--a-text:var(--global-text-color,#18364a);--a-muted:var(--global-text-color-light,#466176);--a-border:var(--global-divider-color,#dce8ee);--a-card:var(--global-card-bg-color,var(--global-bg-color,#fff));max-width:100%;color:var(--a-text);line-height:1.6}
.sd-animations *{box-sizing:border-box}
.sd-animations .sa-intro{background:radial-gradient(ellipse at 100% 0%,#c8f0ee,transparent 65%),linear-gradient(120deg,#f7fbfe,#eaf4fa);border:1px solid #d7e9ee;border-radius:18px;padding:clamp(1.15rem,4vw,2rem);margin-bottom:1.45rem;color:#18364a}
.sd-animations .sa-kicker{font-size:.76rem;letter-spacing:.1em;text-transform:uppercase;font-weight:750;color:#087b86;margin:0 0 .6rem}
.sd-animations h2{font:700 clamp(1.35rem,3vw,1.9rem)/1.25 Georgia,serif;letter-spacing:-.018em;margin:.2rem 0 .65rem;color:inherit}
.sd-animations p{margin:0 0 .8rem}
.sd-animations .sa-card{background:var(--a-card);border:1px solid var(--a-border);border-radius:16px;overflow:hidden;margin:0 0 1.4rem;box-shadow:0 4px 18px rgba(24,67,91,.07)}
.sd-animations .sa-copy{padding:clamp(1rem,3vw,1.5rem)}
.sd-animations .sa-meta{color:var(--a-muted);font-size:.83rem;margin:0 0 .45rem}
.sd-animations video{display:block;width:100%;aspect-ratio:16/9;height:auto;background:#fff;border-top:1px solid var(--a-border);border-bottom:1px solid var(--a-border)}
.sd-animations .sa-actions{display:flex;gap:.65rem 1.2rem;flex-wrap:wrap;padding:1rem 1.35rem;font-size:.88rem}
.sd-animations a{color:var(--global-theme-color,#087b86);text-decoration:underline;text-underline-offset:3px}
.sd-animations a:focus-visible{outline:2px solid #13a7a5;outline-offset:3px}
</style>

<div class="sd-animations" markdown="0">
  <div class="sa-intro">
    <p class="sa-kicker">Near-field communications &amp; sensing</p>
    <h2>When Near Becomes Far</h2>
    <p>Two animated slides from <em>From Rayleigh to Optimal Near/Far-Field Boundaries</em>. Both original animations play automatically when supported by your browser. Use the controls to pause, replay, seek or enter fullscreen.</p>
    <p style="margin-bottom:0"><a href="{{ '/assets/pdf/GLOBECOM_2025_Near_Far_Field.pdf' | relative_url }}">Full presentation (PDF)</a> &nbsp;·&nbsp; <a href="https://arxiv.org/abs/2505.07743">Related research paper</a> &nbsp;·&nbsp; <a href="{{ '/talks/' | relative_url }}">All talks and presentations</a></p>
  </div>
  <article class="sa-card" id="slide-5">
    <div class="sa-copy"><p class="sa-meta">Slide 5 · 6 seconds · 60 frames · 10 fps</p><h2>Boundary depends on the metric</h2><p>The moving user crosses metric-dependent transition boundaries. The original slide illustrates the near-field, transition and within-tolerance regions for the same geometry.</p></div>
    <video autoplay muted controls playsinline loop preload="metadata" poster="{{ '/assets/video/metric-dependent-boundaries.webp' | relative_url }}" aria-label="Boundary depends on the metric">
      <source src="{{ '/assets/video/metric-dependent-boundaries.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support embedded video. Use the MP4 link below.
    </video>
    <div class="sa-actions"><a href="{{ '/assets/video/metric-dependent-boundaries.mp4' | relative_url }}" download>Download animation (MP4)</a><a href="{{ '/assets/pdf/GLOBECOM_2025_Near_Far_Field.pdf' | relative_url }}#page=5">View original slide (PDF)</a></div>
  </article>
  <article class="sa-card" id="slide-12">
    <div class="sa-copy"><p class="sa-meta">Slide 12 · 24 seconds · 120 frames · 5 fps</p><h2>Two Links, Three Metrics: Walking Through the Near–Far Transition</h2><p>Two links at 10 GHz with 5 and 64 receive antennas. Follow the changing distance and the element-wise mismatch, normalized ℓ₂ mismatch and spectral-efficiency loss as the user moves across the boundaries.</p></div>
    <video autoplay muted controls playsinline loop preload="metadata" poster="{{ '/assets/video/two-links-three-metrics.webp' | relative_url }}" aria-label="Two Links, Three Metrics: Walking Through the Near–Far Transition">
      <source src="{{ '/assets/video/two-links-three-metrics.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support embedded video. Use the MP4 link below.
    </video>
    <div class="sa-actions"><a href="{{ '/assets/video/two-links-three-metrics.mp4' | relative_url }}" download>Download animation (MP4)</a><a href="{{ '/assets/pdf/GLOBECOM_2025_Near_Far_Field.pdf' | relative_url }}#page=12">View original slide (PDF)</a></div>
  </article>
</div>
