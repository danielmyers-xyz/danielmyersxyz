---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-19
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-18

## Raw Metrics

- **Total cases**: 56
- **Open**:       42
- **Closed**:     14

### Request Type Breakdown

| request_type                 |   cnt |
|:-----------------------------|------:|
| Street and Sidewalk Cleaning |    23 |
| Parking Enforcement          |    10 |
| Encampment                   |     7 |
| General Request              |     5 |
| Tree Maintenance             |     4 |
| RPD General                  |     3 |
| Illegal Postings             |     2 |
| Graffiti Public              |     1 |
| Street Defect                |     1 |

- **Average resolution time**: 1.1 hrs
- **Open-case aging**:           0–1 d=10, 1–3 d=32, 3+ d=0

## AI Report

Summary: **42 open vs. 14 closed cases.**  
Top 3 Request Types:
* Street and Sidewalk Cleaning (23)
* Encampment (7)
* Parking Enforcement (10)  

Closing: Resolution speed is 1.1 hrs, with open-case aging spread across 0–1 d=10, 1–3 d=32, and 3+ d=0.
