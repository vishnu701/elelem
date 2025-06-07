---
title: "São Paulo - Applied LLM Workshop" 
permalink: /workshops/saopaulo/
cycle: worldtour2025
classes: wide
kind: workshop
excerpt: Epoch Tour Applied LLM Workshop - Professional Development in Large Language Models
sequence: 11
header:
  overlay_image: /assets/images/header/HeaderDesign4.jpeg
  overlay_filter: "0.7"
  teaser: /assets/images/header/HeaderDesign4.jpeg
  actions:
    - label: "Register for Workshop"
      url: "/experiences/saopaulo/"
      btn_class: "btn--primary"
---

<style>
.workshop-hero {
  background: #809AFF;
  color: white;
  padding: 40px;
  margin: 30px 0;
  border-radius: 8px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.15);
}

.workshop-hero h1 {
  font-size: 2.5rem;
  font-weight: 300;
  margin-bottom: 10px;
  letter-spacing: -0.5px;
}

.workshop-hero .subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
  font-weight: 300;
}

.info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.info-card {
  background: #ffffff;
  border: 1px solid #e1e5e9;
  border-radius: 8px;
  padding: 30px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
}

.info-card:hover {
  box-shadow: 0 4px 24px rgba(0,0,0,0.12);
  transform: translateY(-2px);
}

.info-card h3 {
  color: #000000;
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 15px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.info-card .metric {
  font-size: 2.2rem;
  font-weight: 700;
  color: #809AFF;
  margin-bottom: 5px;
}

.schedule-section {
  background: #f8f9fa;
  padding: 40px;
  margin: 40px 0;
  border-radius: 8px;
  border-left: 4px solid #809AFF;
}

.schedule-table {
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  margin: 20px 0;
}

.schedule-table table {
  width: 100%;
  margin: 0;
}

.schedule-table th {
  background: #809AFF;
  color: white;
  padding: 15px;
  font-weight: 600;
  font-size: 0.9rem;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.schedule-table td {
  padding: 15px;
  border-bottom: 1px solid #e9ecef;
  vertical-align: top;
}

.schedule-table tr:nth-child(even) {
  background: #f8f9fa;
}

.session-title {
  font-weight: 600;
  color: #000000;
  margin-bottom: 5px;
}

.session-exercise {
  color: #6c757d;
  font-size: 0.9rem;
  font-style: italic;
}

.faculty-section {
  background: #000000;
  color: white;
  padding: 40px;
  margin: 40px 0;
  border-radius: 8px;
}

.faculty-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.faculty-member {
  text-align: center;
  padding: 20px;
  background: rgba(255,255,255,0.1);
  border-radius: 8px;
  backdrop-filter: blur(10px);
}

.faculty-avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin: 0 auto 15px auto;
  overflow: hidden;
  border: 3px solid #809AFF;
  background: #809AFF;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 2rem;
}

.faculty-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.faculty-avatar i {
  font-size: 2rem;
}

.faculty-member h4 {
  margin-bottom: 5px;
  font-weight: 600;
}

.faculty-member .role {
  font-size: 0.9rem;
  opacity: 0.8;
  margin-bottom: 15px;
}

.faculty-links {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 15px;
}

.faculty-link {
  width: 24px;
  height: 24px;
  border-radius: 50%;
  background: #809AFF;
  color: white !important;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  font-size: 10px;
  transition: all 0.3s ease;
}

.faculty-link:hover {
  background: #000000 !important;
  color: white !important;
  text-decoration: none;
  transform: translateY(-2px);
}

.faculty-link:visited {
  background: #809AFF !important;
  color: white !important;
}

.faculty-link.harvard {
  background: #A51C30 !important;
}

.faculty-link.harvard:hover {
  background: #8B1538 !important;
}

.faculty-link.harvard:visited {
  background: #A51C30 !important;
  color: white !important;
}

.faculty-link.linkedin {
  background: #0077B5 !important;
}

.faculty-link.linkedin:hover {
  background: #005885 !important;
}

.faculty-link.linkedin:visited {
  background: #0077B5 !important;
  color: white !important;
}

.faculty-link.scholar {
  background: #4285F4 !important;
}

.faculty-link.scholar:hover {
  background: #3367D6 !important;
}

.faculty-link.scholar:visited {
  background: #4285F4 !important;
  color: white !important;
}

.prerequisites-section {
  background: white;
  border: 1px solid #e1e5e9;
  border-radius: 8px;
  padding: 40px;
  margin: 40px 0;
}

.prerequisites-section h2 {
  color: #000000;
  border-bottom: 2px solid #e1e5e9;
  padding-bottom: 15px;
  margin-bottom: 30px;
}

.prereq-category {
  margin-bottom: 25px;
}

.prereq-category h3 {
  color: #809AFF;
  font-size: 1.1rem;
  margin-bottom: 10px;
}

.prereq-list {
  list-style: none;
  padding: 0;
}

.prereq-list li {
  padding: 8px 0;
  padding-left: 25px;
  position: relative;
}

.prereq-list li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #28a745;
  font-weight: bold;
}

.investment-section {
  background: #809AFF;
  color: white;
  padding: 40px;
  margin: 40px 0;
  border-radius: 8px;
  text-align: center;
}

.investment-section h2 {
  margin-bottom: 20px;
}

.price-highlight {
  font-size: 3rem;
  font-weight: 700;
  margin: 20px 0;
}

.venue-section {
  background: white;
  border: 1px solid #e1e5e9;
  border-radius: 8px;
  padding: 40px;
  margin: 40px 0;
}

.venue-links {
  display: flex;
  gap: 15px;
  margin: 20px 0;
  flex-wrap: wrap;
}

.venue-link {
  padding: 10px 20px;
  background: #809AFF;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-size: 0.9rem;
  transition: all 0.3s ease;
}

.venue-link:hover {
  background: #000000;
  color: white !important;
  text-decoration: none;
}

/* Override theme default link colors */
.venue-links a {
  background: #809AFF !important;
  color: white !important;
  text-decoration: none !important;
}

.venue-links a:hover {
  background: #000000 !important;
  color: white !important;
  text-decoration: none !important;
}

.venue-links a:visited {
  background: #809AFF !important;
  color: white !important;
  text-decoration: none !important;
}

.cta-section {
  background: #000000;
  color: white;
  padding: 50px;
  margin: 50px 0;
  border-radius: 8px;
  text-align: center;
}

.cta-section h2 {
  margin-bottom: 20px;
  font-size: 2rem;
}

.cta-buttons {
  display: flex;
  gap: 20px;
  justify-content: center;
  margin-top: 30px;
  flex-wrap: wrap;
}

.cta-btn {
  padding: 15px 30px;
  background: #809AFF;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
  transition: all 0.3s ease;
}

.cta-btn:hover {
  background: white;
  color: #000000;
  text-decoration: none;
  transform: translateY(-2px);
}

/* Simple wider layout with proper centering - target only main content, not masthead */
article .page__content,
.page__inner-wrap {
  max-width: 1100px !important;
  margin: 0 auto !important;
}

/* Mobile responsive fixes */
@media (max-width: 768px) {
  .workshop-hero h1 {
    font-size: 2rem;
  }
  
  /* Header overlay with minimal margins for dramatic effect */
  .page__hero--overlay .page__hero-caption,
  .page__hero--overlay .page__title,
  .page__hero--overlay .page__meta,
  .page__hero--overlay .page__lead,
  .page__hero--overlay .archive__item-excerpt {
    padding-left: 5px !important;
    padding-right: 5px !important;
    margin-left: 0 !important;
    margin-right: 0 !important;
  }
  
  /* Force button alignment with text content */
  .page__hero--overlay .btn,
  .page__hero--overlay .btn--primary,
  .page__hero--overlay a.btn,
  .page__hero--overlay a.btn--primary {
    margin-left: 5px !important;
    margin-right: 5px !important;
    padding-left: 15px !important;
    padding-right: 15px !important;
    display: inline-block !important;
    text-align: center !important;
    box-sizing: border-box !important;
  }
  
  /* Override any button container that might be centering */
  .page__hero--overlay .page__hero-caption .btn,
  .page__hero--overlay .archive__item .btn {
    margin-left: 5px !important;
  }
  
  /* Force container padding for overlay */
  .page__hero--overlay {
    padding-left: 5px !important;
    padding-right: 5px !important;
  }
  
  /* Target the wrapper inside overlay */
  .page__hero--overlay .wrapper {
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
  
  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .venue-links {
    flex-direction: column;
  }
  
  /* Override content width constraints on mobile - exclude masthead */
  .layout--single,
  .page,
  .page__content,
  .page__inner-wrap,
  .wrapper,
  article,
  article .page__content,
  main {
    max-width: 100% !important;
    width: 100% !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    margin-left: 0 !important;
    margin-right: 0 !important;
  }
  
  /* Add consistent padding to page content only */
  .page__content {
    padding: 0 35px !important;
  }
  
  /* Make all content sections with comfortable margins */
  .workshop-hero,
  .info-grid,
  .schedule-section,
  .faculty-section,
  .prerequisites-section,
  .venue-section,
  .investment-section,
  .cta-section {
    width: calc(100% - 40px) !important;
    max-width: none !important;
    margin-left: 20px !important;
    margin-right: 20px !important;
    padding-left: 20px !important;
    padding-right: 20px !important;
    box-sizing: border-box !important;
  }
  
  /* Ensure body and html don't have margins/padding */
  html,
  body {
    margin: 0 !important;
    padding: 0 !important;
    overflow-x: hidden;
  }
  
  /* Horizontal scroll for schedule table */
  .schedule-section {
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
  }
  
  .schedule-table {
    min-width: 600px;
    overflow-x: auto;
  }
  
  .schedule-table table {
    width: 100%;
    min-width: 600px;
  }
  
  /* Better mobile table styling */
  .schedule-table th,
  .schedule-table td {
    padding: 10px 8px;
    font-size: 0.85rem;
    white-space: nowrap;
  }
  
  .schedule-table th:first-child,
  .schedule-table td:first-child {
    min-width: 80px;
  }
  
  .schedule-table th:nth-child(2),
  .schedule-table td:nth-child(2) {
    min-width: 100px;
  }
  
  .schedule-table th:nth-child(3),
  .schedule-table td:nth-child(3) {
    min-width: 300px;
    white-space: normal;
  }
}
</style>

<div class="workshop-hero">
  <h1>Applied LLM Workshop</h1>
  <div class="subtitle">Professional Development in Large Language Models</div>
  <div style="margin-top: 20px; font-size: 1rem;">
    <strong>São Paulo, Brazil</strong> | August 8-10, 2025 | IBMEC University
  </div>
</div>

## Course Overview

This intensive workshop offers a comprehensive, hands-on introduction to Large Language Models (LLMs) for professionals, researchers, and advanced practitioners. The program balances theoretical foundations with practical implementation, covering everything from core concepts to advanced deployment strategies.

Participants will explore text preprocessing, neural networks, and transformer architecture before advancing to real-world applications including customer support automation, content generation, and enterprise AI integration.

<div class="info-grid">
  <!-- <div class="info-card">
    <h3>Participants</h3>
    <div class="metric">150</div>
    <p>Maximum capacity for optimal learning experience</p>
  </div> -->
  
  <!-- <div class="info-card">
    <h3>Investment</h3>
    <div class="metric">$500</div>
    <p>Per participant, including all materials and catering</p>
  </div> -->
  
  <div class="info-card">
    <h3>Duration</h3>
    <div class="metric">2.5</div>
    <p>Intensive days of hands-on learning</p>
  </div>
  
  <div class="info-card">
    <h3>Sessions</h3>
    <div class="metric">9</div>
    <p>Comprehensive modules with practical exercises</p>
  </div>
</div>

## Workshop Format

**Faculty-led instruction** combined with **interactive coding laboratories** and **practitioner discussions**. Participants work directly with industry-standard APIs (OpenAI, Hugging Face) implementing:

- Agentic workflow development
- Retrieval-Augmented Generation (RAG)
- LoRA-based fine-tuning techniques  

All learning is project-focused and application-driven, ensuring immediate practical value.

<div class="schedule-section">
  <h2>Workshop Schedule</h2>
  
  <div class="schedule-table">
    <table>
      <thead>
        <tr>
          <th>Day</th>
          <th>Time</th>
          <th>Session Content</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Friday<br>8/8/2025</strong></td>
          <td>12:00-14:00</td>
          <td>
            <div class="session-title">Introduction to Language Models</div>
            <div class="session-exercise">Hands-on: Text Preprocessing & Language Model Fundamentals</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>14:30-16:30</td>
          <td>
            <div class="session-title">Transformer Architecture</div>
            <div class="session-exercise">Hands-on: Text Embeddings Implementation</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>17:00-19:00</td>
          <td>
            <div class="session-title">BERT & GPT Models</div>
            <div class="session-exercise">Hands-on: Pre-trained Models from HuggingFace</div>
          </td>
        </tr>
        <tr>
          <td><strong>Saturday<br>8/9/2025</strong></td>
          <td>09:30-11:30</td>
          <td>
            <div class="session-title">ChatGPT & API Integration</div>
            <div class="session-exercise">Hands-on: Working with LLM APIs</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>12:00-14:00</td>
          <td>
            <div class="session-title">Agentic Systems</div>
            <div class="session-exercise">Hands-on: Simple Agentic Flow Development</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>15:30-17:30</td>
          <td>
            <div class="session-title">Advanced Agents & RAG</div>
            <div class="session-exercise">Hands-on: Self-RAG Implementation</div>
          </td>
        </tr>
        <tr>
          <td><strong>Sunday<br>8/10/2025</strong></td>
          <td>09:30-11:30</td>
          <td>
            <div class="session-title">Retrieval-Augmented Generation</div>
            <div class="session-exercise">Hands-on: Advanced RAG Techniques</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>12:00-14:00</td>
          <td>
            <div class="session-title">Model Fine-tuning</div>
            <div class="session-exercise">Hands-on: Fine-tuning with QLoRA</div>
          </td>
        </tr>
        <tr>
          <td></td>
          <td>15:30-17:30</td>
          <td>
            <div class="session-title">State-of-the-Art Techniques</div>
            <div class="session-exercise">Hands-on: Latest LLM Developments</div>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

## Learning Outcomes

Upon completion, participants will demonstrate proficiency in:

- **Prompt Engineering** - Design effective prompts and AI-driven workflows
- **API Integration** - Implement advanced LLM architectures using industry-standard APIs
- **Model Customization** - Fine-tune models for specific use cases using LoRA and QLoRA
- **System Deployment** - Deploy agentic systems and retrieval-based pipelines

Participants also join a professional network of applied AI practitioners across Latin America.

<div class="faculty-section">
  <h2>Faculty</h2>
  <p>Learn from industry leaders and researchers at the forefront of LLM development and application.</p>
  
  <div class="faculty-grid">
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/PavlosProtopapas.jpeg' | relative_url }}" alt="Pavlos Protopapas">
      </div>
      <h4>Pavlos Protopapas</h4>
      <div class="role">Lead Instructor</div>
      <div class="faculty-links">
        <a href="https://seas.harvard.edu/person/pavlos-protopapas" class="faculty-link harvard" target="_blank" title="Harvard Directory"><i class="fas fa-university"></i></a>
        <a href="https://www.linkedin.com/in/pavlos-protopapas-a2156a4/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
        <a href="https://scholar.google.com/citations?user=hlFnwxwAAAAJ&hl=en" class="faculty-link scholar" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      </div>
    </div>
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/IgnacioBecker.jpeg' | relative_url }}" alt="Ignacio Becker">
      </div>
      <h4>Ignacio Becker</h4>
      <div class="role">Co-Instructor</div>
      <div class="faculty-links">
        <a href="https://seas.harvard.edu/person/ignacio-becker-troncoso" class="faculty-link harvard" target="_blank" title="Harvard Directory"><i class="fas fa-university"></i></a>
        <a href="https://www.linkedin.com/in/ignacio-becker/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
        <a href="https://scholar.google.com/citations?user=qIX3ldUAAAAJ&hl=en" class="faculty-link scholar" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      </div>
    </div>
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/ShivasJayaram.jpg' | relative_url }}" alt="Shivas Jayaram">
      </div>
      <h4>Shivas Jayaram</h4>
      <div class="role">Teaching Fellow</div>
      <div class="faculty-links">
        <a href="https://www.linkedin.com/in/shivasj/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/ChrisGumb.jpeg' | relative_url }}" alt="Chris Gumb">
      </div>
      <h4>Chris Gumb</h4>
      <div class="role">Teaching Fellow</div>
      <div class="faculty-links">
        <a href="https://www.linkedin.com/in/chris-gumb-28856875/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/VishnuM.png' | relative_url }}" alt="Vishnu M">
      </div>
      <h4>Vishnu M</h4>
      <div class="role">Teaching Fellow</div>
      <div class="faculty-links">
        <a href="https://www.linkedin.com/in/vishnu701/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
    <div class="faculty-member">
      <div class="faculty-avatar">
        <img src="{{ '/assets/images/team/Itamar.png' | relative_url }}" alt="Itamar Rocha Filho">
      </div>
      <h4>Itamar Rocha Filho</h4>
      <div class="role">Teaching Fellow</div>
      <div class="faculty-links">
        <a href="https://www.linkedin.com/in/itamarrocha/" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>
</div>

<div class="faculty-section">
  <h2>Management</h2>
  
  <div class="faculty-grid">
    <div class="faculty-member">
      <div class="faculty-avatar">
        <i class="fas fa-user"></i>
      </div>
      <h4>Giulia Federighi</h4>
      <div class="role">Program Director</div>
      <div class="faculty-links">
        <a href="#" class="faculty-link linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>
</div>

<div class="prerequisites-section">
  <h2>Prerequisites</h2>
  
  <div class="prereq-category">
    <h3>Programming Skills</h3>
    <ul class="prereq-list">
      <li>Proficiency in Python (essential for coding exercises and API usage)</li>
      <li>Familiarity with machine learning frameworks (PyTorch or TensorFlow)</li>
    </ul>
  </div>
  
  <div class="prereq-category">
    <h3>AI & Machine Learning Knowledge</h3>
    <ul class="prereq-list">
      <li>Understanding of supervised and unsupervised learning</li>
      <li>Knowledge of loss functions and optimization</li>
      <li>Experience with model evaluation metrics</li>
    </ul>
  </div>
  
  <div class="prereq-category">
    <h3>Neural Network Experience</h3>
    <ul class="prereq-list">
      <li>Prior exposure to feed-forward neural network architectures</li>
      <li>Working knowledge of deep learning frameworks</li>
    </ul>
  </div>
  
  <div class="prereq-category">
    <h3>API Integration Skills</h3>
    <ul class="prereq-list">
      <li>Basic experience using Python APIs</li>
      <li>Understanding of REST API concepts and JSON handling</li>
    </ul>
  </div>
  <p style="margin-top: 30px; font-style: italic; color: #666; text-align: center;"><strong>Pre-Workshop Preparation:</strong> Comprehensive pre-reading materials and setup guides will be provided to all participants prior to workshop commencement to ensure optimal learning outcomes.</p> 
</div>

<div class="venue-section">
  <h2>Venue & Location</h2>
  
  <p><strong>IBMEC University, São Paulo, Brazil</strong></p>
  
  <p>State-of-the-art facilities featuring modern classrooms with advanced AV equipment, high-speed internet infrastructure for API integration exercises, collaborative workspace areas, and comprehensive catering facilities.</p>
  
  <div class="venue-links">
    <a href="https://tourvirtual.ibmec.br/sp" class="venue-link" target="_blank">Virtual Tour</a>
    <a href="https://my.matterport.com/show/?m=34DP2Vhovv1&ss=506&sr=-.66,-1.21" class="venue-link" target="_blank">3D Campus View</a>
    <a href="https://www.google.com/maps/place/Unidade+Ibmec/@-23.5585722,-46.6612906,16.66z" class="venue-link" target="_blank">Google Maps</a>
  </div>
</div>

<div class="investment-section">
  <h2>Investment</h2>
  <div class="price-highlight">1000π BRL</div>
  <p><strong>Comprehensive workshop fee includes:</strong></p>
  <p>All sessions and materials • Catering and refreshments • Professional networking opportunities • Completion certificate • Ongoing community access</p>
</div>

## Registration Process

1. **Application Submission** - Complete online application with technical background
2. **Technical Assessment** - Brief evaluation to ensure prerequisite compliance  
3. **Confirmation & Payment** - Receive acceptance notification and payment instructions
4. **Pre-Workshop Preparation** - Access to setup materials and environment configuration

<div class="cta-section">
  <h2>Secure Your Position</h2>
  <p>Limited to 150 participants. Early registration recommended.</p>
  
  <div class="cta-buttons">
    <a href="mailto:info@theepochtour.ai" class="cta-btn">Apply Now</a>
    <a href="/experiences/saopaulo/" class="cta-btn">Learn More</a>
  </div>
  
  <div style="margin-top: 30px; font-size: 0.9rem;">
    <p><strong>Contact:</strong> info@theepochtour.ai</p>
  </div>
</div>