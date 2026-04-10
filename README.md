# UNFPA Adolescent SRH Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Dashboard-009EDB?style=flat-square)](https://haijunche.github.io/unfpa-cse-dashboard/dashboard.html)
[![Data Source](https://img.shields.io/badge/Data-WHO%20%7C%20UNFPA%20%7C%20UNAIDS-0077A3?style=flat-square)](https://www.who.int/data/gho)

An interactive data visualization dashboard for monitoring adolescent sexual and reproductive health indicators across countries worldwide. Built with vanilla HTML/CSS/JavaScript — no build tools required.

[View Live Dashboard](https://haijunche.github.io/unfpa-cse-dashboard/dashboard.html)

---

## Features

### Data Visualization
- **World Map** — Choropleth map with color-coded adolescent birth rates by country; click any country for detailed indicators
- **Country Ranking** — Interactive bar chart comparing contraceptive prevalence across countries
- **Trend Analysis** — Multi-line chart showing key indicator trends from 2010-2022 with COVID-19 annotation
- **Relationship Analysis** — Scatter plot exploring the correlation between contraceptive use and adolescent birth rates
- **Regional Comparison** — Grouped bar chart comparing average indicators across five global regions

### Interactive Features
- **Metric Switching** — Toggle between 4 indicators on the map (Birth Rate, Contraceptive Use, Unmet Need, HIV Prevalence)
- **Country Search** — Real-time search with auto-selection for single results
- **Region Filter** — Filter all charts by Sub-Saharan Africa, Asia, Americas, Europe, or MENA
- **Country Detail Panel** — Slide-out panel with radar chart and 6 key indicators per country
- **Data Export** — Export any chart as PNG or download the full dataset as CSV
- **Sort Controls** — Cycle bar chart sorting (descending / ascending / alphabetical)

### Design
- Clean, professional UI matching UNFPA brand colors (teal/blue palette)
- Lucide icons throughout
- Animated number counters, card hover effects, and scroll-triggered animations
- Loading screen with progress indicator
- Fully responsive layout for mobile and desktop

---

## Data

The dashboard includes data for **75 countries** across 10 key indicators:

| Indicator | Description |
|-----------|-------------|
| Adolescent Birth Rate (15-19) | Births per 1,000 women aged 15-19 |
| Adolescent Birth Rate (10-14) | Births per 1,000 girls aged 10-14 |
| Contraceptive Prevalence | % of women 15-49 using modern methods |
| Unmet Need for FP | % of women with unmet family planning need |
| HIV Prevalence | % of women aged 15-24 living with HIV |
| Sex Ed Coverage | % of schools with comprehensive sexuality education |
| Child Marriage | % of women 20-24 married before age 18 |
| Maternal Mortality | Maternal deaths per 100,000 live births |

**Data Sources:**
- [WHO Global Health Observatory](https://www.who.int/data/gho)
- [UNFPA State of World Population](https://www.unfpa.org/swp)
- [UNAIDS Data](https://data.unaids.org/)
- [World Bank Open Data](https://data.worldbank.org/)

Values are estimates based on the most recent available data (2015-2022) and are intended for informational and educational purposes.

---

## Quick Start

No installation required — just open the HTML file in any modern browser:

```bash
# Clone the repo
git clone https://github.com/HaijunChe/unfpa-cse-dashboard.git

# Open in browser
cd unfpa-cse-dashboard
open dashboard.html        # macOS
start dashboard.html       # Windows
xdg-open dashboard.html    # Linux
```

Or simply visit the [live demo](https://haijunche.github.io/unfpa-cse-dashboard/dashboard.html).

---

## Tech Stack

- **Plotly.js** — Interactive charts and maps
- **Lucide Icons** — Clean, consistent iconography
- **Google Fonts (Inter)** — Modern typography
- **Vanilla HTML/CSS/JS** — No build tools, no dependencies to install

---

## Project Structure

```
unfpa-cse-dashboard/
├── dashboard.html    # Complete single-file dashboard (all code inline)
└── README.md         # This file
```

All data, styles, and JavaScript are embedded directly in `dashboard.html` for easy deployment to static hosting (GitHub Pages, Netlify, etc.).

---

## License

This project is provided for **educational and informational purposes**. Data values are estimates sourced from publicly available WHO, UNFPA, and UNAIDS publications.

---

Built with care for better data-driven conversations about adolescent sexual and reproductive health.
