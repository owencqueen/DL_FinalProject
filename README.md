# Temporal Graph Neural Networks for Epidemiological Forecasting
Group 8: Rekha Bhupatiraju, Owen Queen, and Sai Thatigotla. 

COSC 525 Final Project

## Repository Outline
1. StaticGraphs
  - Repository containing code for the static GNNs.
  - `GCN.ipynb`: Notebook with Graph Convolutional Network code ran on synthetic data.
  - `GAT.ipynb`: Notebook with Graph Attention Network code ran on synthetic data.
  - `SAGE.ipynb`: Notebook with Graph SAGE network on the synthetic data.
2. TemporalGNNs
  - Repository containing temporal GNN code.
  - `Temporal_Synthetic.ipynb`: Notebook with temporal models ran on synthetic data.
  - `Temporal_Synthetic_more_filters.ipynb`: Notebook with optimized temporal models ran on synthetic data. This notebook contains more varying hyperparameters to achieve the best results on the synthetic data.
  - `chickenpox.ipynb`: Contains temporal models predicting on the Chicken Pox dataset.
3. Data
  - `net_1000.pickle`: Benchmark dataset used for the synthetic dataset.
