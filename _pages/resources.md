---
layout: page
permalink: /resources/
title: RESOURCES
description: 
nav: true
nav_order: 3
---


<script>
  document.title = "Resources: Andrea Pop-Catalisan";
</script>

<style>
body {
  background-color: #FFFCFB;
}
  /* Top fixed bar background */
.navbar, .navbar-fixed-top {
  background-color: #FFF6F4 !important;
}
</style>
  

<!-- Section title -->
<div style="text-align: center; font-family: 'EB Garamond', serif;">
  <h2 style="
    display: inline-block;
    margin-bottom: 1.2em;
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 0.5px;
  ">
    Resources & Codes
  </h2>
</div>

<!-- Cards container -->
<div style="
  display: flex;
  gap: 20px;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  margin-bottom: 30px;
">

  <!-- Card 1 -->
  <div
    onclick="window.open('https://andreapopcatalisan.shinyapps.io', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 460px;
      display: flex;
      flex-direction: column;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 3px 8px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 1px 4px rgba(0,0,0,0.1)'"
  >
    <h3 style="margin: 0 0 8px 0; font-size: 1rem; color: #BF245F;">
      Age at Leaving the Parental Home in Europe (2005–2019)
    </h3>

    <img
      src="https://andreapopcatalisan.github.io/assets/img/eurostat.png"
      alt="Eurostat"
      style="
        width: 100%;
        height: 160px;
        object-fit: cover;
        border-radius: 2px;
        margin: 6px 0;
      "
    >

    <p style="font-size: 0.85rem; line-height: 1.35; margin: 6px 0;">
      Interactive Shiny dashboard visualizing cross-country differences in the
      average age of leaving the parental home in Europe (Source: EU-SILC).
    </p>

    <p style="margin-top: auto; font-size: 0.85rem;">
      <strong>
        <a href="https://github.com/andreapopcatalisan" target="_blank">
          Code coming soon →
        </a>
      </strong>
    </p>
  </div>

  <!-- Card 2 -->
  <div
    onclick="window.open('https://andreapopcatalisan.shinyapps.io/eurotravels-master/', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 460px;
      display: flex;
      flex-direction: column;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 3px 8px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 1px 4px rgba(0,0,0,0.1)'"
  >
    <h3 style="margin: 0 0 8px 0; font-size: 1rem; color: #BF245F;">
      Travel patterns across Europe
    </h3>

    <img
      src="https://andreapopcatalisan.github.io/assets/img/mapa.png"
      alt="EuroTravels map preview"
      style="
        width: 100%;
        height: 160px;
        object-fit: cover;
        border-radius: 2px;
        margin: 6px 0;
      "
    >

    <p style="font-size: 0.85rem; line-height: 1.35; margin: 6px 0;">
      Interactive Shiny dashboard exploring my travel patterns across European
      countries.
    </p>

    <p style="margin-top: auto; font-size: 0.85rem;">
      <strong>
        <a href="https://github.com/andreapopcatalisan/world-happiness-prediction" target="_blank">
          Code →
        </a>
      </strong>
    </p>
  </div>

</div>




