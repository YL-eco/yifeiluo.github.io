---
layout: default
title: Home
---

{% include nav.html %}

<div class="hero">
  <img src="/assets/img/profile.jpg" alt="{{ site.author.name }}" class="avatar">
  <div>
    <h1>{{ site.author.name }}</h1>
    <p class="small">
      <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> ·
      <a href="{{ site.author.ssrn }}">SSRN</a> ·
      <a href="https://scholar.google.com/" target="_blank">Google Scholar</a> ·
      <a href="https://github.com/yifeiluo">GitHub</a> ·
      <a href="/cv">CV</a>
    </p>
  </div>
</div>

<p style="margin-top:14px;">
I study political economy and economic history, with an emphasis on how historical shocks shape modern institutions, identity, and economic behavior. How bounded rationality, misspecified model, and cultural evolution collaboratively affect social norm, limits technological advancement. My recent work incorporates: misspecified model affecting belief system, political capture of religious interpretive power, norm and AI usage, and a little bit network theory.
</p>

<footer class="site-footer">
  © {{ site.time | date: "%Y" }} {{ site.author.name }}
</footer>
