# Istanbul Traffic Congestion Analysis

When and where traffic is worst in Istanbul — a full-year analysis of the IBB Hourly Traffic Density dataset (19M records, January–December 2024).

## Key Findings

- **Üsküdar (Bridge Approach) is the worst hotspot** — averaging ~38 km/h, roughly 20 km/h slower than the city average
- **Evening rush (5-7 PM)** is consistently the slowest time across all seasons
- **Weekends are 5% faster than weekdays** during daytime hours (3.5% all-hours — nighttime free-flow data dilutes the gap)
- **Istanbul has no off-season** — monthly averages only vary by ~2 km/h year-round

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook istanbul_traffic_analysis.ipynb
```

Run all cells. The notebook will auto-download the 12 monthly CSVs (~1.4 GB) to `data/` on first execution.

## Data

Source: [IBB Açık Veri Portalı — Saatlik Trafik Yoğunluk Veri Seti](https://data.ibb.gov.tr/dataset/hourly-traffic-density)

## Built With

pandas, matplotlib, seaborn, scipy, requests

