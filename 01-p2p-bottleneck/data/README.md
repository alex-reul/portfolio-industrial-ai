# Data

This folder is not versioned (see `.gitignore`). To reproduce the analysis, download the raw event log and place it here:

- **File:** `BPI_Challenge_2019.xes` (~730 MB)
- **Source:** 4TU.ResearchData — [BPI Challenge 2019](https://doi.org/10.4121/uuid:d06aff4b-79f0-45e6-8ec8-e19730c248f1) (CC BY 4.0)
- **MD5:** `4eb909242351193a61e1c15b9c3cc814`

The first run of `01_data_understanding.ipynb` creates a parquet cache in this folder (`bpic2019.parquet`) and the scoped subset (`bpic2019_3way_before_gr.parquet`) used by the following notebooks.
