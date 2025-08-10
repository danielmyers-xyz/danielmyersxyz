---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-08-10
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-08-04

## Raw Metrics

- **Total cases**: 77
- **Open**:       55
- **Closed**:     22

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    20 |
| Parking Enforcement                       |    14 |
| General Request                           |    13 |
| Tree Maintenance                          |     8 |
| Graffiti Public                           |     5 |
| Residential Building                      |     3 |
| Litter Receptacle Maintenance             |     2 |
| Sidewalk and Curb                         |     2 |
| Encampment                                |     2 |
| Graffiti Private                          |     2 |
| Blocked Street and Sidewalk               |     1 |
| MTA Parking Traffic Signs Normal Priority |     1 |
| Muni Service Feedback                     |     1 |
| Sewer                                     |     1 |
| Street Defect                             |     1 |
| Streetlights                              |     1 |

- **Average resolution time**: 1.5 hrs
- **Open-case aging**:           0–1 d=4, 1–3 d=51, 3+ d=0

## AI Report

Summary: 55 open vs. 22 closed cases.

Top 3 Request Types:
  - Street and Sidewalk Cleaning (20)
  - Parking Enforcement (14)
  - General Request (13)

Closing: Resolution speed 1.5 hrs, open-case aging distribution 0–1 d=4, 1–3 d=51, 3+ d=0
