# Titanic Survival Prediction

A Jupyter Notebook for cleaning, analyzing, visualizing, and modeling the Titanic dataset.

## Dataset
- train.csv (included)

## Environment
- Python 3.8+
- Install dependencies:
  - In a notebook cell: `%pip install numpy pandas matplotlib seaborn scikit-learn`
  - Or terminal (Windows): `python -m pip install numpy pandas matplotlib seaborn scikit-learn`

## How to Run
1. Open `titanic.ipynb` in VS Code.
2. Select a Python kernel.
3. Run All Cells (restart if prompted).

## What the Notebook Does
- Cleans data (drops Cabin, fills Age and Embarked).
- EDA with Seaborn/Matplotlib:
  - Countplots, line, bar, scatter, hist, box, heatmap, pairplot.
- Exports summary:
  - `titanic_summary.csv` (survival by class and sex).
- Trains Logistic Regression and prints train/test accuracy.

## Files
- `titanic.ipynb` — main notebook.
- `train.csv` — dataset.
- `titanic_summary.csv` — generated after running notebook.

## Notes
- If plots don’t show, add `plt.show()` after plot calls.
- If LogisticRegression warns, set `max_iter=1000`.