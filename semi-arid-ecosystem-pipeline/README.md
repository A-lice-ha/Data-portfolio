### Vegetation Pattern Analysis in Semi-Arid Ecosystems  
*Project Assistant, Indian Institute of Science, Bengaluru (Jun 2024 – Mar 2025)*  
**Custom R-based geospatial and statistical pipeline to assess vegetation dynamics using NDVI from LANDSAT-2.**

---

####  Tools Used  
- **R**: `raster`, `spdep`, `ggplot2`, `sf`, `tidyverse`  
- **Satellite Data**: LANDSAT-2 NDVI  
- **Other**: ISRO BHOONIDHI (data acquisition), Google Earth Pro (manual validation)

---

#### Workflow  
- Preprocessed NDVI raster stacks from LANDSAT-8 across semi-arid regions in Madhya Pradesh and Rajasthan (pilot phase of a PhD project)  
- Computed cell-wise statistics: **mean, standard deviation, skewness, variance, RMS**  
- Applied **Global and Local Moran’s I** to quantify spatial autocorrelation and clustering  
- Visualized results via **Moran scatter plots** and **spatial heatmaps**  
- Evaluated statistical significance of vegetation clusters and outliers using **Wilcoxon tests**  
- Shared reproducible R scripts and results internally to support future automation of ecological diagnostics  

---

#### Outputs  
- Moran’s I maps, raster-based statistical summaries, vegetation clustering visualizations  
- `.tif` outputs showing spatial patterns, anomalies, and continuity  
*(Add select images or processed raster files here)*

---

#### Files  
- `vegetation_stats_pipeline.R`: Complete spatial analysis and visualization pipeline  
- `outputs/`: Moran plots, summary stats, classified raster maps  
- `data/`: Preprocessed NDVI raster tiles from LANDSAT-2
