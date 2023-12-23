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
    max-width: 100%;
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
  <h3>Multimodal Recording of iEEG, Scalp EEG, and Behavior During Freely Walking DBS Patients</h3>
  <p>
    to be updated 
  </p>

  <div class="subproject-section">
    <h4 style="color: #1e5fa8;">Basal Ganglia Dysfunction During Freezing of Gait</h4>
    <p>

    </p>
  </div>

  <div class="subproject-section">
    <h4 style="color: #3d8a5a;">Basal Ganglia Correlates of Dual-Task Walking</h4>
    <p>

    </p>
  </div>
</div>

<div class="project-section">
  <h3 style="color: #1e8a9a;">Cortical dynamics of cued gait in Parkinson's disease</h3>
  <p>
    Freezing of gait (FOG) is a debilitating symptom of Parkinson’s disease: a brief, involuntary inability to step forward. Using high-density scalp EEG, I map cortical activity during cued and uncued walking in patients with and without FOG. The animation below tracks sensorimotor beta-band power across the gait cycle, revealing heightened engagement during contralateral swing when patients with FOG use visual cues.
  </p>
  <figure class="project-figure">
    <img src="{{ '/assets/images/ersp_beta_sub_fog_data_selfBase_visu.gif' | relative_url }}" alt="Animated scalp topography of beta-band EEG activity during Parkinsonian gait with cues">
    <figcaption>Beta-band ERSP scalp topography across the gait cycle during cued walking.</figcaption>
  </figure>
</div>

<div class="project-section">
  <h3 style="color: #b5612e;">Gait analysis tool for free overground walking</h3>
  <p>
    I am developing a tool that extracts gait events from motion-capture data recorded during free overground walking. It detects heel strikes from the left and right heel trajectories and computes spatiotemporal gait metrics without the constraints of a treadmill or fixed walkway.
  </p>
  <figure class="project-figure">
    <img src="{{ '/assets/images/HS_extraction_example_ui.png' | relative_url }}" alt="Gait analysis interface showing right and left heel signals with detected heel strikes and a bird's-eye walking path">
    <figcaption>Heel-strike extraction and walking-path reconstruction during free overground walking.</figcaption>
  </figure>
</div>
