---
permalink: /
title: "About"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="home-intro">
  <header class="home-intro__header">
    <h1 class="home-intro__name">Jiayi (Maggie) Shao</h1>
    <p class="home-intro__affiliation">UbiComp Lab, Electrical and Computer Engineering, University of Washington</p>
    {% if site.author.github or site.author.email %}
    <p class="home-intro__links">
      {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}">GitHub</a>
      {% endif %}
      {% if site.author.github and site.author.email %}
      <span class="home-intro__dot" aria-hidden="true">·</span>
      {% endif %}
      {% if site.author.email %}
      <a href="mailto:{{ site.author.email }}">Email</a>
      {% endif %}
    </p>
    {% endif %}
  </header>

  <div class="home-intro__body">
    <img class="home-intro__photo" src="{{ '/images/jiayi-profile.jpg' | relative_url }}" alt="Jiayi (Maggie) Shao" width="2376" height="2376">
    <div class="home-intro__text" markdown="1">

I am currently a Research Scientist/Engineer at the [Paul G. Allen School of Computer Science & Engineering](https://www.cs.washington.edu/) at the University of Washington, working with Prof. [Vikram Iyer](https://homes.cs.washington.edu/~vsiyer/). I joined the [UbiComp Lab](https://ubicomplab.cs.washington.edu/) during my master's studies and received my M.S. in Electrical and Computer Engineering from the University of Washington. My current work includes a collaboration with General Motors on low-power, multimodal edge sensing for vehicle safety. I also collaborate with Prof. [Qiuyue (Shirley) Xue](https://xueqiuyue.com/) at Purdue University and Prof. [Tingyu Cheng](https://tingyucheng.com/) at the University of Notre Dame.

I'm broadly interested in ubiquitous computing, wearable sensing, and intelligent embedded systems. I enjoy building end-to-end sensing systems, from hardware design and sensor integration to embedded firmware and on-device machine learning. I'm particularly interested in combining on-device intelligence with ultra-low-power and battery-free computing to make intelligent sensing systems more practical for everyday use.

**I am applying to PhD programs for Fall 2027**.

    </div>
  </div>
</div>
