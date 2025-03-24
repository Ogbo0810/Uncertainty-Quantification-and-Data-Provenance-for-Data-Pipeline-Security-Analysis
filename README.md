# DPUQC
Uncertainty Quantification and Data Provenance for Data Pipeline Security Analysis

This repository contains results for the DESTION 2025 paper submission.
Two cases were discussed in the paper:
### Case 1: Single-Stage Computational Corruption Detection
### Case 2: Inline Data Corruption Detection
Files include UQ plot images for features not included in the paper


---
## 📊 Dataset 1: HVAC Dataset

This repository utilizes the [LBNL Fault Detection and Diagnostics (FDD) Datasets](https://data.openei.org/submissions/5763) for experiments presented in our paper.

**Citation:**  
Granderson, J., Lin, G., Chen, Y., Casillas, A., Im, P., Jung, S., ... & Vrabie, D. (2022). *LBNL fault detection and diagnostics datasets (No. 5763)*. DOE Open Energy Data Initiative (OEDI); Lawrence Berkeley National Laboratory (LBNL), Berkeley, CA (United States).



## 🏢 About the Dataset

The dataset includes operational data collected from simulations, lab experiments, and real-world building measurements across **seven HVAC system types**:

- Rooftop unit  
- Single-duct air handler unit  
- Dual-duct air handler unit  
- Variable air volume (VAV) box  
- Fan coil unit  
- Chiller plant  
- Boiler plant  

Each dataset contains:

- Multiple `.csv` files with time-series data covering both fault-free and various fault scenarios (at different severity levels)  
- A `.pdf` document summarizing key details and context  
- A `.ttl` file to support data visualization via the BRICK schema

This dataset was developed collaboratively by **LBNL, PNNL, NREL, ORNL, and Drexel University**.

---
## 📊 Dataset 2: UAV Dataset

The second dataset utilized in this paper is the Cyber-Physical Dataset for UAVs Under Normal Operations and Cyberattacks. 

**Citation**
S. C. Hassler, U. A. Mughal and M. Ismail, "Cyber-Physical Intrusion Detection System for Unmanned Aerial Vehicles," in IEEE Transactions on Intelligent Transportation Systems, vol. 25, no. 6, pp. 6106-6117, June 2024, doi: 10.1109/TITS.2023.3339728.



## About the Dataset:
It was developed using a testbed that includes UAV, controller, and data collection tools to execute cyber-attacks and gather cyber and physical data under normal and attack conditions. 
The dataset covers a range of cyber-attacks including:

- denial-of-service
- replay
- evil twin
- false data injection 
  
The experiments for fault analysis in our paper includes data from denial of service attacks.

