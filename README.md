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

### 1. Issue 1: Marker Overlap & Zoom Threshold Thresholding
* **Challenge:** High marker density causes overlap and visual clutter when zoomed out.
* **Solution:** Implemented dynamic marker clustering using `Leaflet.markercluster` to group nearby points at lower zoom levels, combined with zoom-level event listeners/visibility thresholds to control marker visibility dynamically based on map zoom.

### 2. Issue 2: Continuous World Wrapping / Earth Repeating
* **Challenge:** When zoomed out, tile maps wrap infinitely across the horizontal axis, repeating the globe infinitely.
* **Solution:** Applied map view boundaries and extent limits (e.g., `noWrap: true` on tile layers and view constraints like `maxBounds` / `extent` settings) to restrict panning and prevent the world map from repeating itself horizontally.

---

## 🛠️ Technical Stack & Frameworks

- **Front-End:** HTML5, CSS3 (Poppins typography, responsive layout, CSS grid & flexbox)
- **Web GIS Libraries:** Leaflet.js v1.9.4, OpenLayers v7.x
- **Basemaps:** Esri World Imagery / ArcGIS World Street Map (optimized for CORS compliance)
- **Deployment & Hosting:** GitHub Pages & GitHub Codespaces

---

## 🤖 Statement on AI Usage & Development Methodology

In line with academic integrity standards, **AI assistance was utilized responsibly as a learning accelerator and research partner** rather than a primary code generation shortcut:

- **Research & Conceptual Understanding:** AI tools were used to research library documentation, compare OpenLayers vs. Leaflet API patterns, and clarify Web GIS standards (such as CORS policy constraints and tile source compatibility).
- **Code Optimization & Debugging:** Guidance was sought for troubleshooting specific layout responsiveness issues and resolving CORS 403 errors encountered with third-party basemap tiles.
- **Hands-on Implementation:** All visual design decisions, structural architecture, spatial data integrations, and code deployment workflows were personally configured and tested.

---

## 🌐 Live Application

Access the deployed Web GIS portfolio live on GitHub Pages:
🔗 **[GMT 458 Web GIS Assigment](https://busra28.github.io/gmt458-assignment1/)**



