---
layout: page
title: "City Catalog"
permalink: /catalog/
---

# World Tour 2025 - City Catalog

Explore our complete collection of destinations. Each city has been carefully curated to provide authentic cultural experiences, incredible local cuisine, and unforgettable memories.

## Available Destinations

### 🇪🇺 Europe
{% assign europe_cities = site.catalog | where: "cycle", "worldtour2025" | where_exp: "item", "item.sequence <= 4" | sort: "sequence" %}
<div class="city-grid">
{% for city in europe_cities %}
  <div class="city-card">
    <h3><a href="{{ city.url }}">{{ city.title }}</a></h3>
    <p>{{ city.excerpt }}</p>
    <a href="{{ city.url }}" class="btn">Learn More</a>
  </div>
{% endfor %}
</div>

### 🌏 Asia
{% assign asia_cities = site.catalog | where: "cycle", "worldtour2025" | where_exp: "item", "item.sequence >= 5 and item.sequence <= 8" | sort: "sequence" %}
<div class="city-grid">
{% for city in asia_cities %}
  <div class="city-card">
    <h3><a href="{{ city.url }}">{{ city.title }}</a></h3>
    <p>{{ city.excerpt }}</p>
    <a href="{{ city.url }}" class="btn">Learn More</a>
  </div>
{% endfor %}
</div>

### 🌎 Americas
{% assign americas_cities = site.catalog | where: "cycle", "worldtour2025" | where_exp: "item", "item.sequence >= 9 and item.sequence <= 12" | sort: "sequence" %}
<div class="city-grid">
{% for city in americas_cities %}
  <div class="city-card">
    <h3><a href="{{ city.url }}">{{ city.title }}</a></h3>
    <p>{{ city.excerpt }}</p>
    <a href="{{ city.url }}" class="btn">Learn More</a>
  </div>
{% endfor %}
</div>

### 🌍 Africa & Oceania
{% assign africa_oceania_cities = site.catalog | where: "cycle", "worldtour2025" | where_exp: "item", "item.sequence >= 13" | sort: "sequence" %}
<div class="city-grid">
{% for city in africa_oceania_cities %}
  <div class="city-card">
    <h3><a href="{{ city.url }}">{{ city.title }}</a></h3>
    <p>{{ city.excerpt }}</p>
    <a href="{{ city.url }}" class="btn">Learn More</a>
  </div>
{% endfor %}
</div>

---

## All Cities Overview

{% assign all_cities = site.catalog | where: "cycle", "worldtour2025" | sort: "sequence" %}

| City | Region | Excerpt | Duration |
|------|--------|---------|----------|
{% for city in all_cities %}| [{{ city.title }}]({{ city.url }}) | {% if city.sequence <= 4 %}Europe{% elsif city.sequence <= 8 %}Asia{% elsif city.sequence <= 12 %}Americas{% else %}Africa/Oceania{% endif %} | {{ city.excerpt }} | 4-6 days |
{% endfor %}

---

## Planning Your Journey

**Regional Tours:** Choose one continent for an in-depth exploration  
**Grand World Tour:** Experience all 16 cities over 85 incredible days  
**Custom Experience:** Create your own itinerary with selected cities

[View All Experiences →](/experiences/) | [Book Your Adventure →](/experiences/#book)

<style>
.city-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.city-card {
  border: 1px solid #ddd;
  padding: 20px;
  border-radius: 8px;
  background: #f9f9f9;
}

.city-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
}

.city-card h3 a {
  text-decoration: none;
  color: #333;
}

.city-card h3 a:hover {
  color: #007bff;
}

.btn {
  display: inline-block;
  padding: 8px 16px;
  background: #007bff;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  margin-top: 10px;
}

.btn:hover {
  background: #0056b3;
  color: white;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
}

table th, table td {
  border: 1px solid #ddd;
  padding: 8px;
  text-align: left;
}

table th {
  background-color: #f2f2f2;
}
</style>