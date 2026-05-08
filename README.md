#  Smartphone Market Analysis

> An interactive Power BI dashboard providing comprehensive insights into the global smartphone market — covering device specs, pricing tiers, OS distribution, connectivity, and brand performance.

---

##  Dashboard Overview

This Power BI report (`smartphone_dashboard.pbix`) is a two-page interactive dashboard built on the `Smartphone_Dataset_new` dataset. It enables analysts and product teams to explore market trends across brands, hardware specifications, price segments, and connectivity standards.

---

##  Pages

### Page 1 — Market Overview
A high-level summary of the smartphone landscape with key KPIs and segmentation.

| Visual | Type | Description |
|--------|------|-------------|
| Total Devices | Card | Total number of devices in the dataset |
| 5G Penetration % | Card | Share of 5G-enabled devices across the market |
| Avg Rating | Card | Average user/reviewer rating across all devices |
| 5G vs 4G Distribution | Donut Chart | Breakdown of 5G and 4G device counts |
| Devices by RAM Band | Column Chart | Distribution of devices across RAM tiers |
| Brand Filter | Slicer | Filter all visuals by brand name |

---

### Page 2 — Deep-Dive Analysis
Detailed breakdowns by price, battery, OS, processor, and camera specifications.

| Visual | Type | Description |
|--------|------|-------------|
| Devices by Price Band | Clustered Column Chart | Count of devices segmented by price range |
| Battery Capacity Groups | Donut Chart | Distribution of devices across battery capacity tiers |
| Model Count by Brand | Treemap | Visual representation of model portfolio size per brand |
| Price by Processor Brand | Line Chart | Average/total price trends across processor manufacturers |
| Android vs iOS vs Other | Donut Chart | OS market share by brand count |
| Camera & Specs Table | Table | Detailed breakdown including rear camera specs, brand, and model |

---

##  Key Metrics & Fields

| Field / Measure | Description |
|-----------------|-------------|
| `Total Devices` | Count of all smartphone entries |
| `5G Penetration %` | Percentage of devices with 5G support |
| `Avg Rating` | Mean rating across the dataset |
| `5G_or_4G` | Connectivity generation classification |
| `brand_name` | Manufacturer/brand |
| `model` | Device model name |
| `Ram Band` | RAM tier grouping (e.g., 4GB, 8GB, 12GB+) |
| `Price Band` | Price tier grouping (budget, mid-range, flagship) |
| `Battery Band` | Battery capacity tier grouping |
| `processor_brand` | Chipset manufacturer (e.g., Qualcomm, MediaTek, Apple) |
| `os` | Operating system (Android, iOS, Other) |
| `primary_camera_rear` | Rear primary camera resolution (MP) |
| `price` | Device retail price |

---


---

##  Repository Structure

```
smartphone-dashboard/
│
├── smartphone_dashboard.pbix   # Power BI report file
├── README.md                   # Project documentation
└── data/
    └── Smartphone_Dataset_new  # Source dataset (add CSV/Excel if applicable)
```

---

##  Use Cases

- **Market Research** — Identify which price segments and brands dominate device volumes
- **Product Strategy** — Benchmark specs (RAM, battery, camera) across competitors
- **Connectivity Trends** — Measure 5G adoption rates across the market
- **OS Analysis** — Understand Android vs iOS vs other OS distribution by brand

---

##  Notes

- The dashboard was built and last updated in **May 2026**
- All visuals are cross-filtered — clicking any chart segment will filter the rest of the page
- The dataset (`Smartphone_Dataset_new`) must remain connected for data refresh

---

##  Contributing

Contributions are welcome! To suggest improvements

---

## Source file
https://app.gigasheet.com/spreadsheet/real-world-smartphones-dataset/196cc5ce_9bc1_41ab_b794_f93df5b6b482
