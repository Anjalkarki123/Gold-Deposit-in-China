# Gold Deposits in China — Data Science Project

**Team 6** — Anjal Karki, Collin Worth, John Bieren, Rowen Probst, Arjun Rai, Alex Johnson

## What This Project Does

We analyzed gold deposits in China to find spatial and topographic patterns.
We used Mindat for locality data and Open Elevation API for elevation,
then ran DBSCAN clustering to find natural groups.

## Files in This Repo

- `ChinaGold.ipynb` — main analysis notebook
- `output.json` — cleaned dataset (Mindat + elevation)
- `section1_gold_map.html` — interactive dot map
- `section2_gold_heatmap.html` — density heatmap
- `section3_spatial_distribution.png` — KDE + hexbin chart
- `section4_cooccurring_elements.png` — co-occurring elements bar chart
- `section5_3d_scatter.html` — 3D scatter (lon, lat, elevation)
- `dbscan_3d_clusters.html` — DBSCAN clustering result

## Data Sources

- Mindat (mineral localities)
- Open Elevation API (elevations)
- datasets/geo-countries (China border GeoJSON)

## Tools Used

- Python (pandas, numpy, scikit-learn)
- Folium (interactive maps)
- Plotly (3D plots)
- matplotlib + seaborn (static charts)
- DBSCAN clustering

## How to Run

1. Open `ChinaGold.ipynb` in Google Colab
2. Run all cells in order
3. Output files will be saved to `/content/`

## Keywords

gold, China, Mindat, DBSCAN, clustering, elevation, geochemistry, data science
