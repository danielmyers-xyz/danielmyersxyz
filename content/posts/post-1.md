---
title: "Zoning Lookup Tool"
description: "Explore an interactive app for accessing zoning data in Marin County"
date: 2025-05-09
draft: false
---

🛠️ **Zoning Lookup Tool — Technical Breakdown**

This application is a browser-based GIS tool built using the ArcGIS API for JavaScript (v4.27), designed to help users search and interactively query zoning information for Marin County, CA.

### 🔧 Features and Architecture

- **Framework**: The app is written in plain JavaScript and styled with custom CSS and the ArcGIS dark theme.
- **Map Initialization**: Uses a `MapView` with a default zoom centered on Marin County. A custom extent is defined for a consistent viewport.
- **Search Integration**: The Esri `Search` widget enables address and Parcel ID lookups, which trigger `FeatureLayer` intersections.
- **Layer Queries**: Parcel, zoning, and general plan layers are all hosted in ArcGIS Online and queried dynamically using spatial `intersects` relationships.
- **Intersection Logic**: A unified query checks all layers and extracts the smallest relevant feature to reduce ambiguity.
- **UI Rendering**: Results are displayed in a sidebar panel. The view automatically zooms to the selected parcel or clicked feature.
- **Performance Optimization**: Layers are hidden by default and only displayed at appropriate zoom levels based on `view.scale` watchers.

### 📦 Tech Stack

- ArcGIS API for JavaScript (CDN)
- Static HTML/CSS/JS, deployed on GitHub Pages
- Hosted ArcGIS Online feature layers
- Fully client-side, no server-side code

### 🖼️ Architecture Diagram

<p align="center">
  <img src="/images/lookup-diagram.png" width="700" alt="Zoning App Architecture Diagram">
</p>

<iframe
  src="https://danielmyersxyz.github.io/lookup-app/"
  width="100%"
  height="600"
  style="border: 1px solid #ccc; border-radius: 4px;"
  loading="lazy"
></iframe>

_Source code available on [GitHub](https://github.com/danielmyersxyz/lookup-app)._
