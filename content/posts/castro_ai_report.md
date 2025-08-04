---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-08-04
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-31

## Raw Metrics

- **Total cases**: 80
- **Open**:       47
- **Closed**:     33

### Request Type Breakdown

| request_type                  |   cnt |
|:------------------------------|------:|
| Street and Sidewalk Cleaning  |    35 |
| Graffiti Public               |    13 |
| Parking Enforcement           |    12 |
| General Request               |     8 |
| Street Defect                 |     3 |
| Graffiti Private              |     2 |
| Tree Maintenance              |     2 |
| RPD General                   |     2 |
| Sewer                         |     1 |
| Litter Receptacle Maintenance |     1 |
| Muni Service Feedback         |     1 |

- **Average resolution time**: 1.5 hrs
- **Open-case aging**:           0–1 d=20, 1–3 d=27, 3+ d=0

## AI Report

Summary: 47 open vs. 33 closed cases.

Top 3 Request Types:
* Street and Sidewalk Cleaning (35)
* Graffiti Public (13)
* Parking Enforcement (12)

Closing: One sentence commenting on the resolution speed (1.5 hrs) and the open-case aging distribution (0–1 d=20, 1–3 d=27, 3+ d=0).
