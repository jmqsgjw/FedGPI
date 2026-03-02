# FedGPI: Geometric Aggregation Driven by Gravitational Potential Index for Federated Learning

This repository contains the datasets and partial core code for the paper:  
**"FedGPI: Geometric Aggregation Driven by Gravitational Potential Index for Federated Learning"**

> **Important Note**: This repository provides **datasets and illustrative code snippets** to facilitate understanding of the FedGPI algorithm. The complete implementation is not publicly available due to ongoing research and intellectual property considerations. Full code will be released upon paper acceptance or by reasonable request to the corresponding author.

---

## 📁 Repository Structure
FedGPI/
│
├── datasets/ # Dataset information and download links
│ ├── dataset_info.md # Detailed dataset descriptions
│ └── download_links.md # Direct links to original data sources
│
├── code/ # Partial core code snippets
│ ├── gpi_calculation.py # Gravitational Potential Index computation (Eq. 4)
│ ├── markov_sampling.py # Markov sampling illustration (Eq. 2)
│ └── fda_training.py # FDA training example (Eq. 3)
│
└── README.md # This file


---

## 📊 Datasets

We use nine real-world binary classification benchmark datasets from the UCI Machine Learning Repository. Below is a summary of the datasets used in our experiments:

| Dataset | Training Samples | Test Samples | Features |
|---------|-----------------|--------------|----------|
| Cod-rna | 325,710 | 162,855 | 8 |
| Shuttle | 46,400 | 11,600 | 9 | 
| Poker | 768,757 | 256,253 | 10 | 
| Image | 260,000 | 20,200 | 18 |
| Census_income | 199,523 | 99,762 | 41 |
| UJIIndoorLoc | 14,032 | 7,016 | 528 | 
| HAPT | 7,767 | 2,589 | 561 | |
| Bincifar10 | 50,000 | 10,000 | 3072 |
| Binmapping | 15,000 | 5,329 | 5329 |

### Dataset Preprocessing
All datasets are preprocessed to:
- Convert to binary classification format
- Normalize features to zero mean and unit variance
- Split into training/test sets as specified in the paper

---

