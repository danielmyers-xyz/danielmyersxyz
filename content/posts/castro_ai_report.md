---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-12
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-10

## Raw Metrics

- **Total cases**: 89
- **Open**:       55
- **Closed**:     34

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    35 |
| Graffiti Public                           |    17 |
| Encampment                                |     9 |
| Parking Enforcement                       |     6 |
| General Request                           |     5 |
| Graffiti Private                          |     5 |
| Tree Maintenance                          |     3 |
| Sewer                                     |     2 |
| MTA Parking Traffic Signs Normal Priority |     1 |
| Blocked Street and Sidewalk               |     1 |
| Illegal Postings                          |     1 |
| Autonomous Vehicle Complaints             |     1 |
| Muni Employee Feedback                    |     1 |
| Muni Service Feedback                     |     1 |
| Street Defect                             |     1 |

- **Average resolution time**: 1.3 hrs
- **Open-case aging**:           0–1 d=0, 1–3 d=55, 3+ d=0

## AI Report

Summary: Open cases total 55 with 34 closed and 21 still pending for over a week, while average resolution time is 1.3 hours per case.

Top 3 Request Types: Graffiti Private (17), Street and Sidewalk Cleaning (35), Parking Enforcement (6).
