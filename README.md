# Quark vs Gluon Jet Classification (ML4SCI GSoC 2026)

## Summary

In this project, we perform quark vs gluon jet classification  
using simulated jet datasets and a machine learning pipeline.

We extract physics-based features including jet mass, width,  
pT dispersion (pTD), and multiplicity, and analyze both  
lab frame and rest frame representations.

We train Logistic Regression and Random Forest models.  
The best performance is achieved by Logistic Regression  
in the lab frame with an AUC of approximately 0.85.

This project serves as a foundational step toward analyzing  
simulation bias between Monte Carlo generators (Pythia vs Herwig)  
as part of the ML4SCI GSoC 2026 project.

---

## Methodology

- Dataset loading and preprocessing  
- Physics-based feature engineering  
- Lorentz boost to rest frame  
- Machine learning (Logistic Regression + Random Forest)  
- Evaluation (ROC, AUC, Confusion Matrix, Accuracy, Precision, Recall)  

---

## Results

- Lab Logistic AUC: ~0.85  
- Lab RF AUC: ~0.84–0.85  
- Rest Frame AUC: ~0.84–0.85  

---

## How to Run

### 1. Clone the Repository

git clone https://github.com/Rajan-Gupta365/ml4sci-simulation-bias-analysis.git  
cd ml4sci-simulation-bias-analysis  

---

### 2. Open the Notebook

You can open the notebook using:

- Jupyter Notebook  
- VS Code  
- Google Colab  

---

### 3. Dataset Setup

Upload or place the required dataset files:

- QG_jets.npz  
- QG_jets_1.npz  
- QG_jets_2.npz  

Place them in the same directory as the notebook:

ml4sci-simulation-bias-analysis/
│
├── quark_gluon_analysis.ipynb  
├── QG_jets.npz  
├── QG_jets_1.npz  
├── QG_jets_2.npz  

---

### 4. Run the Notebook

Run all cells sequentially:

Runtime → Run All  

---

### 5. Requirements

- Python 3.x  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

## Project Structure

ml4sci-simulation-bias-analysis/
│
├── quark_gluon_analysis.ipynb   (Complete pipeline)  
├── README.md                   (Project documentation)  

---

## Notes

- Ensure dataset files are available before running  
- The notebook runs end-to-end without errors  
- This pipeline is designed to be extended for simulation bias analysis  

---

## Author

Rajan Gupta  
B.Tech CSE, KIIT University (2nd Year, 4th Semester)  

GitHub: https://github.com/Rajan-Gupta365  
LinkedIn: https://www.linkedin.com/in/7herajangupta/  
