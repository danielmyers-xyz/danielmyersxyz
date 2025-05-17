---
title: "ChatGPT Zoning Chatbot"
date: 2025-05-16
draft: false
description: "A demo using GeoPandas, Folium, and the OpenAI API to summarize zoning for a given address in Marin County."
tags: ["zoning", "chatbot", "folium", "geopandas", "openai"]
---


## Building a Zoning Chatbot with GeoPandas, Folium, and the OpenAI API

I wanted to create a proof-of-concept chatbot that could answer basic zoning questions using spatial data. The idea was simple: enter an address, and get back a zoning summary with a map. I used a combination of Python tools I already lean on—GeoPandas, Folium, and the OpenAI API—and wired them up into a notebook that does just that.

🧠 The chatbot takes in an address, geocodes it with Nominatim, runs a spatial join with a zoning shapefile (in this case, for Marin County), and then sends the resulting zoning description to the OpenAI API for summarization. It returns both the original zoning text and a cleaned-up explanation in plain English. I also generate an interactive map with Folium showing the parcel boundary and surrounding zoning.

One of my main goals here was **accessibility**—I wanted a zoning lookup tool that produces output that's easy to read aloud by a screen reader or text-to-speech tool. A lot of existing GIS interfaces aren't optimized for accessibility or non-technical users. This approach keeps the logic spatial but outputs something lightweight, plain-text, and structured for assistive tech.


## 🔧 Tech Stack
- `GeoPandas` for spatial joins
- `Folium` for web map generation
- `geopy` + Nominatim for geocoding
- `openai` Python library for GPT-based summarization
- A zoning geojson of Unincorporated Marin County from Open Data


## 📂 Files & Structure

This notebook defines four core functions:

- `lookup_zoning(address)`: Geocodes the input address, converts it to a GeoDataFrame, reprojects to match the zoning data, and performs a spatial join to find the intersecting zoning polygon.
- `summarize_zoning(zone_gdf)`: Extracts zoning attributes from the joined polygon, builds a prompt, and sends it to the OpenAI API for summarization.
- `show_result_map(point_geom, result_gdf)`: Uses Folium to visualize the point and intersecting zoning polygon.
- `zoning_chatbot(address)`: High-level wrapper function that ties everything together, prints the zoning attributes, gets the summary, and shows the map.

## 🗺️ Try it yourself

You can view the notebook on GitHub or interact with the embedded version below:

[🔗 View the repository on GitHub](https://github.com/danielmyers-xyz/zoning-chatbot)

<iframe src="/notebooks/chatbot.html" width="100%" height="800px" style="border:none;"></iframe>