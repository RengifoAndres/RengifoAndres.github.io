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
     <img src="/images/research_images/event_log_wages_MigML.png" alt="Event" style="width: 290px; height: auto; margin-right: 20px;">
  <div>
    <strong>Boosted Migration: The Effect of Venezuelan Exodus on Low-Wage Native Employees</strong> Submitted <br>
    <ul>
      <li>  <a href="/files/MigML.pdf"> Working Paper Version</a> </li>
    </ul>
    <!-- Button to toggle abstract -->
    <button class="toggle-button" onclick="toggleAbstract(this, 'abstract1')">Abstract</button>
    
    <!-- Abstract content -->
    <div id="abstract1" class="abstract-content" style="display: none; margin-top: 10px;">
      <p>  
This paper examines the labor market effects of Venezuelan migration on low-wage Colombian workers. Using nationally representative survey data from 2012 to 2019 and a machine learning model to classify workers by their predicted probability of being in the lower tail of the wage distribution, I implement a Triple Differences-in-Differences strategy to estimate causal impacts across cities with varying levels of migrant exposure. The main finding is that, although migration had no significant effects on employment formality or self-employment, it did lead to a decline in wages among low-wage natives in high-migration cities. This effect is robust to alternative definitions of treatment and control groups. This finding suggests that immigration can exert downward pressure on earnings at the lower end of the wage distribution  and underscore the importance of protecting vulnerable groups during large-scale displacement events. 
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



