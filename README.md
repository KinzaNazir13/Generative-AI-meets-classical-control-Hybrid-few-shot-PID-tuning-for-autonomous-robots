# Generative-AI-meets-classical-control-Hybrid-few-shot-PID-tuning-for-autonomous-robots
This file contains the complete datasets and Python code utilized in our manuscript titled "Generative AI meets classical control: Hybrid few-shot PID tuning for autonomous robots."

The compressed archive (Data and Code Files.zip) includes two main folders:

1. 2025-03-24_train1/
This folder contains all datasets used in our study, structured as follows:

all/
Original experimental data collected from real Automated Guided Vehicle (AGV) runs at various operational speeds and payload conditions. This data was used to train the ensemble regression model.

augmented/
Synthetic datasets generated using a foundation model (GPT) to augment AGV operation data specifically for speeds of 5 m/min and 20 m/min. These synthetic samples enhance the robustness and generalization of our predictive model.

llm_data/
Results from the initial few-shot experiments conducted across multiple operational speeds. These results provided the seed data required for generating the synthetic datasets in the "augmented" folder.

2. agv_pid_train_llm_v02/
This folder contains all Python code scripts essential for reproducing our methodology, including:

Data preprocessing scripts

Feature engineering and augmentation scripts

Ensemble model training and validation scripts

Synthetic data generation via GPT

Evaluation scripts for discriminator analysis and statistical validation

Visualization scripts for results interpretation

All provided data and code facilitate comprehensive replication, validation, and further exploration of our methods, results, and analyses described in the manuscript.
