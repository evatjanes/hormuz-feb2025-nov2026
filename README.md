# Strait of Hormuz: Daily Vessel Transits (Feb 2025 – Nov 2026)

An interactive Python data visualization analyzing daily tanker and cargo transits through the Strait of Hormuz using [IMF PortWatch](https://straits.live/data) data to illustrate the **92.8% drop** in maritime traffic during the 2026 Strait of Hormuz crisis.

**[View the Live Interactive Chart](https://evatjanes.github.io/hormuz-feb2025-nov2026/)**

## Overview

Between March 2025 and February 2026, an average of **84.9 vessels per day** transited the Strait of Hormuz. Following the onset of US-Israeli strikes on Iran and subsequent Iranian restrictions and US naval blockades in late February 2026, average daily transits fell to **6.1 vessels per day**, including 14 recorded zero-transit days.

This project generates a standalone, interactive Plotly visualization (`index.html`) featuring:
- **Stacked Area Chart**: Daily counts for tankers and cargo vessels with interactive hover tooltips, zoom/pan controls, and clickable legend toggles.
- **Pre-War Baseline**: A dashed reference line showing the pre-war daily average (84.9 vessels/day).
- **Annotated Timeline**: Key military escalations and diplomatic milestones mapped directly onto the time series with hoverable event descriptions.

## Repository Contents

- `Hormuz.ipynb` – Jupyter Notebook containing the data audit and Plotly visualization code.
- `index.html` – Standalone interactive web visualization hosted via GitHub Pages.
- `straits-transits.csv` – Daily Strait of Hormuz transit dataset (`date`, `n_total`, `n_tanker`, `n_cargo`).

## Requirements & Usage

To reproduce or modify the visualization locally:

1. Install the required Python libraries:
   ```bash
   pip install pandas plotly

## Sources & Citation

- **Transit Data:** IMF PortWatch. (2026). *Strait of Hormuz daily transits, 28 February 2025–8 November 2026* [Data set]. Straits. https://straits.live/data © IMF PortWatch.
- **Event Timeline:** Compiled from Wikipedia (*2026 Strait of Hormuz crisis*) and `straits.live` daily briefs.
