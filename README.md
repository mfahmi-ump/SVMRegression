This project extends previous work on epidemic modeling using the SInRD model, DRAM parameter estimation, and SRK4 simulation. Here, Support Vector Machine (SVM) regression is employed to predict key epidemiological parameters based on data obtained from DRAM. The predicted parameters are then used to simulate the epidemic dynamics via the SInRD model, maintaining high accuracy while reducing computational cost. This approach enables fast, data-driven forecasting of epidemic progression.

Key Components:
SVM Regression: Trained on DRAM-estimated parameters to learn the mapping from input features to epidemiological parameters.
DRAM: Robust posterior parameter estimates used on the pandemic data.
SInRD Model: Multiple Compartment of Infectious Severity Model.
SRK4 Numerical Simulation: Simulation of the pandemic compartmental data.
