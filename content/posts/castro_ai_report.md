---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-29
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-27

## Raw Metrics

- **Total cases**: 82
- **Open**:       54
- **Closed**:     28

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    27 |
| Graffiti Public                           |    22 |
| Parking Enforcement                       |    10 |
| Encampment                                |     8 |
| Illegal Postings                          |     7 |
| MTA Parking Traffic Signs Normal Priority |     3 |
| Graffiti Private                          |     2 |
| Street Defect                             |     2 |
| Sewer                                     |     1 |

- **Average resolution time**: 1.0 hrs
- **Open-case aging**:           0–1 d=43, 1–3 d=11, 3+ d=0

## AI Report

Summary:  
There were 28 closed cases and 54 open cases.
Top 3 Request Types:  
Street and Sidewalk Cleaning, Graffiti Public, Encampment
Closing:  
Resolution speed is 1 hour (on average), and the open-case aging distribution is primarily < 1 day (43%), > 1–3 days (11%), and > 3+ days (0%).
