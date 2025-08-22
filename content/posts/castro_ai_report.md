---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-08-22
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-08-13

## Raw Metrics

- **Total cases**: 69
- **Open**:       30
- **Closed**:     39

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    22 |
| Parking Enforcement                       |    17 |
| General Request                           |    10 |
| Encampment                                |     6 |
| Graffiti Public                           |     3 |
| Sidewalk and Curb                         |     3 |
| Graffiti Private                          |     2 |
| Street Defect                             |     1 |
| Streetlights                              |     1 |
| Illegal Postings                          |     1 |
| Tree Maintenance                          |     1 |
| MTA Parking Traffic Signs Normal Priority |     1 |
| Residential Building                      |     1 |

- **Average resolution time**: 2.9 hrs
- **Open-case aging**:           0–1 d=0, 1–3 d=0, 3+ d=30

## AI Report

Summary: 30 open vs. 39 closed cases.

Top 3 Request Types:
- Street and Sidewalk Cleaning              (22)
- Parking Enforcement                       (17)
- General Request                           (10)

Closing: One sentence commenting on the resolution speed (2.9 hrs) and the open-case aging distribution (0–1 d=0, 1–3 d=0, 3+ d=30).
