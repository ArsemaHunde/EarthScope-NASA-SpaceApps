# EarthScope — Orbit Data Explorers
NASA Space Apps 2026 • Be An Earth System Trend Detective!

## What is included
- EarthScope_Dashboard.xlsx: an Excel dashboard and source tables, adapting the analytical workflow of an earlier sales dashboard to NASA data.
- EarthScope_Demo.pptx: 7-slide demonstration.
- historical_trend.png and recent_monthly.png: exported charts.
- Two CSV files: the exact observations used in the analysis.

## Findings
Historical 1880–1929 mean anomaly: -0.272 °C. Linear fit slope: -0.014 °C/decade. October 2026 monthly anomaly: +1.55 °C.

## Data provenance
NASA GISTEMP v4 https://data.giss.nasa.gov/gistemp/ . Historical 1880–1929 annual J-D values transcribed from https://glitchdata.com/datasets/nasa-giss/nasa-gistemp-global/viewer . Recent monthly observations from NASA GISTEMP mirror https://www.greendecades.org/tracker/temperature-anomaly-global (accessed 2026-11-15). Original official data: https://data.giss.nasa.gov/gistemp/tabledata_v4/GLB.Ts+dSST.csv .

## Limitations
This is a small verified-data prototype, **not** a full 1880–2025 global time series or regional trend detector. The historical and recent panels are not directly connected; the historical regression is descriptive and does not account for autocorrelation. 2026 is incomplete. It is not an interactive web app.

## Acknowledgment
GISTEMP Team (2026), NASA GISS Surface Temperature Analysis v4; Lenssen et al. (2024), JGR Atmospheres, DOI 10.1029/2023JD040179.
