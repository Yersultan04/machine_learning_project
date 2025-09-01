# Rock-Paper-Scissors Classification with CNNs

This repository contains the implementation and report for the project **[RPS] Building a CNN for Rock-Paper-Scissors Classification**.  
The project was developed as part of the Machine Learning course at the University of Milan.  

---

## Repository Structure
- `rock_paper_scissors.ipynb` — Jupyter Notebook with full implementation (manual preprocessing, CNN training, evaluation).
- `Machine_learning_Project.pdf` — Final report (10–15 pages) describing methodology, results, error analysis, and conclusions.
- `README.md` — Project documentation.

---

## Run on Google Colab
You can open and run the notebook directly in Colab:

https://colab.research.google.com/drive/1d7lmrbHEy6-t_51xpVEAHZt5STf7S3Ev?usp=sharing
---

## Project Overview
- **Dataset**: [Rock-Paper-Scissors Dataset (Kaggle)](https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors)  
- **Task**: Classify hand gesture images into `rock`, `paper`, or `scissors`.
- **Models**:  
  - Model 1: Baseline CNN (~5.3M params)  
  - Model 2: CNN with Dropout (~4.8M params)  
  - Model 3: CNN with BatchNorm + Dropout (~3.6M params, best test accuracy ~99%)  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix.  
- **Generalization Test**: Additional images tested to analyze robustness.  

---

## Reproducibility
1. Clone the repository:  
   ```bash
   git clone https://github.com/Yersultan04/machine_learning_project.git
   cd machine_learning_project
