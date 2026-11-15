# Strait of Hormuz: Daily Vessel Transits (Feb 2025 – Nov 2026) – Data visualization analyzing daily tanker and cargo transits through the Strait of Hormuz (Feb 2025–Nov 2026) using IMF PortWatch data to illustrate the 92.8% drop in maritime traffic during the 2026 crisis

A Python data visualization analyzing daily tanker and cargo transits through the Strait of Hormuz using [IMF PortWatch](https://straits.live/data) data to illustrate the **92.8% drop** in maritime traffic during the 2026 Strait of Hormuz crisis.

![Strait of Hormuz Daily Vessel Transits](hormuz_transits.png)

## Overview

Between March 2025 and February 2026, an average of **84.9 vessels per day** transited the Strait of Hormuz. Following the onset of US-Israeli strikes on Iran and subsequent Iranian restrictions and US naval blockades in late February 2026, average daily transits fell to **6.1 vessels per day**, including 14 recorded zero-transit days.

This script generates a publication-ready figure featuring:
- **Stacked Area Chart**: Daily counts for tankers and cargo vessels using an Okabe-Ito color-blind safe palette (`dark` or `light` theme options).
- **Trend Overlay**: A 7-day rolling mean and pre-war baseline average.
- **Annotated Timeline**: Key military escalations and diplomatic milestones mapped directly onto the time series.
- **High-Resolution Exports**: Automatically outputs both a 300 DPI `.png` and a vector `.pdf`.

## Requirements

- Python 3.8+
- `pandas`
- `matplotlib`

Install dependencies via pip:
```bash
pip install pandas matplotlib
