---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-17
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-14

## Raw Metrics

- **Total cases**: 164
- **Open**:       117
- **Closed**:     47

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Graffiti Public                           |    49 |
| Street and Sidewalk Cleaning              |    35 |
| Illegal Postings                          |    23 |
| Parking Enforcement                       |    16 |
| Graffiti Private                          |    10 |
| General Request                           |     8 |
| MTA Parking Traffic Signs Normal Priority |     7 |
| Encampment                                |     6 |
| Street Defect                             |     2 |
| Litter Receptacle Maintenance             |     2 |
| Tree Maintenance                          |     2 |
| Shared Spaces Request                     |     1 |
| Streetlights                              |     1 |
| Sidewalk and Curb                         |     1 |
| Temporary Sign Applications               |     1 |

- **Average resolution time**: 1.7 hrs
- **Open-case aging**:           0–1 d=21, 1–3 d=96, 3+ d=0

## AI Report

Summary: 117 open vs. 47 closed cases.

Top 3 Request Types: Graffiti Public, Street and Sidewalk Cleaning, Illegal Postings.

Closing: With an average resolution time of 1.7 hrs and open-case aging distribution of 0–1 d=21, 1–3 d=96, 3+ d=0, the SF 311 service is moderately performing in terms of both speed and retention.
