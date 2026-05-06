#  Smartphone Market Analysis Dashboard

> An interactive **Power BI** dashboard providing end-to-end analysis of the global smartphone market — covering device specs, pricing tiers, brand distribution, connectivity trends, and camera capabilities.

---

##  Dashboard Overview

This `.pbix` report is structured across **3 focused pages**, each exploring a distinct dimension of the smartphone dataset.

---

### Page 1 — Market Overview

A high-level snapshot of the smartphone landscape.

| Visual | Description |
|--------|-------------|
| **KPI Cards** | Total Devices, 5G Penetration %, Average Rating |
| **Donut Chart** | 5G vs 4G device split |
| **Column Chart** | Device count by RAM band |
| **Slicer** | Filter by brand name |

---

### Page 2 — Brand & Segment Analysis

Deep-dive into brand performance and product segmentation.

| Visual | Description |
|--------|-------------|
| **Clustered Column Chart** | Total devices by price band |
| **Donut Chart** | Device distribution by battery band |
| **Treemap** | Model count per brand |
| **Line Chart** | Average price by processor brand |
| **Clustered Bar Chart** | Total devices ranked by brand |

---

### Page 3 — Technical Specifications

Granular analysis of hardware and software features.

| Visual | Description |
|--------|-------------|
| **Column Chart** | Fast charging availability by brand |
| **Table** | Model-level specs — rear/front camera (MP), refresh rate |
| **Donut Chart** | OS (Android / iOS / Other) distribution |
| **Line Chart** | Price trend by processor brand |

---

##  Dataset

**Source file:** `https://app.gigasheet.com/spreadsheet/real-world-smartphones-dataset/196cc5ce_9bc1_41ab_b794_f93df5b6b482`

The dataset includes the following fields (non-exhaustive):

| Field | Description |
|-------|-------------|
| `brand_name` | Smartphone manufacturer |
| `model` | Device model name |
| `price` | Retail price |
| `os` | Operating system |
| `processor_brand` | Chipset manufacturer |
| `ram` | RAM capacity |
| `primary_camera_rear` | Rear camera resolution (MP) |
| `primary_camera_front` | Front camera resolution (MP) |
| `refresh_rate` | Display refresh rate (Hz) |
| `battery` | Battery capacity |
| `fast_charging_available` | Fast charging support (Yes/No) |
| `5G_or_4G` | Network connectivity generation |

**Calculated / Derived Measures:**

- `Total Devices` — Count of devices
- `5G Penetration %` — Percentage of 5G-capable devices
- `Avg Rating` — Average user rating
- `Price Band` — Bucketed price segments (Budget / Mid-range / Premium)
- `Ram Band` — Bucketed RAM tiers
- `Battery Band` — Bucketed battery capacity tiers

---

##  Requirements

| Tool | 
|------|
| [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) |


---

## 🔍 Key Insights the Dashboard Can Answer

- Which brands dominate the market by device count?
- What percentage of smartphones support 5G?
- How do prices vary across processor brands?
- What is the distribution of RAM tiers across the market?
- Which brands offer fast charging, and how does that vary?
- How do Android vs iOS devices compare in market share?
- What are the camera and display specs of top-rated models?

---


##  Contributing

Contributions are welcome! To suggest improvements:


---


##  Contact

For questions or feedback, open an [issue](https://github.com/your-username/smartphone-dashboard/issues) or reach out via GitHub.

---

*Built with using Microsoft Power BI*


