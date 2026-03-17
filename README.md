# Tariff Wars & Supply Chain Restructuring Dashboard

An interactive, data-driven dashboard analysing the impact of US–China and US–India tariff wars on global supply chains (2020–2026).

## Features

- **7 analytical sections**: Tariff Timeline, US Import Shifts, Shipping Lanes Map, Industrial Clusters, India Analysis, Country Comparison, Sector Impact
- **14 interactive charts** (Chart.js): line charts, bar charts, bubble charts, doughnut, radar, stacked bars
- **Leaflet.js geospatial map** with shipping lanes and key port markers
- **Source tooltips**: hover over any underlined figure to see the primary source
- **Fully self-contained**: single `index.html`, no build step required

## Deploying to GitHub Pages

### Step 1 — Create a GitHub repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `tariff-dashboard` (or any name you like)
3. Set visibility to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload the file
**Option A: GitHub web interface (easiest)**
1. In your new repository, click **Add file → Upload files**
2. Drag and drop `index.html` into the upload area
3. Click **Commit changes**

**Option B: Git command line**
```bash
git init
git add index.html
git commit -m "Add tariff dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/tariff-dashboard.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**

### Step 4 — Access your live dashboard
After ~1-2 minutes, your dashboard will be live at:
```
https://YOUR_USERNAME.github.io/tariff-dashboard/
```

## Data Sources
All sources are documented inline via hover tooltips. Primary sources include:
- Alfaro & Chor (2025), CEPR VoxEU
- Rhodium Group "Chain Reaction" (2025)
- US Census Bureau / BEA Trade Release (Feb 2026)
- Tax Foundation Tariff Tracker (Mar 2026)
- ClearTax India, India Briefing, PIB India
- Richmond Fed Economic Brief EB 25-12 (Apr 2025)
