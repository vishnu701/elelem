---
layout: splash
title: "The Epoch Tour"
description: "Master AI with Harvard faculty across global innovation hubs."
excerpt: "Master AI with Harvard faculty worldwide"
header:
  overlay_image: /assets/images/header/header3.png
  overlay_filter: "0.3"
  actions:
    - label: "View Workshops"
      url: "/workshops/"
      btn_class: "btn--primary"
---

<style>
/* Reset and base styles */
.page__content {
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

.page__content p {
  margin: 0 auto !important;
  text-align: center !important;
}

.splash {
  margin: 0 !important;
  padding: 0 !important;
}

/* Hero button styling */
.btn--light-outline {
  background: transparent !important;
  color: white !important;
  border: 2px solid white !important;
  padding: 0.75rem 1.5rem !important;
  border-radius: 8px !important;
  font-weight: 500 !important;
  transition: all 0.3s ease !important;
  text-decoration: none !important;
}

.btn--light-outline:hover {
  background: white !important;
  color: #809AFF !important;
  border-color: white !important;
  text-decoration: none !important;
  transform: translateY(-2px) !important;
}

/* Container for centered content */
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

/* Hero Section */
.hero {
  background: linear-gradient(135deg, rgba(128, 154, 255, 0.1) 0%, rgba(255, 255, 255, 0.95) 100%);
  padding: 5rem 0;
  text-align: center;
}

.hero h1 {
  font-size: 3.5rem;
  font-weight: 300;
  color: #1a1a1a;
  margin-bottom: 1.5rem;
  line-height: 1.1;
}

.hero p {
  font-size: 1.25rem;
  color: #666;
  max-width: 700px;
  margin: 0 auto 2rem;
  line-height: 1.6;
}

.hero-badges {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
  margin-top: 2rem;
}

.badge {
  background: white;
  padding: 0.75rem 1.5rem;
  border-radius: 50px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  font-size: 0.9rem;
  color: #666;
  border: 1px solid #f0f0f0;
}

/* Section styles */
.section {
  padding: 5rem 0;
}

.section-alt {
  background: #f8f9fa;
}

.section-header {
  text-align: center;
  margin-bottom: 4rem;
}

.section-title {
  font-size: 2.5rem;
  font-weight: 300;
  color: #1a1a1a;
  margin-bottom: 1rem;
}

.section-subtitle {
  font-size: 1.1rem;
  color: #666;
  max-width: 600px;
  margin: 0 auto;
  line-height: 1.6;
}

/* Grid layouts */
.grid {
  display: grid;
  gap: 2rem;
}

.grid-3 {
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

.grid-4 {
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

/* Cards */
.card {
  background: white;
  padding: 2.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.12);
}

.card h3 {
  font-size: 1.25rem;
  font-weight: 500;
  color: #1a1a1a;
  margin-bottom: 1rem;
}

.card p {
  color: #666;
  line-height: 1.6;
  margin: 0;
}

/* Location cards */
.location-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
  border: 1px solid #f0f0f0;
  transition: all 0.3s ease;
}

.location-card:hover {
  border-color: #809AFF;
  box-shadow: 0 4px 20px rgba(128, 154, 255, 0.1);
}

.location-flag {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.location-name {
  font-size: 1.1rem;
  font-weight: 500;
  color: #1a1a1a;
  margin-bottom: 0.5rem;
}

.location-status {
  color: #809AFF;
  font-size: 0.9rem;
  font-weight: 500;
}

/* Faculty cards */
.faculty-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}

.faculty-avatar {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin: 0 auto 1rem;
  background: #f0f0f0;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.faculty-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.faculty-name {
  font-size: 1.1rem;
  font-weight: 500;
  color: #1a1a1a;
  margin-bottom: 0.5rem;
}

.faculty-role {
  color: #809AFF;
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

.faculty-bio {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.5;
}

/* CTA Section */
.cta-section {
  background: linear-gradient(135deg, #809AFF 0%, #6A85FF 100%);
  color: white;
  text-align: center;
}

.cta-section .section-title,
.cta-section .section-subtitle {
  color: white;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 2rem;
}

.btn {
  padding: 1rem 2rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
  display: inline-block;
  border: none;
  cursor: pointer;
}

.btn-primary {
  background: white;
  color: #809AFF;
}

.btn-primary:hover {
  background: #f8f9ff;
  text-decoration: none;
  color: #809AFF;
  transform: translateY(-2px);
}

.btn-outline {
  background: transparent;
  color: white;
  border: 2px solid rgba(255,255,255,0.8);
}

.btn-outline:hover {
  background: rgba(255,255,255,0.1);
  text-decoration: none;
  color: white;
  transform: translateY(-2px);
}

/* Curriculum list styling */
.curriculum-list {
  list-style: none;
  padding: 0;
  text-align: left;
  max-width: 280px;
  margin: 0 auto;
}

.curriculum-list li {
  padding: 0.5rem 0;
  color: #666;
  position: relative;
  padding-left: 1.5rem;
}

.curriculum-list li:before {
  content: "•";
  color: #809AFF;
  font-weight: bold;
  position: absolute;
  left: 0;
}

/* Responsive design */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .section-title {
    font-size: 2rem;
  }
  
  .container {
    padding: 0 1rem;
  }
  
  .hero-badges {
    flex-direction: column;
    align-items: center;
  }
  
  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .btn {
    width: 250px;
    text-align: center;
  }
}
</style>

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1>The Epoch Tour</h1>
    <p>Professional workshops on Large Language Models and AI applications, taught by Harvard faculty and industry experts across global innovation cities.</p>
    <div class="hero-badges">
      <div class="badge">🎓 Harvard Faculty</div>
      <div class="badge">🌍 Global Locations</div>
      <div class="badge">🛠️ Hands-On Learning</div>
    </div>
  </div>
</section>

<!-- About Section -->
<section class="section section-alt">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">About The Program</h2>
      <p class="section-subtitle">Intensive workshops designed for professionals looking to build practical AI skills and understand modern language model applications.</p>
    </div>
    <div class="grid grid-3">
      <div class="card">
        <h3>Expert Faculty</h3>
        <p>Learn from Harvard researchers and industry practitioners who work with AI systems in production environments.</p>
      </div>
      <div class="card">
        <h3>Practical Focus</h3>
        <p>Build real applications using APIs, implement RAG systems, and work with popular frameworks and tools.</p>
      </div>
      <div class="card">
        <h3>Global Community</h3>
        <p>Connect with professionals from diverse backgrounds and industries, all working to advance their AI capabilities.</p>
      </div>
    </div>
  </div>
</section>


<!-- Locations Section -->
<section class="section section-alt">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Workshop Locations</h2>
      <p class="section-subtitle">We bring the program to major innovation hubs worldwide. Each location offers the same high-quality curriculum adapted to local contexts.</p>
    </div>
    <div class="grid grid-4">
      <div class="location-card">
        <div class="location-flag">🇧🇷</div>
        <div class="location-name">São Paulo</div>
        <div class="location-status">August 8-10, 2025</div>
      </div>
      <div class="location-card">
        <div class="location-flag">🇯🇵</div>
        <div class="location-name">Tokyo</div>
        <div class="location-status">Planning in progress</div>
      </div>
      <div class="location-card">
        <div class="location-flag">🇬🇧</div>
        <div class="location-name">London</div>
        <div class="location-status">Planning in progress</div>
      </div>
      <div class="location-card">
        <div class="location-flag">🇸🇬</div>
        <div class="location-name">Singapore</div>
        <div class="location-status">Planning in progress</div>
      </div>
      <div class="location-card">
        <div class="location-flag">🇦🇪</div>
        <div class="location-name">Dubai</div>
        <div class="location-status">Planning in progress</div>
      </div>
      <div class="location-card">
        <div class="location-flag">🇦🇺</div>
        <div class="location-name">Sydney</div>
        <div class="location-status">Planning in progress</div>
      </div>
    </div>
  </div>
</section>

<!-- Faculty Section -->
<section class="section">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Faculty & Instructors</h2>
      <p class="section-subtitle">Our team combines academic expertise with practical industry experience in AI and machine learning.</p>
    </div>
    <div class="grid grid-3" style="justify-items: center; max-width: 800px; margin: 0 auto;">
      <div class="faculty-card">
        <div class="faculty-avatar">
          <img src="/assets/images/team/PavlosProtopapas.jpeg" alt="Pavlos Protopapas">
        </div>
        <div class="faculty-name">Pavlos Protopapas</div>
        <div class="faculty-role">Harvard University</div>
        <div class="faculty-bio">Scientific Program Director at the Institute for Applied Computational Science, Harvard University.</div>
      </div>
      <div class="faculty-card">
        <div class="faculty-avatar">
          <img src="/assets/images/team/IgnacioBecker.jpeg" alt="Ignacio Becker">
        </div>
        <div class="faculty-name">Ignacio Becker</div>
        <div class="faculty-role">Harvard University</div>
        <div class="faculty-bio">AI researcher and instructor with expertise in machine learning applications and educational program development.</div>
      </div>
    </div>
  </div>
</section>

<!-- CTA Section -->
<section class="section cta-section">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Join The Next Workshop</h2>
      <p class="section-subtitle">Ready to advance your AI skills? Our São Paulo workshop is now accepting applications.</p>
    </div>
    <div class="cta-buttons">
      <a href="/workshops/" class="btn btn-primary">View Workshop Details</a>
      <a href="mailto:info@theepochtour.ai" class="btn btn-outline">Contact Us</a>
    </div>
  </div>
</section>