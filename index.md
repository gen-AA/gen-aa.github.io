---
layout: default
title: Home
permalink: /
---

<style>
  .hero-inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
  }
  .hero-text {
    flex: 1;
    min-width: 0;
  }
  .hero-logo {
    height: 120px;
    width: auto;
    max-width: 220px;
    flex-shrink: 0;
    object-fit: contain;
  }
  .interest {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1.5rem;
    margin: 1.5rem 0;
    padding: 1.25rem 1.5rem;
    border: 1px solid #d9deee;
    border-radius: 12px;
    background: #f7f9fd;
  }
  .interest h3 {
    margin: 0 0 0.35rem;
  }
  .interest p {
    margin: 0 0 0.9rem;
  }
  .interest-btn {
    display: inline-block;
    padding: 0.55rem 1.1rem;
    background: #1e2a5a;
    color: #fff !important;
    font-weight: 600;
    text-decoration: none !important;
    border-radius: 8px;
  }
  .interest-btn:hover {
    background: #2d3d80;
  }
  .interest-qr {
    width: 130px;
    height: 130px;
    flex-shrink: 0;
  }
  .org-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem 1.5rem;
    margin: 1.5rem auto;
    max-width: 720px;
  }
  .org-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    font-size: 0.9rem;
    line-height: 1.35;
  }
  .org-card img {
    width: 110px;
    height: 110px;
    object-fit: cover;
    object-position: center 20%;
    border-radius: 50%;
    background: #e8eaf0;
    margin-bottom: 0.6rem;
  }
  .org-card strong {
    display: block;
  }
  .org-card span {
    display: block;
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
  @media (max-width: 700px) {
    .hero-inner {
      flex-direction: column-reverse;
      align-items: flex-start;
      gap: 1rem;
    }
    .hero-logo {
      height: 80px;
    }
  }
  @media (max-width: 600px) {
    .interest-qr {
      display: none;
    }
    .org-grid {
      grid-template-columns: repeat(2, 1fr);
    }
    .affiliations img {
      height: 64px;
    }
  }
  @media (max-width: 380px) {
    .org-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="hero">
  <div class="hero-inner">
    <div class="hero-text">
      <span class="badge">INLG 2027 Shared Task</span>
      <h1>Generalisable Authorship Attribution in Human and LLM-Generated Texts</h1>
      <p>A shared task on authorship attribution across human and LLM-generated texts.</p>
    </div>
    <img class="hero-logo" src="{{ '/assets/logos/inlg_logo.png' | relative_url }}" alt="INLG 2027">
  </div>
</div>

<div class="card">
<strong>Coming soon.</strong> More details will be announced here.
</div>

<div class="interest">
  <div>
    <h3>Stay updated</h3>
    <p>Register your interest to be notified when data, baselines and deadlines are released.</p>
    <a class="interest-btn" href="https://forms.gle/p9dCrvZfuqatiSMC7" target="_blank" rel="noopener">Register your interest</a>
  </div>
  <img class="interest-qr" src="{{ '/assets/qr/interest_form.png' | relative_url }}" alt="QR code to register your interest">
</div>

## Organizers

<div class="org-grid">
  <div class="org-card">
    <img src="{{ '/assets/photos/anudeex_shetty.jpg' | relative_url }}" alt="Anudeex Shetty">
    <strong>Anudeex Shetty</strong>
    <span>PhD Candidate</span>
    <span>University of Melbourne</span>
  </div>
  <div class="org-card">
    <img src="{{ '/assets/photos/matteo_greco.jpg' | relative_url }}" alt="Matteo Greco" style="object-position: center 65%;">
    <strong>Matteo Greco</strong>
    <span>Master's Graduate</span>
    <span>University of Calabria</span>
  </div>
  <div class="org-card">
    <img src="{{ '/assets/photos/andrea_tagarelli.jpg' | relative_url }}" alt="Andrea Tagarelli">
    <strong>Andrea Tagarelli</strong>
    <span>Full Professor</span>
    <span>University of Calabria</span>
  </div>
  <div class="org-card">
    <img src="{{ '/assets/photos/wei_lu.jpg' | relative_url }}" alt="Wei Lu">
    <strong>Wei Lu</strong>
    <span>Professor</span>
    <span>Nanyang Technological University</span>
  </div>
  <div class="org-card">
    <img src="{{ '/assets/photos/jey_han_lau.jpg' | relative_url }}" alt="Jey Han Lau">
    <strong>Jey Han Lau</strong>
    <span>Associate Professor</span>
    <span>University of Melbourne</span>
  </div>
  <div class="org-card">
    <img src="{{ '/assets/photos/qiongkai_xu.jpg' | relative_url }}" alt="Qiongkai Xu">
    <strong>Qiongkai Xu</strong>
    <span>Lecturer</span>
    <span>Macquarie University</span>
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

For questions or inquiries, please reach us via:

- **Email:** [{{ site.contact_email }}](mailto:{{ site.contact_email }})
- **Discord:** [Join our server](https://discord.gg/XaJ5hXeGv)