# Process-Mining
# 🏥 Process Mining on Sepsis Cases

This repository contains the work conducted as part of our project on **Process Mining** using the **Sepsis Cases - Event Log** dataset. Our goal was to analyze patient treatment paths, detect process inefficiencies, and assess compliance with clinical guidelines using process mining techniques.

## 📂 Project Overview

**Process Mining** is a powerful technique used to extract process-related insights from event logs. By leveraging algorithms such as the **Alpha Miner**, **Inductive Miner**, and **Heuristics Miner**, we reconstructed and evaluated healthcare workflows from real patient journeys.

This project was carried out as part of a university workshop and includes:
- Implementation of multiple process discovery algorithms
- Analysis of patient trajectories for sepsis cases
- Visualization and interpretation of care pathways
- Bottleneck and compliance detection

## 📊 Use Case: Sepsis Treatment Pathways

Sepsis is a life-threatening medical condition that requires early detection and treatment. Our project focuses on analyzing hospital event logs to:
- Identify **delays and bottlenecks**
- Evaluate **adherence to clinical protocols**
- Explore **variations in patient journeys**

We used a real-world event log from a Dutch hospital, containing:
- **1,050 patient cases**
- **~15,000 events**
- **16 distinct hospital activities**
- **39 clinical attributes**

## 🛠️ Tools and Libraries

- [**PM4Py**](https://pm4py.fit.fraunhofer.de/) – an open-source Python library for process mining
- Python (Jupyter Notebooks)
- Pandas, NumPy, Matplotlib, Seaborn

## 📁 Repository Structure

├── notebooks/ # Process mining experiments and analysis
│ └── sepsis_analysis.ipynb
├── data/ # Sepsis Cases Event Log (not included due to privacy)
├── presentation/ # Final presentation slides
│ └── Final Presentation - Process Mining.pptx
└── README.md # Project documentation

markdown
Copy
Edit

## 🧠 Methods Applied

### Alpha Miner
- Discovers basic process models
- Good for noise-free data
- Based on strict control-flow relations

### Inductive Miner
- Builds structured, sound models
- Handles loops and parallelism
- Suitable for complex real-life logs

### Heuristics Miner
- Captures frequent behavior
- Filters out noise
- Ideal for messy logs with exceptions

## 🎯 Objectives

- 🔎 **Analyze patient trajectories** to uncover hidden patterns.
- 🕓 **Detect bottlenecks** and common delay points in treatment.
- ✅ **Check compliance** with medical guidelines (e.g., timely antibiotics).
- 🧭 **Support decision-makers** with insights for optimizing hospital processes.

## 🎓 Team

Group 5 – June 2025  
- Amit Haritan  
- Elore Paz  
- Alisa Bogomolny  
- Amitai Kellerman

## 📝 Acknowledgements

- Special thanks to the workshop instructors and the providers of the Sepsis Cases Event Log.
- Event log sourced from the [BPI Challenge 2019](https://www.tf-pm.org/process-mining-bpi-challenge)

## 📽️ Presentation

You can view the full project presentation [here](./presentation/Final%20Presentation%20-%20Process%20Mining.pptx).
