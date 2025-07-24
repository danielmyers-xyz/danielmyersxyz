---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-07-24
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-07-22

## Raw Metrics

- **Total cases**: 108
- **Open**:       61
- **Closed**:     47

### Request Type Breakdown

| request_type                              |   cnt |
|:------------------------------------------|------:|
| Street and Sidewalk Cleaning              |    43 |
| Illegal Postings                          |    23 |
| Parking Enforcement                       |    10 |
| Encampment                                |    10 |
| General Request                           |     8 |
| Graffiti Public                           |     4 |
| Muni Service Feedback                     |     3 |
| Litter Receptacle Maintenance             |     2 |
| Tree Maintenance                          |     1 |
| MTA Parking Traffic Signs Normal Priority |     1 |
| RPD General                               |     1 |
| Shared Spaces Request                     |     1 |
| Blocked Street and Sidewalk               |     1 |

- **Average resolution time**: 2.1 hrs
- **Open-case aging**:           0–1 d=22, 1–3 d=39, 3+ d=0

## AI Report

Summary: 61 open vs. 47 closed cases.

Top 3 Request Types: Street and Sidewalk Cleaning, Illegal Postings, Parking Enforcement
Closing: This average resolution time (2.1 hrs) indicates a reasonable speed for SF public works requests. The open-case aging distribution shows that most issues are resolved within a week (0–1 d=22), with fewer cases being resolved over 3 days (1–3 d=39) or more than 3 days (3+ d=0).
