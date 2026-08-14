# 🗺️ KUAGI AI Accessibility Gap Explorer
<img width="960" height="441" alt="image" src="https://github.com/user-attachments/assets/c08bbff3-e92e-4fd6-9085-557217f02925" />


## Map<>Kathon 2026 Project

**KUAGI (Kigali Urban Accessibility Gap Index)** is an AI-powered GIS decision-support platform developed to identify, visualize, analyze, and explain urban accessibility gaps across Kigali City, Rwanda.

The project combines **OpenStreetMap data, spatial analysis, ArcGIS technology, interactive visualization, and an integrated AI assistant** to support data-driven urban planning and improve access to essential services.

---

# 🌍 Public Good Problem

Many urban communities experience unequal access to essential services and infrastructure, including:

* 🏥 Health facilities
* 🏫 Schools
* 🛒 Markets
* 🚌 Public transport
* 🛣️ Road networks
* 🏢 Urban infrastructure

Limited accessibility can increase travel difficulties and create unequal access to essential services and opportunities.

**KUAGI helps identify where accessibility gaps are greatest and where infrastructure interventions should be prioritized.**

---

# 🎯 Project Objectives

The project aims to:

* Identify areas with high accessibility gaps across Kigali
* Support urban planners and decision-makers with spatial evidence
* Transform open geographic data into actionable insights
* Improve understanding of the distribution of essential services
* Classify areas according to accessibility priority
* Enable users to explore GIS results interactively
* Integrate AI-powered natural language analysis into the GIS experience

---

# 🚀 Main Features

## 🗺️ Interactive GIS Experience

The KUAGI AI Experience provides:

✅ Interactive accessibility gap maps
✅ District and sector exploration
✅ KUAGI Score analysis
✅ Gap Priority classification
✅ Population density information
✅ Infrastructure indicators
✅ Roads and connectivity information
✅ Schools and health facility accessibility
✅ Market and transport accessibility
✅ Interactive charts and indicators
✅ Integrated KUAGI AI Assistant

---

## 🤖 KUAGI AI Accessibility Assistant

KUAGI AI is an intelligent GIS and urban accessibility assistant integrated into the ArcGIS Experience.

Users can click the **KUAGI AI logo** to open an interactive chat interface and ask questions about the KUAGI accessibility dataset.

Example questions include:

> Which sector has the highest accessibility gap?

> Which areas are classified as critical?

> Which district has the greatest infrastructure challenge?

> Where should health facilities be prioritized?

> Compare accessibility gaps between sectors.

KUAGI AI uses the available KUAGI accessibility dataset as its knowledge source to provide data-grounded responses.

The assistant can analyze:

* KUAGI Score
* Gap Priority
* Service gaps
* Road gaps
* Health gaps
* Education gaps
* Market gaps
* Infrastructure conditions
* Population density
* Buildings and service availability
* Districts and sectors
* Recommended interventions

---

# 📊 Gap Priority Classification

Accessibility gaps are categorized into four levels:

| Priority    | Score Range |
| ----------- | ----------- |
| 🔴 Critical | 80 – 100    |
| 🟠 High     | 60 – 79.99  |
| 🟡 Moderate | 40 – 59.99  |
| 🟢 Low      | 0 – 39.99   |

Higher KUAGI scores represent areas requiring greater attention and intervention.

---

# 🗺️ OpenStreetMap Data Used

OpenStreetMap provides the geographic foundation for the project.

Data used includes:

* 🛣️ Roads and pathways
* 🏫 Educational facilities
* 🏥 Health facilities
* 🛒 Markets
* 🚌 Transport-related features
* 🏢 Buildings and urban infrastructure

OpenStreetMap was selected because it provides open, community-driven geographic data suitable for urban accessibility analysis.

---

# 🔬 Methodology

## 1. Data Collection

OpenStreetMap and other available spatial datasets were collected and prepared for analysis across Kigali City.

## 2. Spatial Analysis

GIS analysis was performed using multiple accessibility indicators, including:

* Service availability
* Road accessibility
* Infrastructure distribution
* Health accessibility
* Education accessibility
* Market accessibility
* Transport accessibility
* Population density

## 3. Spatial Grid Analysis

Kigali was analyzed using a **500 m × 500 m spatial grid**.

Each grid cell was evaluated according to the availability of services, infrastructure conditions, accessibility gaps, and population-related indicators.

## 4. KUAGI Score Calculation

The accessibility and infrastructure indicators were combined to generate the **KUAGI Score**.

Higher scores indicate greater accessibility challenges and a higher need for intervention.

## 5. Gap Priority Classification

Grid cells were classified into:

* 🔴 Critical
* 🟠 High
* 🟡 Moderate
* 🟢 Low

This allows priority intervention areas to be identified spatially.

## 6. Interactive Visualization

The results were published through an interactive **ArcGIS Experience Builder application**.

Users can explore the accessibility map, indicators, charts, and spatial patterns directly through the web application.

## 7. AI-Powered Accessibility Analysis

The KUAGI accessibility dataset was connected to an AI knowledge retrieval workflow.

When a user asks a question, KUAGI AI:

1. Receives the user's natural language question.
2. Interprets the intended meaning, including common spelling or typing mistakes.
3. Searches the KUAGI accessibility knowledge dataset.
4. Retrieves relevant information.
5. Uses the retrieved context to support its analysis.
6. Generates a structured, data-grounded response.

---

# 🧠 How KUAGI AI Works

```text
USER
  │
  │ Ask a question
  ▼
KUAGI AI CHAT INTERFACE
  │
  ▼
QUESTION UNDERSTANDING
  │
  ▼
KUAGI ACCESSIBILITY KNOWLEDGE DATASET
  │
  ▼
HYBRID SEARCH & RETRIEVAL
  │
  ▼
RELEVANT KUAGI DATA
  │
  ▼
AI ANALYSIS
  │
  ▼
FINDING + EVIDENCE + EXPLANATION
+ RECOMMENDED ACTION
```

The AI assistant is designed to avoid inventing sectors, districts, statistics, KUAGI scores, accessibility gaps, or population values that are not supported by the available KUAGI dataset.

---

# 🛠️ Tools Used

## GIS & Mapping

* ArcGIS Pro
* ArcGIS Online
* ArcGIS Experience Builder
* ArcGIS Dashboards
* ArcGIS Map Viewer
* ArcGIS Arcade

## OpenStreetMap

* OpenStreetMap
* Overpass Turbo
* OpenStreetMap data services

## AI & Knowledge Retrieval

* Dify
* GPT-5
* Knowledge Retrieval
* Hybrid Search
* Vector Search
* Reranking
* Retrieval-Augmented Generation

## Spatial Analysis

* Spatial grid analysis
* Accessibility analysis
* Spatial overlay
* Infrastructure analysis
* Population analysis
* Priority classification

---

# 🤖 AI Usage

AI is used as an integrated decision-support component of KUAGI.

KUAGI AI supports:

* Natural language questions about accessibility
* Accessibility gap analysis
* Sector and district comparison
* Identification of priority areas
* Interpretation of GIS indicators
* Data-grounded explanations
* Recommended interventions

The AI assistant uses retrieved information from the KUAGI accessibility dataset when responding to project-related questions.

No AI-generated edits were directly added to OpenStreetMap.

---

# 📌 Live KUAGI AI Experience

Explore the live project:

[🚀 Open KUAGI AI Accessibility Gap Explorer](https://experience.arcgis.com/experience/f4c36912969b4664a4efe3109aa5b965?utm_source=chatgpt.com)

---

# 📁 Repository Contents

```text
KUAGI-AI-Accessibility-Gap-Explorer
│
├── README.md
├── AI_USAGE.md
├── links.md
├── methodology.md
├── KUAGI_Project_Documentation.md
└── dashboard-screenshot.png
```

---

# 👨‍💻 Developer

**NSABIMANA Fabrice**

Map<>Kathon 2026 Submission

Country: Rwanda 🇷🇼

---

# 📚 Data Attribution

© OpenStreetMap contributors

OpenStreetMap data is available under the Open Database License (ODbL).

[OpenStreetMap Copyright and License Information](https://www.openstreetmap.org/copyright?utm_source=chatgpt.com)

---

# 🏆 Project Vision

**KUAGI demonstrates how open geographic data, GIS analysis, interactive visualization, and artificial intelligence can work together to support smarter, more inclusive, and evidence-based urban accessibility planning.**

> **Transforming open spatial data into intelligent and actionable urban planning insights.**
