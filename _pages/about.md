---
layout: home
permalink: /
title: "Andrés Rengifo"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<section class="hero">
  <div class="hero__text">
    <p class="hero__eyebrow">Hi there!</p>
    <h1 class="hero__name">Andrés Felipe<br>Rengifo Jaramillo</h1>
    <p class="hero__tagline">Economist interested in Causal Inference, Econometrics, Data Science and Labor Economics.</p>
    <p class="hero__bio">
      Currently, I am a Senior Research Associate at <a href="https://goodbusinesslablatam.org/">Good Business Lab Latin America</a>.
      Previously I was a research assistant at Harvard Business School <a href="https://d3.harvard.edu/labs/digital-reskilling-lab/">Digital Reskilling Lab</a>.
      I also worked at the Business Department at Universidad de los Andes.
    </p>
    <div class="hero__actions">
      <a class="hero__btn hero__btn--solid" href="/research/">See my research</a>
      <a class="hero__btn" href="/cv/">CV</a>
      {% if site.author.googlescholar %}<a class="hero__btn" href="{{ site.author.googlescholar }}">Google Scholar</a>{% endif %}
      {% if site.author.orcid %}<a class="hero__btn" href="{{ site.author.orcid }}">ORCID</a>{% endif %}
      {% if site.author.email %}<a class="hero__btn" href="mailto:{{ site.author.email }}">Email</a>{% endif %}
    </div>
    <ul class="hero__chips">
      <li>Causal Inference</li>
      <li>Econometrics</li>
      <li>Machine Learning</li>
      <li>Labor Economics</li>
    </ul>
  </div>

  <div class="hero__photo">
    <div class="hero__arch" aria-hidden="true"></div>
    <img src="/images/profile3.jpg" alt="Portrait of Andrés Rengifo">
    <span class="hero__badge"><i class="fa-solid fa-location-dot" aria-hidden="true"></i> Colombia</span>
  </div>
</section>

<section class="home-grid">
  <article class="home-card">
    <span class="home-card__icon">🎓</span>
    <h2>Background</h2>
    <p>MSc in Economics from Universidad de los Andes and a Bachelor’s degree from Universidad del Valle. I was the Teaching Assistant (TA) for the course Big Data and Machine Learning at Universidad de los Andes.</p>
  </article>

  <article class="home-card">
    <span class="home-card__icon">🔭</span>
    <h2>Right now</h2>
    <p>I’m working with firm's administrative data to understand how to improve managerial practices.</p>
  </article>

  <article class="home-card">
    <span class="home-card__icon">🌱</span>
    <h2>Learning</h2>
    <p>New Big Data and Machine Learning techniques and how to apply them to interesting Economic questions.</p>
  </article>

  <article class="home-card">
    <span class="home-card__icon">💬</span>
    <h2>Let’s collaborate</h2>
    <p>Have an idea and want to collaborate? Feel free to <a href="mailto:{{ site.author.email }}">send me an email</a>.</p>
  </article>
</section>

<aside class="home-fun">
  <span class="home-fun__icon">⚡</span>
  <p><strong>Fun fact:</strong> I want to be a writer, but with the advent of AI, I don’t know if there will still be room for a human—imperfect and messy—writer.</p>
</aside>
