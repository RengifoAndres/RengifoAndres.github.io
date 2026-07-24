---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<script>
    function toggleAbstract(button, abstractId) {
        var abstract = document.getElementById(abstractId);
        
        if (abstract.style.display === "none" || abstract.style.display === "") {
            abstract.style.display = "block";
            button.textContent = "Hide Abstract";
        } else {
            abstract.style.display = "none";
            button.textContent = "Abstract";
        }
    }
</script>


In this page you can find my research. 


## Working Papers

<div class="research-card">
  <div class="research-card__main">
    <div class="research-card__image">
      <img src="/images/research_images/bunching.png" alt="Bunching estimates for Boosted Migration">
    </div>
    <div class="research-card__body">
      <span class="research-card__title">Boosted Migration: The Effect of Migration on Low-Wage Workers</span>
      <div class="research-card__links">
        <button class="toggle-button" onclick="toggleAbstract(this, 'abstract1')">Abstract</button>
        <a class="paper-link" href="/files/MigML.pdf">Paper</a>
        <a class="paper-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5668270">SSRN</a>
      </div>
    </div>
    <div class="research-card__meta">
      <span class="paper-status">Status: Revise &amp; Resubmit,<br>Labour Economics</span>
    </div>
  </div>
  <div id="abstract1" class="abstract-content" style="display: none;">
    <p>
This paper estimates the causal effect of Venezuelan migration on the wage distribution of low-wage Colombian workers following the 2016 border reopening. Combining a machine-learning-based exposure measure with a grouped difference-in-differences design, I find that the shock increases the probability of being at the bottom of the wage distribution by 3.1 percentage points, alongside a corresponding decline of 3.1 percentage points just below the minimum wage; both effects are statistically significant at the 1 percent level.
The effect is concentrated in industries where the minimum wage binds tightly and informality is high. 
A placebo group with low predicted exposure, but subject to the same local labor market shocks, exhibits no changes across wage bins, and a battery of sensitivity checks rules out selective worker sorting across cities, differential minimum-wage bindingness, and dependence on the training year of the classifier. The shock does not raise unemployment but increases labor-force participation by 3.5 percentage points among the most exposed workers. 
</p>
  </div>
</div>

<div class="research-card">
  <div class="research-card__main">
    <div class="research-card__image">
      <img src="/images/research_images/coming_soon.svg" alt="Draft coming soon">
    </div>
    <div class="research-card__body">
      <span class="research-card__title">Longer School Day and Student Trajectories: Short and Long-Run Evidence from Colombia's Jornada Unica</span>
      <div class="research-card__links">
        <button class="toggle-button" onclick="toggleAbstract(this, 'abstract3')">Abstract</button>
      </div>
    </div>
    <div class="research-card__meta">
      <span class="paper-status">Status: Draft<br>Available Soon</span>
    </div>
  </div>
  <div id="abstract3" class="abstract-content" style="display: none;">
    <p>
We study Colombia's Jornada Unica (JU), a reform that converts public schools from half-day shifts to a single full day, exploiting its staggered roll-out across schools between 2015 and 2019. Using an event-study design, we estimate the effect of adopting JU on (i) Saber 11 exit-exam scores in the short run and (ii) higher-education outcomes in the long run. We find small but positive and statistically significant effects on test scores across subjects. These gains are driven by an increase in the share of students in the upper tail of the score distribution and a corresponding decrease in the lower tail. The improvement in scores does not translate into higher overall enrollment in tertiary education; instead, it lowers the probability of enrolling in a technological program. The results are robust to using never-treated rather than not-yet-treated schools as the comparison group.
</p>
  </div>
</div>


## Other Papers

<div class="research-card">
  <div class="research-card__main">
    <div class="research-card__body">
      <span class="research-card__title">Comparing Human-Only, AI-Assisted, and AI-Led Teams on Assessing Research Reproducibility in Quantitative Social Science</span>
      <span class="research-card__authors">with Abel Brodeur, David Valenta, Alexandru Marcoci, Juan P. Aparicio, Derek Mikola, Bruno Barbarioli, Rohan Alexander, Lachlan Deer, Tom Stafford</span>
      <div class="research-card__links">
        <button class="toggle-button" onclick="toggleAbstract(this, 'abstract2')">Abstract</button>
        <a class="paper-link" href="/files/brodeur-et-al-2026-ai-assisted-teams.pdf">Published Version</a>
        <a class="paper-link" href="https://docs.iza.org/dp17645.pdf">IZA Discussion Paper</a>
      </div>
    </div>
    <div class="research-card__meta">
      <span class="paper-date">2025</span>
      <span class="paper-status">Published in PNAS</span>
    </div>
  </div>
  <div id="abstract2" class="abstract-content" style="display: none;">
    <p>
This study evaluates the effectiveness of varying levels of human and artificial intelligence (AI) integration in reproducibility assessments. We computationally reproduced quantitative results from published articles in the social sciences with 288 researchers, randomly assigned to 103 teams across three groups — human-only teams, AI-assisted teams and teams whose task was to minimally guide an AI to conduct reproducibility checks (the "AI-led" approach). Findings reveal that when working independently, human teams matched the reproducibility success rates of teams using AI assistance, while both groups substantially outperformed AI-led approaches (with human teams achieving 57 pp higher success rates than AI-led teams). Human teams found significantly more major errors compared to both AI-assisted teams and AI-led teams. AI-assisted teams demonstrated an advantage over more automated approaches, detecting 0.4 more major errors per team than AI-led teams, though still significantly fewer than human-only teams. Finally, both human and AI-assisted teams significantly outperformed AI-led approaches in both proposing and implementing comprehensive robustness checks.
</p>
  </div>
</div>


## Master Thesis

<div class="research-card">
  <div class="research-card__main">
    <div class="research-card__image">
      <img src="/images/research_images/exclution_r.jpg" alt="Image related to Commodity Price Shocks">
    </div>
    <div class="research-card__body">
      <span class="research-card__title">Commodity Price Shocks, Factor Intensity and Non-primary Production Growth: Evidence from Colombia</span>
      <div class="research-card__links">
        <a class="paper-link" href="/files/Commodity_price_Rengifo.pdf">Paper</a>
        <a class="paper-link" href="https://repositorio.uniandes.edu.co/entities/publication/71893776-ea19-4290-909b-341633836cce">Uniandes Repository</a>
      </div>
    </div>
    <div class="research-card__meta">
      <span class="paper-status">MSc Thesis,<br>Universidad de los Andes</span>
    </div>
  </div>
</div>
