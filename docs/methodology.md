# Research Methodology

## Research Overview

This research investigates intelligent route optimization for Flying Ad Hoc Networks (FANETs) under dynamic and random mobility conditions.

The proposed framework combines sequential mobility prediction using Long Short-Term Memory (LSTM) with a Random Forest-based decision mechanism to support adaptive route selection.

## Proposed Approach

The methodology consists of the following major stages:

1. Mobility data collection
2. Feature extraction and preprocessing
3. Sequential mobility analysis
4. LSTM-based mobility prediction
5. Random Forest-based decision making
6. Adaptive route selection
7. Network performance evaluation

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
* Connectivity
* Environmental conditions
* Weather
* Terrain

## Data Processing

The mobility information is prepared and transformed into suitable sequential observations for the prediction component.

The dataset is divided into training and testing subsets using an 80/20 split.

## LSTM Component

The LSTM component is used to learn sequential mobility patterns from historical UAV movement information.

The objective is to predict future mobility behavior that can support improved routing decisions in a dynamic FANET environment.

## Random Forest Component

The Random Forest component is used as a decision-making mechanism for route selection based on relevant mobility and network characteristics.

## Adaptive Route Selection

The predicted mobility information is incorporated into the routing decision process to support selection of more suitable communication paths.

## Experimental Environment

The simulation environment was implemented using MATLAB.

The experimental configuration included:

* Simulation area: 450 × 450 m
* Number of UAVs: Up to 100
* Base stations: 1
* Simulation duration: 15 minutes
* Network: IEEE 802.11 WLAN
* Mobility model: Random mobility
* Evaluation metrics: Latency, throughput, and route stability

## Machine Learning Configuration

The main configuration included:

* Data split: 80/20
* Optimizer: Adam
* Activation function: ReLU
* Batch size: 32
* Epochs: 10
* Validation split: 0.2
* Random state: 42
* Loss: Sparse

## Evaluation Metrics

The proposed framework is evaluated using:

### Latency

Measures the time required for data to travel through the network.

### Throughput

Measures the amount of data successfully transmitted through the network over a given period.

### Route Stability

Evaluates the reliability and consistency of selected communication routes under changing UAV mobility.

## Data Availability

The original research dataset is not publicly available because of confidentiality and research restrictions.

A synthetic dataset may be provided in this repository for demonstration and educational purposes. The synthetic data does not contain original confidential records.

## Code Availability

The complete experimental implementation is not publicly released.

Selected demonstration materials may be provided to illustrate the research methodology without exposing confidential research components.
