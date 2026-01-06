---
layout: page
permalink: /tools/
title: TOOLS
description: 
nav: true
nav_order: 3
---


<script>
  document.title = "Resources: Andrea Pop-Catalisan";
</script>

<style>
body {
  background-color: #FFF9F7;
}
  /* Top fixed bar background */
.navbar, .navbar-fixed-top {
  background-color: #FFF9F7 !important;
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
  gap: 30px;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  margin-bottom: 20px;
">

  <!-- Card 1 -->
  <div
    onclick="window.open('https://andreapopcatalisan.shinyapps.io/average-age-when-leaving-home', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 460px;
      background: #fff;
      display: flex;
      margin-bottom: 45px;
      flex-direction: column;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 3px 8px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 1px 4px rgba(0,0,0,0.1)'"
  >
    <h3 style="margin: 0 0 8px 0; font-size: 1rem; color: #BF245F;">
     Average Age at Moving-Out in Europe (2000–2024)
    </h3>

    <img
      src="https://andreapopcatalisan.github.io/assets/img/eurostat.png"
      alt="Eurostat"
      style="
        width: 100%;
        height: auto; /* lets height adjust automatically */
        max-height: 170px; /* max height for large screens */
        object-fit: cover;
        border-radius: 2px;
        margin: 6px 0;
      "
    >

  <p style="font-size: 0.85rem; line-height: 1.35; margin: 6px 0;">
 An interactive visualization tool to explore the estimated average age of leaving the parental home across Europe (sources: EU-SILC & EU-LFS).
</p>

<p style="font-size: 0.75rem; line-height: 1.3; margin: 4px 0; font-style: italic;">
  Under development for the years 1990–1999.
</p>

    <p style="margin-top: auto; font-size: 0.85rem;">
      <strong>
        <a href="https://github.com/andreapopcatalisan/average-age-when-leaving-home" target="_blank">
          Code & Data →
        </a>
      </strong>
    </p>
  </div>


<!-- Card 2 -->
<a href="https://andreapopcatalisan.shinyapps.io/average-age-at-first-marriage" target="_blank" style="text-decoration: none; color: inherit;">
  <div
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      background: #fff;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 100%;
      max-width: 460px;
      display: flex;
      flex-direction: column;
      margin: 0 auto 45px auto;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 3px 8px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 1px 4px rgba(0,0,0,0.1)'"
  >
    <h3 style="margin: 0 0 8px 0; font-size: 1rem; color: #BF245F;">
      Average Age at Marriage in Europe (2013–2013)
    </h3>

    <img
      src="https://andreapopcatalisan.github.io/assets/img/marriage.png"
      alt="Eurostat"
      style="
        width: 100%;
        height: auto; /* lets height adjust automatically */
        max-height: 190px; /* max height for large screens */
        object-fit: cover;
        border-radius: 2px;
        margin: 6px 0;
      "
    >

    <p style="font-size: 0.85rem; line-height: 1.35; margin: 6px 0;">
      An interactive visualization tool to explore the estimated average age of marriage across Europe (sources: EU-SILC).
    </p>

    <p style="margin-top: auto; font-size: 0.85rem;">
      <strong>
        <a href="https://github.com/andreapopcatalisan/average-age-first-marriage" target="_blank">
          Code & Data →
        </a>
      </strong>
    </p>
  </div>
</a>



 <!-- Card 3 -->
  <div
    onclick="window.open('https://andreapopcatalisan.shinyapps.io/age_first_birth', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 460px;
      background: #fff;
      display: flex;
      margin-bottom: 45px;
      flex-direction: column;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 3px 8px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 1px 4px rgba(0,0,0,0.1)'"
  >
    <h3 style="margin: 0 0 8px 0; font-size: 1rem; color: #BF245F;">
    Average Age at First Birth in Europe (2012–2023)
    </h3>

    <img
      src="https://andreapopcatalisan.github.io/assets/img/birth.png"
      alt="Eurostat"
      style="
        width: 100%;
        height: auto; /* lets height adjust automatically */
        max-height: 22px; /* max height for large screens */
        object-fit: cover;
        border-radius: 2px;
        margin: 6px 0;
      "
    >

  <p style="font-size: 0.85rem; line-height: 1.35; margin: 6px 0;">
 An interactive visualization tool to explore the estimated average age at first birth across Europe (sources: EU-SILC & EU-LFS).
</p>

    <p style="margin-top: auto; font-size: 0.85rem;">
      <strong>
        <a href="https://github.com/andreapopcatalisan/age_at_first_birth" target="_blank">
          Code & Data →
        </a>
      </strong>
    </p>
  </div>





  <!-- Card 4 -->
<a href="https://andreapopcatalisan.shinyapps.io/eurotravels-master/" target="_blank" style="text-decoration: none; color: inherit;">
  <div
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 6px;
      background: #fff;
      padding: 16px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      transition: transform 0.15s, box-shadow 0.15s;
      width: 460px;
      display: flex;
      margin-bottom: 45px;
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
        height: 150px;
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
        <a href="https://github.com/andreapopcatalisan/euroTrips" target="_blank" onclick="event.stopPropagation();" style="text-decoration: none; color: #BF245F;">
          Code →
        </a>
      </strong>
    </p>
  </div>
</a>






