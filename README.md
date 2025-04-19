# Cybersecurity Data Mining Project

## Project Context
This project is part of the Data Mining curriculum at the Faculty of Sciences of Sfax (FSS). It focuses on applying unsupervised learning techniques to a cybersecurity dataset in order to extract hidden patterns, identify groups of similar attack behaviors, and detect anomalies. The dataset includes detailed records of network traffic and security events, offering rich opportunities for exploratory analysis and pattern recognition.

## Authors:
- **Hamza ZARAI**  
  Email: hamzazarai11@gmail.com
- **Mabrouka MESSAOUDI**  
  Email: mabroukamessaoudi892@gmail.com

## Repository Structure
```
cybersecurity-data-mining/
│
├── README.md               # Project overview (this file)
├── data/
│   ├── raw/                # Raw data (original CSV files)
│   │   └── cybersecurity_attacks.csv
│   ├── processed/          # Cleaned and encoded data
│       └── processed_cybersecurity_attacks.csv
        |__encoded_cybersecurity_attacks.csv
├── notebooks/
│   └── CyberAttacks.ipynb  # Jupyter Notebook with full workflow
├── results/
│   ├── figures/            # Saved visualizations
│   └── tables/             # Tabular summaries and cluster insights
└── .gitignore
```

## Objectives and Key Questions

### General Objectives:
- Segment network traffic into distinct behavioral groups using clustering.
- Detect anomalous or rare behaviors within otherwise homogeneous clusters.
- Uncover meaningful patterns across platforms, protocols, traffic types, and time.

### Specific Data Mining Questions:
- Can we detect natural groupings of attack types based on their attributes?
- Are there recurring behavior profiles in attack patterns (e.g., based on protocol, time, severity)?
- Which features (e.g., packet type, platform, browser) contribute most to cluster formation?
- Can we detect outliers or abnormal activity within a cluster using anomaly detection techniques?
- Do temporal patterns of attacks reveal periods of heightened vulnerability?



## How to Use
1. **Clone the repository:**
```bash
git clone https://github.com/Hamzazarai/Data-Mining-Project.git
cd Data-Mining-Project
```

2. **Explore Notebooks:**
```bash
jupyter notebook
```
Open and run the notebook in the `notebooks/` directory.

3. **Analyze Results:**
Visualizations and clustering results are saved in the `results/` directory.

## Dependencies
This project uses the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

