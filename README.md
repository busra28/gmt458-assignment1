# GMT 458 - Web GIS Assignment 

Welcome to my personal Web GIS assignment repository! This project showcases interactive web mapping applications built using modern front-end technologies and open-source spatial mapping libraries.

---

## 📌 Project Overview

This repository hosts a multi-page web application developed as part of the **GMT 458 (Web GIS)** course at **Hacettepe University, Department of Geomatics/Map Engineering**.

The web application consists of three main pages:
1. **About Me (`index.html`):** Personal presentation, academic background, geomatics engineering context, and profile branding.
2. **Maps (`maps.html`):** Interactive Web GIS applications featuring Leaflet.js and OpenLayers.
3. **Contact (`social.html`):** Contact information and professional networking links.

---

## 💡 Solution to Web GIS Technical Issues

As required by the assignment guidelines, the following core web mapping challenges were explicitly addressed in the code:

### 1. Issue 1: Marker Overlap & Zoom Threshold
* **Challenge:** High marker density causes overlap and visual clutter when zoomed out.
* **Solution:** Implemented dynamic marker clustering using `Leaflet.markercluster` to group nearby points at lower zoom levels, combined with zoom-level event listeners to control marker visibility dynamically based on map zoom.

### 2. Issue 2: Continuous World Wrapping / Earth Repeating
* **Challenge:** When zoomed out, tile maps wrap infinitely across the horizontal axis, repeating the globe.
* **Solution:** Applied map view boundaries and extent limits (e.g., `noWrap: true` on tile layers and view constraints like `maxBounds`) to restrict panning and prevent the world map from repeating itself horizontally.

---

## 🤖 Statement on AI Usage & Development Methodology

In compliance with the course guidelines regarding AI assistance (prioritizing independent research and utilizing AI when needed), here are the specific details of my AI usage:

* **Specific Issues/Learnings from AI:** 
  - Learned how to properly configure custom vector layers and view constraints in OpenLayers to prevent infinite world repeating.
  - Resolved specific CORS 403 error behaviors encountered when loading third-party tile server basemaps.
* **Total AI Usage Estimate:** Approximately **1.5 hours** total across the entire development and debugging lifecycle (primarily used for documentation syntax review and troubleshooting specific library integration errors).
* **Development Principle:** All visual design decisions, architectural structuring, content creation, and code deployment workflows were personally configured, tested, and implemented.

---

## 🛠️ Technical Stack & Frameworks

- **Front-End:** HTML5, CSS3 (Poppins typography, responsive layout, CSS grid & flexbox)
- **Web GIS Libraries:** Leaflet.js v1.9.4, OpenLayers v7.x
- **Basemaps:** Esri World Imagery / ArcGIS World Street Map
- **Deployment & Hosting:** GitHub Pages & GitHub Codespaces

---

## 🌐 Live Website

Access the deployed Web GIS portfolio live on GitHub Pages:
🔗 **[GMT 458 Web GIS Portfolio](https://busra28.github.io/gmt458-assignment1/)**





