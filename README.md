## Project Summary

This project uses Sentinel-2 satellite imagery and remote sensing indices (NBR, dNBR) to analyze vegetation burn in conflict-affected areas of Eastern Ukraine during Spring 2022.

The region of interest, around Marinka in Donetsk Oblast, was the site of heavy artillery shelling and reported incendiary weapon use, including white phosphorus. While the project does not aim to verify specific weapon types, it assesses burn severity over time using the Normalized Burn Ratio, offering a data-driven perspective on environmental impact during armed conflict.

## Goals
- Demonstrate the use of open-source Earth Observation data to assess fire-related damage.
- Build an end-to-end pipeline using Python and Sentinel-2 imagery.
- Create reproducible visualizations and spatial layers showing potential high-burn areas.

## Output
- dNBR raster map of damage zones
- Before/after satellite image pairs
- GitHub repo with code + PDF summary

## Folder Structure 
burn_detection/
├── data/
│   ├── raw/             # Original Sentinel-2 imagery (GeoTIFFs)
│   └── processed/       # dNBR outputs, masks, clipped rasters
├── notebooks/
├── outputs/
│   ├── maps/           # PNGs or PDFs for before/after & dNBR maps
│   └── report/         # Summary PDF (1-pager) if needed
├── README.md           # Project intro + goal + sample image
├── requirements.txt    # List of Python packages (rasterio, numpy, etc.)

