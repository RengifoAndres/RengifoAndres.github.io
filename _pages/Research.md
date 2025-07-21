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
    <img src="/images/research_images/pr_re_auc.jpg" alt="AUC FOR MODELS" style="width: 290px; height: auto; margin-right: 20px;">
     <img src="/images/research_images/ML_MIG_robuss.jpg" alt="AUC FOR MODELS" style="width: 290px; height: auto; margin-right: 20px;">
  <div>
    <strong>Boosted Migration: The Effect of Venezuelan Exodus on Low-Wage Native Employees</strong><br>
    <ul>
      <li>Draft Coming soon</li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract1')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract1" class="abstract-content" style="display: none; margin-top: 10px;">
      <p>  This paper examines the short-run labor market effects of Venezuelan migration on low-wage Colombian workers following the 2016 reopening of the border between the two countries. Using nationally representative household survey data from 2012 to 2019 and a machine learning model to classify workers by their predicted probability of being low-wage, I implement a triple-differences (DDD) strategy to estimate causal impacts across cities with varying levels of migrant exposure. The main finding is that, although migration had no significant effects on employment formality, contract type, or self-employment, it did lead to a decline in log wages among low-wage natives in high-migration cities. This effect is robust to alternative definitions of treatment and control groups and persists across multiple model specifications. This suggests that immigration can exert downward pressure on earnings at the lower end of the wage distribution. This last results contradict previous studies carried out in the same context. I suggest that this is due to the lack of a robust identification technique, and provide evidence in that direction.  The findings contribute to growing evidence on the distributional consequences of migration in middle-income countries and underscore the importance of protecting vulnerable groups during large-scale displacement events.
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



