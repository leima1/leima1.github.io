---
layout: page
title: Current Projects
permalink: /current/
---

<style>
  .page-title {
    margin-bottom: 2rem;
  }
  .project-section {
    margin-bottom: 4rem;
  }
  .project-section h3 {
    margin-bottom: 0.5rem;
    color: #333;
  }
  .project-figure {
    margin: 1rem 0;
    text-align: center;
    padding: 0 4px;
  }
  .project-figure img {
    max-width: min(100%, 600px);
    height: auto;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  }
  .project-figure figcaption {
    margin-top: 0.5rem;
    font-size: 0.9rem;
    color: #666;
    font-style: italic;
  }
  .subproject-section {
    margin-top: 1.5rem;
    padding-left: 1.25rem;
    border-left: 3px solid #ddd;
  }
  .subproject-section h4 {
    margin-bottom: 0.4rem;
  }
</style>

<div class="project-section">
  <h3>Multimodal recording of iEEG, scalp EEG, and behavior in freely walking DBS patients</h3>
  <figure class="project-figure">
    <img src="{{ '/assets/images/multimodel_wide.png' | relative_url }}" alt="Synchronized recording streams showing a virtual reality headset view, motion-capture skeleton, left and right acceleration traces, a rising freeze index, and simultaneous scalp EEG and intracranial EEG">
    <figcaption>Deep brain stimulation (DBS) implants allow direct recording from the basal ganglia during walking. Here, intracranial EEG is synchronized with scalp EEG, motion capture, accelerometry, and virtual reality to study freezing of gait.</figcaption>
  </figure>

  <!-- Sub-projects hidden until written up. Each needs a sentence or two.
  <div class="subproject-section">
    <h4 style="color: #1e5fa8;">Basal Ganglia Dysfunction During Freezing of Gait</h4>
    <p></p>
  </div>

  <div class="subproject-section">
    <h4 style="color: #3d8a5a;">Basal Ganglia Correlates of Dual-Task Walking</h4>
    <p></p>
  </div>
  -->
</div>

<div class="project-section">
  <h3 style="color: #1e8a9a;">Mapping cortical dynamics of cued and uncued gait in Parkinson's disease (PD) with high-density scalp EEG</h3>
  <figure class="project-figure">
    <img src="{{ '/assets/images/ersp_beta_sub_fog_data_selfBase_visu.gif' | relative_url }}" alt="Animated scalp topography of beta-band EEG activity during Parkinsonian gait with cues">
    <figcaption>Beta-band event-related spectral perturbation scalp topography across the gait cycle, showing heightened sensorimotor responses during visually cued walking in PD patients with freezing of gait.</figcaption>
  </figure>
</div>

<div class="project-section">
  <h3 style="color: #b5612e;">Extracting heel strikes and spatiotemporal gait metrics from free overground walking in healthy and patient populations</h3>
  <figure class="project-figure">
    <img src="{{ '/assets/images/HS_extraction_example_ui.png' | relative_url }}" alt="Gait analysis interface showing right and left heel signals with detected heel strikes and a bird's-eye walking path">
    <figcaption>Heel-strike extraction and walking-path reconstruction during free overground walking.</figcaption>
  </figure>
</div>
