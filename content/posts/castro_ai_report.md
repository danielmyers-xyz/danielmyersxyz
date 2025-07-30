---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-30
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-29

## Raw Metrics

- **Total cases**: 94
- **Open**:       60
- **Closed**:     34

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    27 |
| Parking Enforcement                       |    19 |
| Graffiti Public                           |     9 |
| Sewer                                     |     7 |
| General Request                           |     6 |
| Graffiti Private                          |     6 |
| Tree Maintenance                          |     5 |
| Noise                                     |     2 |
| Encampment                                |     2 |
| Litter Receptacle Maintenance             |     2 |
| MTA Parking Traffic Signs Normal Priority |     2 |
| Blocked Street and Sidewalk               |     2 |
| RPD General                               |     2 |
| Street Defect                             |     2 |
| Sidewalk and Curb                         |     1 |

- **Average resolution time**: 0.8 hrs
- **Open-case aging**:           0–1 d=10, 1–3 d=50, 3+ d=0

## AI Report

Summary:  60 open vs. 34 closed cases.

Top 3 Request Types:
1. Street and Sidewalk Cleaning
2. Parking Enforcement
3. Graffiti Private

Closing:  0.8 hrs is the average resolution time, with an open-case aging distribution of 0–1 d=10, 1–3 d=50, 3+ d=0
