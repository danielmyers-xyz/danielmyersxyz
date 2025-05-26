---
title: "Building a Personal GeoServer & PostGIS Stack"
date: 2025-05-25
draft: false
description: "How I built a self-hosted open-source GIS stack using Docker, GeoServer, PostGIS, and AWS Lightsail"
tags: ["GIS", "PostGIS", "GeoServer", "AWS", "Open Source"]
---

## Building a Personal GeoServer & PostGIS Stack

I've worked with ArcGIS Online, ArcGIS Enterprise, and Microsoft SQL Server throughout my GIS career. I wanted a way to explore serving geospatial data using open-source tools and cloud infrastructure.

That led me to build a personal GeoServer and PostGIS stack. I wanted a mini-server setup I could tinker with, break, rebuild, and use for hobby projects without relying on enterprise software. Here’s how I built it.

#### Why GeoServer & PostGIS?

GeoServer is the open-source counterpart to something like ArcGIS Server—it serves spatial data via standards like WFS and WMS, letting me host layers from my own database with full control. PostGIS, on the other hand, is the spatial extension for PostgreSQL and a powerful alternative to Microsoft SQL Server’s spatial capabilities. Together, they give me the kind of stack you'd expect from an enterprise GIS setup, but entirely open-source and self-hosted.

#### My Setup

I chose AWS Lightsail because of its fixed monthly cost, which makes budgeting easier than with EC2. I went with the 4 GB RAM, 2 vCPU Ubuntu 22.04 LTS instance (80 GB SSD) to keep costs low, even though I'd prefer the 8 GB tier.  

- **Dockerized Stack:**  
  GeoServer and PostGIS run in Docker containers (using official Docker images) and are orchestrated via a simple `docker-compose.yml`, ensuring easy deployment, consistent environments, and persistent data volumes.

![Architecture Diagram](/images/architecture-diagram.webp)

#### Connecting the Dots

To simplify and secure remote access, I configured a Cloudflare Tunnel paired with their free DNS service. This let me route traffic through a stable URL without needing to open ports on my server or worry about dynamic IPs. It's secure, low‑maintenance, and perfect for a side project like this.

#### What's Next?

My plans include:

- Building dashboards (stay tuned for another blog post!)  
- Playing around with spatial data for San Francisco neighborhoods  
- Experimenting more with styling and theming

This setup is practical and it gives me the freedom to experiment with an enterprise‑style GIS stack on my own terms, without license constraints or vendor lock‑in. And because it’s all open‑source, I can dig into every layer, customize everything, and actually understand how the whole thing works under the hood.