# KUAGI AI Accessibility Gap Explorer

## Map<>Kathon 2026 Project

### Developer
**NSABIMANA Fabrice**

---

## Overview

KUAGI AI Accessibility Gap Explorer is an AI-powered GIS decision-support platform that identifies, visualizes, and explains accessibility gaps across Kigali City, Rwanda.

The project combines **OpenStreetMap data, GIS analysis, ArcGIS Experience Builder, and an integrated AI assistant** to support better urban planning and infrastructure decisions.

---

## Public Good Problem

Many communities experience unequal access to essential services such as:

- Schools
- Health facilities
- Markets
- Public transport
- Roads

Limited accessibility can make it difficult for communities to reach essential services.

KUAGI helps identify areas where accessibility improvements and infrastructure interventions are most needed.

---

## OSM Data Used

OpenStreetMap contributed geographic data including:

- Road networks
- Schools
- Health facilities
- Markets
- Transport locations
- Buildings and other urban features

---

## Methodology

1. Collect OpenStreetMap data.
2. Prepare and analyze spatial layers.
3. Create a 500 m × 500 m analysis grid.
4. Calculate accessibility and infrastructure indicators.
5. Generate KUAGI scores.
6. Classify areas according to accessibility priority.
7. Publish the results through an interactive ArcGIS Experience.
8. Connect the KUAGI accessibility dataset to an AI knowledge retrieval system.
9. Provide AI-assisted analysis, explanations, and recommended interventions.

---

## KUAGI AI Assistant

KUAGI AI is integrated into the ArcGIS Experience as an interactive accessibility assistant.

Users can click the **KUAGI AI logo** to open the chat interface and ask questions about:

- Accessibility gaps
- KUAGI scores
- Priority areas
- Districts and sectors
- Health accessibility
- Education accessibility
- Market accessibility
- Transport and road accessibility
- Infrastructure conditions
- Population density
- Recommended interventions

KUAGI AI searches the available KUAGI accessibility dataset and uses relevant information to generate data-grounded responses.

Example questions:

> Which sector has the highest accessibility gap?

> Which areas should be prioritized for health facilities?

> Compare accessibility gaps between districts.

---

## Priority Classification

| Priority | Score |
|----------|-------|
| 🔴 Critical | 80–100 |
| 🟠 High | 60–79.99 |
| 🟡 Moderate | 40–59.99 |
| 🟢 Low | 0–39.99 |

Higher KUAGI scores indicate greater accessibility challenges and a higher need for intervention.

---

## Tools Used

### GIS and Mapping

- ArcGIS Pro
- ArcGIS Online
- ArcGIS Experience Builder
- ArcGIS Dashboards
- ArcGIS Map Viewer
- ArcGIS Arcade

### OpenStreetMap and Data

- OpenStreetMap
- Overpass Turbo
- Python

### AI and Knowledge Retrieval

- Dify
- GPT-5
- Knowledge Retrieval
- Hybrid Search
- AI-assisted analysis

---

## Dashboard

### 🚀 Live KUAGI AI Accessibility Gap Explorer
[
:contentReference[oaicite:0]{index=0}](https://experience.arcgis.com/experience/f4c36912969b4664a4efe3109aa5b965)

---

## Project Workflow

```text
OpenStreetMap Data
        │
        ▼
GIS Data Preparation
        │
        ▼
Spatial Analysis
        │
        ▼
500 m × 500 m Grid Analysis
        │
        ▼
Accessibility Indicators
        │
        ▼
KUAGI Score
        │
        ▼
Priority Classification
        │
        ├── Critical
        ├── High
        ├── Moderate
        └── Low
        │
        ▼
ArcGIS Experience Builder
        │
        ├── Interactive Maps
        ├── Charts and Indicators
        └── KUAGI AI Assistant
                    │
                    ▼
          Knowledge Retrieval
                    │
                    ▼
               AI Analysis
                    │
                    ▼
       Evidence-Based Insights
