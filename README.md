
# ECOTEC Estuary Water Quality and Microbial Bioremediation Dataset (2024–2025)

This repository contains data and scripts used in the study of microbial bioremediation performance in a tropical estuarine channel near ECOTEC University, Guayaquil, Ecuador.

## Contents

- ECOTEC_Estuary_WQ_MBio_2024-2025.csv: Raw water quality dataset with 176 observations across 13 variables.
- metadata.yaml: Variable definitions, units, QA/QC codes, and geospatial metadata.
- ECOTEC_E_WQ_MB_Analysis_v1_0.py: Python script for data preprocessing, efficiency computation, and visualization.

## Description

The dataset includes high-resolution measurements of dissolved oxygen (DO), ammonium (NH₄⁺), nitrite (NO₂⁻), nitrate (NO₃⁻), total Kjeldahl nitrogen (TKN), biochemical and chemical oxygen demand (BOD₅ and COD), salinity, alkalinity, and H₂S across five fixed stations between January 2024 and June 2025.

All samples were processed using APHA Standard Methods and subjected to full QA/QC (e.g., duplicates, blanks, calibration).

## How to Use

To reproduce analyses and visualizations:

```bash
python ECOTEC_E_WQ_MB_Analysis_v1_0.py
```

Python 3.10+ and the libraries `pandas`, `matplotlib`, and `statsmodels` are required.

## Citation

Hechavarria-Hernandez, J.R., Sanoja-Lopez, K., & Luque, R. (2025). ECOTEC Estuary Water Quality and Microbial Bioremediation Dataset (2024–2025). DOI: https://zenodo.org/records/17807650

## License

This dataset is made available under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.



