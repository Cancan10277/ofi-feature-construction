# Order Flow Imbalance (OFI) Feature Construction

## Overview  
This repository implements Tasks for “Cross-Impact of Order Flow Imbalance in Equity Markets” (Cont et al., 2023). You will find:  
- A clean, modular Python script to compute four OFI features per timestamp:  
  1. **Best-Level OFI**  
  2. **Multi-Level OFI**  
  3. **Integrated OFI**  
  4. **Cross-Asset OFI**  
- A LaTeX-generated PDF with concise answers to three conceptual questions:  
  - Why measure OFI at multiple depths?  
  - Why use LASSO vs. OLS for cross-impact?  
  - Why is OFI superior to volume for short-term return forecasting?  

## Instructions
To run the notebook:
1. Install required packages: `pandas`, `numpy`, etc.
2. Open `ofi_feature_construction.ipynb`.
3. Run all cells to generate feature outputs.
