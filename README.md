# Machine Learning with Python

This repository contains the code I am writing while learning Machine Learning (ML) with Python from a YouTube tutorial. The code focuses on practical implementation of different machine learning models using Jupyter Notebooks for an interactive learning experience.

## Contents

- **first_file.py**: 
  - Basic exploration of a dataset (`vgsales.csv`).
  - Includes data loading, basic statistics, and dataset inspection.
  - Dataset used: [Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)
  
- **music_prediction.py**:
  - Implements a simple machine learning model using `DecisionTreeClassifier` to predict music genres based on age and gender.
  - The code includes data splitting (train/test), model training, and accuracy evaluation.

- **visualizingDecisionTree.py**:
  - Code to visualize a trained Decision Tree using `tree.export_graphviz` from scikit-learn.
  - Exports the Decision Tree as a `.dot` file for visualization.

## Libraries Used

- `pandas`
- `scikit-learn`
- `joblib` (for model persistence)

## How to Run

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Clone the repository and navigate into the directory:
   ```bash
   git clone https://github.com/thabir303/Start-ML-with-Python.git
   cd Start-ML-with-Python
   ```
3. Run the Python scripts or Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```
