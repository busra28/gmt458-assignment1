# 🌍 GMT 458 Web GIS Personal Portfolio & Interactive Maps

**Author:** Büşra Başoğlu  
**Course:** GMT 458 - Web GIS | Hacettepe University  
**Live Demo:** [https://busra28.github.io/gmt458-assignment1/](https://busra28.github.io/gmt458-assignment1/)    

---

## 📌 Project Overview & Aim
The primary aim of this project is to construct a personalized, interactive Web GIS portfolio utilizing **HTML5, CSS3, OpenLayers, and Leaflet.js**. The website highlights my academic background as a Senior Geomatics/Map Engineering student at Hacettepe University, showcases professional GIS software skills, and provides interactive maps for exploring global vinyl record spots and concert journal memories.

---

## 🎯 Fulfillment of Course Objectives

### 1. Structure & HTML Files 
The web application is structured with **4 distinct HTML pages** sharing a cohesive design language:
* `index.html` - Professional Bio, Geomatics Skills, Experience, and Interactive Nav Cards.
* `maps.html` - Dual-engine Web GIS mapping interface using **OpenLayers** and **Leaflet.js**.
* `gallery.html` - Concert journal featuring a clustered Leaflet map, category filters, and upcoming show countdowns.
* `social.html` - Contact details, GitHub repository, and professional links.

### 2. Styling, Animations & Tables (20%)
* **CSS Animations :** Custom `@keyframes fadeInUp` loading animations, smooth `cubic-bezier` hover elevations, and dynamic card transitions.
* **Tabular Data with Images :** Styled technology and software tables enriched with visual tech logos and interactive row hover effects.

### 3. OpenLayers & Leaflet Web Mapping 
* **OpenLayers Integration (10%):** Vector layers and micro-scale visualization implemented on `maps.html`.
* **Leaflet Integration (10%):** Client-side interactive mapping on `maps.html` and `gallery.html`.

---

## 🛠️ Solutions to Common Web GIS Issues

### 📍 Issue 1: Overlapping Markers on Zoom
* **Problem:** When multiple markers share similar geographic coordinates, they overlap and obscure each other.
* **Solution:** Integrated `Leaflet.markercluster` plugin (`L.markerClusterGroup`). Configured `spiderfyOnMaxZoom: true` and `zoomToBoundsOnClick: true` so markers automatically cluster at lower zoom levels and spread out upon zooming in.

### 🌐 Issue 2: Earth Repeating Itself Across Map Bounds
* **Problem:** Horizontal panning allows tile basemaps to wrap infinitely, creating repeating worlds.
* **Solution:** 
  1. Set `noWrap: true` on tile layers (`L.tileLayer`).
  2. Applied strict spatial bounds using `maxBounds: L.latLngBounds(L.latLng(-85, -180), L.latLng(85, 180))`.
  3. Enforced constraint rigidity with `maxBoundsViscosity: 1.0`.

---

## 🤖 AI Usage Declaration

* **What was learned/resolved using AI:**
  * Consulted for syntax structures and configuration guidelines when implementing Leaflet marker clustering and spatial boundary constraints (`maxBoundsViscosity`).
  * Used for brainstorming CSS grid layouts, card transitions, and debugging responsive mobile styling issues.
  * Researched best practices for structuring clean Web GIS HTML/CSS repositories.
* **Estimated Total AI Usage:** Approximately **2 hours** of collaborative troubleshooting, concept verification, and code optimization throughout the assignment process.

---

© 2026 GMT 458 Web GIS Assignment | Designed by Büşra Başoğlu 💙




