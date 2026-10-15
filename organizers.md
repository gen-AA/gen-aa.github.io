---
layout: default
title: Organizers
permalink: /organizers/
---

<style>
  .organizer {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin-bottom: 2rem;
  }
  .organizer img {
    width: 150px;
    height: 150px;
    flex-shrink: 0;
    object-fit: cover;
    object-position: center 20%;
    border-radius: 50%;
    background: #e8eaf0;
  }
  .organizer h3 {
    margin: 0 0 0.25rem;
  }
  .organizer .affiliation {
    margin: 0 0 0.5rem;
    font-weight: 600;
  }
  .organizer p {
    margin: 0;
  }
  .affiliations {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 1.5rem 3rem;
    margin: 1.5rem 0 2rem;
  }
  .affiliations a {
    display: flex;
    align-items: center;
  }
  .affiliations img {
    height: 90px;
    width: auto;
    max-width: 260px;
    object-fit: contain;
  }
  @media (max-width: 600px) {
    .organizer {
      flex-direction: column;
      text-align: center;
    }
    .affiliations img {
      height: 64px;
    }
  }
</style>

# Organizers

<div class="organizer">
  <img src="{{ '/assets/photos/anudeex_shetty.jpg' | relative_url }}" alt="Anudeex Shetty">
  <div>
    <h3>Anudeex Shetty</h3>
    <p class="affiliation">University of Melbourne</p>
    <p>PhD candidate working on AI text forensics, particularly authorship attribution and obfuscation.</p>
  </div>
</div>

<div class="organizer">
  <img src="{{ '/assets/photos/matteo_greco.jpg' | relative_url }}" alt="Matteo Greco" style="object-position: center 65%;">
  <div>
    <h3>Matteo Greco</h3>
    <p class="affiliation">University of Calabria</p>
    <p>Master's graduate and former visiting student at the University of Melbourne, working on multilingual AI detection.</p>
  </div>
</div>

<div class="organizer">
  <img src="{{ '/assets/photos/andrea_tagarelli.jpg' | relative_url }}" alt="Andrea Tagarelli">
  <div>
    <h3>Andrea Tagarelli</h3>
    <p class="affiliation">University of Calabria</p>
    <p>Full Professor and scientific coordinator of the AI and Data Science Lab, working on AI detection and authorship attribution.</p>
  </div>
</div>

<div class="organizer">
  <img src="{{ '/assets/photos/wei_lu.jpg' | relative_url }}" alt="Wei Lu">
  <div>
    <h3>Wei Lu</h3>
    <p class="affiliation">Nanyang Technological University</p>
    <p>Professor working on NLP with emphasis on fundamental machine learning; Editor-in-Chief of <em>Computational Linguistics</em>.</p>
  </div>
</div>

<div class="organizer">
  <img src="{{ '/assets/photos/jey_han_lau.jpg' | relative_url }}" alt="Jey Han Lau">
  <div>
    <h3>Jey Han Lau</h3>
    <p class="affiliation">University of Melbourne</p>
    <p>Associate Professor working on language modelling; President of ALTA.</p>
  </div>
</div>

<div class="organizer">
  <img src="{{ '/assets/photos/qiongkai_xu.jpg' | relative_url }}" alt="Qiongkai Xu">
  <div>
    <h3>Qiongkai Xu</h3>
    <p class="affiliation">Macquarie University and University of Melbourne</p>
    <p>Lecturer working on NLP security, including AI detection and text watermarking.</p>
  </div>
</div>

## Affiliations

<div class="affiliations">
  <a href="https://www.unimelb.edu.au/" target="_blank" rel="noopener">
    <img src="{{ '/assets/logos/unimelb_logo.png' | relative_url }}" alt="University of Melbourne">
  </a>
  <a href="https://www.unical.it/" target="_blank" rel="noopener">
    <img src="{{ '/assets/logos/unical_logo.png' | relative_url }}" alt="University of Calabria">
  </a>
  <a href="https://www.ntu.edu.sg/" target="_blank" rel="noopener">
    <img src="{{ '/assets/logos/ntu_logo.png' | relative_url }}" alt="Nanyang Technological University">
  </a>
  <a href="https://www.mq.edu.au/" target="_blank" rel="noopener">
    <img src="{{ '/assets/logos/macquarie_logo.png' | relative_url }}" alt="Macquarie University">
  </a>
</div>

## Contact

Email: [{{ site.contact_email }}](mailto:{{ site.contact_email }})