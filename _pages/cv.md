---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a class="btn btn--primary" href="{{ '/files/cv.pdf' | relative_url }}">Download CV</a></p>

<div class="cv-viewer">
  <object class="cv-viewer__frame" data="{{ '/files/cv.pdf' | relative_url }}" type="application/pdf" aria-label="Curriculum vitae of Jiayi (Maggie) Shao">
    <p><a href="{{ '/files/cv.pdf' | relative_url }}">Download CV</a></p>
  </object>
</div>

<style>
  .cv-viewer {
    margin-top: 1rem;
  }

  .cv-viewer__frame {
    display: block;
    width: 100%;
    height: 80vh;
    min-height: 32rem;
    border: 1px solid var(--global-border-color);
    border-radius: 4px;
  }

  @media (max-width: 700px) {
    .cv-viewer__frame {
      height: 70vh;
      min-height: 24rem;
    }
  }
</style>
