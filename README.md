# FlowST-Net

**FlowST-Net**, our novel framework for uniform spatial and temporal feature learning in point clouds, designed to tackle non-uniform spatial and temporal distributions in scene flow estimation.

---

## Overview

FlowST-Net addresses the challenges of:

1. **Non-uniform spatial distributions** within a single frame.
2. **Non-uniform temporal distributions** between consecutive frames.

The architecture integrates:

- **SVI Module**: Extracts locally consistent and discriminative features within a frame.
- **CFA Module**: Captures dependencies between frames in feature space using cross-attention.
- **CGA Module**: Enhances geometric alignment through cross-frame nearest neighbor search.
- **Flow Estimator**: Computes scene flow with optimal transportation theory.

FlowST-Net demonstrates **state-of-the-art performance** on **FlyingThings3D** and strong generalization to **KITTI Scene Flow**.

---

## Features

- End-to-end deep learning framework for scene flow estimation.
- Modules for handling non-uniform point cloud distributions.
- Robust performance in both dynamic and static scenarios.

---

## Code Availability

- The code for **FlowST-Net** will be made publicly available upon the acceptance of the associated paper. This includes the implementation, dataset splits, pre-trained models, and detailed instructions to ensure reproducibility and facilitate further research. Stay tuned for updates!
