# TP Dashboard – Wastewater & Bathing Water Indicators

Interactive web dashboard visualizing environmental indicators across Dutch provinces.

## Indicators available

- Number of WWTP (Wastewater Treatment Plants)
- Pollution capacity (population equivalent)
- Bathing water quality

Users can:
- Select an indicator
- Navigate through years
- Click on a province to see time-series charts
- Explore stacked bar charts for detailed breakdown

---

## Access the dashboard online

The dashboard is hosted using **GitHub Pages**.

Open it directly in your browser:

https://YOUR_GITHUB_USERNAME.github.io/TP_Dashboard/

No installation required.

---

## Run locally on your computer

If you want to run it locally:

1. Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/TP_Dashboard.git
```

2. Open the folder.

3. Double-click on index.html.

If the GeoJSON files do not load (CORS restriction), use a local server:

```bash
# If Python is installed
python -m http.server 8000
```

Then open:

```bash
http://localhost:8000
```

## Project structure

```bash
TP_Dashboard/
│
├── index.html
├── data/
│   ├── number_WWTP.geojson
│   ├── capacity_pollution_eq.geojson
│   └── bathing_water_provinces.geojson
└── README.md
```

## Technologies used

Leaflet.js (interactive maps)

Chart.js (data visualization)

GeoJSON

GitHub Pages (hosting)
