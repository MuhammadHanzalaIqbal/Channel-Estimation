# Channel Estimation Using MATLAB

This repository contains a MATLAB implementation for adaptive channel estimation and noise mitigation using Power Delay Profile (PDP)-based thresholding techniques. The project explores optimal window size selection to enhance signal recovery and minimize noise effects in communication systems.

## Features
- **Adaptive Window Optimization**: Automatically determines the best window size for different Signal-to-Noise Ratios (SNRs).
- **SNR-Based Analysis**: Evaluates channel estimation performance across varying SNR levels.
- **Comprehensive Workflows**:
  - **Training Phase**: Determines optimal parameters using 30 realizations.
  - **Validation Phase**: Validates performance using 10 unseen realizations.
  - **Testing Phase**: Evaluates the final model on a new dataset.
- **Visualization**: Plots training, validation, and testing error trends as well as signal comparisons.

## Workflow
1. **Training Phase**:
   - Optimize window sizes for each SNR.
   - Compute average training errors.
2. **Validation Phase**:
   - Test optimized window sizes on validation datasets.
   - Evaluate performance metrics for unseen data.
3. **Testing Phase**:
   - Apply trained parameters to a new realization (e.g., `Berlin.mat`).
   - Compute average error for each SNR.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/MuhammadHanzalaIqbal/Channel-Estimation.git
   cd Channel-Estimation
