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

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
     <img src="/images/research_images/bunching.png" alt="Event" style="width: 290px; height: auto; margin-right: 20px;">
  <div>
    <strong>Boosted Migration: The Effect of Migration on Low-Wage Workers</strong> Submitted <br>
    <ul>
      <li>  <a href="/files/MigML.pdf"> Working Paper Version</a> </li>
    </ul>
     <ul>
      <li>  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5668270">SSRN</a> </li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract1')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract1" class="abstract-content" style="display: none; margin-top: 10px;">
      <p>  
This paper estimates the causal effect of Venezuelan migration on the wage distribution of low-wage Colombian workers following the 2016 border reopening. Combining a machine-learning-based exposure measure with a grouped difference-in-differences design, I find that the shock increases the probability of being at the bottom of the wage distribution by 3.1 percentage points, alongside a corresponding decline of 3.1 percentage points just below the minimum wage; both effects are statistically significant at the 1 percent level.
The effect is concentrated in industries where the minimum wage binds tightly and informality is high. 
A placebo group with low predicted exposure, but subject to the same local labor market shocks, exhibits no changes across wage bins, and a battery of sensitivity checks rules out selective worker sorting across cities, differential minimum-wage bindingness, and dependence on the training year of the classifier. The shock does not raise unemployment but increases labor-force participation by 3.5 percentage points among the most exposed workers. 
</p>
    </div>
  </div>
</div>



## Other Papers

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div>
    <strong>Comparing Human-Only, AI-Assisted, and AI-Led Teams on Assessing Research Reproducibility in Quantitative Social Science</strong><br>
    Abel Brodeur, David Valenta, Alexandru Marcoci, Juan P. Aparicio, Derek Mikola, Bruno Barbarioli, Rohan Alexander, Lachlan Deer, Tom Stafford <br>
    <em>IZA Discussion Paper No. 17645, January 2025</em>
    <ul>
      <li><a href="https://docs.iza.org/dp17645.pdf">IZA Discussion Paper</a></li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract2')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract2" class="abstract-content" style="display: none; margin-top: 10px;">
      <p>
This study evaluates the effectiveness of varying levels of human and artificial intelligence (AI) integration in reproducibility assessments. We computationally reproduced quantitative results from published articles in the social sciences with 288 researchers, randomly assigned to 103 teams across three groups — human-only teams, AI-assisted teams and teams whose task was to minimally guide an AI to conduct reproducibility checks (the "AI-led" approach). Findings reveal that when working independently, human teams matched the reproducibility success rates of teams using AI assistance, while both groups substantially outperformed AI-led approaches (with human teams achieving 57 pp higher success rates than AI-led teams). Human teams found significantly more major errors compared to both AI-assisted teams and AI-led teams. AI-assisted teams demonstrated an advantage over more automated approaches, detecting 0.4 more major errors per team than AI-led teams, though still significantly fewer than human-only teams. Finally, both human and AI-assisted teams significantly outperformed AI-led approaches in both proposing and implementing comprehensive robustness checks.
</p>
    </div>
  </div>
</div>


### Check my Master Thesis:
<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/research_images/exclution_r.jpg" alt="Image related to Commodity Price Shocks" style="width: 250px; height: auto; margin-right: 20px;">
  <div>
    <strong>Commodity Price Shocks, Factor Intensity and Non-primary Production Growth: Evidence from Colombia.</strong><br>
 <ul>
      <li>Latest version: <a href="/files/Commodity_price_Rengifo.pdf">PDF</a></li>
      <li>Uniandes Repository: <a href="https://repositorio.uniandes.edu.co/entities/publication/71893776-ea19-4290-909b-341633836cce">PDF</a></li>
    </ul>
  </div>
</div>



