# 🗺️ Tobeez — Sales Activation Map

A single-file, zero-dependency web tool for sales teams to visualize client call campaigns on an interactive map — with a live dashboard and rep performance analytics.

> Built for a Moroccan FMCG distribution team to track daily field activation across hundreds of clients.

![Status](https://img.shields.io/badge/status-live-brightgreen) ![Stack](https://img.shields.io/badge/stack-HTML%20%2F%20CSS%20%2F%20JS-teal) ![Deploy](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)

---

## 🔗 Live Demo

👉 **[Launch the app](https://YOUR-USERNAME.github.io/tobeez-activation-map/)**

> Upload the sample CSV (included in this repo) to see the full experience.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📍 **Interactive Map** | Leaflet.js map with color-coded client markers by call status |
| 📊 **Live Dashboard** | 4 charts: coverage donut, results breakdown, rep bar chart, activation funnel |
| 👤 **Rep Filtering** | Filter map and stats by sales representative |
| 🔍 **Search** | Real-time search by client name, rep, or city |
| 📋 **Data Table** | Sortable table view of all clients |
| 📁 **CSV / Excel import** | Upload `.xlsx` / `.csv` or paste directly from Excel |
| 📱 **No backend** | 100% client-side — runs from a single HTML file |

---

## 📸 Screenshots

| Map View | Dashboard |
|---|---|
| *(add screenshot here)* | *(add screenshot here)* |

---

## 🚀 Getting Started

### Option 1 — Use the live demo
Click the link above, upload your CSV, and you're live.

### Option 2 — Run locally
```bash
git clone https://github.com/YOUR-USERNAME/tobeez-activation-map.git
cd tobeez-activation-map
# Open index.html in your browser — no server needed
open index.html
```

---

## 📄 Data Format

Your CSV or Excel file should include these columns:

| Column | Description |
|---|---|
| `SALE_REP` | Sales representative name |
| `CUSTOMER_NAME` | Client name |
| `CONTACT NUMBER` | Phone number |
| `CITY` | City name |
| `X` | Longitude coordinate |
| `Y` | Latitude coordinate |
| `VALUE_TIER` | Client tier (A / B / C) |
| `TOTAL_REVENUE` | Revenue in MAD |
| `ORDER_COUNT` | Number of past orders |
| `DAYS_INACTIVE` | Days since last order |
| `LAST_ORDER_DATE` | Date of last order |
| `CONTACT_1_DATE` | First contact attempt date |
| `CONTACT_1_RESULT` | Result: Positive / Call Again / Negative |
| `CONTACT_2_DATE` | Second contact attempt date |
| `CONTACT_2_RESULT` | Result of second contact |
| `ORDER` | Order created? (yes / no) |
| `Order Date` | Date order was placed |
| `ORDER_VALUE` | Order value in MAD |
| `Order Status` | Status of the order |
| `NOTES` | Free-text notes |

> A sample file `sample_data.csv` is included in the repo.

---

## 🏗️ Tech Stack

- **[Leaflet.js](https://leafletjs.com/)** — interactive map rendering
- **[Chart.js](https://www.chartjs.org/)** — dashboard charts
- **[SheetJS (xlsx)](https://sheetjs.com/)** — Excel file parsing
- **[PapaParse](https://www.papaparse.com/)** — CSV parsing
- **[DM Sans + DM Mono](https://fonts.google.com/)** — typography
- Pure HTML / CSS / JS — no build tools, no frameworks

---

## 📁 Repo Structure

```
tobeez-activation-map/
├── index.html          # The entire app (single file)
├── sample_data.csv     # Example dataset to try the app
└── README.md           # This file
```

---

## 💡 Use Cases

- FMCG field sales activation tracking
- Territory management & rep performance review
- Daily call campaign monitoring
- Client reactivation campaigns

---

## 👤 Author

Built by **[Your Name]** — [LinkedIn](https://linkedin.com/in/YOUR-PROFILE) · [Portfolio](https://your-site.com)

---

## 📜 License

MIT — free to use and adapt.
