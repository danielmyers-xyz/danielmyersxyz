---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-08-04
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-08-03

## Raw Metrics

- **Total cases**: 87
- **Open**:       40
- **Closed**:     47

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    27 |
| Illegal Postings                          |    24 |
| Parking Enforcement                       |    12 |
| Tree Maintenance                          |     4 |
| MTA Parking Traffic Signs Normal Priority |     4 |
| Encampment                                |     3 |
| General Request                           |     3 |
| RPD General                               |     3 |
| Graffiti Public                           |     2 |
| Noise                                     |     1 |
| Graffiti Private                          |     1 |
| Blocked Street and Sidewalk               |     1 |
| Sewer                                     |     1 |
| Sidewalk and Curb                         |     1 |

- **Average resolution time**: 1.3 hrs
- **Open-case aging**:           0–1 d=6, 1–3 d=34, 3+ d=0

## AI Report

Summary: **40 open vs. 47 closed cases.**  
Top 3 Request Types: Street and Sidewalk Cleaning, Illegal Postings, Parking Enforcement  
 Closing: Resolution speed is 1.3 hrs; Open-case aging distribution varies from 0–1 d=6 to 3+ d=0
