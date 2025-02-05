# Capuchinbird Call Classification & Event Detection  

## Overview  

This repository contains a **Jupyter Notebook** implementing a **mini-project in Machine Learning**, inspired by the **[HP Z Challenge](https://www.hp.com/us-en/workstations/industries/data-science/unlocked-challenge.html)**. The goal of this project is to train a model that recognizes **Capuchinbird calls** and applies it to long **forest recordings** to detect occurrences of the bird.  

🚧 **Status: Work in Progress** 🚧  
- The project is still under development, with ongoing **model optimization**.  
- The final **CSV output generation** is yet to be implemented.  
- However, **intermediate results** can already be explored in the notebook.  

## Requirements  

- **Python 3.12.3** (Ensure you use this version for compatibility)  
- Dependencies listed in `requirements.txt`  

## Setup Instructions  

### 1️⃣ Create a Virtual Environment  

```bash
python -m venv .venv
source .venv/bin/activate  # For Mac/Linux
.venv\Scripts\activate     # For Windows
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download the Kaggle Dataset
Before running the notebook, download the dataset from [Kaggle](https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing) using the following command:

```bash
kaggle datasets download -d kenjee/z-by-hp-unlocked-challenge-3-signal-processing -p data/ --unzip
```
Make sure the dataset is placed in the appropriate directory for the notebook to access.

### 4️⃣ Start Jupyter Notebook
```bash
jupyter notebook
```
Then open and run `Capuchinbird_Classifier.ipynb`.

### Contributions
This is a personal project, but feel free to open issues or make suggestions!
