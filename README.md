# SSF-LIO: Exploring Self-Supervised Feature of Intensity Images to Improve LiDAR-Inertial Odometry

[![GitHub Repository](https://img.shields.io/badge/GitHub-SSF--LIO-blue?logo=github)](https://github.com/cimu67/SSF-LIO)

## 📖 Overview
This repository provides the official implementation of our novel LiDAR-Inertial Odometry (LIO) framework designed for robust ego-motion estimation in feature-sparse or degenerate environments. The code integrates geometry-based LiDAR odometry with self-supervised visual features to address ill-constrained registration in challenging scenarios. 

## ✨ Key Features
### Degeneracy-Aware Registration
- 🧮 Degeneracy Detection: Hessian matrix analysis for identifying under-constrained directions during point cloud registration.

### Cross-Modal Fusion
- 🖼️ **SuperPoint** self-supervised visual feature extraction
- 🔗 **LightGlue** adaptive feature matching network
- 📊 Multi-modal residual optimization via error-state iterated Kalman filter

## 📊 Benchmark Performance
| Dataset       | ATE Reduction |
|---------------|---------------|
| New College   | 21.1%         | 
| Enwide        | 19.4%         |

This work is submitted to IROS 2025. We will release our code upon paper acceptance—stay tuned!
