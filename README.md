# Rainfall Prediction Classifier

A machine learning classifier for predicting rainfall using weather data with preprocessing, feature engineering, model training, and performance evaluation.

## Contents

- `Building_a_Rainfall_Prediction_Classifier.ipynb` - notebook with data loading, preprocessing, feature engineering, model training, and evaluation.
- `requirements.txt` - Python packages needed to run the notebook locally.
- `LICENSE` - MIT license for the project.

## Setup

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.

## Data

The notebook expects the dataset file `weatherAUS.csv`. In the current notebook, it is loaded from:

```python
/content/weatherAUS.csv
```

When running in Colab, upload `weatherAUS.csv` to `/content/`. When running locally, either place the CSV where the notebook expects it or update the `pd.read_csv(...)` path in the notebook.

The dataset file is not included in this repository.
