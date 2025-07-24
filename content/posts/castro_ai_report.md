---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-24
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-23

## Raw Metrics

- **Total cases**: 127
- **Open**:       86
- **Closed**:     41

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    32 |
| Graffiti Public                           |    25 |
| Illegal Postings                          |    23 |
| Parking Enforcement                       |    16 |
| Encampment                                |     9 |
| MTA Parking Traffic Signs Normal Priority |     7 |
| Street Defect                             |     4 |
| Muni Service Feedback                     |     3 |
| Blocked Street and Sidewalk               |     2 |
| Muni Employee Feedback                    |     1 |
| MTA Parking Traffic Signs High Priority   |     1 |
| Sidewalk and Curb                         |     1 |
| Litter Receptacle Maintenance             |     1 |
| General Request                           |     1 |
| Tree Maintenance                          |     1 |

- **Average resolution time**: 1.2 hrs
- **Open-case aging**:           0–1 d=29, 1–3 d=57, 3+ d=0

## AI Report

Summary: 86 open vs. 41 closed cases.

Top 3 Request Types: Graffiti Public, Street and Sidewalk Cleaning, Illegal Postings.
Closing: Resolution speed (1.2 hrs) is slower than expected for the 0–1 d=29, 1–3 d=57, 3+ d=0 open-case aging distribution.
