# AI Semiconductor Market Dynamics: Revenue Growth & Supply Chain Risk (2022–2026)

**Tools Used:** Tableau, Python
**Domain:** Business Analytics, Data-Driven Decision Making, Operations

> An end-to-end analytical dashboard engineered to track the exponential growth of the global AI hardware market, map vendor dominance, and flag legacy supply chain risks.

*(Please view the Dashboard AI.jpg file included in this repository to see the final visualisation).*

## Project Overview
As enterprise AI adoption accelerates, tracking hardware revenue and operational constraints is critical. This project processes raw global B2B semiconductor data to visualise a market projected to hit massive valuations by 2026. The final dashboard acts as a strategic MIS reporting tool for operations and strategy teams, minimizing executive cognitive load while highlighting critical supply chain vulnerabilities (End-of-Life hardware).

## Technical Stack & Workflow
* **Python (Data Engineering):** 
  * Imputed missing variables and engineered raw global sales datasets.
  * Developed a dynamic, time-aware logical framework to categorise hardware into active, medium-risk, and high-risk obsolescence tiers based on system date.
* **Tableau (Data Visualisation & UI/UX):** 
  * Built a high-fidelity, interactive SaaS-style card layout.
  * Executed complex visual formatting, including dual-axis continuous trend lines, custom color maps, and dynamic "Top N" logic filtering.
* **Domain Focus:** Data-Driven Decision Making, Product Lifecycle Management, and Market Intelligence.

## Key Features & Visual Insights
1. **Hyper-Growth Trend Modelling:** A dual-axis area chart capturing the >400% revenue explosion in the AI hardware sector from 2022 to 2026.
2. **Vendor Consolidation Analysis:** Donut and horizontal bar configurations mapping vendor B2B dominance, prominently displaying NVIDIA's >70% market capture versus competitors like Google and AMD.
3. **Supply Chain Obsolescence Alert Matrix:** A custom-built status table using KPI traffic-light indicators to isolate legacy shipments (e.g., Google TPU v3, NVIDIA V100), flagging potential bottlenecks in IT infrastructure upgrades.

## View the Interactive Dashboard
To fully interact with the dashboard, data filters, and tooltips, download the packaged workbook directly from this repository:
**`AI Semiconductor Dynamics.twbx`**

*(Note: The file can be opened seamlessly using either a standard Tableau Desktop license or the free, publicly available [Tableau Reader](https://www.tableau.com/products/reader)).*

## Repository Structure
* **Data folder:** Contains the raw CSV and the Python-cleaned output files.
* **Scripts folder:** Python scripts/Jupyter Notebooks detailing the data cleaning and dynamic EOL logic generation.
* **Dashboard file:** The final Tableau Packaged Workbook (`AI Semiconductor Dynamics.twbx`) file.
* **Dashboard AI.jpg:** High-resolution screenshot of the final UI layout.

---
*This portfolio project demonstrates end-to-end business analytics capabilities—from raw data processing to actionable, executive-level visualisation.*
