# Applied Machine Learning for Biological Problems

This repository contains two group projects developed in the course  
**“Applied Machine Learning for Biological Problems”**.

The projects focus on applying classical and automated machine learning
methods to biologically and medically relevant datasets, with an emphasis
on reproducibility, interpretability, and rigorous data preprocessing.

---

## Overview of projects

### Project 1 – Environmental data classification
**Use case:** Predicting water quality and edibility based on environmental measurements.

This project implements core steps of the data science workflow:
- Use case and target variable definition
- Exploratory data analysis (EDA)
- Data preparation and cleaning
- Training and evaluation of baseline machine learning models

**Models used:**
- Naive Bayes
- K-Nearest Neighbours (KNN)

**Main tools:**  
Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

---

### Project 2 – Predicting antibiotic resistance in *Neisseria gonorrhoeae*
**Use case:** Predicting resistance to azithromycin and ciprofloxacin from genomic k-mer features.

This project represents a full, real-world–style machine learning pipeline
for biological data, including extensive preprocessing and model optimization.

#### Dataset
- 3,971 *Neisseria gonorrhoeae* genomes
- Genomic k-mers associated with antibiotic resistance
- Antibiotics studied:
  - Azithromycin
  - Ciprofloxacin  
  (Cefixime excluded from final modeling due to extreme class imbalance)

#### Workflow
1. Exploratory data analysis (EDA)
2. Data cleaning  
   - Duplicate detection and removal  
   - Handling of missing values  
   - Removal of low-information features  
   - Outlier detection
3. Feature selection  
   - Correlation analysis between genomic features and resistance
4. Model selection and optimization
5. Performance evaluation and interpretation

#### Models and methods
- Random Forest (baseline and optimized)
- Auto-Sklearn (automated model selection and hyperparameter optimization)

#### Results
- High predictive performance (>95% accuracy) for azithromycin and ciprofloxacin resistance
- Identification of strongly correlating genomic features (k-mers)
- Discussion of limitations due to class imbalance and dataset scope

