In this experiment, fault-free data is passed through the pipeline for a given time, followed up with faulty data to mimic an attacker-induced corrupt data ingestion. Shifts in UQ statistics between batches are observed. Every batch represents 30 minutes of processed data. The statistics are averaged across all stages.

Two types of fault-free and faulty data sequences are represented:
- NF1+F2: Fault-free data is sent into the pipeline for 1 hour, followed by 2 hours of faulty data
- NF2+F1: Fault-free data is sent into the pipeline for 2 hours, followed by 1 hour of faulty data


Case 2. Statistical Feature Comparison across Batches. 
The figures represent IQR, Mean, STD (Standard Deviation), Variance, and scaled Entropy across different batches for all features

