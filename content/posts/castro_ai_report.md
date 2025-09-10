---
title: "Daily AI-Enhanced 311 Report for San Francisco’s Castro"
date: 2025-09-10
description: "Automated daily summary of 311 service requests in the Castro neighborhood using Python, SQL, PostGIS and the smollm2:1.7b model via a local chat API."
tags: ["castro", "311", "san francisco", "postgis", "sql", "jupyter", "ai", "smollm2", "chat-api"]
draft: false
---

# SF Castro 311 Dashboard Summary — 2025-08-24

## Raw Metrics

- **Total cases**: 70
- **Open**:       41
- **Closed**:     29

### Request Type Breakdown

| request_type                 |   cnt |
|:-----------------------------|------:|
| Street and Sidewalk Cleaning |    26 |
| Graffiti Public              |    11 |
| Parking Enforcement          |     8 |
| General Request              |     6 |
| Encampment                   |     3 |
| Tree Maintenance             |     3 |
| Noise                        |     2 |
| Blocked Street and Sidewalk  |     2 |
| RPD General                  |     2 |
| Sidewalk and Curb            |     2 |
| Sewer                        |     1 |
| Graffiti Private             |     1 |
| Muni Employee Feedback       |     1 |
| Muni Service Feedback        |     1 |
| Street Defect                |     1 |

- **Average resolution time**: 1.5 hrs
- **Open-case aging**:           0–1 d=3, 1–3 d=38, 3+ d=0

## AI Report

**SF_OpenCloseReport: {date}**  
- Summary: Open cases: 41 | Closed cases: 29  
- Top Request Types:  
  - Street and Sidewalk Cleaning (26)   
  - Graffiti Public (11)    
  - Parking Enforcement (8)   
- The average resolution time stands at a swift 1.5 hrs, with most open cases resolved within the first day; however, longer durations are notably less common beyond three days ago and none past that mark remain unresolved today.
