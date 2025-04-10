# Network-Data-Analysis

This repository contains coursework for network data analysis.

## Files

- `Part1.ipynb` : Wikidata Editor Network Analysis (Part 1)
- `Part2.ipynb` : Road Network and Events in Central Leeds (Part 2)
- `data/` :
  - **For Part 1**:
    - `REQUEST_FOR_DELETION.csv`
    - `PROPERTY_PROPOSAL.csv`
    - `INTERWIKI_CONFLICT.csv`
  - **For Part 2**: 
    - `accidents_2015_2019_merged`
    - `voronoi_polygons_8.gpkg`
    - `voronoi_polygons_v22.gpkg`

## Part 1 Overview

- Constructs editor networks from three Wikidata Talk datasets
- Measures metrics (e.g., degree, clustering, diameter)
- Compares real networks to random graphs
- Simulates epidemic-style influence and prioritisation

## Part 2 Overview

- Selects a high-accident area in Leeds for detailed analysis (QGIS and Python)
- Extracts road network and computes metrics like spatial diameter, node/edge density, and circuitry
- Uses K-function and Moran’s I to assess clustering and spatial autocorrelation of accidents
- Examines accident proximity to intersections using network distance
- Divides the city into Voronoi cells and finds marathon-length circular paths
- Builds a provenance graph for marathon events and applies PageRank and KG embeddings

---

## How to Run

1. Clone this repo
2. Install required packages (`pandas`, `networkx`, `matplotlib`, `geopandas`, etc.)
3. Run the notebooks in order:
   - `Part1.ipynb`
   - `Part2.ipynb`

All cells include output so the notebook can be viewed directly without re-execution.
