# 🔐 Synthetic Data Generation for IDS & DDoS Detection

## 📌 Project Overview

This repository implements **synthetic data generation for network intrusion and DDoS detection datasets** using generative models.  
It helps overcome challenges such as limited labeled samples, class imbalance, and privacy concerns in cybersecurity research.  
The project allows machine learning models to be trained on **realistic synthetic datasets**, improving model robustness and generalization.

---

## 🎯 Supported Datasets

- KDD Cup 1999 (KDD) – intrusion detection dataset
- CIC-IDS 2017 (CIC) – network intrusion dataset
- UNSW-NB15 (CSNW) – network security dataset
- CIC-DDoS2019 (DDoS) – DDoS attack dataset

> **Note:** Datasets are **not included** due to size and licensing restrictions. Download them from official sources and place inside the `data/` folder.

---

## 🧠 Methodology

1. **Data Preprocessing**  
   - Clean missing or infinite values  
   - Encode categorical features  
   - Normalize numeric features  

2. **Synthetic Data Generation**  
   - **CTGAN**: Conditional Tabular GAN  
   - **TVAE**: Tabular Variational AutoEncoder  
   - **CopulaGAN**: Preserves dependencies across columns  

3. **Evaluation**  
   - Compare statistical similarity between real and synthetic data  
   - Validate ML model performance (accuracy, precision, recall, F1-score)

---

## 📊 Key Features

- Multi-dataset support for IDS and DDoS  
- Handles categorical and continuous features  
- Preserves class balance for rare attacks  
- Generates privacy-preserving synthetic data  
- Enables robust ML model training and benchmarking  

---

## 🛠 Technology Stack

- Python  
- Pandas & NumPy  
- Scikit-learn  
- PyTorch & TensorFlow  
- SDV (CTGAN, TVAE, CopulaGAN)  
- Matplotlib  

---
## 🔬 Future Improvements

- Integrate differential privacy
- Hybrid GAN + rule-based synthetic generation
- Real-time DDoS simulation environment
- Advanced visualization dashboards

## 👩‍💻 Author

**Kashvi Patil**  
GitHub: https://github.com/kashvipatil20

