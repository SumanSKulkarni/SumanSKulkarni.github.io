---
layout: page
title: research
permalink: /research/
description: Research organized thematically (under construction...)
nav: true
nav_order: 4
horizontal: false
---
<style>
  @media (max-width: 600px) {
    .research-flex {
      flex-direction: column !important;
    }
    .research-flex img {
      width: 100% !important;
      max-width: 320px;
    }
  }
</style>
## Statistical physics & dynamics on networks
<div class="research-flex" style="display: flex; gap: 2rem; align-items: center; margin-bottom: 1.5rem;" markdown="1">
  <img src="/assets/img/research_stat_dyn_networks.png" alt="Statistical physics and dynamics on networks" style="width: 280px; flex-shrink: 0; border-radius: 4px;">
  <div style="flex: 1; min-width: 250px;" markdown="1">
Tools from statistical physics and dynamical systems are useful for modeling a range of phenomena on networks---from opinion dynamics on social networks to neural activity in the brain. We ask how network structure shapes the collective behavior of canonical models in statistical physics.
<div class="statphys-refs" markdown="1">
{% bibliography --query @*[keywords=statphys] --group_by none %}
</div>
<style>
  .statphys-refs .col-sm-2.abbr {
    display: none;
  }
  .statphys-refs .col-sm-8 {
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }
  .statphys-refs .row {
    margin: 0;
  }
  .statphys-refs ol.bibliography {
    padding-left: 1.5em;
    font-size: 0.85em;
  }
  .statphys-refs .author em {
    font-style: normal;
    font-weight: bold;
  }
  .statphys-refs .periodical,
  .statphys-refs .links {
    display: inline;
  }
</style>
  </div>
</div>
## Information networks in music
<div class="research-flex" style="display: flex; gap: 2rem; align-items: flex-start; margin-bottom: 1.5rem;" markdown="1">
  <img src="/assets/img/research_music.png" alt="Music networks" style="width: 280px; flex-shrink: 0; border-radius: 4px;">
  <div style="flex: 1; min-width: 250px;" markdown="1">
Music unfolds as a sequence of notes whose statistical structure shapes what a listener expects and, in turn, how much information each transition conveys. We use tools from information theory and network science to quantify how note-transitions in music are structured and identify distinctive patterns.
<div class="music-refs" markdown="1">
{% bibliography --query @*[keywords=music] --group_by none %}
</div>
<style>
  .music-refs .col-sm-2.abbr {
    display: none;
  }
  .music-refs .col-sm-8 {
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }
  .music-refs .row {
    margin: 0;
  }
  .music-refs ol.bibliography {
    padding-left: 1.5em;
    font-size: 0.85em;
  }
  .music-refs .author em {
    font-style: normal;
    font-weight: bold;
  }
  .music-refs .periodical,
  .music-refs .links {
    display: inline;
  }
</style>
  </div>
</div>