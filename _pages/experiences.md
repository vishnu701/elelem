---
title: "Tour Experiences"
permalink: /experiences/
layout: splash
header:
  overlay_image: /assets/images/experiences-hero.jpg
  overlay_filter: "0.5"
  actions:
    - label: "Book Your Adventure"
      url: "#booking"
      btn_class: "btn--primary"
excerpt: "Choose from our carefully curated travel experiences, each designed to immerse you in local culture and create unforgettable memories."

feature_row1:
  - image_path: /assets/images/experiences/grand-tour.jpg
    alt: "Grand World Tour"
    title: "Grand World Tour"
    excerpt: "The complete experience - all 16 cities across 6 continents in 85 unforgettable days."
    url: "/experiences/grand-tour/"
    btn_label: "Full Details"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/experiences/europe-tour.jpg
    alt: "European Discovery"
    title: "European Discovery"
    excerpt: "Paris, Rome, Barcelona, Amsterdam - 4 cities, 20 days of European charm and culture."
    url: "/experiences/europe/"
    btn_label: "Explore Europe"
    btn_class: "btn--primary"
  - image_path: /assets/images/experiences/asia-tour.jpg
    alt: "Asian Adventure"
    title: "Asian Adventure"
    excerpt: "Tokyo, Bangkok, Singapore, Mumbai - 4 cities, 24 days of traditions and innovation."
    url: "/experiences/asia/"
    btn_label: "Discover Asia"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/experiences/americas-tour.jpg
    alt: "Americas Journey"
    title: "Americas Journey"
    excerpt: "NYC, San Francisco, Rio, Buenos Aires - 4 cities, 22 days from skyscrapers to beaches."
    url: "/experiences/americas/"
    btn_label: "Explore Americas"
    btn_class: "btn--primary"
  - image_path: /assets/images/experiences/custom-tour.jpg
    alt: "Custom Experience"
    title: "Custom Experience"
    excerpt: "Design your own adventure - choose your cities, duration, and special interests."
    url: "/experiences/custom/"
    btn_label: "Customize Tour"
    btn_class: "btn--primary"
---

<style>
.experience-highlight {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 40px;
  border-radius: 20px;
  margin: 40px 0;
  text-align: center;
}

.pricing-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.pricing-card {
  background: white;
  border-radius: 15px;
  padding: 30px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  border: 3px solid transparent;
  transition: all 0.3s ease;
}

.pricing-card.featured {
  border-color: #667eea;
  transform: scale(1.05);
}

.price-header {
  text-align: center;
  margin-bottom: 20px;
}

.price {
  font-size: 2.5em;
  font-weight: bold;
  color: #667eea;
}

.inclusions {
  list-style: none;
  padding: 0;
}

.inclusions li {
  padding: 8px 0;
  border-bottom: 1px solid #eee;
}

.inclusions li:before {
  content: "✓ ";
  color: #28a745;
  font-weight: bold;
}

.booking-section {
  background: linear-gradient(45deg, #ff6b6b, #ee5a24);
  color: white;
  padding: 50px;
  border-radius: 20px;
  text-align: center;
  margin: 50px 0;
}

.testimonial {
  background: #f8f9fa;
  padding: 30px;
  border-radius: 15px;
  margin: 20px 0;
  border-left: 5px solid #667eea;
  font-style: italic;
}
</style>

## Choose Your Adventure

{% include feature_row id="feature_row1" type="center" %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row3" %}

## Tour Packages & Pricing

<div class="pricing-grid">
  <div class="pricing-card">
    <div class="price-header">
      <h3>Regional Explorer</h3>
      <div class="price">$3,999</div>
      <p>Single continent experience</p>
    </div>
    <ul class="inclusions">
      <li>4-5 cities per region</li>
      <li>18-24 days of adventure</li>
      <li>Premium accommodations</li>
      <li>All meals included</li>
      <li>Expert local guides</li>
      <li>Small group (max 16)</li>
      <li>Cultural experiences</li>
      <li>Transportation included</li>
    </ul>
    <div style="text-align: center; margin-top: 20px;">
      <a href="#booking" class="btn btn--primary">Book Regional</a>
    </div>
  </div>

  <div class="pricing-card featured">
    <div class="price-header">
      <h3>Grand World Tour</h3>
      <div class="price">$24,999</div>
      <p>Complete global experience</p>
    </div>
    <ul class="inclusions">
      <li>All 16 amazing cities</li>
      <li>85 days of pure adventure</li>
      <li>Luxury accommodations</li>
      <li>All meals & experiences</li>
      <li>Private group benefits</li>
      <li>VIP access & exclusives</li>
      <li>Personal trip coordinator</li>
      <li>All flights included</li>
      <li>24/7 concierge service</li>
    </ul>
    <div style="text-align: center; margin-top: 20px;">
      <a href="#booking" class="btn btn--primary btn--large">Book Grand Tour</a>
    </div>
  </div>

  <div class="pricing-card">
    <div class="price-header">
      <h3>Custom Experience</h3>
      <div class="price">$4,999+</div>
      <p>Your personalized journey</p>
    </div>
    <ul class="inclusions">
      <li>Choose your cities</li>
      <li>Flexible duration</li>
      <li>Tailored experiences</li>
      <li>Special interests focus</li>
      <li>Private or group options</li>
      <li>Extended stays available</li>
      <li>Family-friendly options</li>
      <li>Anniversary specials</li>
    </ul>
    <div style="text-align: center; margin-top: 20px;">
      <a href="/experiences/custom/" class="btn btn--primary">Customize</a>
    </div>
  </div>
</div>

<div class="experience-highlight">
<h2>What Makes Our Tours Extraordinary?</h2>
<p>We don't just show you destinations—we immerse you in them. Every experience is designed to create deep connections with local culture, cuisine, and communities.</p>
</div>

## What's Always Included

- **Premium Accommodations:** Handpicked hotels, boutique properties, and unique stays
- **Expert Guides:** Local professionals who bring destinations to life
- **Cultural Immersion:** Authentic experiences unavailable to typical tourists
- **Small Groups:** Maximum 20 people for personalized attention
- **Culinary Experiences:** Local cuisine, cooking classes, and food tours
- **Transportation:** All local transport, transfers, and applicable flights
- **24/7 Support:** Always available assistance throughout your journey
- **Pre-Trip Planning:** Detailed preparation and cultural orientation

## Traveler Stories

<div class="testimonial">
"The Grand World Tour exceeded every expectation. From the cooking class in a Parisian apartment to watching the sunrise over Angkor Wat, every moment was magical. Our guide team became like family, and I made friendships that will last forever."
<br><strong>— Maria S., Grand Tour 2024</strong>
</div>

<div class="testimonial">
"As someone who has traveled extensively for work, I thought I knew what to expect. I was completely wrong. This tour showed me sides of cities I thought I knew, and introduced me to places I never would have discovered on my own."
<br><strong>— James L., European Discovery 2024</strong>
</div>

<div class="testimonial">
"The custom tour option was perfect for our 25th anniversary. They incorporated our love of art and wine into every stop, creating experiences that were uniquely ours. Worth every penny."
<br><strong>— Robert & Linda K., Custom Tour 2024</strong>
</div>

## Frequently Asked Questions

**Q: What if I have dietary restrictions?**
A: We accommodate all dietary needs including vegetarian, vegan, gluten-free, and religious restrictions. We'll ensure you enjoy the local cuisine safely.

**Q: How much walking is involved?**
A: Most tours involve moderate walking (3-5 miles per day). We always provide alternatives for those who prefer less walking.

**Q: What about travel insurance?**
A: We strongly recommend travel insurance and can connect you with trusted providers. Some coverage is included in our premium packages.

**Q: Can I join a tour as a solo traveler?**
A: Absolutely! About 40% of our travelers are solo adventurers. We ensure everyone feels welcome and included.

**Q: How far in advance should I book?**
A: We recommend booking 6-12 months in advance for the best selection and pricing. Popular dates sell out quickly.

<div class="booking-section" id="booking">
<h2>Ready to Begin Your Adventure?</h2>
<p>Don't just dream about seeing the world—make it happen. Our travel experts are standing by to help you choose the perfect experience.</p>
<br>
<a href="mailto:bookings@worldtour2025.com" class="btn btn--large btn--light">Email Us</a>
<a href="tel:+1-555-WORLD-TOUR" class="btn btn--large btn--outline">Call Now</a>
<br><br>
<p>📧 bookings@worldtour2025.com | 📞 +1 (555) WORLD-TOUR</p>
</div>

*Every journey begins with a single step. Take yours today.*