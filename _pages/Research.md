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
            button.textContent = "Show Abstract";
        }
    }
</script>


In this page you can find my research. 


## Working Papers

<div class="research-card">
  <img src="/images/research_images/event_log_wages_MigML.png" alt="Event study of log wages">
  <div>
    <strong>Boosted Migration: The Effect of Migration on Low-Wage Workers</strong> <span class="paper-status">Submitted</span><br>
    <ul>
      <li><a href="/files/MigML.pdf">Working Paper Version</a></li>
      <li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5668270">SSRN</a></li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract1')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract1" class="abstract-content" style="display: none;">
      <p>  
This paper examines the labor market effects of Venezuelan migration on low-wage Colombian workers. Using nationally representative survey data from 2012 to 2019 and a machine learning model to classify workers by their predicted probability of being in the lower tail of the wage distribution, I implement a Triple Differences-in-Differences strategy to estimate causal impacts across cities with varying levels of migrant exposure. The main finding is that, although migration had no significant effects on employment formality or self-employment, it did lead to a decline in wages among low-wage natives in high-migration cities. This effect is robust to alternative definitions of treatment and control groups. This finding suggests that immigration can exert downward pressure on earnings at the lower end of the wage distribution  and underscore the importance of protecting vulnerable groups during large-scale displacement events. 
</p>
    </div>
  </div>
</div>


## Other Papers

<div class="research-card">
  <div>
    <strong>Comparing Human-Only, AI-Assisted, and AI-Led Teams on Assessing Research Reproducibility in Quantitative Social Science</strong><br>
    <span class="paper-authors">Abel Brodeur, David Valenta, Alexandru Marcoci, Juan P. Aparicio, Derek Mikola, Bruno Barbarioli, Rohan Alexander, Lachlan Deer, Tom Stafford</span><br>
    <span class="paper-venue">IZA Discussion Paper No. 17645, January 2025</span>
    <ul>
      <li><a href="https://docs.iza.org/dp17645.pdf">IZA Discussion Paper</a></li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract2')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract2" class="abstract-content" style="display: none;">
      <p>
This study evaluates the effectiveness of varying levels of human and artificial intelligence (AI) integration in reproducibility assessments. We computationally reproduced quantitative results from published articles in the social sciences with 288 researchers, randomly assigned to 103 teams across three groups — human-only teams, AI-assisted teams and teams whose task was to minimally guide an AI to conduct reproducibility checks (the "AI-led" approach). Findings reveal that when working independently, human teams matched the reproducibility success rates of teams using AI assistance, while both groups substantially outperformed AI-led approaches (with human teams achieving 57 pp higher success rates than AI-led teams). Human teams found significantly more major errors compared to both AI-assisted teams and AI-led teams. AI-assisted teams demonstrated an advantage over more automated approaches, detecting 0.4 more major errors per team than AI-led teams, though still significantly fewer than human-only teams. Finally, both human and AI-assisted teams significantly outperformed AI-led approaches in both proposing and implementing comprehensive robustness checks.
</p>
    </div>
  </div>
</div>


### Check my Master Thesis:

<div class="research-card">
  <img src="/images/research_images/exclution_r.jpg" alt="Image related to Commodity Price Shocks">
  <div>
    <strong>Commodity Price Shocks, Factor Intensity and Non-primary Production Growth: Evidence from Colombia.</strong><br>
    <ul>
      <li>Latest version: <a href="/files/Commodity_price_Rengifo.pdf">PDF</a></li>
      <li>Uniandes Repository: <a href="https://repositorio.uniandes.edu.co/entities/publication/71893776-ea19-4290-909b-341633836cce">PDF</a></li>
    </ul>
  </div>
</div>



