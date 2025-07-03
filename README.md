# Credit Card Fraud Detection 🚨

A machine learning project to detect fraudulent credit card transactions using multiple models, trained and evaluated on real-world data.

---

## 📋 Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Project Structure](#project-structure)  
- [Models & Techniques](#models--techniques)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Evaluation Metrics](#evaluation-metrics)  
- [Results](#results)  
- [Future Work](#future-work)  
- [Contributing](#contributing)  
- [License](#license)

---

## Overview

As digital payments surge, so does the risk of credit card fraud. This project leverages ML to detect fraudulent transactions by analyzing patterns within a labeled dataset—focusing on accuracy, reliability, and interpretability.

---

## Dataset

- **Source**: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Details**:
  - ~ 284,807 transactions over 2 days in 2013 (European users)
  - 31 features: `V1–V28` (PCA components), `Time`, `Amount`
  - Target column `Class`: 1 = fraud, 0 = legitimate  
- **Imbalance**: Only 492 fraud cases (~0.17%) :contentReference[oaicite:1]{index=1}

---

## Project Structure

```text
.
├── data/                 # Raw and processed datasets
├── notebooks/            # Exploratory data analysis & model prototyping
├── src/                  # Training and evaluation scripts
├── models/               # Saved trained models
├── reports/              # Plots and performance figures
└── README.md             # Project overview
