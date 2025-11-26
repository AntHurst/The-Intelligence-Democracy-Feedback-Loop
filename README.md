# The-Intelligence-Democracy-Feedback-Loop
# Politicization Pressure Index (PPI) & IPSS Framework – Research Code Repository
David Hurst  
Master’s Thesis, Intelligence Studies  
American Military University  

## Overview
This repository contains the analytical code, reproducible workflows, and supporting materials used in the development of the **Politicization Pressure Index (PPI)** and the **Intelligence Politicization → Security Spiral (IPSS) Framework**. The project examines how political pressures on the U.S. Intelligence Community influence democratic resilience, institutional performance, and international volatility.

The scripts in this repository support:
- Construction of the Politicization Pressure Index (PPI)
- Time-series preparation of FISA/ASTR/FISC indicators
- Integration of ACLED and GDELT (V1/V2) event data
- Statistical tests (ADF, VAR, ARDL, Granger causality, structural break detection)
- Graphing and visualization of relationships between politicization and stability metrics
- Replication procedures for transparency and future doctoral research

## Contents

## Data Sources (Not Included in Repository)
This repository does **not** contain classified, proprietary, or restricted data.  
Users must obtain the following datasets independently:

- DOJ FISA Annual Reports (2008–2024)  
- ODNI ASTR Reports (2014–2024)  
- FISC Annual Reports (2015–2024)  
- ACLED (2015–2025) political violence and protest events  
- GDELT v1 and v2 global event datasets  

## Replication Requirements
- Python 3.10+
- Recommended libraries: `pandas`, `numpy`, `statsmodels`, `matplotlib`, `seaborn`, `scikit-learn`, `pmdarima`
- Google Cloud Storage if downloading large GDELT archives

A message outlining the recommended environment configuration can be found in `docs/replication_instructions.md`.

## Disclaimer
This repository contains only non-sensitive, unclassified code for academic research.  
No proprietary datasets, intelligence materials, or government-owned documents are included.  
Users are responsible for complying with relevant data-handling and legal requirements.

## Citation
If you use any part of this repository in academic work, please cite:

Hurst, David. *The Politicization of U.S. Intelligence and Its Consequences for Democratic Stability.* Master’s Thesis, American Military University (forthcoming).

## Contact
For questions or collaboration, contact: david.hurst6@mycampus.apus.edu

