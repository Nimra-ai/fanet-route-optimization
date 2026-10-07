# Adaptive Hybrid LSTM–Random Forest Framework for Route Optimization in FANETs

## Overview

This repository presents the research work **"Neural Network-Based Route Optimization for Random Mobility Models in FANETs"**, focused on intelligent route optimization for Flying Ad Hoc Networks (FANETs).

The research investigates the use of sequential mobility information and machine learning techniques to improve routing performance in highly dynamic UAV communication environments.

The proposed framework combines **LSTM-based mobility prediction** with a **Random Forest decision-making approach** to support adaptive route selection.

> **Note:** The original research dataset and complete experimental implementation are not publicly available because of data confidentiality and research restrictions. This repository therefore provides the research methodology, documentation, selected results, and a synthetic demonstration dataset for reproducibility and educational purposes.

---

## Research Objectives

The main objectives of this research are:

* Predict UAV mobility patterns using historical mobility information.
* Improve route selection in dynamic FANET environments.
* Reduce communication latency.
* Improve network throughput.
* Enhance route stability.
* Evaluate routing performance under different UAV densities.

---

## Proposed Framework

The proposed approach follows a hybrid methodology:

```text
Mobility Data
      |
      v
Feature Extraction
      |
      v
LSTM Mobility Prediction
      |
      v
Predicted Mobility Pattern
      |
      v
Random Forest Decision Model
      |
      v
Adaptive Route Selection
      |
      v
FANET Communication
```

The LSTM component is used to capture sequential mobility patterns, while the Random Forest model supports the routing decision process.

---

## Input Features

The research considers mobility and network-related features including:

* Timestamp
* UAV ID
* Latitude
* Longitude
* Altitude
* Speed
* Direction
* Waypoints
* Connectivity information
* Environmental conditions
* Weather and terrain information

---

## Experimental Environment

The simulation environment was configured using MATLAB.

Key simulation parameters included:

| Parameter           | Configuration                        |
| ------------------- | ------------------------------------ |
| Simulation Area     | 450 × 450 m                          |
| UAVs                | Up to 100                            |
| Base Station        | 1                                    |
| Simulation Duration | 15 minutes                           |
| Network             | IEEE 802.11 WLAN                     |
| Mobility            | Random Mobility Models               |
| Evaluation Metrics  | Latency, Throughput, Route Stability |

---

## Machine Learning Configuration

The machine learning framework used the following configuration:

| Parameter        | Value  |
| ---------------- | ------ |
| Data Split       | 80/20  |
| Optimizer        | Adam   |
| Activation       | ReLU   |
| Batch Size       | 32     |
| Epochs           | 10     |
| Validation Split | 0.2    |
| Random State     | 42     |
| Loss             | Sparse |

---

## Dataset

The original research dataset is **not publicly available** because it contains confidential research data.

For demonstration purposes, this repository may include a **synthetic dataset** generated to represent the structure of the research data.

The synthetic dataset does **not contain any original confidential records** and should not be considered the actual research dataset.

Example features:

```text
Timestamp
UAV_ID
Latitude
Longitude
Altitude
Speed
Direction
Connectivity
```

---

## Results

The proposed approach was evaluated using network performance metrics including:

### Latency

The proposed framework demonstrated improved latency performance under different UAV densities compared with the baseline routing approach.

### Throughput

The proposed approach demonstrated improved throughput across the evaluated UAV-density scenarios.

### Route Stability

The framework was designed to improve routing stability by incorporating predicted mobility patterns into route selection.

> Results presented in this repository are provided for research documentation and visualization. The complete experimental dataset is not publicly released.

---

## Research Publication

**Nimra Imam Shah, Dr. Fahad Masood, Saqib Shahid Raheem**

**"Neural Network-Based Route Optimization for Random Mobility Models in FANETs"**

5th Abasyn International Conference on Technology and Business Management (AICTBM 2024).

---

## Technologies

* MATLAB
* Python
* Machine Learning
* LSTM
* Random Forest
* Flying Ad Hoc Networks
* IEEE 802.11 WLAN

---

## Data Availability

The original dataset is not publicly available due to confidentiality and research restrictions.

A synthetic/sample dataset may be provided for demonstration and educational purposes.

---

## Code Availability

The complete experimental source code is not publicly released.

Selected implementation examples and demonstration code may be provided to illustrate the methodology without exposing confidential research components.

---

## Citation

If you reference this research, please cite the published conference paper.

---

## Author

**Nimra Imam Shah**

Computer Science Researcher & Lecturer

Research Interests: Artificial Intelligence, Machine Learning, FANETs, Intelligent Routing, Mobility Prediction, and Network Optimization.
