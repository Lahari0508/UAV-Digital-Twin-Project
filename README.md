# UAV-Digital-Twin-Project
“UAV digital twin synchronization and speed prediction project
# Contextual Bandit-Based Adaptive Synchronization and Retraining of UAV Network Digital Twins

## Project Overview
This project explores UAV speed prediction and synchronization using machine learning and a simulated multi-UAV scenario.

## Objectives
- Analyse UAV flight telemetry.
- Demonstrate speed prediction using machine learning.
- Study synchronization of UAV arrival times in a simulation.
- Explore adaptive synchronization and retraining as a project direction.

## Repository Contents
- `01_Documents/` — Abstract, final report, and dataset/EDA report.
- `02_Literature_Survey/` — Literature survey and research references.
- `03_Presentations/` — Project presentations.
- `04_Code/` — Implementation notebook and supporting code.
- `05_Dataset_and_Results/` — Dataset reference and generated results.

## Dataset
The project references the Drone Flight Operations Data repository:
https://github.com/yogesh031020/drone-flight-operations-data

## Implementation Notes
The repository documents the implementation and its experimental results. The scope of the contextual-bandit, synchronization, and retraining components should be understood from the submitted code and report.
## Dataset

### Dataset Name
Drone Flight Operations Data — Autonomous Waypoint Mission.

### Source
- **GitHub repository:** https://github.com/yogesh031020/drone-flight-operations-data
- **Direct CSV:** https://raw.githubusercontent.com/yogesh031020/drone-flight-operations-data/main/2024-05-20_Autonomous_Waypoint_Mission.csv

### Dataset Description
The dataset contains UAV flight telemetry recorded during an autonomous waypoint mission. The repository describes telemetry fields such as mission time, GPS coordinates, altitude, velocity, speed, and battery level.

### Loading the Dataset
The CSV can be loaded in Python using pandas:

```python
import pandas as pd

url = "https://raw.githubusercontent.com/yogesh031020/drone-flight-operations-data/main/2024-05-20_Autonomous_Waypoint_Mission.csv"
df = pd.read_csv(url)

print(df.shape)
print(df.head())
```

### Role in This Project
The telemetry is used for dataset exploration and the speed-prediction demonstration, according to the features and target defined in the implementation notebook.

**Limitation:** This CSV is not a labelled multi-UAV synchronization dataset. The UAV arrival-time synchronization experiment should be identified separately as a simulation unless validated multi-UAV data is available.
