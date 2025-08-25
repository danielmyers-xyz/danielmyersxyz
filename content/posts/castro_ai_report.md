---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-08-25
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-08-21

## Raw Metrics

- **Total cases**: 66
- **Open**:       41
- **Closed**:     25

### Request Type Breakdown

| request_type                 |   cnt |
|:-----------------------------|------:|
| Street and Sidewalk Cleaning |    28 |
| General Request              |    10 |
| Parking Enforcement          |     7 |
| Encampment                   |     6 |
| Tree Maintenance             |     4 |
| RPD General                  |     3 |
| Graffiti Public              |     3 |
| Sewer                        |     2 |
| Blocked Street and Sidewalk  |     2 |
| Street Defect                |     1 |

- **Average resolution time**: 1.1 hrs
- **Open-case aging**:           0–1 d=10, 1–3 d=31, 3+ d=0

## AI Report

**Summary:** 41 open vs. 25 closed cases

**Top 3 Request Types:**  
| request_type                 |   cnt |
|:-----------------------------|------:|
| Street and Sidewalk Cleaning |    28 |
| General Request              |    10 |
| Parking Enforcement          |     7 |

**Closing:** Resolution speed is 1.1 hrs, open-case aging is distributed from 0–1 d=10 (first 3 days), to 1–3 d=31 (days 4–10) and 3+ days (more than 10 days).
