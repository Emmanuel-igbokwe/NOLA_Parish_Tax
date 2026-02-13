# ⚡ New Orleans Tax Analytics Intelligence Platform (2020–2025)
**Analyst / Builder:** Emmanuel Igbokwe  
A high-impact, executive-ready HTML dashboard that tells the story of New Orleans Parish tax performance and forecasts future revenue using modern analytics visuals.

---

## 📌 Overview
This project is a **single-page interactive analytics dashboard** built with:
- **HTML + CSS** for a premium “executive intelligence” layout
- **Chart.js** for interactive visualizations
- Embedded dataset (CSV-like string) covering **Q1 2020 → Q1 2025**
- Forecast extension (Q2 2025 → Q1 2026) using a model-style growth projection
- Advanced analytics storytelling: composition, district performance, growth trends, correlations, and insights

> Goal: Deliver a clean, CFO-ready dashboard that communicates revenue growth, drivers, and forecast—fast.

---

## ✅ What’s Included
### 1) KPI Stats Bar (Executive Snapshot)
- Total Revenue 2024
- ML Forecast Q2 2025
- CAGR (2020–2024)
- Model Accuracy

### 2) Executive Summary (Narrative)
- Clear narrative explaining recovery, composition, district performance, and forecast

### 3) Interactive Panels
- **Time Series Forecast** (Historical + Forecast + 95% bounds)
- **District Performance Heatmap** (YoY Growth matrix)
- **Quarterly Growth Analysis** (QoQ bar chart)
- **Revenue Composition** (Sales vs Property donut + table)
- **Top Revenue Contributors** (Horizontal ranking bar chart)
- **Correlation Matrix** (Pearson-style matrix visualization)

### 4) Advanced Analytics Insights (Storytelling)
- Seasonality patterns
- Risk/volatility narrative
- Regression-style driver story
- Elasticity narrative
- Ensemble performance narrative

---

## 🖥️ Live Demo (GitHub Pages)
Once deployed with GitHub Pages, your dashboard is accessible as a public link.

**Example format:**
`https://<your-username>.github.io/<your-repo-name>/`

---

## 🚀 How to Run Locally
This is a static HTML dashboard—no backend required.

### Option A: Open directly
1. Download or clone the repo
2. Double-click `index.html`

### Option B (Recommended): Run a local web server
Some browsers block certain local JS features when opened directly. Use a lightweight server:

**Python (recommended):**
```bash
python -m http.server 8000
