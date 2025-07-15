---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-15
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-13

## Raw Metrics

- **Total cases**: 100
- **Open**:       73
- **Closed**:     27

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    29 |
| Graffiti Public                           |    16 |
| Parking Enforcement                       |    15 |
| Graffiti Private                          |    10 |
| Illegal Postings                          |    10 |
| Encampment                                |     8 |
| Tree Maintenance                          |     4 |
| RPD General                               |     3 |
| Street Defect                             |     2 |
| MTA Parking Traffic Signs Normal Priority |     1 |
| Sidewalk and Curb                         |     1 |
| Litter Receptacle Maintenance             |     1 |

- **Average resolution time**: 2.1 hrs
- **Open-case aging**:           0–1 d=35, 1–3 d=38, 3+ d=0

## AI Report

Summary: 73 open vs. 27 closed cases.

Top 3 Request Types: 
1. Street and Sidewalk Cleaning – 29 requests (64%)
2. Graffiti Public – 16 requests (35%)
3. Parking Enforcement – 15 requests (30%)

Closing: Resolution speed is 2.1 hrs, with open-case aging at 0–1 d=35, 1–3 d=38, and 3+ d=0.
