---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-21
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-20

## Raw Metrics

- **Total cases**: 91
- **Open**:       50
- **Closed**:     41

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    36 |
| Graffiti Public                           |    17 |
| Parking Enforcement                       |     9 |
| Encampment                                |     8 |
| MTA Parking Traffic Signs Normal Priority |     6 |
| Graffiti Private                          |     5 |
| Illegal Postings                          |     3 |
| Sidewalk and Curb                         |     2 |
| Tree Maintenance                          |     1 |
| General Request                           |     1 |
| Litter Receptacle Maintenance             |     1 |
| Sewer                                     |     1 |
| Blocked Street and Sidewalk               |     1 |

- **Average resolution time**: 1.9 hrs
- **Open-case aging**:           0–1 d=0, 1–3 d=50, 3+ d=0

## AI Report

Summary: 41 closed vs. 50 open cases

Top 3 Request Types: 
* Graffiti Public (17)
* Street and Sidewalk Cleaning (36)
* Illegal Postings (5)

Closing: The resolution speed is 1.9 hrs, with an open-case aging distribution of 0–1 d=0, 1–3 d=50, and 3+ days
