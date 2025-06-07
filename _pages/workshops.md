---
layout: single
title: "The Epoch Tour Workshops"
permalink: /workshops/
author_profile: false
classes: wide
header:
  overlay_image: /assets/images/header/Pavlos teaching.jpg
  overlay_filter: "0.6"
  overlay_color: "#000"
  actions:
    - label: "Apply for São Paulo"
      url: "/workshops/saopaulo/"
      btn_class: "btn--primary"
---

<style>
.workshop-hero {
  background: linear-gradient(135deg, #809AFF 0%, #000000 100%);
  color: white;
  padding: 60px 40px;
  margin: 40px 0;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 8px 32px rgba(0,0,0,0.15);
}

.workshop-hero h1 {
  font-size: 3rem;
  font-weight: 300;
  margin-bottom: 20px;
  letter-spacing: -1px;
}

.workshop-hero .subtitle {
  font-size: 1.3rem;
  opacity: 0.9;
  font-weight: 300;
  margin-bottom: 30px;
}

.workshop-hero .description {
  font-size: 1.1rem;
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.6;
}

.workshops-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 40px;
  margin: 50px 0;
}

.workshop-card {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 24px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  border: 1px solid #e1e5e9;
}

.workshop-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 48px rgba(0,0,0,0.15);
}

.workshop-card-header {
  background: linear-gradient(135deg, #809AFF 0%, #6A85FF 100%);
  color: white;
  padding: 30px;
  text-align: center;
}

.workshop-card-header h3 {
  margin: 0 0 10px 0;
  font-size: 1.5rem;
  font-weight: 600;
}

.workshop-card-header .location {
  font-size: 1rem;
  opacity: 0.9;
  margin-bottom: 15px;
}

.workshop-card-header .date {
  background: rgba(255,255,255,0.2);
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.9rem;
  display: inline-block;
}

.workshop-card-body {
  padding: 30px;
}

.workshop-highlights {
  list-style: none;
  padding: 0;
  margin: 20px 0;
}

.workshop-highlights li {
  padding: 8px 0;
  padding-left: 25px;
  position: relative;
  color: #555;
}

.workshop-highlights li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #809AFF;
  font-weight: bold;
}

.workshop-cta {
  text-align: center;
  margin-top: 25px;
}

.workshop-btn {
  background: #809AFF;
  color: white;
  padding: 12px 30px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  display: inline-block;
}

.workshop-btn:hover {
  background: #000000 !important;
  color: white !important;
  text-decoration: none;
  transform: translateY(-2px);
}

/* Override theme default button/link colors */
.workshop-cta a,
.workshop-cta a:link,
.workshop-cta a:visited {
  background: #809AFF !important;
  color: white !important;
  text-decoration: none !important;
}

.workshop-cta a:hover,
.workshop-cta a:focus,
.workshop-cta a:active {
  background: #000000 !important;
  color: white !important;
  text-decoration: none !important;
}

.coming-soon {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border: 2px dashed #dee2e6;
  padding: 60px 40px;
  text-align: center;
  border-radius: 12px;
  margin: 40px 0;
}

.coming-soon h2 {
  color: #6c757d;
  margin-bottom: 15px;
}

.coming-soon p {
  color: #868e96;
  font-size: 1.1rem;
}

@media (max-width: 768px) {
  .workshop-hero h1 {
    font-size: 2.2rem;
  }
  
  .workshop-hero {
    padding: 40px 20px;
  }
  
  .workshops-grid {
    grid-template-columns: 1fr;
    gap: 30px;
  }
  
  .workshop-card-header, .workshop-card-body {
    padding: 20px;
  }
}
</style>

<!-- <div class="workshop-hero">
  <h1>World-Class LLM Education</h1>
  <div class="subtitle">Master Large Language Models with Harvard Faculty</div>
  <div class="description">
    Join EL EL EM's intensive workshops as we bring cutting-edge AI education to innovation hubs across the globe. Learn from industry leaders, build production systems, and connect with the world's brightest AI practitioners.
  </div>
</div> -->

## Current Workshops

<div class="workshops-grid">
  <div class="workshop-card">
    <div class="workshop-card-header">
      <h3>Applied LLM Workshop</h3>
      <div class="location">São Paulo, Brazil</div>
      <div class="date">August 8-10, 2025</div>
    </div>
    <div class="workshop-card-body">
      <p>Comprehensive hands-on introduction to Large Language Models for professionals, researchers, and advanced practitioners.</p>
      
      <ul class="workshop-highlights">
        <li>2.5 intensive days of hands-on learning</li>
        <li>Build Agentic Systems</li>
        <li>Expert faculty from Harvard & industry</li>
        <li>Maximum 150 participants</li>
      </ul>
      
      <div class="workshop-cta">
        <a href="/workshops/saopaulo/" class="workshop-btn">Learn More & Apply</a>
      </div>
    </div>
  </div>
</div>

<div class="coming-soon">
  <h2>More Workshops Coming Soon</h2>
  <p>We're expanding globally to bring world-class LLM education to major innovation hubs across Europe, Asia-Pacific, Americas, and emerging markets.</p>
  <p><strong>Interested in hosting a workshop in your city?</strong> Contact us at <a href="mailto:info@theepochtour.ai">info@theepochtour.ai</a></p>
</div>

<!-- ## Why Choose EL EL EM?

Our workshops combine theoretical rigor with practical application, ensuring you can immediately apply what you learn:

- **Expert Faculty**: Learn from Harvard researchers and industry veterans who've built billion-dollar AI systems
- **Hands-On Learning**: Work directly with production APIs and real-world datasets
- **Small Cohorts**: Maximum 150 participants for personalized attention and networking
- **Global Network**: Connect with AI practitioners from around the world
- **Continued Support**: Join our worldwide community of AI professionals

Ready to transform your career? [Contact us](mailto:workshops@epochtour.com) to learn about upcoming workshops in your region. -->