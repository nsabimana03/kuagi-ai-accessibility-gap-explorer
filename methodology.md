# KUAGI Methodology

## Overview

KUAGI, or **Kigali Urban Accessibility Gap Index**, is a spatial analysis framework developed to identify and visualize areas with limited access to essential services and infrastructure across Kigali City, Rwanda.

The methodology combines **OpenStreetMap data, GIS spatial analysis, accessibility indicators, population information, and AI-assisted interpretation**.

The purpose is to transform spatial data into a **KUAGI Score** and **Gap Priority classification** that can support urban planning and infrastructure decision-making.

---

# 1. Data Collection

The geographic data used in KUAGI was primarily obtained from **OpenStreetMap**.

The dataset includes information related to:

- Road networks
- Buildings
- Schools
- Health facilities
- Markets
- Bus stops and transport-related features
- Other urban infrastructure

These datasets were collected, cleaned, and prepared for spatial analysis.

---

# 2. Spatial Analysis Grid

Kigali City was divided into a **500 m × 500 m spatial grid**.

Each grid cell was analyzed independently to measure the availability and accessibility of essential services and infrastructure.

Using a consistent grid allows accessibility conditions to be compared across different areas of Kigali.

---

# 3. Accessibility Indicators

KUAGI evaluates multiple spatial indicators.

## Infrastructure Availability

Infrastructure availability considers the presence and distribution of important urban features within or near each analysis area.

Indicators include:

- Buildings
- Roads
- Transport facilities
- Other mapped infrastructure

Areas with limited infrastructure availability may experience greater accessibility challenges.

---

## Service Coverage

Service coverage measures the availability of essential services, including:

- Schools
- Health facilities
- Markets
- Transport-related services

Areas with fewer available services receive higher accessibility gap values.

---

## Road Accessibility

Road accessibility evaluates the availability and connectivity of the road network.

Road-related indicators include:

- Road length
- Road coverage
- Road accessibility gaps

Areas with limited road connectivity may experience greater difficulty accessing essential services.

---

## Population Density

Population density is used to represent potential demand for services and infrastructure.

Areas with higher population density may require additional infrastructure and services when accessibility gaps are also present.

This helps identify areas where limited service availability may affect a larger number of people.

---

# 4. Gap Indicators

The analysis generates indicators representing accessibility gaps.

These include:

- Health Gap
- Education Gap
- Market Gap
- Service Gap
- Road Gap
- Transport accessibility
- Infrastructure conditions

Higher gap values generally indicate greater accessibility challenges.

---

# 5. KUAGI Score Calculation

The accessibility indicators were combined to generate the **KUAGI Score**.

The score represents the relative level of accessibility challenges within an analysis area.

The analysis considers the combined effects of:

- Service availability
- Health accessibility
- Education accessibility
- Market accessibility
- Road accessibility
- Transport accessibility
- Infrastructure conditions
- Population-related demand

Higher KUAGI Scores indicate greater accessibility gaps and a stronger potential need for intervention.

---

# 6. Priority Classification

KUAGI Scores were classified into four priority categories.

| Priority | KUAGI Score |
|---|---|
| Critical | 80–100 |
| High | 60–79.99 |
| Moderate | 40–59.99 |
| Low | 0–39.99 |

This classification helps planners quickly identify areas that may require greater attention.

---

# 7. Spatial Visualization

The resulting KUAGI Scores and Gap Priority classifications were published through an interactive **ArcGIS Experience Builder application**.

Users can explore:

- Accessibility gaps
- Priority areas
- Districts and sectors
- Population density
- Infrastructure indicators
- Service accessibility

The interactive environment allows users to investigate spatial patterns and compare accessibility conditions across Kigali.

---

# 8. AI-Assisted Accessibility Interpretation

The KUAGI accessibility dataset was connected to an AI-powered knowledge retrieval workflow.

The AI assistant can respond to questions related to the available KUAGI data, including:

- Priority areas
- Accessibility gaps
- KUAGI Scores
- District and sector comparisons
- Health accessibility
- Education accessibility
- Market accessibility
- Road and transport accessibility
- Infrastructure conditions

When a user asks a question, the system retrieves relevant information from the KUAGI dataset and uses that information to generate a data-grounded response.

The AI component is intended to make GIS results easier to explore and understand through natural language interaction.

---

# 9. Decision-Support Output

The final KUAGI system provides three main outputs:

1. **Spatial Evidence**  
   Interactive maps showing accessibility patterns and priority areas.

2. **Accessibility Classification**  
   KUAGI Scores and Gap Priority categories identifying areas with greater accessibility challenges.

3. **AI-Assisted Insights**  
   Natural language explanations and recommended interventions based on the available KUAGI dataset.

Together, these outputs support the transformation of open geographic data into actionable information for urban accessibility analysis and planning.

---

# Limitations

KUAGI results depend on the completeness and accuracy of the available geographic data.

OpenStreetMap data may contain missing or unevenly mapped features in some locations. Therefore, KUAGI should be interpreted as a **decision-support and exploratory analysis tool**, rather than as a replacement for detailed field surveys or official infrastructure planning data.

Future improvements may include:

- Additional demographic data
- Travel-time and network accessibility analysis
- Real-time infrastructure updates
- Community feedback
- Additional service categories
- Improved AI data querying and analysis

---

# Conclusion

KUAGI combines **OpenStreetMap, GIS spatial analysis, accessibility indicators, interactive visualization, and AI-assisted interpretation** to identify areas where accessibility challenges may require greater attention.

The methodology demonstrates how open geographic data can be transformed into an interactive decision-support system for more inclusive and evidence-based urban planning.

## Output

Areas are classified into:

- Critical
- High
- Moderate
- Low

Higher KUAGI scores indicate higher accessibility gaps.
