---
layout: page
permalink: /research/
title: RESEARCH
nav: true
nav_order: 1
---

<script>
  document.title = "Research: Andrea Pop-Catalisan";
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
  

<link href="https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap" rel="stylesheet">

<link href="https://fonts.googleapis.com/css2?family=STIX+Two+Text:wght@400;600&display=swap" rel="stylesheet"> 

<style>
  .container .jumbotron {
    padding-top: 12px; 
    padding-bottom: 8px; 
    padding-left: 20px; 
    padding-right: 20px; 
    display: flex; /* Enable flexbox layout */
    flex-direction: row; /* Default for larger screens, image next to text */
  }

  .jumbotron.no-image {
    display: block; /* Use block display for jumbotrons without images */
  }

  .jumbotron img {
    flex: 0 0 20%; /* Adjust the size of the image as needed */
    max-width: 30%; /* Make the image responsive to its container */
    height: auto; /* Maintain aspect ratio */
    margin-top: auto; /* Center vertically */
    margin-bottom: auto; /* Center vertically */
    margin-right: 12px; /* Space between the image and text */
  }

  .text-container {
    flex: 1;
    max-width: 80%; /* Adjust to ensure text fits next to the image */
  }

  @media (max-width: 768px) {
    .container .jumbotron {
        flex-direction: column; /* Stack the image and text vertically */
    }
    
    .jumbotron img {
        max-width: 100%; /* Image takes full width in mobile view */
        margin-right: 0; /* Remove right margin */
        margin-bottom: 15px; /* Add space between image and text */
    }
    
    .text-container {
        max-width: 100%; /* Ensure text takes full width */
    }
  }

  .btn-ssrn {
    display: inline-block;
    padding: 5px 5px; /* Adjust padding as needed */
    background-color: #e5e5e5; /* Same as background color */
    color: #1C1C1D; /* Button text color */
    text-decoration: none;
    border: 0px solid #8e7bd0; /* Button border color */
    border-radius: 10px; /* Make borders round */
    font-size: 11px;
    margin-left: 10px; /* Adjust margin as needed */
  }

  .btn-ssrn:hover {
    background-color: #CF8852; /* Hover background color */
    color: #1C1C1D;
  }

  .paper-title {
    display: inline-block;
    font-weight: bold;
  }

  .paper-title a {
    color: #BF245F; /* Match the default link color */
    text-decoration: none;
    font-weight: bold;
  }


    .abstract {
    text-align: justify;
    font-size: 15px;
    margin-left: 25px;
    color: #2c3237;
  }

  .presentation-info {
    text-align: justify;
    font-size: 12px;
    color: #828282;
    line-height: 1.2em;
  }
</style>

<!-------------------
WORKING PAPERS 
--------------------->


<!-- ====== WORKING PAPERS TITLE ====== -->

<div style="text-align: center; font-family: 'STIX Two Text', serif;">
  <h2 style="
    display: inline-block;
    margin-bottom: 0;
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 2px;
    font-family: 'EB Garamond', serif;
  ">
    Working Papers
  </h2>
</div>

<!-- ====== WORKING PAPER ====== -->

<div class="container">
  <div
    class="jumbotron no-image"
    onclick="window.open('#', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      background: #fff;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.1)'"
  >

    <h6 class="paper-title" style="margin-bottom: 6px; color:#BF245F;">
      Inequality and Conflict: The Long-Run Legacy of the Reconquesta
    </h6>

    <span style="font-size:16px;">
      (with 
      <a target="_blank" href="https://sites.google.com/view/stefanofalcone" onclick="event.stopPropagation();">
        Stefano Falcone
      </a>, 
      <a target="_blank" href="https://gianlucarusso.github.io/" onclick="event.stopPropagation();">
        Gianluca Russo
      </a>, 
      and Daniel Carrera)
    </span>

    <details class="abstract-box" onclick="event.stopPropagation();">
      <summary><span class="triangle"></span>Abstract</summary>
      <p style="text-align: justify;">
        We study how historical inequality shapes long-run political preferences. Our setting is Catalonia, where Christian counts expanded southward into Al-Andalus between the ninth and eleventh centuries at heterogeneous speeds, creating a frontier whose location was driven by idiosyncratic military events. Using a spatial regression discontinuity design comparing municipalities on either side of this frontier, we find that areas conquered more rapidly display persistently stronger support for the radical left. Southern municipalities show higher vote shares for radical-left parties in all democratic elections since 1977, a greater historical presence of anarcho-syndicalist and communist organizations, and more frequent protest activity. These patterns extend back to the Second Republic and the Spanish Civil War, including differences in militias, collectivization, and repression. We trace these effects to the resettlement process in fast-conquered territories, which produced concentrated landholding, weaker state capacity, and a large class of landless peasants. Our findings show how inequality under weak political authority can generate lasting radical political identities.
      </p>
    </details>

    <em style="font-size: 0.9em; font-family: 'STIX Two Text'; color:#555;">
      Draft coming soon
    </em>

    <p class="presentation-info" style="margin-top: 7px;">
      Media Coverage:
      [
      <a
        href="https://www.5centims.cat/desigualtat-i-conflicte-social-a-catalunya/"
        target="_blank"
        style="color:#B45346"
        onclick="event.stopPropagation();"
      >
        5centims
      </a>
      ]
    </p>

  </div>
</div>




<!-------------------
Other Research Contributions
--------------------->

<!-- ====== WORKING PAPERS TITLE ====== -->

<div style="text-align: center; font-family: 'STIX Two Text', serif;">
  <h2 style="
    display: inline-block;
    margin-bottom: 0;
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 2px;
    font-family: 'EB Garamond', serif;
  ">
    Working Papers
  </h2>
</div>

<!-- ====== WORKING PAPER ====== -->

<div class="container">
  <div
    class="jumbotron no-image"
    onclick="window.open('#', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      background: #fff;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.1)'"
  >

    <h6 class="paper-title" style="margin-bottom: 6px; color:#BF245F;">
      Inequality and Conflict: The Long-Run Legacy of the Reconquesta
    </h6>

    <span style="font-size:16px;">
      (with 
      <a target="_blank" href="https://sites.google.com/view/stefanofalcone" onclick="event.stopPropagation();">
        Stefano Falcone
      </a>, 
      <a target="_blank" href="https://gianlucarusso.github.io/" onclick="event.stopPropagation();">
        Gianluca Russo
      </a>, 
      and Daniel Carrera)
    </span>

    <details class="abstract-box" onclick="event.stopPropagation();">
      <summary><span class="triangle"></span>Abstract</summary>
      <p style="text-align: justify;">
        We study how historical inequality shapes long-run political preferences. Our setting is Catalonia, where Christian counts expanded southward into Al-Andalus between the ninth and eleventh centuries at heterogeneous speeds, creating a frontier whose location was driven by idiosyncratic military events. Using a spatial regression discontinuity design comparing municipalities on either side of this frontier, we find that areas conquered more rapidly display persistently stronger support for the radical left. Southern municipalities show higher vote shares for radical-left parties in all democratic elections since 1977, a greater historical presence of anarcho-syndicalist and communist organizations, and more frequent protest activity. These patterns extend back to the Second Republic and the Spanish Civil War, including differences in militias, collectivization, and repression. We trace these effects to the resettlement process in fast-conquered territories, which produced concentrated landholding, weaker state capacity, and a large class of landless peasants. Our findings show how inequality under weak political authority can generate lasting radical political identities.
      </p>
    </details>

    <em style="font-size: 0.9em; font-family: 'STIX Two Text'; color:#555;">
      Draft coming soon
    </em>

    <p class="presentation-info" style="margin-top: 7px;">
      Media Coverage:
      [
      <a
        href="https://www.5centims.cat/desigualtat-i-conflicte-social-a-catalunya/"
        target="_blank"
        style="color:#B45346"
        onclick="event.stopPropagation();"
      >
        5centims
      </a>
      ]
    </p>

  </div>
</div>





<!-- ====== RESEARCH CONTRIBUTIONS TITLE ====== -->

<div style="text-align: center; font-family: 'STIX Two Text', serif;">
  <h2 style="
    display: inline-block;
    margin-bottom: 0;
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 2px;
    font-family: 'EB Garamond', serif;
  ">
    Research Contributions
  </h2>
</div>

<!-- ====== SECOND PAPER ====== -->

<div class="container">
  <div
    class="jumbotron no-image"
    onclick="window.open('https://academic.oup.com/qje/advance-article-abstract/doi/10.1093/qje/qjaf052/8314061', '_blank')"
    style="
      cursor: pointer;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      background: #fff;
    "
    onmouseover="this.style.transform='scale(1.01)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'"
    onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.1)'"
  >

  <h6 class="paper-title" style="margin-bottom: 6px; color:#BF245F;">
  Banking Crises Without Panics
</h6>

    <p class="presentation-info" style="margin-top: 7px;">
      [
      <a
        href="https://academic.oup.com/qje/advance-article-abstract/doi/10.1093/qje/qjaf052/8314061"
        target="_blank"
        style="color:#B45346"
        onclick="event.stopPropagation();"
      >
        Quarterly Journal of Economics
      </a>
      ]
    </p>

    <p class="abstract">
      During my stay at the European Central Bank (ECB), I provided research assistance to
      Luc Laeven and Matthew Baron.
    </p>

    <p class="presentation-info">
      Presented at: European Central Bank.
    </p>

  </div>
</div>






