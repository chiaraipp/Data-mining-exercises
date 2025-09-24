# Data-mining-exercises
This repository contains a collection of **9 Jupyter notebooks** used to prepare for the **Data Mining** course at the University of Pisa. The notebooks cover various stages of data analysis, including:
- **Data preprocessing:** cleaning, normalization, feature selection and transformation
- **Exploratory data analysis (EDA):** visualizing and understanding dataset characteristics
- **Classification and regression tasks**

Each notebook focuses on a specific dataset, illustrating the **steps from raw data to model evaluation**. This repository is intended as a personal study resource and demonstration of data mining techniques learned during the course. 

---

## Dataset and Notebooks:
1. Coeliac Disease Dataset
2. Diabetes Dataset
3. Cancer Gene Expression Dataset
4. Hypothyroid Dataset
5. Framingham Heart Disease Dataset
6. Heart Disease Dataset
7. Hepatitis Dataset
8. Parkinson's Voice Dataset
9. Fetal Heart Rate (FHR) Dataset

---

## Datasets Overview

| Dataset | Source | Objective | Task |
|---------|--------|-----------|------|
| [Coeliac Disease](notebooks/CoeliacDisease.ipynb) | Wageningen University & Research Biotechnology Dept. | Predict whether a patient has Coeliac disease based on medical variables | Classification (binary) |
| [Diabetes](notebooks/Diabetes.ipynb) | Proof-of-concept study, 1999 | Predict whether a patient has diabetes using demographic and medical measurements | Classification (binary) |
| [Cancer Gene Expression](notebooks/CancerGeneExpression.ipynb) | Published study | Classify cancer type (AML vs ALL) using gene expression | Classification (binary) |
| [Hypothyroid](notebooks/Hypothyroid.ipynb) | Various medical records | Predict thyroid disease status based on clinical attributes | Classification (binary) |
| [Framingham Heart Disease](notebooks/FraminghamHeartDisease.ipynb) | Framingham, Massachusetts cardiovascular study | Predict 10-year risk of coronary heart disease (CHD) based on clinical features | Classification (binary) |
| [Heart Disease](notebooks/HeartDisease.ipynb) | Clinical dataset | Predict whether a patient has heart disease using medical features | Classification (binary) |
| [Hepatitis](notebooks/Hepatitis.ipynb) | Clinical dataset | Discriminate between healthy and diseased patients using lab measurements | Classification (binary) |
| [Parkinson's Voice](notebooks/Parkinson'sVoice.ipynb) | Telemonitoring trial | Predict total UPDRS score from biomedical voice features | Regression |
| [Fetal Heart Rate](notebooks/FetalHeartRate.ipynb) | Cardiotocograms, expert annotations | Classify fetal state (Normal, Suspect, Pathologic) | Classification (multiclass) |

---

## Libraries used:
- Pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

---
## 🛠️ Installation

To get started with these notebooks, follow these steps:
## 🛠️ Installation

To get started with these notebooks, follow these steps:

1.  **Clone the repository:**
    Open your terminal or command prompt and run:
    ```bash
    git clone https://github.com/chiaraipp/Data-mining-exercises.git
    cd Data-Mining-Exercises
    ```

2.  **Use base Anaconda environment:**
    It's highly recommended to use the same environment as the notebooks
    ```bash
    conda activate base
    ```
    Alternatively you can create a new virtual environment and install the same dependencies,        but using the base environment will match the original setup. 

3.  **Install dependencies:**
    With your environment activated, install all required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter Lab/Notebook:**
    Finally, you can launch Jupyter and open the notebooks in your browser:
    ```bash
    jupyter notebook
    ```
---

## 🚀 Usage

Navigate to the `notebooks/` directory and open any `.ipynb` file to explore the examples. Each notebook is self-contained and demonstrates a complete workflow from data loading to model evaluation.
