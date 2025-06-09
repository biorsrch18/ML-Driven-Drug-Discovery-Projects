# ML-Driven-Drug-Discovery-Project
This project has two phases: 
1. QED Prediction (Drug-likeness Regression) and
2. Bioactivity Classification
# Common Setup for Both Phases: 
1. Install required packages (rdkit, scikit-learn, pandas, etc.)
2. Load a small molecule dataset (e.g., SMILES).
3. Generate molecular descriptors with RDKit.

# 💊 Machine Learning-Driven Drug Discovery (ML-DD)

This repository is showing Machine learning project for drug discovery using small molecules. It is structured in two phases:

1. **QED Prediction** – A regression task to predict the Quantitative Estimate of Drug-likeness (QED) score based on molecular descriptors.
2. **Bioactivity Classification** – A binary classification task to determine if a molecule is active or inactive against a specific protein target.

---

## 🧠 Project Goals

- Learn how to use **SMILES** strings to derive molecular features.
- Apply **machine learning models** to solve regression and classification problems in cheminformatics.
- Understand the importance of molecular descriptors in predictive modeling.

---

## 📁 Project Structure

ML-Driven-Drug-Discovery
  data collection # Sample or processed datasets
  notebooks # Google Colab-ready Jupyter notebooks
    1. qed_prediction.ipynb
    2. bioactivity_classification.ipynb
  README.md
  requirements.txt # Python dependencies

---

## 🛠️ Tools & Libraries

- Python 3.8+
- [RDKit](https://www.rdkit.org/)
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ML-Driven-Drug-Discovery.git
   cd ML-Driven-Drug-Discovery

2. Create a virtual environment and activate it (Optional) 

3. Install dependencies: !pip install -r requirements.txt

## Stepwise Explaination:
**Phase 1: QED Prediction**
Input: SMILES strings
Output: Predicted QED scores
Run notebooks/01_qed_prediction.ipynb

** Phase 2: Bioactivity Classification
Input: Molecules labeled as active/inactive

Output: Binary classification (active or not)

👉 Run notebooks/02_bioactivity_classification.ipynb

🧪 Sample Descriptors Used
Molecular Weight

LogP (lipophilicity)

Hydrogen Bond Donors/Acceptors

Topological Polar Surface Area (TPSA)

Rotatable Bonds

📊 Model Types
QED Prediction: Random Forest Regressor

Bioactivity Classification: Random Forest / Logistic Regression

📚 References
RDKit: https://www.rdkit.org/

ChEMBL Database: https://www.ebi.ac.uk/chembl/

DeepChem / MoleculeNet: https://deepchem.io/

✍️ Author
Mala Sharma
Ph.D. in Bioinformatics | ML & Computational Biology Enthusiast
📍 Chicago, IL
📫 bio.rsrch18@gmail.com
🔗 GitHub | Google Scholar
